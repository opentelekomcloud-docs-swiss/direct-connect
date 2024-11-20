:original_name: en-us_topic_0032053183.html

.. _en-us_topic_0032053183:

Overview
========

What Is Direct Connect?
-----------------------

Direct Connect establishes a dedicated connection between your data center and the cloud. You can use one connection to access cloud computing resources in different regions, helping build a secure and reliable hybrid environment.

Why Direct Connect?
-------------------

-  Network quality: Direct Connect allows you to establish a dedicated network for data transmission, which brings high network performance, low latency, and excellent user experience.
-  Security: Direct Connect establishes private connectivity between your on-premises data center and the cloud. Data is transmitted over a secure dedicated connection.
-  Transmission speed: A connection supports a maximum of 10 Gbit/s bandwidth, meeting various bandwidth requirements.

Components
----------

There are three key components for you to use Direct Connect: connection, virtual gateway, and virtual interface.

-  **Connection**

   A connection links your on-premises data center and a carrier's physical network at the Direct Connect location you select.

   A standard connection provides a port that is exclusive to you and allows you to have multiple virtual interfaces associated.

-  **Virtual gateway**

   A virtual gateway is a logical gateway for accessing a VPC. A virtual gateway can be associated with only one VPC. Multiple connections can access the same VPC through a single virtual gateway.

-  **Virtual interface**

   A virtual interface is an entrance for you to access VPCs through a leased line. A virtual interface associates your connection with a virtual gateway, which connects to a VPC so that your network can access the cloud.
