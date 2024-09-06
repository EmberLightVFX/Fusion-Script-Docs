# Gradient
 : [Object](Object.md) : [Parameter](Parameter.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Value](#Value)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddColor](#AddColor)()
>
> [AddRGBA](#AddRGBA)()
>
> [Clear](#Clear)()
>
> [ClearTables](#ClearTables)()
>
> [GetColor](#GetColor)()
>
> [GetColorCount](#GetColorCount)()
>
> [QuickEvaluate](#QuickEvaluate)()
>
> [SetPreset](#SetPreset)()
>
> [_newGrad](#_newGrad)()
>
> [_newPreset](#_newPreset)()
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
> [REGB_Utility_Toggle](#REGB_Utility_Toggle)
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

# Properties: <!-- {docsify-ignore} -->

### Value
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> The gradient in table form
>
> `Type: table`
>
> *<span class="read_write">Read/Write</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### AddColor()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Gradient:AddColor(float64 pos, FltPixel pix)
> ```
>
___

### AddRGBA()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Gradient:AddRGBA(float64 pos, float32 r, float32 g, float32 b, float32 a)
> ```
>
___

### Clear()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Gradient:Clear()
> ```
>
___

### ClearTables()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Gradient:ClearTables()
> ```
>
___

### GetColor()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
FltPixel Gradient:GetColor(float64 pos)
> ```
>
___

### GetColorCount()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int32 Gradient:GetColorCount()
> ```
>
___

### QuickEvaluate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
FltPixel Gradient:QuickEvaluate(float64 pos, string cstr)
> ```
>
___

### SetPreset()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Gradient:SetPreset(string pstr)
> ```
>
___

### _newGrad()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Gradient Gradient:_newGrad(Gradient grad)
> ```
>
___

### _newPreset()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Gradient Gradient:_newPreset(string pstr)
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

### REGB_Utility_Toggle
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
> 1507328 = CT_Parameter
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
> Gradient
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Gradient
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Aug 21 2024
>
___

