---
title: "directoryObjectPartnerReference resource type"
description: "Represents a reference to a directory object in a partner tenant. Inherits from directoryObject."
---

# directoryObjectPartnerReference resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

Represents a reference to a directory object in a partner tenant. Inherits from [directoryObject](directoryobject.md).

## Properties

| Property | Type | Description |
|:---------------|:--------|:----------|
|description|String| Description of the object returned. Read-only. |
|displayName|String| Name of directory object being returned, like group or application. Read-only. |
|externalPartnerTenantId|Guid| The tenant identifier for the partner tenant. Read-only. |
|objectType|String| The type of the referenced object in the partner tenant. Read-only. |

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.directoryObjectPartnerReference"
}-->

```json
{
  "description": "string ",
  "displayName": "string",
  "externalPartnerTenantId": "string (identifier)",
  "objectType": "string"
}
```

## See also

- [Get partner object references](/graph/api/directoryobject-getbyids)

<!-- uuid: fbec8cd7-cfe4-431d-87fc-d102cd2841a4
2018-12-06 02:01:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "directoryObjectPartnerReference resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->