:original_name: dc_04_0701.html

.. _dc_04_0701:

Key Operations Recorded by CTS
==============================

Scenarios
---------

With Cloud Trace Service (CTS), you can record operations associated with Direct Connect for later query, audit, and backtracking.

Constraints
-----------

You have enabled CTS.

Key Direct Connect Operations Recorded by CTS
---------------------------------------------

.. table:: **Table 1** Direct Connect operations that can be recorded by CTS

   +-------------------------------+-----------------------+------------------------+
   | Operation                     | Resource Type         | Trace                  |
   +===============================+=======================+========================+
   | Requesting a connection       | dcaasConnection       | createConnection       |
   +-------------------------------+-----------------------+------------------------+
   | Modifying a connection        | dcaasConnection       | modifyConnection       |
   +-------------------------------+-----------------------+------------------------+
   | Deleting a connection         | dcaasConnection       | deleteConnection       |
   +-------------------------------+-----------------------+------------------------+
   | Creating a virtual gateway    | dcaasVirtualGateway   | createVirtualGateway   |
   +-------------------------------+-----------------------+------------------------+
   | Modifying a virtual gateway   | dcaasVirtualGateway   | modifyVirtualGateway   |
   +-------------------------------+-----------------------+------------------------+
   | Deleting a virtual gateway    | dcaasVirtualGateway   | deleteVirtualGateway   |
   +-------------------------------+-----------------------+------------------------+
   | Creating a virtual interface  | dcaasVirtualInterface | createVirtualInterface |
   +-------------------------------+-----------------------+------------------------+
   | Modifying a virtual interface | dcaasVirtualInterface | modifyVirtualInterface |
   +-------------------------------+-----------------------+------------------------+
   | Deleting a virtual interface  | dcaasVirtualInterface | deleteVirtualInterface |
   +-------------------------------+-----------------------+------------------------+
