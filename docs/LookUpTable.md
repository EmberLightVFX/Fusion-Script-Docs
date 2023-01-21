# LookUpTable
 : [Object](Object.md) : [Parameter](Parameter.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Attach](#Attach)()
>
> [Detach](#Detach)()
>
> [GetTable](#GetTable)()
>
> [GetValue](#GetValue)()
>
> [IsOneToOne](#IsOneToOne)()
>
> [SetOneToOne](#SetOneToOne)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [_newCopy](#_newCopy)()
>
> [_newDef](#_newDef)()
>
> [_newLUT](#_newLUT)()
>
### Tag Map
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
> [LUT_MaximumValue](#LUT_MaximumValue)
>
> [LUT_Result](#LUT_Result)
>
> [LUT_Time](#LUT_Time)
>
> [LUT_Maximum](#LUT_Maximum)
>
> [LUT_Value](#LUT_Value)
>
> [LUT_Minimum](#LUT_Minimum)
>
> [LUT_Flags](#LUT_Flags)
>
> [LUT_Entries](#LUT_Entries)
>
> [LUT_Type](#LUT_Type)
>
> [LUT_Offset](#LUT_Offset)
>
> [LUT_StartIn](#LUT_StartIn)
>
> [LUT_MinimumValue](#LUT_MinimumValue)
>
> [LUT_StartSlope](#LUT_StartSlope)
>
> [LUT_EndSlope](#LUT_EndSlope)
>
> [LUT_OneToOne](#LUT_OneToOne)
>
> [LUT_EndIn](#LUT_EndIn)
>
> [LUT_Context](#LUT_Context)
>
### Registry Attributes
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> [REGI_ClassType](#REGI_ClassType)
>
> [REGB_ControlView](#REGB_ControlView)
>
> [REGB_Hide](#REGB_Hide)
>
> [REGS_ID](#REGS_ID)
>
> [REGS_Name](#REGS_Name)
>
> [REGI_Priority](#REGI_Priority)
>
> [REGB_SupportsDoD](#REGB_SupportsDoD)
>
> [REGB_Unpredictable](#REGB_Unpredictable)
>
> [REGB_Utility_Toggle](#REGB_Utility_Toggle)
>
> [REGI_Version](#REGI_Version)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Methods: <!-- {docsify-ignore} -->

### Attach()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 LookUpTable:Attach(Object obj)
> ```
>
___

### Detach()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 LookUpTable:Detach()
> ```
>
___

### GetTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LUT LookUpTable:GetTable(TagList tags)
> ```
>
___

### GetValue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 LookUpTable:GetValue(float64 inval)
> ```
>
___

### IsOneToOne()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean LookUpTable:IsOneToOne()
> ```
>
___

### SetOneToOne()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 LookUpTable:SetOneToOne(boolean set)
> ```
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### _newCopy()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LookUpTable LookUpTable:_newCopy(LookUpTable lut)
> ```
>
___

### _newDef()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LookUpTable LookUpTable:_newDef()
> ```
>
___

### _newLUT()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LookUpTable LookUpTable:_newLUT(LUT lut, string id)
> ```
>
___


# Tag Map: <!-- {docsify-ignore} -->

### LUT_MaximumValue
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Result
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Time
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Maximum
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Value
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Minimum
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Flags
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Entries
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Type
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Offset
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_StartIn
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_MinimumValue
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_StartSlope
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_EndSlope
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_OneToOne
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
### LUT_EndIn
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
### LUT_Context
> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
___


# Registry Attributes: <!-- {docsify-ignore} -->

### REGI_ClassType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 1507328 = CT_Parameter
>
___

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

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> LookUpTable
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> LookUpTable
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
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

### REGI_Version
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Dec  7 2022
>
___

