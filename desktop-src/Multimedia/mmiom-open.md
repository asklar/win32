---
title: MMIOM_OPEN message
description: The MMIOM\_OPEN message is sent to an I/O procedure by the mmioOpen function to request that a file be opened or deleted.
ms.assetid: 02b2cf22-21a3-4f49-b90e-7b44478c0168
keywords:
- MMIOM_OPEN message Windows Multimedia
topic_type:
- apiref
api_name:
- MMIOM_OPEN
api_location:
- Mmsystem.h
api_type:
- HeaderDef
ms.topic: reference
ms.date: 05/31/2018
---

# MMIOM\_OPEN message

The **MMIOM\_OPEN** message is sent to an I/O procedure by the [**mmioOpen**](https://msdn.microsoft.com/en-us/library/Dd757331(v=VS.85).aspx) function to request that a file be opened or deleted.


```C++
MMIOM_OPEN 
lParam1 = (LPARAM) lpszFileName 
lParam2 = reserved 
```



## Parameters

<dl> <dt>

<span id="lpszFileName"></span><span id="lpszfilename"></span><span id="LPSZFILENAME"></span>*lpszFileName*
</dt> <dd>

Null-terminated string containing the name of the file to open.

</dd> <dt>

<span id="lParam2"></span><span id="lparam2"></span><span id="LPARAM2"></span>*lParam2*
</dt> <dd>

Reserved.

</dd> </dl>

## Return Value

Returns MMSYSERR\_NOERROR if successful or an error otherwise. Possible error values include the following:



|                    |                                             |
|--------------------|---------------------------------------------|
| MMIOM\_CANNOTOPEN  | The file could not be opened.               |
| MMIOM\_OUTOFMEMORY | Not enough memory to perform the operation. |



 

## Remarks

The **dwFlags** member of the [**MMIOINFO**](https://msdn.microsoft.com/en-us/library/Dd757322(v=VS.85).aspx) structure contains flags passed to the [**mmioOpen**](https://msdn.microsoft.com/en-us/library/Dd757331(v=VS.85).aspx) function.

The **lDiskOffset** member of the [**MMIOINFO**](https://msdn.microsoft.com/en-us/library/Dd757322(v=VS.85).aspx) structure is initialized to zero. If this value is incorrect, the I/O procedure must correct it.

If the application passed an [**MMIOINFO**](https://msdn.microsoft.com/en-us/library/Dd757322(v=VS.85).aspx) structure to [**mmioOpen**](https://msdn.microsoft.com/en-us/library/Dd757331(v=VS.85).aspx), the return value is returned in the **wErrorRet** member.

## Requirements



|                                     |                                                                                                           |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 2000 Professional \[desktop apps only\]<br/>                                                |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                                      |
| Header<br/>                   | <dl> <dt>Mmsystem.h (include Windows.h)</dt> </dl> |



 

 





