:original_name: en-us_topic_0055025324.html

.. _en-us_topic_0055025324:

Deleting a Virtual Gateway
==========================

Function
--------

This API is used to delete a virtual gateway.

URI
---

DELETE /v2.0/dcaas/virtual-gateways/{virtual_gateway_id}

.. table:: **Table 1** Parameter description

   ================== ====== ========= =================================
   Parameter          Type   Mandatory Description
   ================== ====== ========= =================================
   virtual_gateway_id String Yes       Specifies the virtual gateway ID.
   ================== ====== ========= =================================

Request
-------

:ref:`Table 2 <en-us_topic_0055025324__table2198437322244>` lists the request parameter.

.. _en-us_topic_0055025324__table2198437322244:

.. table:: **Table 2** Request parameter

   ================== ====== ========= =================================
   Parameter          Type   Mandatory Description
   ================== ====== ========= =================================
   virtual_gateway_id String Yes       Specifies the virtual gateway ID.
   ================== ====== ========= =================================

Response
--------

None

Examples
--------

-  Example request

.. code-block:: text

   DELETE /v2.0/dcaas/virtual-gateways/{virtual_gateway_id}

-  Response example

   None

Status Codes
------------

For details, see :ref:`Common Status Codes <en-us_topic_0055025342>`.
