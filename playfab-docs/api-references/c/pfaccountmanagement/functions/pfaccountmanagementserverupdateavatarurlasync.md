---
author: jasonsandlin
title: "PFAccountManagementServerUpdateAvatarUrlAsync"
description: "Update the avatar URL of the specified player"
ms.author: jasonsa
ms.topic: reference
ms.service: azure-playfab
ms.date: 02/22/2024
---

# PFAccountManagementServerUpdateAvatarUrlAsync  

Update the avatar URL of the specified player  

## Syntax  
  
```cpp
HRESULT PFAccountManagementServerUpdateAvatarUrlAsync(  
    PFEntityHandle titleEntityHandle,  
    const PFAccountManagementServerUpdateAvatarUrlRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`titleEntityHandle`** &nbsp; PFEntityHandle  
  
PFEntityHandle for a title Entity obtained using PFAuthenticationGetEntityWithSecretKeyAsync.  
  
**`request`** &nbsp; [PFAccountManagementServerUpdateAvatarUrlRequest*](../../pfaccountmanagementtypes/structs/pfaccountmanagementserverupdateavatarurlrequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This API is available on Win32, Linux, and macOS. Call XAsyncGetStatus to get the status of the operation. If the service call is unsuccessful, the async result will be one of global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
## Requirements  
  
**Header:** PFAccountManagement.h
  
## See also  
[PFAccountManagement members](../pfaccountmanagement_members.md)  

  
  
