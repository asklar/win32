---
Description: The RemoveI method removes the item at the specified position.
ms.assetid: 6a6d54ce-7ab3-48dd-8d5d-1315816bcbb9
title: CBaseList.RemoveI method
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CBaseList.RemoveI
api_type: 
- COM
api_location: 
- Strmbase.lib
- Strmbase.dll
- Strmbasd.lib
- Strmbasd.dll
---

# CBaseList.RemoveI method

The `RemoveI` method removes the item at the specified position.

## Syntax


```C++
void* RemoveI(
   POSITION pos
);
```



## Parameters

<dl> <dt>

*pos* 
</dt> <dd>

POSITION value indicating the item to remove.

</dd> </dl>

## Return value

Returns a pointer to the item.

## Remarks

This method deletes the node from the list, but does not delete the item contained in that node.

If *pos* is **NULL**, the method returns **NULL**.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Wxlist.h (include Streams.h)</dt> </dl>                                                                                    |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CBaseList Class**](cbaselist.md)
</dt> </dl>

 

 




