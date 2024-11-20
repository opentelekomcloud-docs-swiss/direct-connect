:original_name: dc_03_0701.html

.. _dc_03_0701:

Creating a User and Granting Permissions
========================================

Use `IAM <https://docs.sc.otc.t-systems.com/en-us/usermanual/iam/iam_01_0026.html>`__ to implement fine-grained permissions control over your Direct Connect resources. With IAM, you can:

-  Create IAM users for employees based on the organizational structure of your enterprise. Each IAM user has their own security credentials, providing access to cloud resources.
-  Grant only the permissions required for users to perform a specific task.
-  Entrust another account or cloud service to perform professional and efficient O&M on your cloud resources.

Skip this part if your account does not require individual IAM users.

The following is the procedure for granting permissions.

Prerequisites
-------------

Before assigning permissions to user groups, you should learn about Direct Connect system policies and select the policies based on service requirements. For details about system permissions of Direct Connect, see :ref:`Permissions <dc_01_0008>`. For system permissions of other cloud services, see Permission Description\ `Permission Description <https://docs.sc.otc.t-systems.com/en-us/permissions/index.html>`__.

Process Flow
------------


.. figure:: /_static/images/en-us_image_0000001081864909.jpg
   :alt: **Figure 1** Process for granting Direct Connect permissions

   **Figure 1** Process for granting Direct Connect permissions

#. .. _dc_03_0701__en-us_topic_0173533526_en-us_topic_0173481716_en-us_topic_0172268189_li10269636890:

   `Create a user group and assign permissions <https://docs.sc.otc.t-systems.com/usermanual/iam/iam_01_0030.html>`__.

   Create a user group on the IAM console and attach the **Direct Connect Administrator** policy to the group, which grants users read-only permissions to Direct Connect resources.

#. `Create an IAM user and add it to the created user group <https://docs.sc.otc.t-systems.com/usermanual/iam/iam_01_0031.html>`__.

   Create a user on the IAM console and add the user to the group created in :ref:`1 <dc_03_0701__en-us_topic_0173533526_en-us_topic_0173481716_en-us_topic_0172268189_li10269636890>`.

#. `Log in to the management console as the created user <https://docs.sc.otc.t-systems.com/usermanual/iam/iam_01_0032.html>`__.

   Switch to the authorized region and verify the permissions.

   -  Choose **Service List** > **Network** > **Direct Connect**. On the displayed page, click **Create Connection**. If the connection fails to be created, the **Direct Connect Administrator** policy has taken effect.
   -  Choose any other service in **Service List**. If a message appears indicating that you have insufficient permissions to access the service, the **Direct Connect Administrator** policy has already taken effect.
