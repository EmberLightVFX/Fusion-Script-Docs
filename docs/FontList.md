# FontList
 : [Object](Object.md) : [LockableObject](LockableObject.md) : [List](List.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddFont](#AddFont)()
>
> [Clear](#Clear)()
>
> [GetFontList](#GetFontList)()
>
> [ScanDir](#ScanDir)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetFontManager](#GetFontManager)()
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

# Methods: <!-- {docsify-ignore} -->

### AddFont()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds the specified font to the global font list
>
> ```php
boolean FontList:AddFont(string fontfile)
> ```
>
> ```
where fontfile is the full path to a font to be added.
> ```
>
___

### Clear()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Empties the global font list
>
> ```php
 FontList:Clear()
> ```
>
___

### GetFontList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns all font files in the global font list
>
> ```php
table FontList:GetFontList()
> ```
>
> ```
where fonts is a table of subtables, indexed by font name,
and each subtable contains filename strings, indexed by style name.
> ```
>
___

### ScanDir()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds the specified dir to the global font list
>
> ```php
 FontList:ScanDir([string dirname])
> ```
>
> ```
where dirname is the full path to a directory of fonts to add.
If dirname is not specified, the list will be cleared and the standard
font directory will be rescanned.
> ```
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### GetFontManager()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
FontList FontList:GetFontManager()
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
> FontList
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> FontList
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 2025
>
___

