:original_name: en-us_topic_0032053183.html

.. _en-us_topic_0032053183:

Overview
========

What Is Direct Connect?
-----------------------

Direct Connect establishes a dedicated connection between your data center and the cloud. You can use one connection to access cloud computing resources in different regions, helping build a secure and reliable hybrid environment.

Application Scenarios
---------------------

You need a dedicated network connection between your data center and a Virtual Private Cloud (VPC) to ensure high bandwidth, low latency, and robust security.

Components
----------

There are three key components for you to use Direct Connect: connection, virtual gateway, and virtual interface.

-  **Connection**

   A connection is a dedicated network connection between your on-premises data center and a Direct Connect location over a leased line provided by a carrier. You can request standard connections.

   A standard connection provides a port that is exclusive to you and allows you to have multiple virtual interfaces associated.

-  **Virtual gateway**

   A virtual gateway is a logical gateway for accessing a VPC. A virtual gateway can be associated with only one VPC. Multiple connections can access the same VPC through a single virtual gateway.

-  **Virtual interface**

   A virtual interface is an entrance for you to access VPCs through a leased line. A virtual interface associates your connection with a virtual gateway, which connects to a VPC so that your network can access the cloud.

Advantages
----------

-  High security

   You can use Direct Connect to connect to VPCs. Direct Connect provides a dedicated channel for communication, and this channel is isolated from other networks, ensuring the security.

-  Low latency

   A dedicated network is used for data transmission, which brings high network performance, low latency, and excellent user experience.

-  High bandwidth

   A connection supports a maximum of 10 Gbit/s bandwidth, meeting various requirements.

-  Seamless resource expansion

   You can use Direct Connect to connect your data center to the resources in the cloud, which enables you to deploy a hybrid cloud in a flexible and scalable manner.
