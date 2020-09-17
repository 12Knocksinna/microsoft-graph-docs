---
title: "policyRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# policyRoot resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List policyRoots](../api/policyroot-list.md)|[policyRoot](../resources/policyroot.md) collection|Get a list of the [policyRoot](../resources/policyroot.md) objects and their properties.|
|[Create policyRoot](../api/policyroot-create.md)|[policyRoot](../resources/policyroot.md)|Create a new [policyRoot](../resources/policyroot.md) object.|
|[Get policyRoot](../api/policyroot-get.md)|[policyRoot](../resources/policyroot.md)|Read the properties and relationships of a [policyRoot](../resources/policyroot.md) object.|
|[Update policyRoot](../api/policyroot-update.md)|[policyRoot](../resources/policyroot.md)|Update the properties of a [policyRoot](../resources/policyroot.md) object.|
|[Delete policyRoot](../api/policyroot-delete.md)|None|Deletes a [policyRoot](../resources/policyroot.md) object.|
|[List b2cAuthenticationMethodsPolicy](../api/policyroot-list-b2cauthenticationmethodspolicy.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) collection|Get the b2cAuthenticationMethodsPolicy resources from the b2cAuthenticationMethodsPolicy navigation property.|
|[Create b2cAuthenticationMethodsPolicy](../api/policyroot-post-b2cauthenticationmethodspolicy.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|Create a new b2cAuthenticationMethodsPolicy object.|
|[Get b2cAuthenticationMethodsPolicy](../api/policyroot-get-b2cauthenticationmethodspolicy.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|Read the properties and relationships of a [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.|
|[Update b2cAuthenticationMethodsPolicy](../api/policyroot-update-b2cauthenticationmethodspolicy.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|Update the properties of a b2cAuthenticationMethodsPolicy object.|
|[Delete b2cAuthenticationMethodsPolicy](../api/policyroot-delete-b2cauthenticationmethodspolicy.md)|None|Delete a [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|authenticationFlowsPolicy|[authenticationFlowsPolicy](../resources/authenticationflowspolicy.md)|**TODO: Add Description**|
|b2cAuthenticationMethodsPolicy|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.policyRoot",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.policyRoot"
}
```
