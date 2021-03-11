---
title: "androidDeviceOwnerKioskModeManagedFolderReference resource type"
description: "A reference to folder containing apps and weblinks on the Managed Home Screen"
author: "dougeby"
localization_priority: Normal
ms.prod: "intune"
doc_type: resourcePageType
---

# androidDeviceOwnerKioskModeManagedFolderReference resource type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

A reference to folder containing apps and weblinks on the Managed Home Screen


Inherits from [androidDeviceOwnerKioskModeHomeScreenItem](../resources/intune-deviceconfig-androiddeviceownerkioskmodehomescreenitem.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|folderName|String|Name of the folder|
|folderIdentifier|String|Unique identifier for the folder|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.androidDeviceOwnerKioskModeManagedFolderReference"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.androidDeviceOwnerKioskModeManagedFolderReference",
  "folderName": "String",
  "folderIdentifier": "String"
}
```



