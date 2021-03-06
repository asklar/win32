---
Description: The GetLocked method retrieves the object's editing state (locked or unlocked).
ms.assetid: ecd258db-36bf-41b6-9bdf-537efcf0a46a
title: IAMTimelineObj::GetLocked method
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IAMTimelineObj.GetLocked
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IAMTimelineObj::GetLocked method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `GetLocked` method retrieves the object's editing state (locked or unlocked). A locked state indicates that the object should not be edited; an unlocked state indicates that the object can be edited. The timeline does not enforce the lock. The locked setting exists only for the convenience of the application.

## Syntax


```C++
 GetLocked(
   BOOL *pVal
);
```



## Parameters

<dl> <dt>

*pVal* 
</dt> <dd>

Receives the object's editing state. If the value is **TRUE**, the object is locked and should not be edited. If **FALSE**, the object is unlocked and can be edited.

</dd> </dl>

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://go.microsoft.com/fwlink/p/?linkid=129787). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IAMTimelineObj Interface**](iamtimelineobj.md)
</dt> <dt>

[Error and Success Codes](error-and-success-codes.md)
</dt> </dl>

 

 




