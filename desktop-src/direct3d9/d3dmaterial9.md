---
Description: Specifies material properties.
ms.assetid: 943e6f6d-8091-462f-8c44-e0c27686934a
title: D3DMATERIAL9 structure
ms.topic: reference
ms.date: 05/31/2018
topic_type:
- APIRef
- kbSyntax
api_name:
- D3DMATERIAL9
api_type:
- HeaderDef
api_location:
- D3D9Types.h
---

# D3DMATERIAL9 structure

Specifies material properties.

## Syntax


```C++
typedef struct D3DMATERIAL9 {
  D3DCOLORVALUE Diffuse;
  D3DCOLORVALUE Ambient;
  D3DCOLORVALUE Specular;
  D3DCOLORVALUE Emissive;
  float         Power;
} D3DMATERIAL9, *LPD3DMATERIAL9;
```



## Members

<dl> <dt>

**Diffuse**
</dt> <dd>

Type: **[**D3DCOLORVALUE**](d3dcolorvalue.md)**

</dd> <dd>

Value specifying the diffuse color of the material. See [**D3DCOLORVALUE**](d3dcolorvalue.md).

</dd> <dt>

**Ambient**
</dt> <dd>

Type: **[**D3DCOLORVALUE**](d3dcolorvalue.md)**

</dd> <dd>

Value specifying the ambient color of the material. See [**D3DCOLORVALUE**](d3dcolorvalue.md).

</dd> <dt>

**Specular**
</dt> <dd>

Type: **[**D3DCOLORVALUE**](d3dcolorvalue.md)**

</dd> <dd>

Value specifying the specular color of the material. See [**D3DCOLORVALUE**](d3dcolorvalue.md).

</dd> <dt>

**Emissive**
</dt> <dd>

Type: **[**D3DCOLORVALUE**](d3dcolorvalue.md)**

</dd> <dd>

Value specifying the emissive color of the material. See [**D3DCOLORVALUE**](d3dcolorvalue.md).

</dd> <dt>

**Power**
</dt> <dd>

Type: **float**

</dd> <dd>

Floating-point value specifying the sharpness of specular highlights. The higher the value, the sharper the highlight.

</dd> </dl>

## Remarks

To turn off specular highlights, set D3DRS\_SPECULARENABLE to **FALSE**, using [**D3DRENDERSTATETYPE**](https://msdn.microsoft.com/en-us/library/Bb172599(v=VS.85).aspx). This is the fastest option because no specular highlights will be calculated.

For more information about using the lighting engine to calculate specular lighting, see [Specular Lighting (Direct3D 9)](specular-lighting.md).

## Requirements



|                   |                                                                                        |
|-------------------|----------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>D3D9Types.h</dt> </dl> |



## See also

<dl> <dt>

[Direct3D Structures](dx9-graphics-reference-d3d-structures.md)
</dt> <dt>

[**IDirect3DDevice9::GetMaterial**](https://msdn.microsoft.com/library/Bb174394(v=VS.85).aspx)
</dt> <dt>

[**IDirect3DDevice9::SetMaterial**](https://msdn.microsoft.com/library/Bb174437(v=VS.85).aspx)
</dt> </dl>

 

 




