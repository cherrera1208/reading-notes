Reading: Access Control (ACL)
=============================

Reading
-------

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

1. What is Role Based Access Control (RBAC) and why do we care?
    * assigning system access to users based on their role in an org. Not every team member needs to have all access
2. Describe a Role/Permission hierarchy that you might implement using RBAC.
    * admin, manager, employee, guest
3. What approach might you take to implement RBAC?
    * determine which roles are necessary and divvy them up accordingly

[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

1. If Authentication is “you are who you say you are,” what is Authorization?
    * you have the permission to access this feature
2. Name three primary rules defined for RBAC.
    * 1) role assignment, 2) role auth, 3) permission auth
3. Describe RBAC to a non-technical friend.
    * imagine a building with various level of security. Employees are given key cards that give them access to the building initially, but then they are given different security levels based on their seniority and responsibilities in the company.

Videos
------

[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

1. What Are access rights Associated with? The User? or The Role? Explain.
    * the role. The role has rights and the role is assigned to the user
2. Access Rights, or Authorization, is activated after a user successfully does what?
    * signs-up and receives permissions
3. Explain how RBAC might benefit a business.
    * not everyone in an org needs all permission. The accountant doesn't need access to the source code, and the programmer doesn't need access to payroll.
