# RHEL9-User-Group-Management-Automation
This project provides a Bash script to automate the creation and management of users and groups on RHEL 9
# RHEL9 User and Group Management Automation

## Overview
This project provides a Bash script to automate the creation and management of users and groups on RHEL 9. It includes functions to:
- Add a new group
- Add a new user and assign to a group
- Set user permissions on directories

## Script Usage
### Adding a Group & Setting Permisions
To add a new group:
```bash
./user_group_management.sh add_group group_name

To set user permissions on a directory:
./user_group_management.sh set_permissions username /path/to/directory
