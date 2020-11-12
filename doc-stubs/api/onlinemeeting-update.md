---
title: "Update onlineMeeting"
description: "Update the properties of an onlineMeeting object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update onlineMeeting
Namespace: microsoft.graph

Update the properties of an [onlineMeeting](../resources/onlinemeeting.md) object.

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
PATCH /me/onlineMeetings/{onlineMeetingId}
PATCH /communications/onlineMeetings/{onlineMeetingId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [onlineMeeting](../resources/onlinemeeting.md) object.

The following table shows the properties that are required when you create the [onlineMeeting](../resources/onlinemeeting.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|startDateTime|DateTimeOffset|**TODO: Add Description**|
|endDateTime|DateTimeOffset|**TODO: Add Description**|
|joinWebUrl|String|**TODO: Add Description**|
|subject|String|**TODO: Add Description**|
|participants|[meetingParticipants](../resources/meetingparticipants.md)|**TODO: Add Description**|
|audioConferencing|[audioConferencing](../resources/audioconferencing.md)|**TODO: Add Description**|
|chatInfo|[chatInfo](../resources/chatinfo.md)|**TODO: Add Description**|
|videoTeleconferenceId|String|**TODO: Add Description**|
|externalId|String|**TODO: Add Description**|
|joinInformation|[itemBody](../resources/itembody.md)|**TODO: Add Description**|
|lobbyBypassSettings|[lobbyBypassSettings](../resources/lobbybypasssettings.md)|**TODO: Add Description**|
|isEntryExitAnnounced|Boolean|**TODO: Add Description**|
|allowedPresenters|onlineMeetingPresenters|**TODO: Add Description**. Possible values are: `everyone`, `organization`, `roleIsPresenter`, `organizer`, `unknownFutureValue`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [onlineMeeting](../resources/onlinemeeting.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_onlinemeeting"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/me/onlineMeetings/{onlineMeetingId}
Content-Type: application/json
Content-length: 782

{
  "@odata.type": "#microsoft.graph.onlineMeeting",
  "creationDateTime": "String (timestamp)",
  "startDateTime": "String (timestamp)",
  "endDateTime": "String (timestamp)",
  "joinWebUrl": "String",
  "subject": "String",
  "participants": {
    "@odata.type": "microsoft.graph.meetingParticipants"
  },
  "audioConferencing": {
    "@odata.type": "microsoft.graph.audioConferencing"
  },
  "chatInfo": {
    "@odata.type": "microsoft.graph.chatInfo"
  },
  "videoTeleconferenceId": "String",
  "externalId": "String",
  "joinInformation": {
    "@odata.type": "microsoft.graph.itemBody"
  },
  "lobbyBypassSettings": {
    "@odata.type": "microsoft.graph.lobbyBypassSettings"
  },
  "isEntryExitAnnounced": "Boolean",
  "allowedPresenters": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.onlineMeeting",
  "id": "9187639d-639d-9187-9d63-87919d638791",
  "creationDateTime": "String (timestamp)",
  "startDateTime": "String (timestamp)",
  "endDateTime": "String (timestamp)",
  "joinWebUrl": "String",
  "subject": "String",
  "participants": {
    "@odata.type": "microsoft.graph.meetingParticipants"
  },
  "audioConferencing": {
    "@odata.type": "microsoft.graph.audioConferencing"
  },
  "chatInfo": {
    "@odata.type": "microsoft.graph.chatInfo"
  },
  "videoTeleconferenceId": "String",
  "externalId": "String",
  "joinInformation": {
    "@odata.type": "microsoft.graph.itemBody"
  },
  "lobbyBypassSettings": {
    "@odata.type": "microsoft.graph.lobbyBypassSettings"
  },
  "isEntryExitAnnounced": "Boolean",
  "allowedPresenters": "String"
}
```

