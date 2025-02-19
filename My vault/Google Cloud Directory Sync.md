Also known as GCDS

Provisions user accounts directly from existing directory

Supports any [[Lightweight Directory Access Protocol (LDAP)]] directory server like Microsoft Active Directory

Ensures that users, groups, OUs, and shared contacts stay synce3d with updates made to local directory
Never modifies local directory info, changes only go from local to Google.
Helpful for orgs with a preestablished directory.
Removed need to manage cloud directory.

An application is installed on an orgs network.
It includes Configuration Manager which provides a step by step guide to configure and run the syncronization process.
With Config Manager, you can set up and test connection
Configure LDAP search criteria to determine which users, groups, or other data to sync
Also set up notification and logging options
Run simulated sync to ensure that everythign it set up correctly
GCDS uses search rules to determine what to include
Exclusion rules can be applied like to exlude emails beginning with a certain string
Sync can be run manually from Config Manager or from command line
Sync command allows you to automate sync process to be scheduled

[[Provisioning]] 
