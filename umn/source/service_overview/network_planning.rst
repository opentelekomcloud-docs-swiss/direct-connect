:original_name: en-us_topic_0166140252.html

.. _en-us_topic_0166140252:

Network Planning
================

Solution Overview
-----------------

You can connect your on-premises data center to the cloud using a standard or hosted connection:

-  Standard connection

   A standard connection provides an exclusive port. You can create standard connections on the console and create multiple connections terminating at different locations as backups for each other to improve reliability. If, for some reason, there is only one carrier, you can create redundancy by configuring different routes for your connections as shown in :ref:`Figure 1 <en-us_topic_0166140252__fig1376510262315>`.

   .. _en-us_topic_0166140252__fig1376510262315:

   .. figure:: /_static/images/en-us_image_0000001490493036.png
      :alt: **Figure 1** Accessing the cloud using standard connections

      **Figure 1** Accessing the cloud using standard connections

-  Hosted Connections

   If you use a hosted connection to access the cloud, the port you use is shared.

   You request a connection from a partner who has a line terminated at the Direct Connect location that is nearby to your on-premises data center.


   .. figure:: /_static/images/en-us_image_0000001490824710.png
      :alt: **Figure 2** Accessing the cloud using hosted connections

      **Figure 2** Accessing the cloud using hosted connections

Network Requirements
--------------------

-  Your network must use a single-mode fiber with a 1GE or 10GE optical module to connect to the access device in the cloud.
-  Auto-negotiation for the port must be disabled.
-  Port speed and full-duplex mode must be manually configured.
-  802.1Q VLAN encapsulation must be supported on the entire connection, including intermediate devices.
-  If BGP routing is used, your device must support BGP and BGP MD5 authentication.
-  (Optional) You can configure Bidirectional Forwarding Detection (BFD) on the network.
-  The maximum transmission unit (MTU) supported at the physical layer is 1522 bytes (14-byte Ethernet header + 4-byte VLAN tag + 1500-byte IP datagram + 4-byte frame check sequence).
-  Private IP addresses are recommended on the cloud, and IP address ranges for interworking cannot conflict with each other.
