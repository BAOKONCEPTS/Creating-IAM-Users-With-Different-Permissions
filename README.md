# Creating-IAM-Users-With-Different-Permissions
## introduction
This assignment demonstrates how to create IAM users with diffrent prtmissions and explains their roles in AWS architecture. IAM (Identity and Access Managemrnt) is a crucial service in AWS that enables you to manage access to your AWS resources
## objective
The objective of this assignment is to;
create IAM users with different permissions
explain the roles of IAM users in AWS architecture
## Prerequisites
AWS account with administrative access
Basic understanding AWS IAM
## Creating IAM Users

Step 1: Create an IAM User for Administrators
- Log in to the AWS Management Console
- Navigate to the IAM dashboard
- Click on "Users" and then "Create user"
- Enter a username (e.g., "admin-user")
- Select "Programmatic access" as the access type
- Attach the "AdministratorAccess" policy to the user
- Click "Create user"

*Step 2: Create an IAM User for Developers*
- Repeat the same steps as above
- Enter a username (e.g., "dev-user")
- Select "Programmatic access" as the access type
- Attach the "DeveloperAccess" policy to the user (create a custom policy with necessary permissions for developers)
- Click "Create user"

*Step 3: Create an IAM User for Read-Only Access*
- Repeat the same steps as above
- Enter a username (e.g., "read-only-user")
- Select "Programmatic access" as the access type
- Attach the "ReadOnlyAccess" policy to the user
- Click "Create user"

## Assigning Permission
- IAM policies define the permissions for IAM users and roles
- Attach relevant policies to each IAM user to grant necessary permissions

## Explaining Roles in AWS Architecture

- IAM users and roles are used to manage access to AWS resources and services
- IAM policies define the permissions for IAM users and roles
- AWS resources and services are accessed through IAM users and roles

## Conclusion

In this assignment, we created IAM users with different permissions and explained their roles in AWS architecture. IAM is a crucial service in AWS that enables you to manage access to your AWS resources. By assigning relevant permissions to IAM users and roles, you can ensure secure and controlled access to your AWS resources.

## References

- AWS IAM Documentation: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
- AWS IAM User Guide: https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html

  ## Files
  - 
  


