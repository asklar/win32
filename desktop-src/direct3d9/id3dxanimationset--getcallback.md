---
Description: Gets information about a specific callback in the animation set.
ms.assetid: e8388bfc-5438-4216-a98f-dd0dbca12c87
title: ID3DXAnimationSet::GetCallback method
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- ID3DXAnimationSet.GetCallback
api_type: 
- COM
api_location: 
- d3dx9.lib
- d3dx9.dll
---

# ID3DXAnimationSet::GetCallback method

Gets information about a specific callback in the animation set.

## Syntax


```C++
HRESULT GetCallback(
  [in]  DOUBLE Position,
  [in]  DWORD  Flags,
  [out] DOUBLE *pCallbackPosition,
  [out] LPVOID *ppCallbackData
);
```



## Parameters

<dl> <dt>

*Position* \[in\]
</dt> <dd>

Type: **[**DOUBLE**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)**

Position from which to find callbacks.

</dd> <dt>

*Flags* \[in\]
</dt> <dd>

Type: **[**DWORD**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)**

Callback search flags. This parameter can be set to a combination of one or more flags from [**D3DXCALLBACK\_SEARCH\_FLAGS**](https://msdn.microsoft.com/en-us/library/Bb172714(v=VS.85).aspx).

</dd> <dt>

*pCallbackPosition* \[out\]
</dt> <dd>

Type: **[**DOUBLE**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)\***

Pointer to the position of the callback.

</dd> <dt>

*ppCallbackData* \[out\]
</dt> <dd>

Type: **[**LPVOID**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)\***

Address of the callback data pointer.

</dd> </dl>

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/en-us/library/Bb401631(v=MSDN.10).aspx)**

The return values of this method are implemented by an application programmer. In general, if no error occurs, program the method to return D3D\_OK. Otherwise, program the method to return an appropriate error message from [D3DERR](d3derr.md) or [**D3DXERR**](https://msdn.microsoft.com/en-us/library/Bb172825(v=VS.85).aspx).

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx9anim.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>   |



## See also

<dl> <dt>

[ID3DXAnimationSet](id3dxanimationset.md)
</dt> </dl>

 

 




