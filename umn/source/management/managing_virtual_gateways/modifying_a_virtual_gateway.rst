:original_name: en_us_topic_0166140212.html

.. _en_us_topic_0166140212:

Modifying a Virtual Gateway
===========================

Scenarios
---------

Modify the name, subnet CIDR block, and description of a virtual gateway. You can only add subnet CIDR blocks subnet but cannot delete existing subnet CIDR blocks.

Procedure
---------

#. Log in to the management console.
#. Click |image1| in the upper left corner and select a region and project.
#. In the service list, choose **Network** > **Direct Connect**.
#. In the navigation pane on the left, choose **Direct Connect** > **Virtual Gateways**.

5. Locate the virtual gateway you want to modify, click **Modify** in the **Operation** column, and modify the virtual gateway.


   .. figure:: /_static/images/en-us_image_0000001251258237.png
      :alt: **Figure 1** Modifying a virtual gateway

      **Figure 1** Modifying a virtual gateway

   .. note::

      -  If you select only IPv4 or IPv6 for **Subnet CIDR Block** when you create a virtual gateway, you cannot deselect the previously selected Subnet CIDR block when you modify the virtual gateway, but you can enable the other Subnet CIDR block.
      -  If you select both IPv4 and IPv6 for **Subnet CIDR Block** when you create a virtual gateway, both IPv4 and IPv6 cannot be deselected when you modify the virtual gateway.

6. Modify the parameters and click **OK**.

.. |image1| image:: /_static/images/en-us_image_0000001187260408.png
