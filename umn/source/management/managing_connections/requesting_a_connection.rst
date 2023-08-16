:original_name: dc_03_0101.html

.. _dc_03_0101:

Requesting a Connection
=======================

Scenarios
---------

Connect your on-premises data center to your VPC using Direct Connect if cloud servers in your VPC need to communicate with your on-premises servers.

Procedure
---------

#. Collect the information listed in :ref:`Table 1 <dc_03_0101__table27593495173236>`.

   .. _dc_03_0101__table27593495173236:

   .. table:: **Table 1** Information required for requesting a connection

      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Parameter             | Description                                                                                                                           | Example Value                    |
      +=======================+=======================================================================================================================================+==================================+
      | Domain Name           | Your account name.                                                                                                                    | abc123                           |
      |                       |                                                                                                                                       |                                  |
      |                       | a. Hover the cursor over the username in the upper right corner and select **My Credentials** from the drop-down list.                |                                  |
      |                       | b. On the **My Credentials** page, view the **Domain Name**.                                                                          |                                  |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Project ID            | Project ID. Perform the following operations to obtain the project ID.                                                                | f9578ed9f9b1496da3ddf4ad29ccd891 |
      |                       |                                                                                                                                       |                                  |
      |                       | a. Hover the cursor over the username in the upper right corner and select **My Credentials** from the drop-down list.                |                                  |
      |                       | b. In the lower part of the **My Credentials** page, locate the project.                                                              |                                  |
      |                       | c. View the project ID.                                                                                                               |                                  |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Provider              | The carrier that provides the connection.                                                                                             | others                           |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Region                | Region where the connection is created. Perform the following steps to view the region.                                               | eu-ch2                           |
      |                       |                                                                                                                                       |                                  |
      |                       | a. Log in to the management console.                                                                                                  |                                  |
      |                       |                                                                                                                                       |                                  |
      |                       | b. Check the information in the upper left corner.                                                                                    |                                  |
      |                       |                                                                                                                                       |                                  |
      |                       |    The part in the red box is the region.                                                                                             |                                  |
      |                       |                                                                                                                                       |                                  |
      |                       |    .. _dc_03_0101__dc_02_0202_fig16855152152117:                                                                                      |                                  |
      |                       |                                                                                                                                       |                                  |
      |                       |    .. figure:: /_static/images/en-us_image_0000001218166290.png                                                                       |                                  |
      |                       |       :alt: **Figure 1** Region                                                                                                       |                                  |
      |                       |                                                                                                                                       |                                  |
      |                       |       **Figure 1** Region                                                                                                             |                                  |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Location              | Location where the connection will be terminated.                                                                                     | location                         |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Port Type             | Port type. The value can be **1GE** or **10GE**.                                                                                      | 1GE or 10GE                      |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Bandwidth             | Bandwidth of the connection in the unit of Mbit/s.                                                                                    | 100 Mbit/s                       |
      |                       |                                                                                                                                       |                                  |
      |                       | -  If **Port Type** is set to **1GE**, the bandwidth ranges from 2 Mbit/s to 1000 Mbit/s.                                             |                                  |
      |                       | -  If **Port Type** is set to **10GE**, the bandwidth ranges from 2 Mbit/s to 10,000 Mbit/s.                                          |                                  |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+
      | Name                  | Connection name. The name can contain a maximum of 64 characters. Only letters, digits, underscores (_), and hyphens (-) are allowed. | directconnect-001                |
      +-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+----------------------------------+

#. Submit a request using any of the following methods:

   -  Email: `Send us an email <https://docs.sc.otc.t-systems.com/en-us/public/learnmore.html>`__ with the title "Applying for Enabling the Direct Connect Service".
   -  Hotline: `Call us <https://docs.sc.otc.t-systems.com/en-us/public/learnmore.html>`__ and provide the collected information to our customer service.
   -  Contact our sales representative and provide the collected information to our sales representative.

#. Wait for the notification of the result from the email, customer service, or sales.
