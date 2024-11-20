:original_name: dc_01_0008.html

.. _dc_01_0008:

Permissions
===========

If you need to assign different permissions to employees in your enterprise to access your Direct Connect resources, Identity and Access Management (IAM) is a good choice for fine-grained permissions management. IAM provides identity authentication, permissions management, and access control, helping you secure access to your resources.

With IAM, you can use your account to create IAM users, and assign permissions to the users to control their access to specific resources. For example, some software developers in your enterprise need to use Direct Connect but should not be allowed to delete other Direct Connect resources or perform any other high-risk operations. In this scenario, you can create IAM users for the software developers and grant them only the required permissions.

Skip this part if your account does not require individual IAM users for permissions management.

IAM is free. You pay only for the resources in your account.

For more information, see `IAM Service Overview <https://docs.sc.otc.t-systems.com/en-us/usermanual/iam/iam_01_0026.html>`__.

Direct Connect Permissions
--------------------------

By default, new IAM users do not have any permissions assigned. To assign permissions to these new users, add them to one or more groups, and attach permissions policies or roles to these groups.

Direct Connect is a project-level service deployed and accessed in specific physical regions. To assign permissions to a user group, specify the scope as region-specific projects and select projects for the permissions to take effect. If **All projects** is selected, the permissions will take effect for the user group in all region-specific projects. When accessing Direct Connect, the users need to switch to a region where they have been authorized to use this service.

You can grant users permissions by using roles or policies.

-  Roles: A type of coarse-grained authorization mechanism that defines permissions related to user responsibilities. This mechanism provides only a limited number of service-level roles for authorization. When using roles to grant permissions, you must also assign other roles on which the permissions depend to take effect. However, roles are not an ideal choice for fine-grained authorization and secure access control.
-  Policies: A type of fine-grained authorization mechanism that defines permissions required to perform operations on specific cloud resources under certain conditions. This mechanism allows for more flexible policy-based authorization, meeting requirements for secure access control. For example, you can grant Direct Connect users the permissions for only managing a certain type of resources.

:ref:`Table 1 <dc_01_0008__en-us_topic_0173524723_en-us_topic_0173475706_en-us_topic_0170232209_table481412518317>` lists all system-defined roles supported by Direct Connect.

.. _dc_01_0008__en-us_topic_0173524723_en-us_topic_0173475706_en-us_topic_0170232209_table481412518317:

.. table:: **Table 1** Direct Connect roles

   +------------------------------+-------------------------------------------------------------------------------------------------------------------------------+-----------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
   | Role/Policy Name             | Description                                                                                                                   | Type                  | Dependency                                                                                                                                |
   +==============================+===============================================================================================================================+=======================+===========================================================================================================================================+
   | Direct Connect Administrator | Has all permissions for Direct Connect resources.                                                                             | System-defined role   | **Tenant Guest** and **VPC Administrator**                                                                                                |
   |                              |                                                                                                                               |                       |                                                                                                                                           |
   |                              | For permissions of this role to take effect, users must also have the **Tenant Guest** and **VPC Administrator** permissions. |                       | -  **VPC Administrator**: project-level policy, which must be assigned in the same project as the **Direct Connect Administrator** policy |
   |                              |                                                                                                                               |                       | -  **Tenant Guest**: project-level policy, which must be assigned in the same project as the **Direct Connect Administrator**             |
   +------------------------------+-------------------------------------------------------------------------------------------------------------------------------+-----------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
   | DCAAS FullAccess             | Permissions: all permissions for Direct Connect                                                                               | System-defined policy | None                                                                                                                                      |
   |                              |                                                                                                                               |                       |                                                                                                                                           |
   |                              | Scope: project-level service                                                                                                  |                       |                                                                                                                                           |
   +------------------------------+-------------------------------------------------------------------------------------------------------------------------------+-----------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
   | DCAAS ReadOnlyAccess         | Permissions: read-only permissions for Direct Connect                                                                         | System-defined policy | None                                                                                                                                      |
   |                              |                                                                                                                               |                       |                                                                                                                                           |
   |                              | Scope: project-level service                                                                                                  |                       |                                                                                                                                           |
   +------------------------------+-------------------------------------------------------------------------------------------------------------------------------+-----------------------+-------------------------------------------------------------------------------------------------------------------------------------------+

:ref:`Table 2 <dc_01_0008__table13641113421711>` lists common operations supported by each system-defined role or policy of Direct Connect.

.. _dc_01_0008__table13641113421711:

.. table:: **Table 2** Common operations and required system-defined permissions

   +------------------------------------+------------------------------+------------------+----------------------+
   | Operation                          | Direct Connect Administrator | DCAAS FullAccess | DCAAS ReadOnlyAccess |
   +====================================+==============================+==================+======================+
   | Creating a connection              | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Viewing a connection               | Y                            | Y                | Y                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Modifying a connection             | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Deleting a connection              | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Creating a virtual gateway         | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Viewing a virtual gateway          | Y                            | Y                | Y                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Modifying a virtual gateway        | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Deleting a virtual gateway         | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Creating a virtual interface       | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Viewing a virtual interface        | Y                            | Y                | Y                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Modifying a virtual interface      | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Deleting a virtual interface       | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Creating an operations connection  | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Viewing an operations connection   | Y                            | Y                | Y                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Modifying an operations connection | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Deleting an operations connection  | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Creating a hosted connection       | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Viewing a hosted connection        | Y                            | Y                | Y                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Modifying a hosted connection      | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+
   | Deleting a hosted connection       | Y                            | Y                | x                    |
   +------------------------------------+------------------------------+------------------+----------------------+

Helpful Links
-------------

-  `IAM Service Overview <https://docs.sc.otc.t-systems.com/en-us/usermanual/iam/iam_01_0026.html>`__

-  :ref:`Creating a User and Granting Permissions <dc_03_0701>`
