:original_name: ErrorCode.html

.. _ErrorCode:

Error Codes (APIs v3)
=====================

+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| Status Code | Error Code | Description                                                                                                  | Solution                                                   |
+=============+============+==============================================================================================================+============================================================+
| 400         | DC.0000    | The request body is abnormal.                                                                                | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0001    | Request parameter error.                                                                                     | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0002    | The resource does not exist.                                                                                 | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0003    | System error.                                                                                                | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0004    | Invalid IP address.                                                                                          | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0005    | Failed to call the VPC API.                                                                                  | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0006    | Failed to call the MO API.                                                                                   | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0007    | The VPC does not exist.                                                                                      | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0008    | The BGP ASN is out of range.                                                                                 | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0009    | Invalid policy.                                                                                              | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0010    | The VPC_VNI does not exist.                                                                                  | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0011    | The AGENT is abnormal.                                                                                       | Correct the parameter settings and send the request again. |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0012    | Failed to call the CBC API.                                                                                  | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.0013    | You have no permission to operate the field.                                                                 | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1000    | Insufficient connection bandwidth.                                                                           | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1001    | A VLAN is specified for a non-hosted connection.                                                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1002    | Failed to create a hosted connection.                                                                        | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1003    | A VLAN is not specified for a hosted connection.                                                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1004    | A non-operations connection is selected for creating a hosted connection.                                    | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1005    | The connection is abnormal.                                                                                  | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1006    | The device and type cannot be modified when the connection is in use.                                        | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1007    | The connection is in use.                                                                                    | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1008    | Hosted connection VLANs conflict.                                                                            | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1010    | Connection bandwidth is decreased.                                                                           | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1011    | Connection bandwidth cannot be changed.                                                                      | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1012    | The connection does not exist.                                                                               | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1014    | A redundant connection is set for a non-standard connection.                                                 | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1015    | The connection or LAG does not exist.                                                                        | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1017    | The VLAN ID of the hosted connection is 0.                                                                   | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1019    | The connection quota has been used up.                                                                       | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1100    | The local endpoint group ID of the virtual gateway is invalid.                                               | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1101    | The number of local subnets exceeds the limit.                                                               | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1102    | The standby device is specified when the active device is not specified.                                     | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1103    | The active and standby devices are the same.                                                                 | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1104    | The device information cannot be updated for the virtual gateway.                                            | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1105    | The local CIDR block overlap with the remote CIDR block.                                                     | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1106    | The virtual gateway is in use.                                                                               | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1107    | Virtual gateway VLANs are exhausted.                                                                         | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1108    | Virtual gateway VNIs are exhausted.                                                                          | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1109    | Virtual gateway VRFs are exhausted.                                                                          | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1110    | A virtual gateway has been associated with the VPC.                                                          | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1111    | The virtual gateway does not exist.                                                                          | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1112    | The devices used by the virtual gateway are not in active/standby mode.                                      | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1113    | The virtual gateway is in the cutover state.                                                                 | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1114    | **traffic_mode** cannot be updated for VLANs or virtual gateways with a single VTEP device.                  | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1115    | The VNI of the virtual gateway does not exist.                                                               | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1116    | Failed to update the route gateway.                                                                          | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1117    | The virtual gateway has been associated with two connections and cannot be associated with more connections. | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1118    | The virtual gateway is being operated (locked).                                                              | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1119    | Failed to create the route gateway device group.                                                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1120    | The **main_az_list** configuration item is incorrect.                                                        | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1200    | No LAG or connection is specified for the virtual interface.                                                 | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1201    | The connection does not match the virtual gateway type.                                                      | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1202    | Virtual interfaces of the **double ipsec** type cannot be created.                                           | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1203    | No ASN is specified for the BGP virtual interface.                                                           | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1204    | Creating virtual interfaces is not supported for operations connections.                                     | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1205    | The status of the resource associated with the virtual interface is abnormal.                                | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1206    | The hosted connection has been associated with a virtual interface.                                          | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1207    | The VLAN of the virtual interface is inconsistent with that of the hosted connection.                        | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1208    | The bandwidth of the virtual interface associated with a hosted connection cannot be modified.               | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1209    | Virtual interface VLANs conflict.                                                                            | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1210    | The virtual interface status cannot be changed.                                                              | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1211    | The virtual interface does not exist.                                                                        | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1212    | The virtual gateway is in a different group from the connection.                                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1213    | The virtual interface does not match the tenant.                                                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1214    | The virtual interface has been used.                                                                         | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1215    | The virtual interface type does not match.                                                                   | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1216    | The local gateway is invalid.                                                                                | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1217    | The IES edge site ID of the connection does not match that of the local gateway.                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1218    | The local gateway does not match.                                                                            | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1219    | A virtual interface with VLAN 0 is created.                                                                  | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1220    | The **vif email** field on the public network is empty.                                                      | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1221    | The selected virtual gateway device does not support access from Direct Connect locations.                   | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1222    | Insufficient POP VNIs.                                                                                       | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1223    | The local BGP ASN is the same as the remote BGP ASN.                                                         | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1224    | The virtual interface of the connection terminated at a Direct Connect location does not support VLAN 0.     | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1225    | The number of virtual interfaces for which traffic statistics collection is enabled reaches the limit.       | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1226    | Traffic statistics collection cannot be enabled on Layer 2 remote interfaces that have no sub-interfaces.    | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1227    | Traffic statistics cannot be updated because the virtual interface is abnormal.                              | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1400    | The number of endpoint groups reaches the limit.                                                             | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1401    | Duplicate CIDR blocks.                                                                                       | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1402    | The endpoint group is in use.                                                                                | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
| 400         | DC.1403    | The endpoint group does not exist.                                                                           | Contact technical support.                                 |
+-------------+------------+--------------------------------------------------------------------------------------------------------------+------------------------------------------------------------+
