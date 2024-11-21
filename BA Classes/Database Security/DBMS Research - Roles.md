#DatabseSecurity
Oracle has evolved over the years and one of the important changes it has undergone is the use of user roles. User roles are a way to group users together and grant privileges to the group as a whole, rather than to individual users. It's like creating a team and assigning certain permissions to that team. This makes managing permissions much easier, because you can add or remove users from the team without having to worry about managing their individual permissions separately. It's a very useful feature that simplifies database security management.

In the older versions of Oracle DBMS, roles were not enabled by default. You had to manually enable them using a special command. This changed in the newer versions, where roles are enabled by default.

In the newer versions, there have also been some changes to the way roles work. For example, in 18c, a new system-defined role called AUDIT_ADMIN was added. This role allows users to manage auditing policies and audit records.

In 19c, there was a change in the way password management is handled for roles. A new parameter called PASSWORD_LIFE_TIME was introduced. This parameter specifies the number of days the password for a role can be used before it expires.

In 21c, Oracle introduced hierarchical roles. This allows for more granular control over privileges. With hierarchical roles, you can grant a role to another role, creating a parent-child relationship between them. This makes it easier to manage large sets of privileges.

Overall, understanding the differences between the versions of Oracle DBMS is important if you want to take advantage of the new features and capabilities to improve your database security and management practices. By using roles effectively, you can simplify database security administration and manage privileges more easily.

# List
1.  Oracle Database Management System (DBMS) 12c Release 1 introduced user roles, but they were not enabled by default. In order to use roles, you had to manually enable them using the ALTER DATABASE statement.
2.  In 18c, a new system-defined role called AUDIT_ADMIN was added, which lets users manage auditing policies and audit records.
3.  In 19c, changes were made to password management for roles, with the introduction of the PASSWORD_LIFE_TIME parameter. This parameter specifies the number of days the password for a role can be used before it expires.
4.  In 21c, hierarchical roles were introduced. With hierarchical roles, roles can be granted to other roles, creating a parent-child relationship between them. This makes it easier to manage large sets of privileges and provides more granular control over privileges.


# 12c Release 1 (Book)
### Defining Roles in Oracle
- Comes with several predefined, built-in roles that are available to administrators and users alike. 
- Automatically defined for Oracle databases when you run the standard scripts that are included during database creates
	- If additional options or features are installed, more roles may be created as well
- Two levels: system level and object level
- Roles can be granted to other roles to further manage the access of users and applications

**Roles:**
|Role|Information|
|-|-|
|DBA|Holds access to all areas of the database; this role is provided for compatibility with previous releases of Oracle Database ans it is recommended that administrators create their own security-based roles|
|JAVA_ADMIN|Provides administrative permissions to update policy tables for Oracle Database Java applications|
|SCHEDULER_ADMIN|Allows the grantee to execute the procedures of the DBMS_SCHEDULER package; it includes all of the job scheduler system privileges and is included in the DBA role
|VM_ADMIN_ROLE|Provides all Workspace Manager permissions and includes the grant option; by default, the DBA is granted the WM_ADMIN_ROLE role
|XDB_WEBSERVICES|Allows the grantee to access Oracle Database Web services over HTTPS
|XDB_SEBSERVICES_OVER_HTTP|Allows the grantee to access Oracle Database Web services over HTTP
|MGMT_USER|Provides administrative privileges to perform various activities with Oracle Enterprise Manager
|OEM_MONITOR|Provides privileges needed by the Management Agent component of Oracle Enterprise Manager to monitor and manage the database

Note: It is possible to grant roles to PUBLIC, yet this is not recommended and would defeat the reason for needing to create a role altogether

Oracle provides several dictionary views to help you find out what roles are assigned and to whom they have been assigned.

**Locating roles in Oracle:**
|View|Contained|
|-|-|
|DBA_ROLES|All of the roles within the database|
|DBA_ROLE_PRIVS|All of the roles that are assigned to a user|
|ROLE_ROLE_PRIVS|All of the roles that are granted to other roles|
|ROLE_SYS_PRIVS|All system privileges that have been assigned to a role|
|ROLE_TAB_PRIVS|All object privileges assigned to a role|
|SESSION_ROLES|A list of roles that are enabled in the current session|



1.  Privilege escalation: If a user is assigned to a role with higher privileges than necessary, they may be able to escalate their privileges and access data they should not be able to access.
    
2.  Password policy: Weak password policies can increase the risk of unauthorized access. In Oracle versions 19c and later, the PASSWORD_LIFE_TIME parameter was introduced for password management for roles, which specifies the number of days a password for a role can be used before it expires.
    
3.  Role hierarchy: The introduction of hierarchical roles in Oracle 21c can create security concerns if not properly managed. Improper management of hierarchical roles can result in granting unnecessary privileges to users.
    
4.  Audit policies: In Oracle version 18c, the AUDIT_ADMIN role was introduced, which allows users to manage auditing policies and audit records. However, if this role is not properly managed, it can increase the risk of audit tampering and unauthorized access to audit data.