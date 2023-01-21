# ColorMatrix
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [TypeName](#TypeName)
>
> [TypeNamePtr](#TypeNamePtr)
>
> [def_BWeight](#def_BWeight)
>
> [def_GWeight](#def_GWeight)
>
> [def_RWeight](#def_RWeight)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Adjoint](#Adjoint)()
>
> [Blend](#Blend)()
>
> [Determinant](#Determinant)()
>
> [GrayScale](#GrayScale)()
>
> [Hue](#Hue)()
>
> [Identity](#Identity)()
>
> [Inverse](#Inverse)()
>
> [IsIdentity](#IsIdentity)()
>
> [Offset](#Offset)()
>
> [RGBtoYUV](#RGBtoYUV)()
>
> [Rotate](#Rotate)()
>
> [RotateWeighted](#RotateWeighted)()
>
> [Saturate](#Saturate)()
>
> [Shear](#Shear)()
>
> [Tint](#Tint)()
>
> [Tint_HighLuma](#Tint_HighLuma)()
>
> [Tint_HighLumaBetter](#Tint_HighLumaBetter)()
>
> [Tint_LowLuma](#Tint_LowLuma)()
>
> [Tint_LowLumaBetter](#Tint_LowLumaBetter)()
>
> [YUVtoRGB](#YUVtoRGB)()
>
> [_RotB1](#_RotB1)()
>
> [_RotB2](#_RotB2)()
>
> [_RotG1](#_RotG1)()
>
> [_RotG2](#_RotG2)()
>
> [_RotR1](#_RotR1)()
>
> [_RotR2](#_RotR2)()
>
> [_Scale3](#_Scale3)()
>
> [_Scale4](#_Scale4)()
>
> [__add](#__add)()
>
> [__eq](#__eq)()
>
> [_mulCM](#_mulCM)()
>
> [_mulNum](#_mulNum)()
>
> [_newCM](#_newCM)()
>
> [_newCMF](#_newCMF)()
>
> [_newDef](#_newDef)()
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

### def_BWeight
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___

### def_GWeight
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___

### def_RWeight
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### Adjoint()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Adjoint()
> ```
>
___

### Blend()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Blend(ColorMatrix cm, float64 blend)
> ```
>
___

### Determinant()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 ColorMatrix:Determinant()
> ```
>
___

### GrayScale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:GrayScale(float64 rweight, float64 gweight, float64 bweight)
> ```
>
___

### Hue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Hue(float64 hue, float64 rweight, float64 gweight, float64 bweight)
> ```
>
___

### Identity()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Identity()
> ```
>
___

### Inverse()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrixFull ColorMatrix:Inverse()
> ```
>
___

### IsIdentity()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean ColorMatrix:IsIdentity()
> ```
>
___

### Offset()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Offset(float64 r, float64 g, float64 b)
> ```
>
___

### RGBtoYUV()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:RGBtoYUV()
> ```
>
___

### Rotate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Rotate(float64 r, float64 g, float64 b, float64 angle)
> ```
>
___

### RotateWeighted()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:RotateWeighted(float64 r, float64 g, float64 b, float64 angle, float64 rweight, float64 gweight, float64 bweight)
> ```
>
___

### Saturate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Saturate(float64 sat, float64 rweight, float64 gweight, float64 bweight)
> ```
>
___

### Shear()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Shear(float64 g, float64 r)
> ```
>
___

### Tint()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Tint(float64 angle, float64 length, float64 rweight, float64 gweight, float64 bweight)
> ```
>
___

### Tint_HighLuma()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Tint_HighLuma(float64 angle, float64 len)
> ```
>
___

### Tint_HighLumaBetter()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Tint_HighLumaBetter(float64 angle, float64 len)
> ```
>
___

### Tint_LowLuma()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Tint_LowLuma(float64 angle, float64 len)
> ```
>
___

### Tint_LowLumaBetter()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:Tint_LowLumaBetter(float64 angle, float64 len)
> ```
>
___

### YUVtoRGB()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:YUVtoRGB()
> ```
>
___

### _RotB1()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_RotB1(float64 angle)
> ```
>
___

### _RotB2()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_RotB2(float64 s, float64 c)
> ```
>
___

### _RotG1()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_RotG1(float64 angle)
> ```
>
___

### _RotG2()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_RotG2(float64 s, float64 c)
> ```
>
___

### _RotR1()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_RotR1(float64 angle)
> ```
>
___

### _RotR2()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_RotR2(float64 s, float64 c)
> ```
>
___

### _Scale3()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_Scale3(float64 r, float64 g, float64 b)
> ```
>
___

### _Scale4()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ColorMatrix:_Scale4(float64 r, float64 g, float64 b, float64 scale)
> ```
>
___

### __add()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrix ColorMatrix:__add(ColorMatrix cm)
> ```
>
___

### __eq()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean ColorMatrix:__eq(ColorMatrix cm)
> ```
>
___

### _mulCM()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrix ColorMatrix:_mulCM(ColorMatrix cm)
> ```
>
___

### _mulNum()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrix ColorMatrix:_mulNum(float64 num)
> ```
>
___

### _newCM()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrix ColorMatrix:_newCM(ColorMatrix cm)
> ```
>
___

### _newCMF()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrix ColorMatrix:_newCMF(ColorMatrixFull cm)
> ```
>
___

### _newDef()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ColorMatrix ColorMatrix:_newDef()
> ```
>
___

