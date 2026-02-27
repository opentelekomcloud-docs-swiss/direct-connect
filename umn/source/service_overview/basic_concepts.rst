:original_name: en-us_topic_0112674194.html

.. _en-us_topic_0112674194:

Basic Concepts
==============

Connection
----------

A connection links your on-premises data center and a carrier's physical network at the Direct Connect location you select.

A standard connection provides a port that is exclusive to you and allows you to have multiple virtual interfaces associated.

Virtual Gateway
---------------

A virtual gateway is a logical gateway for accessing a VPC. A virtual gateway can be associated with only one VPC. Multiple connections can access the same VPC through a single virtual gateway.

Virtual Interface
-----------------

A virtual interface is an entrance for you to access VPCs through a leased line. A virtual interface associates your connection with a virtual gateway, which connects to a VPC so that your network can access the cloud.

Virtual Interface Peer
----------------------

A configuration of the virtual interface to support the IPv4/IPv6 dual stack. The IP address type of a peer depends on the associated connection.
