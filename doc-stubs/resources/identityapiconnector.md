---
title: "identityApiConnector resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityApiConnector resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List apiConnectors](../api/identitycontainer-list-apiconnectors.md)|[identityApiConnector](../resources/identityapiconnector.md) collection|Get the identityApiConnector resources from the apiConnectors navigation property.|
|[Create apiConnectors](../api/identitycontainer-post-apiconnectors.md)|[identityApiConnector](../resources/identityapiconnector.md)|Create a new identityApiConnector object.|
|[Update apiConnectors](../api/identitycontainer-update-apiconnectors.md)|[identityApiConnector](../resources/identityapiconnector.md)|Update the properties of an apiConnectors object.|
|[Get apiConnectors](../api/identitycontainer-get-identityapiconnector.md)|[identityApiConnector](../resources/identityapiconnector.md)|Read the properties and relationships of an [identityApiConnector](../resources/identityapiconnector.md) object.|
|[Delete apiConnectors](../api/identitycontainer-delete-apiconnectors.md)|None|Delete an [identityApiConnector](../resources/identityapiconnector.md) object.|
|[List identityApiConnectors](../api/identityapiconnector-list.md)|[identityApiConnector](../resources/identityapiconnector.md) collection|Get a list of the [identityApiConnector](../resources/identityapiconnector.md) objects and their properties.|
|[Create identityApiConnector](../api/identityapiconnector-create.md)|[identityApiConnector](../resources/identityapiconnector.md)|Create a new [identityApiConnector](../resources/identityapiconnector.md) object.|
|[Get identityApiConnector](../api/identityapiconnector-get.md)|[identityApiConnector](../resources/identityapiconnector.md)|Read the properties and relationships of an [identityApiConnector](../resources/identityapiconnector.md) object.|
|[Update identityApiConnector](../api/identityapiconnector-update.md)|[identityApiConnector](../resources/identityapiconnector.md)|Update the properties of an [identityApiConnector](../resources/identityapiconnector.md) object.|
|[Delete identityApiConnector](../api/identityapiconnector-delete.md)|None|Deletes an [identityApiConnector](../resources/identityapiconnector.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|[apiAuthenticationConfigurationBase](../resources/apiauthenticationconfigurationbase.md)|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|targetUrl|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityApiConnector",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityApiConnector",
  "id": "String (identifier)",
  "displayName": "String",
  "targetUrl": "String",
  "authenticationConfiguration": {
    "@odata.type": "microsoft.graph.apiAuthenticationConfigurationBase"
  }
}
```
