:original_name: en-dc_topic_0055025318.html

.. _en-dc_topic_0055025318:

Querying a Connection
=====================

Function
--------

This API is used to query a connection.

URI
---

GET /v2.0/dcaas/direct-connects/{direct_connect_id}

.. table:: **Table 1** Parameter description

   ================= ====== ========= ============================
   Parameter         Type   Mandatory Description
   ================= ====== ========= ============================
   direct_connect_id String Yes       Specifies the connection ID.
   ================= ====== ========= ============================

Request
-------

None

Response
--------

:ref:`Table 2 <en-dc_topic_0055025318__table7306830153125>` lists the response parameter.

.. _en-dc_topic_0055025318__table7306830153125:

.. table:: **Table 2** Response parameter

   ============== ========== ========================================
   Parameter      Type       Description
   ============== ========== ========================================
   direct_connect Dictionary Specifies the **direct_connect** object.
   ============== ========== ========================================

For details about the **direct_connect** field, see :ref:`Table 1 <en-dc_topic_0055025314__en-us_topic_0070676569_table49902238182444>`.

Examples
--------

-  Example request

.. code-block:: text

   GET /v2.0/dcaas/direct-connects/{direct_connect_id}

-  Example response

   .. code-block::

      {
          "direct_connect": {
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
             }
      }

Status Code
-----------

For details, see :ref:`Common Status Codes <en-dc_topic_0055025342>`.
