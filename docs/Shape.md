# Shape
 : [Object](Object.md)
___
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Clear](#Clear)()
>
> [Close](#Close)()
>
> [Copy](#Copy)()
>
> [ExpandOfShape](#ExpandOfShape)()
>
> [FlattenOfShape](#FlattenOfShape)()
>
> [GetCount](#GetCount)()
>
> [IsEmpty](#IsEmpty)()
>
> [IsFlat](#IsFlat)()
>
> [Shape](#Shape)()
>
> [TransformOfShape](#TransformOfShape)()
>
> [_AddRectangle](#_AddRectangle)()
>
> [_BezierTo](#_BezierTo)()
>
> [_ConicTo](#_ConicTo)()
>
> [_FitSourceTo](#_FitSourceTo)()
>
> [_FitTo](#_FitTo)()
>
> [_FlatBezierTo](#_FlatBezierTo)()
>
> [_FlatConicTo](#_FlatConicTo)()
>
> [_LineTo](#_LineTo)()
>
> [_MoveTo](#_MoveTo)()
>
### Registry Attributes
> [REGB_ControlView](#REGB_ControlView)
>
> [REGB_Hide](#REGB_Hide)
>
> [REGB_SupportsDoD](#REGB_SupportsDoD)
>
> [REGB_Unpredictable](#REGB_Unpredictable)
>
> [REGI_ClassType](#REGI_ClassType)
>
> [REGI_Priority](#REGI_Priority)
>
> [REGI_Version](#REGI_Version)
>
> [REGS_ID](#REGS_ID)
>
> [REGS_Name](#REGS_Name)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Discovered Methods: <!-- {docsify-ignore} -->

### Clear()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:Clear()
> ```
>
___

### Close()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:Close()
> ```
>
___

### Copy()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Shape Shape:Copy()
> ```
>
___

### ExpandOfShape()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Shape Shape:ExpandOfShape(float64 thick, int32 prec, int32 fprec, boolean mod)
> ```
>
___

### FlattenOfShape()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Shape Shape:FlattenOfShape(int32 prec)
> ```
>
___

### GetCount()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int32 Shape:GetCount()
> ```
>
___

### IsEmpty()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Shape:IsEmpty()
> ```
>
___

### IsFlat()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Shape:IsFlat()
> ```
>
___

### Shape()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Shape constructor
>
> ```php
Shape Shape()
> ```
>
___

### TransformOfShape()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Shape Shape:TransformOfShape(Matrix4 mat)
> ```
>
___

### _AddRectangle()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_AddRectangle(Vector2 v1, Vector2 v2, float64 round, int32 prec)
> ```
>
___

### _BezierTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_BezierTo(Vector2 v1, Vector2 v2, Vector2 v3, boolean close)
> ```
>
___

### _ConicTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_ConicTo(Vector2 v1, Vector2 v2, boolean close)
> ```
>
___

### _FitSourceTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_FitSourceTo(Vector2 v1, Vector2 v2, Vector2 v3, Vector2 v4, boolean keepaspect)
> ```
>
___

### _FitTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_FitTo(Vector2 v1, Vector2 v2, boolean keepaspect)
> ```
>
___

### _FlatBezierTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_FlatBezierTo(Vector2 v1, Vector2 v2, Vector2 v3, int32 prec, boolean close)
> ```
>
___

### _FlatConicTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_FlatConicTo(Vector2 v1, Vector2 v2, int32 prec, boolean close)
> ```
>
___

### _LineTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_LineTo(Vector2 v1)
> ```
>
___

### _MoveTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Shape:_MoveTo(Vector2 v1)
> ```
>
___


# Registry Attributes: <!-- {docsify-ignore} -->

### REGB_ControlView
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Hide
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_SupportsDoD
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Unpredictable
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGI_ClassType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0 = CT_Any
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
>
___

### REGI_Version
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
>
___

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Shape
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Shape
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Aug 21 2024
>
___

