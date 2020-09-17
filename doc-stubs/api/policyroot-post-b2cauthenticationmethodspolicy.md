---
title: "Create b2cAuthenticationMethodsPolicy"
description: "Create a new b2cAuthenticationMethodsPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create b2cAuthenticationMethodsPolicy
Namespace: microsoft.graph

Create a new b2cAuthenticationMethodsPolicy object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST ** Collection URI for Microsoft.Cpim.Api.DataModels.b2cAuthenticationMethodsPolicy not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.

The following table shows the properties that are required when you create the [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|isPhoneOneTimePasswordAuthenticationEnabled|Boolean|**TODO: Add Description**|
|isEmailPasswordAuthenticationEnabled|Boolean|**TODO: Add Description**|
|isUserNameAuthenticationEnabled|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_b2cauthenticationmethodspolicy_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for Microsoft.Cpim.Api.DataModels.b2cAuthenticationMethodsPolicy not found
Content-Type: application/json
Content-length: 250

{
  "@odata.type": "#Microsoft.Cpim.Api.DataModels.b2cAuthenticationMethodsPolicy",
  "isPhoneOneTimePasswordAuthenticationEnabled": "Boolean",
  "isEmailPasswordAuthenticationEnabled": "Boolean",
  "isUserNameAuthenticationEnabled": "Boolean"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.Cpim.Api.DataModels.b2cAuthenticationMethodsPolicy"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#Microsoft.Cpim.Api.DataModels.b2cAuthenticationMethodsPolicy",
  "isPhoneOneTimePasswordAuthenticationEnabled": "Boolean",
  "isEmailPasswordAuthenticationEnabled": "Boolean",
  "isUserNameAuthenticationEnabled": "Boolean"
}
```
