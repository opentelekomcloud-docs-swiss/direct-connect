:original_name: dc_03_0200.html

.. _dc_03_0200:

Creating a Virtual Gateway
==========================

Scenarios
---------

Create a virtual gateway based on service requirements.

Procedure
---------

#. Log in to the management console.

#. Click |image1| in the upper left corner and select a region and project.

#. In the service list, choose **Network** > **Direct Connect**.

#. In the navigation pane on the left, choose **Direct Connect** > **Virtual Gateways**.

#. Click **Create Virtual Gateway**.

#. Configure the parameters.


   .. figure:: /_static/images/en-us_image_0000001204177204.png
      :alt: **Figure 1** Creating a virtual gateway

      **Figure 1** Creating a virtual gateway

   .. table:: **Table 1** Parameter description

      +-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
      | Parameter                         | Description                                                                                                                                                     |
      +===================================+=================================================================================================================================================================+
      | Name                              | Specifies the virtual gateway name.                                                                                                                             |
      |                                   |                                                                                                                                                                 |
      |                                   | The name can contain 1 to 64 characters.                                                                                                                        |
      |                                   |                                                                                                                                                                 |
      |                                   | Only digits, letters, underscores (_), hyphens (-), and periods (.) are allowed.                                                                                |
      +-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
      | VPC                               | Specifies the VPC you want to access using the connection.                                                                                                      |
      +-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
      | Subnet CIDR Block                 | Specifies the VPC subnets that can be accessed by the on-premises data center or network over the connection. Both IPv4 subnets and IPv6 subnets are supported. |
      |                                   |                                                                                                                                                                 |
      |                                   | You can enter one or more CIDR blocks and separate every entry with a comma (,).                                                                                |
      +-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
      | Description                       | Provides supplementary information about the virtual gateway.                                                                                                   |
      |                                   |                                                                                                                                                                 |
      |                                   | The value contains 0 to 128 characters.                                                                                                                         |
      +-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+

#. Click **OK**.

.. |image1| image:: /_static/images/en-us_image_0000001249256415.png
