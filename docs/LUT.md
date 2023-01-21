# LUT
 : [Object](Object.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [m_EndIn](#m_EndIn)
>
> [m_EndSlope](#m_EndSlope)
>
> [m_Maximum](#m_Maximum)
>
> [m_MaximumValue](#m_MaximumValue)
>
> [m_Minimum](#m_Minimum)
>
> [m_MinimumValue](#m_MinimumValue)
>
> [m_NumEntries](#m_NumEntries)
>
> [m_Offset](#m_Offset)
>
> [m_StartIn](#m_StartIn)
>
> [m_StartSlope](#m_StartSlope)
>
> [m_Type](#m_Type)
>
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [m_Table](#m_Table)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [EntrySize](#EntrySize)()
>
> [GetValue](#GetValue)()
>
> [Table](#Table)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [_newLUT](#_newLUT)()
>
> [_newNums](#_newNums)()
>
> [_newTags](#_newTags)()
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
> [REGI_Version](#REGI_Version)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Properties: <!-- {docsify-ignore} -->

### m_EndIn
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_EndSlope
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_Maximum
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_MaximumValue
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_Minimum
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_MinimumValue
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_NumEntries
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: int32`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_Offset
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: int32`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_StartIn
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_StartSlope
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### m_Type
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: uint32`
>
> *<span class="read_write">Read/Write</span>*
>
___


# Discovered Properties: <!-- {docsify-ignore} -->

### m_Table
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: `
>
> *<span class="read_write">Read/Write</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### EntrySize()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
uint32 LUT:EntrySize(uint32 ty)
> ```
>
___

### GetValue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 LUT:GetValue(float64 inval)
> ```
>
___

### Table()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___


# Discovered Methods: <!-- {docsify-ignore} -->

### _newLUT()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LUT LUT:_newLUT(LUT lut)
> ```
>
___

### _newNums()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LUT LUT:_newNums(int32 num, int32 ty)
> ```
>
___

### _newTags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
LUT LUT:_newTags(TagList tags)
> ```
>
___


# Registry Attributes: <!-- {docsify-ignore} -->

### REGI_ClassType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0 = CT_Any
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
> LUT
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> LUT
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

