# Parameter
 : [Object](Object.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [ID](#ID)
>
> [Metadata](#Metadata)
>
> [Name](#Name)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetData](#GetData)()
>
> [SetData](#SetData)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Copy](#Copy)()
>
> [InterpolateWith](#InterpolateWith)()
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

### ID
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> ID of this Parameter
>
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___

### Metadata
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Get or set metadata tables
>
> *<span class="read_write">Read/Write</span>*
>
___

### Name
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Friendly name of this Parameter
>
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### GetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get custom persistent data
>
> ```php
(number|string|boolean|table) Parameter:GetData([string name])
> ```
>
> *Se also: [SetData()](#SetData)*
___

### SetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set custom persistent data
>
> ```php
 Parameter:SetData(string name, (number|string|boolean|table) value)
> ```
>
> *Se also: [GetData()](#GetData)*
___


# Discovered Methods: <!-- {docsify-ignore} -->

### Copy()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Parameter Parameter:Copy()
> ```
>
___

### InterpolateWith()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Parameter Parameter:InterpolateWith(float64 weight, Parameter param)
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
> Parameter
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Parameter
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Aug 21 2024
>
___

