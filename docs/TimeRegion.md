# TimeRegion
 : [Object](Object.md) : [LockableObject](LockableObject.md) : [List](List.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [End](#End)
>
> [Start](#Start)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [FromFrameString](#FromFrameString)()
>
> [FromTable](#FromTable)()
>
> [ToFrameString](#ToFrameString)()
>
> [ToTable](#ToTable)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [FromString](#FromString)()
>
> [IsEmpty](#IsEmpty)()
>
> [IsWithin](#IsWithin)()
>
> [ToString](#ToString)()
>
> [_IntersectExt](#_IntersectExt)()
>
> [_IntersectRgn](#_IntersectRgn)()
>
> [_UnionExt](#_UnionExt)()
>
> [_UnionRgn](#_UnionRgn)()
>
> [_newDef](#_newDef)()
>
> [_newNums](#_newNums)()
>
> [_newString](#_newString)()
>
> [_newTR](#_newTR)()
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

# Properties: <!-- {docsify-ignore} -->

### End
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### Start
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### FromFrameString()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Reads a string description
>
> ```php
 TimeRegion:FromFrameString(string frames)
> ```
>
___

### FromTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Reads a table of {start, end} pairs
>
> ```php
 TimeRegion:FromTable(table frames)
> ```
>
___

### ToFrameString()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a string description
>
> ```php
string TimeRegion:ToFrameString()
> ```
>
___

### ToTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of {start, end} pairs
>
> ```php
table TimeRegion:ToTable()
> ```
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### FromString()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TimeRegion:FromString(string str)
> ```
>
___

### IsEmpty()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean TimeRegion:IsEmpty()
> ```
>
___

### IsWithin()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean TimeRegion:IsWithin(TimeStamp t)
> ```
>
___

### ToString()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
string TimeRegion:ToString()
> ```
>
___

### _IntersectExt()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TimeRegion:_IntersectExt(TimeExtent ext)
> ```
>
___

### _IntersectRgn()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TimeRegion:_IntersectRgn(TimeRegion rgn)
> ```
>
___

### _UnionExt()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TimeRegion:_UnionExt(TimeExtent ext)
> ```
>
___

### _UnionRgn()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TimeRegion:_UnionRgn(TimeRegion rgn)
> ```
>
___

### _newDef()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeRegion TimeRegion:_newDef()
> ```
>
___

### _newNums()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeRegion TimeRegion:_newNums(float64 s, float64 e, float64 l)
> ```
>
___

### _newString()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeRegion TimeRegion:_newString(string str)
> ```
>
___

### _newTR()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeRegion TimeRegion:_newTR(TimeRegion tr)
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
> TimeRegion
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> TimeRegion
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

