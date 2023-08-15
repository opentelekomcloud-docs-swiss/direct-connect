:original_name: en-dc_topic_0055025316.html

.. _en-dc_topic_0055025316:

Querying the Connection List
============================

Function
--------

This API is used to query the connection list.

URI
---

GET /v2.0/dcaas/direct-connects

.. table:: **Table 1** Parameter description

   =============== ==== ========= ==============================
   Parameter       Type Mandatory Description
   =============== ==== ========= ==============================
   direct_connects List Yes       Specifies the connection list.
   =============== ==== ========= ==============================

Request
-------

:ref:`Table 2 <en-dc_topic_0055025316__table2198437322244>` lists the request parameter.

.. _en-dc_topic_0055025316__table2198437322244:

.. table:: **Table 2** Request parameter

   +-----------------+-----------------+-----------------+------------------------------------------------------------+
   | Parameter       | Type            | Mandatory       | Description                                                |
   +=================+=================+=================+============================================================+
   | fields          | String          | No              | Specifies the parameters expected to be returned.          |
   |                 |                 |                 |                                                            |
   |                 |                 |                 | If you do not specify it, all parameters will be returned. |
   +-----------------+-----------------+-----------------+------------------------------------------------------------+

Response
--------

:ref:`Table 3 <en-dc_topic_0055025316__table122627546489>` lists the response parameter.

.. _en-dc_topic_0055025316__table122627546489:

.. table:: **Table 3** Response parameter

   =============== ==== ==============================
   Parameter       Type Description
   =============== ==== ==============================
   direct_connects List Specifies the connection list.
   =============== ==== ==============================

For details about the **direct_connects** field, see :ref:`Table 1 <en-dc_topic_0055025314__en-us_topic_0070676569_table49902238182444>`.

Examples
--------

-  Example request

   #. Querying all connections

   .. code-block:: text

      GET /v2.0/dcaas/direct-connects

   2. Querying a connection using its ID

   .. code-block:: text

      GET /v2.0/dcaas/direct-connects?id=6ecd9cf3-ca64-46c7-863f-f2eb1b9e838a

-  Example response

   .. code-block::

      {
          "direct_connects" : [{
              "id": "d58f30f5-549b-401f-ab42-dd7d2898deb5",
              "name": "direct connect",
              "description": null,
              "tenant_id": "0605768a3300d5762f82c01180692873",
              "type": "standard",
              "hosting_id": null,
              "vlan": null,
              "charge_mode": "prepayment",
              "port_type": "1G",
              "bandwidth": 1000,
              "location": "hangzhou",
              "peer_location": null,
              "device_id": "aaa_01",
              "interface_name": null,
              "redundant_id": null,
              "provider": "test",
              "provider_status": "DOWN",
              "status": "BUILD",
              "apply_time": "2021-10-11T12:54:46Z",
              "reason": null,
              "admin_state_up": true,
              "order_id": "CS2110112054UWX16",
              "product_id": "00301-161093-0--0",
              "spec_code": "1ge",
              "applicant": null,
              "mobile": null,
              "email": null,
              "create_time": "2021-10-11T12:54:46Z",
              "region_id": null,
              "service_key": null,
              "cable_label": null,
              "peer_port_type": null,
              "peer_provider": null,
              "onestop_product_id": null,
              "building_line_product_id": null,
              "last_onestop_product_id": null,
              "period_type": null,
              "period_num": null,
              "vgw_type": "default",
              "lag_id": null
          }]
      }

Status Code
-----------

For details, see :ref:`Common Status Codes <en-dc_topic_0055025342>`.
