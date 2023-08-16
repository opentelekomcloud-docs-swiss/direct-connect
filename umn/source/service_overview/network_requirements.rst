:original_name: en-us_topic_0166140252.html

.. _en-us_topic_0166140252:

Network Requirements
====================

-  Your network must use a single-mode fiber with a 1GE or 10GE optical module to connect to the access device in the cloud.
-  Auto-negotiation for the port must be disabled.
-  Port speed and full-duplex mode must be manually configured.
-  802.1Q VLAN encapsulation must be supported on the entire connection, including intermediate devices.
-  If BGP routing is used, your device must support BGP and BGP MD5 authentication.
-  (Optional) You can configure Bidirectional Forwarding Detection (BFD) on the network.
-  The maximum transmission unit (MTU) supported at the physical layer is 1522 bytes (14-byte Ethernet header + 4-byte VLAN tag + 1500-byte IP datagram + 4-byte frame check sequence).
-  Private IP addresses are recommended on the cloud, and IP address ranges for interworking cannot conflict with each other.
