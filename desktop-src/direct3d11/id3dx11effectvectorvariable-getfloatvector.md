---
title: ID3DX11EffectVectorVariable GetFloatVector method
description: Get a four-component vector that contains floating-point data.
ms.assetid: 980c85db-0d40-49e0-99d0-5049fdf62540
keywords:
- GetFloatVector method Direct3D 11
- GetFloatVector method Direct3D 11 , ID3DX11EffectVectorVariable interface
- ID3DX11EffectVectorVariable interface Direct3D 11 , GetFloatVector method
topic_type:
- apiref
api_name:
- ID3DX11EffectVectorVariable.GetFloatVector
api_location:
- N/A
- N/A.dll
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# ID3DX11EffectVectorVariable::GetFloatVector method

Get a four-component vector that contains floating-point data.

## Syntax


```C++
HRESULT GetFloatVector(
   float *pData
);
```



## Parameters

<dl> <dt>

*pData* 
</dt> <dd>

Type: **float\***

A pointer to the first component.

</dd> </dl>

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/en-us/library/Bb401631(v=MSDN.10).aspx)**

Returns one of the following [Direct3D 11 Return Codes](d3d11-graphics-reference-returnvalues.md).

## Remarks

> [!Note]  
> The DirectX SDK does not supply any compiled binaries for effects. You must use Effects 11 source to build your effects-type application. For more information about using Effects 11 source, see [Differences Between Effects 10 and Effects 11](d3d11-graphics-programming-guide-effects-differences.md).

 

## Requirements



|                    |                                                                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx11effect.h</dt> </dl>                                                    |
| Library<br/> | <dl> <dt>N/A (An Effects 11 library is available online as shared source.)</dt> </dl> |



## See also

<dl> <dt>

[ID3DX11EffectVectorVariable](id3dx11effectvectorvariable.md)
</dt> </dl>

 

 





