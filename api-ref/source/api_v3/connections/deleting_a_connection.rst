:original_name: DeleteDirectConnect.html

.. _DeleteDirectConnect:

Deleting a Connection
=====================

Function
--------

This API is used to delete a connection.

URI
---

DELETE /v3/{project_id}/dcaas/direct-connects/{direct_connect_id}

.. table:: **Table 1** Path parameters

   +-------------------+-----------------+-----------------+------------------------------+
   | Parameter         | Mandatory       | Type            | Description                  |
   +===================+=================+=================+==============================+
   | direct_connect_id | Yes             | String          | Specifies the connection ID. |
   |                   |                 |                 |                              |
   |                   |                 |                 | Minimum: **36**              |
   |                   |                 |                 |                              |
   |                   |                 |                 | Maximum: **36**              |
   +-------------------+-----------------+-----------------+------------------------------+
   | project_id        | Yes             | String          | Specifies the project ID.    |
   +-------------------+-----------------+-----------------+------------------------------+

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

Deleting a connection

.. code-block:: text

   DELETE https://{dc_endpoint}/v3/6fbe9263116a4b68818cf1edce16bc4f/dcaas/direct-connects/6ecd9cf3-ca64-46c7-863f-f2eb1b9e838a

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
