---
title: "userConsentRequest resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userConsentRequest resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [request](../resources/request.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userConsentRequests](../api/appconsentrequest-list-userconsentrequests.md)|[userConsentRequest](../resources/userconsentrequest.md) collection|Get the userConsentRequest resources from the userConsentRequests navigation property.|
|[Create userConsentRequests](../api/appconsentrequest-post-userconsentrequests.md)|[userConsentRequest](../resources/userconsentrequest.md)|Create a new userConsentRequest object.|
|[Update userConsentRequests](../api/appconsentrequest-update-userconsentrequests.md)|[userConsentRequest](../resources/userconsentrequest.md)|Update the properties of a userConsentRequests object.|
|[Get userConsentRequests](../api/appconsentrequest-get-userconsentrequest.md)|[userConsentRequest](../resources/userconsentrequest.md)|Read the properties and relationships of a [userConsentRequest](../resources/userconsentrequest.md) object.|
|[Delete userConsentRequests](../api/appconsentrequest-delete-userconsentrequests.md)|None|Delete a [userConsentRequest](../resources/userconsentrequest.md) object.|
|[List userConsentRequests](../api/userconsentrequest-list.md)|[userConsentRequest](../resources/userconsentrequest.md) collection|Get a list of the [userConsentRequest](../resources/userconsentrequest.md) objects and their properties.|
|[Create userConsentRequest](../api/userconsentrequest-create.md)|[userConsentRequest](../resources/userconsentrequest.md)|Create a new [userConsentRequest](../resources/userconsentrequest.md) object.|
|[Get userConsentRequest](../api/userconsentrequest-get.md)|[userConsentRequest](../resources/userconsentrequest.md)|Read the properties and relationships of a [userConsentRequest](../resources/userconsentrequest.md) object.|
|[Update userConsentRequest](../api/userconsentrequest-update.md)|[userConsentRequest](../resources/userconsentrequest.md)|Update the properties of a [userConsentRequest](../resources/userconsentrequest.md) object.|
|[Delete userConsentRequest](../api/userconsentrequest-delete.md)|None|Deletes a [userConsentRequest](../resources/userconsentrequest.md) object.|
|[stop](../api/userconsentrequest-stop.md)|None|**TODO: Add Description**|
|[recordDecisions](../api/userconsentrequest-recorddecisions.md)|None|**TODO: Add Description**|
|[List approval](../api/userconsentrequest-list-approval.md)|[approval](../resources/approval.md) collection|Get the approval resources from the approval navigation property.|
|[Create approval](../api/userconsentrequest-post-approval.md)|[approval](../resources/approval.md)|Create a new approval object.|
|[Get approval](../api/userconsentrequest-get-approval.md)|[approval](../resources/approval.md)|Read the properties and relationships of an [approval](../resources/approval.md) object.|
|[Update approval](../api/userconsentrequest-update-approval.md)|[approval](../resources/approval.md)|Update the properties of an approval object.|
|[Delete approval](../api/userconsentrequest-delete-approval.md)|None|Delete an [approval](../resources/approval.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdBy|[userIdentity](../resources/useridentity.md)|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [request](../resources/request.md)|
|reason|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|approval|[approval](../resources/approval.md)|**TODO: Add Description** Inherited from [request](../resources/request.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userConsentRequest",
  "baseType": "microsoft.graph.request",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userConsentRequest",
  "id": "String (identifier)",
  "reason": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "createdDateTime": "String (timestamp)"
}
```
