---
author: jasonsandlin
title: "PFCatalogGetItemPublishStatusGetResultSize"
description: "Get the size in bytes needed to store the result of a GetItemPublishStatus call."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFCatalogGetItemPublishStatusGetResultSize  

Get the size in bytes needed to store the result of a GetItemPublishStatus call.  

## Syntax  
  
```cpp
HRESULT PFCatalogGetItemPublishStatusGetResultSize(  
    XAsyncBlock* async,  
    size_t* bufferSize  
)  
```  
  
### Parameters  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
**`bufferSize`** &nbsp; size_t*  
*output*  
  
The buffer size in bytes required for the result.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
  
## Requirements  
  
**Header:** PFCatalog.h
  
## See also  
[PFCatalog members](../pfcatalog_members.md)  

  
  