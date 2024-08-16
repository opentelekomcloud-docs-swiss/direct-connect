:original_name: DeleteVifPeer.html

.. _DeleteVifPeer:

Deleting a Virtual Interface Peer
=================================

Function
--------

This API is used to delete a virtual interface. The virtual interface must contain at least one peer, and the last peer cannot be deleted. This API is only available in regions that support IPv6. To use this API, contact customer service.

URI
---

DELETE /v3/{project_id}/dcaas/vif-peers/{vif_peer_id}

.. table:: **Table 1** Path parameters

   =========== ========= ====== ========================================
   Parameter   Mandatory Type   Description
   =========== ========= ====== ========================================
   project_id  Yes       String Specifies the project ID.
   vif_peer_id Yes       String Specifies the virtual interface peer ID.
   =========== ========= ====== ========================================

Request Parameters
------------------

.. table:: **Table 2** Request header parameters

   +-----------------+-----------------+-----------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Parameter       | Mandatory       | Type            | Description                                                                                                                                                                                                        |
   +=================+=================+=================+====================================================================================================================================================================================================================+
   | X-Auth-Token    | Yes             | String          | Specifies the user token. To obtain the token, see section "Obtaining the User Token" in the *Identity and Access Management API Reference*. The token is the value of **X-Subject-Token** in the response header. |
   |                 |                 |                 |                                                                                                                                                                                                                    |
   |                 |                 |                 | Minimum: **0**                                                                                                                                                                                                     |
   |                 |                 |                 |                                                                                                                                                                                                                    |
   |                 |                 |                 | Maximum: **10240**                                                                                                                                                                                                 |
   +-----------------+-----------------+-----------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Response Parameters
-------------------

None

Example Requests
----------------

Deleting a virtual interface peer

.. code-block:: text

   DELETE https://{endpoint}/v3/cfa563efb77d4b6d9960781d82530fd8/dcaas/vif-peers/68250543-0a13-4ac7-aa36-d018856ac640

Example Responses
-----------------

None

Status Codes
------------

=========== ===========
Status Code Description
=========== ===========
204         No Content
=========== ===========

Error Codes
-----------

See :ref:`Error Codes <errorcode>`.
