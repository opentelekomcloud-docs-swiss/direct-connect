:original_name: en-us_topic_0055025300.html

.. _en-us_topic_0055025300:

API Usage Guidelines
====================

Welcome to Direct Connect API Reference. Direct Connect allows you to connect your on-premises data center to the cloud over a dedicated network connection that features stable performance, high transmission speed, low network latency, and secure data transmission. Direct Connect allows you to maximize legacy IT facilities and leverage cloud services to build a flexible, scalable hybrid cloud computing environment.

This document describes how to use application programming interfaces (APIs) to perform operations on Direct Connect resources, such as creating, querying, modifying, or deleting connections. For details about all supported operations, see :ref:`API Overview <en-us_topic_0055025301>`.

Before you access Direct Connect by calling APIs, get yourself familiar with product concepts. For details, see `Service Overview <https://docs.sc.otc.t-systems.com/usermanual/dc/en-us_topic_0032053183.html>`__.

API Calling
-----------

Direct Connect supports Representational State Transfer (REST) APIs that can be called using HTTPS. For details, see :ref:`Calling APIs <en-us_topic_0055025302>`.

Endpoints
---------

An endpoint is the **request address** for calling an API. Endpoints vary depending on services and regions. For the endpoints of all services, see `Regions and Endpoints <https://docs.sc.otc.t-systems.com/en-us/endpoint/index.html>`__.

Constraints
-----------

The number of Direct Connect resources that you can create is determined by your quotas. To view or increase the quotas, see `Constraints and Limitations <https://docs.sc.otc.t-systems.com/usermanual/dc/en-us_topic_0166140183.html>`__ in the *Direct Connect User Guide*.

For more constraints, see API description.

Glossary
--------

-  Domain

   A domain has full access permissions for all of its cloud services and resources. It can be used to reset user passwords and grant user permissions. The domain should not be used directly to perform routine management. To ensure domain security, create Identity and Access Management (IAM) users and grant them permissions for routine management.

-  User

   An IAM user is created by an account in IAM to use cloud services. Each IAM user has its own identity credentials (password and access keys).

   API authentication requires information such as the domain name, username, and password.

-  Region

   A region is a geographic area in which cloud resources are deployed. Availability zones (AZs) in the same region can communicate with each other over an intranet, while AZs in different regions cannot. Deploying cloud resources in different regions can better suit certain user requirements or comply with local laws or regulations.

-  AZ

   An Availability Zone (AZ) comprises of one or more physical data centers equipped with independent ventilation, fire, water, and electricity facilities. Compute, network, storage, and other resources in an AZ are logically divided into multiple clusters. AZs within a region are interconnected using high-speed optical fibers to allow you to build cross-AZ, high-availability systems.

-  Project

   A project corresponds to a region. Default projects are defined to group and physically isolate resources (including computing, storage, and network resources) across regions. Users can be granted permissions in a default project to access all resources under their domains in the region associated with the project. If you need more refined access control, create subprojects under a default project and add resources to subprojects. Then you can assign users the permissions required to access only the resources in the specific subprojects.


   .. figure:: /_static/images/en-us_image_0000002425577453.png
      :alt: **Figure 1** Project isolating model

      **Figure 1** Project isolating model
