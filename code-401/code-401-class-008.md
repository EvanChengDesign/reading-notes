 **Reading Notes | 8 MAY 2024**

# Class 008

### *Bookmarks:*

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

## **Questions & Answers**  

## Role Based Access Control (RBAC) FAQ

1. **What is Role Based Access Control (RBAC) and why do we care?**  
   RBAC is a method for managing permissions by assigning users to roles that have specific privileges. We care because it enhances security and simplifies permission management by grouping users with similar access needs.

2. **Describe a Role/Permission hierarchy that you might implement using RBAC.**  
   An example hierarchy could include roles like "Admin," "Manager," and "User," where "Admin" has full control, "Manager" can manage users and data, and "User" can only view or update their own data.

3. **What approach might you take to implement RBAC?**  
   Start by identifying different roles and defining their permissions, then map these roles to users. Develop middleware or use a library to enforce these roles and permissions in your application.

4. **If Authentication is "you are who you say you are," what is Authorization?**  
   Authorization is the process of verifying what actions or resources a user is allowed to access based on their authenticated identity.

5. **Name three primary rules defined for RBAC.**  
   - Role Assignment: A user must have an assigned role to gain access.
   - Role Authorization: A user’s active role must be authorized for access.
   - Permission Authorization: Permissions must align with the user's current roles.

6. **Describe RBAC to a non-technical friend.**  
   RBAC is like giving different staff members keys to specific rooms based on their job: a manager has a key to all rooms, while an intern only gets a key to their workspace.

7. **What are access rights associated with? The User or the Role? Explain.**  
   Access rights are associated with the role, not the user. This way, any user assigned to a role gains the permissions of that role, simplifying permission management.

8. **Access Rights, or Authorization, is activated after a user successfully does what?**  
   After a user successfully authenticates (proving their identity), the system checks their roles and grants them appropriate access rights.

9. **Explain how RBAC might benefit a business.**  
   RBAC simplifies permission management, enhances security by limiting access to sensitive data, and ensures compliance by aligning access control with organizational policies.
