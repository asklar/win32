---
title: glVertex2s function
description: Specifies a vertex.
ms.assetid: e964d7b0-1cb7-4334-8861-1cc2ee37a71a
keywords:
- glVertex2s function OpenGL
topic_type:
- apiref
api_name:
- glVertex2s
api_location:
- Opengl32.dll
api_type:
- DllExport
ms.topic: reference
ms.date: 05/31/2018
---

# glVertex2s function

Specifies a vertex.

## Syntax


```C++
void WINAPI glVertex2s(
   GLshort x,
   GLshort y
);
```



## Parameters

<dl> <dt>

*x* 
</dt> <dd>

Specifies the x-coordinate of a vertex.

</dd> <dt>

*y* 
</dt> <dd>

Specifies the y-coordinate of a vertex.

</dd> </dl>

## Return value

This function does not return a value.

## Remarks

The glVertex function commands are used within [**glBegin**](glbegin.md)/[**glEnd**](glend.md) pairs to specify point, line, and polygon vertices. The current color, normal, and texture coordinates are associated with the vertex when glVertex is called. When only *x* and *y* are specified, *z* defaults to 0.0 and *w* defaults to 1.0. When *x*, *y*, and *z* are specified, *w* defaults to 1.0. Invoking glVertex outside of a **glBegin**/**glEnd** pair results in undefined behavior.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 2000 Professional \[desktop apps only\]<br/>                              |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>Gl.h</dt> </dl>         |
| Library<br/>                  | <dl> <dt>Opengl32.lib</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Opengl32.dll</dt> </dl> |



## See also

<dl> <dt>

[**glBegin**](glbegin.md)
</dt> <dt>

[**glCallList**](glcalllist.md)
</dt> <dt>

[**glColor**](glcolor-functions.md)
</dt> <dt>

[**glEdgeFlag**](gledgeflag-functions.md)
</dt> <dt>

[**glEnd**](glend.md)
</dt> <dt>

[**glEvalCoord**](glevalcoord-functions.md)
</dt> <dt>

[**glIndex**](glindex-functions.md)
</dt> <dt>

[**glMaterial**](glmaterial-functions.md)
</dt> <dt>

[**glNormal**](glnormal-functions.md)
</dt> <dt>

[**glRect**](glrect-functions.md)
</dt> <dt>

[**glTexCoord**](gltexcoord-functions.md)
</dt> </dl>

 

 





