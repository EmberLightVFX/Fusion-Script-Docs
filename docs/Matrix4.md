# Matrix4
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [TypeName](#TypeName)
>
> [TypeNamePtr](#TypeNamePtr)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Adjoint](#Adjoint)()
>
> [Determinant](#Determinant)()
>
> [Identity](#Identity)()
>
> [Inverse](#Inverse)()
>
> [InverseTranspose](#InverseTranspose)()
>
> [LookAt](#LookAt)()
>
> [MapQuad](#MapQuad)()
>
> [Move](#Move)()
>
> [Perspective](#Perspective)()
>
> [Project](#Project)()
>
> [ProjectWindow](#ProjectWindow)()
>
> [RotAxis](#RotAxis)()
>
> [RotX](#RotX)()
>
> [RotY](#RotY)()
>
> [RotZ](#RotZ)()
>
> [Rotate](#Rotate)()
>
> [Scale](#Scale)()
>
> [SetIdentity](#SetIdentity)()
>
> [SetOne](#SetOne)()
>
> [SetZero](#SetZero)()
>
> [Shear](#Shear)()
>
> [TransformNormal](#TransformNormal)()
>
> [TransformPoint](#TransformPoint)()
>
> [Transpose](#Transpose)()
>
> [_Ortho3](#_Ortho3)()
>
> [_Ortho6](#_Ortho6)()
>
> [__mul](#__mul)()
>
> [_newDef](#_newDef)()
>
> [_newMat4](#_newMat4)()
>
> [_newNums](#_newNums)()
>
___

# Discovered Properties: <!-- {docsify-ignore} -->

### TypeName
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___

### TypeNamePtr
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### Adjoint()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Adjoint()
> ```
>
___

### Determinant()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 Matrix4:Determinant()
> ```
>
___

### Identity()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Identity()
> ```
>
___

### Inverse()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:Inverse()
> ```
>
___

### InverseTranspose()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:InverseTranspose()
> ```
>
___

### LookAt()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:LookAt(Vector4 eye, Vector4 at, Vector4 up)
> ```
>
___

### MapQuad()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Matrix4:MapQuad(float64 tlX, float64 tlY, float64 trX, float64 trY, float64 blX, float64 blY, float64 brX, float64 brY)
> ```
>
___

### Move()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Move(float64 x, float64 y, float64 z)
> ```
>
___

### Perspective()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Perspective(float64 fovy, float64 aspect, float64 znear, float64 zfar)
> ```
>
___

### Project()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Project(float64 persp)
> ```
>
___

### ProjectWindow()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:ProjectWindow(float64 width, float64 height, float64 znear, float64 zfar)
> ```
>
___

### RotAxis()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:RotAxis(float64 xaxis, float64 yaxis, float64 zaxis, float64 rad)
> ```
>
___

### RotX()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:RotX(float64 a)
> ```
>
___

### RotY()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:RotY(float64 a)
> ```
>
___

### RotZ()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:RotZ(float64 a)
> ```
>
___

### Rotate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Rotate(float64 x, float64 y, float64 z, string order)
> ```
>
___

### Scale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Scale(float64 x, float64 y, float64 z)
> ```
>
___

### SetIdentity()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:SetIdentity()
> ```
>
___

### SetOne()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:SetOne()
> ```
>
___

### SetZero()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:SetZero()
> ```
>
___

### Shear()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:Shear(float64 x, float64 y, float64 z)
> ```
>
___

### TransformNormal()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Vector3f Matrix4:TransformNormal(Vector3f norm)
> ```
>
___

### TransformPoint()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:TransformPoint(Vector4 out, Vector4 inp)
> ```
>
___

### Transpose()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:Transpose()
> ```
>
___

### _Ortho3()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:_Ortho3(float64 width, float64 height, float64 depth)
> ```
>
___

### _Ortho6()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Matrix4:_Ortho6(float64 xmin, float64 xmax, float64 ymin, float64 ymax, float64 zmin, float64 zmax)
> ```
>
___

### __mul()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:__mul(Matrix4 mat)
> ```
>
___

### _newDef()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:_newDef()
> ```
>
___

### _newMat4()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:_newMat4(Matrix4 mat)
> ```
>
___

### _newNums()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 Matrix4:_newNums(float64 a11, float64 a12, float64 a13, float64 a14, float64 a21, float64 a22, float64 a23, float64 a24, float64 a31, float64 a32, float64 a33, float64 a34, float64 a41, float64 a42, float64 a43, float64 a44)
> ```
>
___

