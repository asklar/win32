---
title: ID3DX11EffectShaderVariable GetVertexShader method
description: Get a vertex shader.
ms.assetid: 31a250ae-154b-43ce-97e3-6480f23dc4e2
keywords:
- GetVertexShader method Direct3D 11
- GetVertexShader method Direct3D 11 , ID3DX11EffectShaderVariable interface
- ID3DX11EffectShaderVariable interface Direct3D 11 , GetVertexShader method
topic_type:
- apiref
api_name:
- ID3DX11EffectShaderVariable.GetVertexShader
api_location:
- N/A
- N/A.dll
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# ID3DX11EffectShaderVariable::GetVertexShader method

Get a vertex shader.

## Syntax


```C++
HRESULT GetVertexShader(
   UINT               ShaderIndex,
   ID3D11VertexShader **ppVS
);
```



## Parameters

<dl> <dt>

*ShaderIndex* 
</dt> <dd>

Type: **[**UINT**](https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types)**

A zero-based index.

</dd> <dt>

*ppVS* 
</dt> <dd>

Type: **[**ID3D11VertexShader**](https://msdn.microsoft.com/en-us/library/Ff476641(v=VS.85).aspx)\*\***

A pointer to an [**ID3D11VertexShader**](https://msdn.microsoft.com/en-us/library/Ff476641(v=VS.85).aspx) pointer that will be set to the vertex shader on return.

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

[ID3DX11EffectShaderVariable](id3dx11effectshadervariable.md)
</dt> </dl>

 

 





