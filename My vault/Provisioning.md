Users, groups, and resources

If org uses Gmail, this gives users email addresses
Trial Workspace account is free for up to 10 users

Each member of org requires a user account and license to use Workspace apps and services

There are 4 ways to do this
1. One at a time
2.  In bulk via CSV
3. Admin SDK Directory API
4. Provisioning tool like Google cloud Directory Sync

In bulk: Navigate to Directory, then Users. Click Bulk update users, then DOWNLOAD BLANK CSV TEMPLATE. Fill out the template. First name, last name, email address, password, and org unit path are all required info. For org unit path, "/" represents the root org. Return to the Bulk update suers box, then click ATTACH CSV FILE and upload it.

It can take up to 24 hours for new user accounts to appear in the searchable domain directory. When uploading more than 500 accounts, you can optimize the experience by splitting uploads into smaller batches, but up to 150,000 is allowed.

Directory sync: