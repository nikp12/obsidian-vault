2025-01-13 15:59

Tags: #Windows10 #Windows11 #md-102 #Security 

# Local accounts

Local accounts are accounts created directly on a Windows 10 or 11 device.

No network access is needed to access these accounts.

The credentials are stored in the [[Security Accounts Manager (SAM)]] section of the [[Registry]].

The first time a user logs in, their user profile is created.

Local accounts can be customized with gpedit.

There are two accounts which cannot be deleted:

1. Administrator: This account runs with no UAC and its security token is always elevated.
2. Guest: This account is disabled by default. It cannot change settings or install programs.

Local accounts can be edited with several GUI tools:

- The Account tile in Settings
- User accounts control panel or NETPLWIZ.EXE
- Computer management or COMPMGMT.MSC
- Local user management or LUSRMGR.MSC


## References

[[Pluralsight User Authentication in Windows]]

