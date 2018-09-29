# attachDisk


## Description
Attach a data disk (cloud hard disk) for a virtual machine, and the Virtual Machines and the Cloud Disk Service are not attached when they are in progress. <br>
The virtual machine status must be running or stopped status. <br>
The VM of the local disk as system disk can be attached with eight data disks, and the VM of Cloud Disk Service can be attached with seven data disks.


## Request method
POST

## Request address
https://vm.jdcloud-api.com/1.0.3/regions/{regionId}/instances/{instanceId}:attachDisk

|Name|Type|Required or not|Default value|Description|
|---|---|---|---|---|
|**instanceId**|String|True| |VM ID|
|**regionId**|String|True| |Region ID|

## Request parameter
|Name|Type|Required or not|Default value|Description|
|---|---|---|---|---|
|**autoDelete**|Boolean|False| |Automatically delete this Cloud Disk Service with the machine, False by default. It supports only the cloud disk service that is paid by instance types. This parameter is not valid for a shared type cloud disk service.|
|**deviceName**|String|False| |The data disk logical attach point [vda, vdb, vdc, vdd, vde, vdb, vdg, vdh, vdi], vda required when the system disk is attached.|
|**diskId**|String|True| |Cloud Disk Service ID|


## Response parameter
None



## Response code
|Return code|Description|
|---|---|
|**400**|Invalid parameter|
|**401**|Authentication failed|
|**404**|Not Found  |
|**503**|Service unavailable|
|**200**|OK|
|**500**|Internal server error|
