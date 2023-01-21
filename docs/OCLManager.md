# OCLManager
 : [Object](Object.md) : [LockableObject](LockableObject.md)
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [FP16](#FP16)
>
> [FP64](#FP64)
>
> [GLSharing](#GLSharing)
>
> [GLSync](#GLSync)
>
> [SupportsImage](#SupportsImage)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [BuildProgram](#BuildProgram)()
>
> [Create](#Create)()
>
> [_BuildCachedProgramFile](#_BuildCachedProgramFile)()
>
> [_BuildCachedProgramReg](#_BuildCachedProgramReg)()
>
> [OCLManager](#OCLManager)()
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

# Discovered Properties: <!-- {docsify-ignore} -->

### FP16
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### FP64
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### GLSharing
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### GLSync
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### SupportsImage
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### BuildProgram()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
OCLProgram OCLManager:BuildProgram(FusionDoc doc, string source, size_t len, string opts)
> ```
>
___

### Create()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean OCLManager:Create(string device)
> ```
>
___

### _BuildCachedProgramFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
OCLProgram OCLManager:_BuildCachedProgramFile(string id, FusionDoc doc, string filename, string source, size_t len, string opts)
> ```
>
___

### _BuildCachedProgramReg()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
OCLProgram OCLManager:_BuildCachedProgramReg(Registry reg, FusionDoc doc, string source, size_t len, string opts)
> ```
>
___

### OCLManager()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> OCLManager constructor
>
> ```php
OCLManager OCLManager()
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
> OCLManager
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> OCLManager
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

