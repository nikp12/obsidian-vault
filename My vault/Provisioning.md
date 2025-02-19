Users, groups, and resources

If org uses Gmail, this gives users email addresses
Trial Workspace account is free for up to 10 users

Each member of org requires a user account and license to use Workspace apps and services

There are 4 ways to do this
1. One at a time
2.  In bulk via CSV
3. Admin SDK Directory API
4. Provisioning tool like Google cloud Directory Sync

In bulk: 
Navigate to Directory, then Users. Click Bulk update users, then DOWNLOAD BLANK CSV TEMPLATE. Fill out the template. First name, last name, email address, password, and org unit path are all required info. For org unit path, "/" represents the root org. Return to the Bulk update suers box, then click ATTACH CSV FILE and upload it.

It can take up to 24 hours for new user accounts to appear in the searchable domain directory. When uploading more than 500 accounts, you can optimize the experience by splitting uploads into smaller batches, but up to 150,000 is allowed.

Directory sync:
No software needs to be installed or maintained. Directory Sync is connected to AD environment and Workspace domain with secure authentication. It automatically synchronizes essential user attributes. Can also be customized by selecting specific OUs to include or exclude. This is a separate service from GCDS, which is an on-prem tool with extensive customization. Directory Sync is a cloud-based service for basic user and group sync.

Initially, all provisoned resources will be placed in a single org
All settings made in admin console apply to the top level organization
You can create OUs to control what apps and services are available to users. They can be configured differently for different sets of users.
Each child OU inherits settings from its parent unless this has been overridden.

If managing lots of users or syncing LDAP, a configuration or access group can be used. Config groups customize service settings. Access groups customize service access.