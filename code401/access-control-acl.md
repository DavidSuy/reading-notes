# Reading: Access Control (ACL)

## Reading

### [5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

1. What is Role Based Access Control (RBAC) and why do we care?

   RBAC is the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs.

2. Describe a Role/Permission hierarchy that you might implement using RBAC.

   Analyze your workforce and create roles. You need to group your workforce members into roles with common access needs. Avoid the temptation to have too many roles defined. Keep them as simple and stratified as possible. For example, you might have a basic user role, which includes the access any employee would need, such as email and the intranet site. Another role might be a customer service rep, that would have read/write access to the customer database, and a customer database administrator, that would have full control of the customer database.

3. What approach might you take to implement RBAC?
   - Inventory your systems. Figure out what resources you have for which you need to control access, if you don't already have them listed. ...
   - Analyze your workforce and create roles. ...
   - Assign people to roles. ...
   - Never make one-off changes. ...
   - Audit.

## [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

1. If Authentication is “you are who you say you are,” what is Authorization?

   Authorization is if you have the permissions based on your roles.

2. Name three primary rules defined for RBAC.

   - Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
   - Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
   - Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

3. Describe RBAC to a non-technical friend.

   Role-based access control is a policy-neutral access-control mechanism defined around roles and privileges. The components of RBAC such as role-permissions, user-role and role-role relationships make it simple to perform user assignments.

## Videos

[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

1. What Are access rights Associated with? The User? or The Role? Explain.

   Access rights are associated with roles, not users because the roles determine what resources you have access to.

2. Access Rights, or Authorization, is activated after a user successfully does what?

   Access rights are authorize when a user is successfully authenticated

3. Explain how RBAC might benefit a business.

   - Policy need not be updated when a certain person with a role leaves the organization.
   - New employee should be able to activate the desired role
   - revisiting least privilege
     - User in one role has access to a subject of the files
     - switch roles to gain access to other resources
   - SELinux supports RBAC
