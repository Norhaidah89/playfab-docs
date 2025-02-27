---
title: MultiplayerServerRequestedEventPayload
author: joannaleecy
description: MultiplayerServerRequestedEventPayload data type.
ms.author: joanlee
ms.date: 02/19/2019
ms.topic: article
ms.service: azure-playfab
keywords: playfab, playstream events
ms.localizationpriority: medium
---

# MultiplayerServerRequestedEventPayload

## Properties

|Name|Type|Description|
| :--------------------|:-------------------|:----------------------|
|AllocatedRegion|[AzureRegion](azureregion.md)|The region where the multiplayer server was allocated.|
|AllocatedRegionPreferenceRanking|int32|The integer ranking of what region that the multiplayer server was allocated in from the PreferredRegions list.|
|BuildId|String|The guid string ID of the build.|
|ErrorCode|[GenericErrorCodes](genericerrorcodes.md)|The error when a multiplayer server request fails to allocate. If there was no failure, returns null.|
|PreferredRegions|[AzureRegion](azureregion.md)|The list of preferred region to request a server from.|
|ServerId|String|The string ID of the server which is generated by PlayFab.|
|SessionId|String|The guid string ID of the session.|

