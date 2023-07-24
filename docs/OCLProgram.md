# OCLProgram
 : [Object](Object.md) : [LockableObject](LockableObject.md)
___
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Build](#Build)()
>
> [CopyToBuffer](#CopyToBuffer)()
>
> [CreateKernel](#CreateKernel)()
>
> [Lock](#Lock)()
>
> [OCLProgram](#OCLProgram)()
>
> [Release](#Release)()
>
> [ReleaseMemory](#ReleaseMemory)()
>
> [RunKernel](#RunKernel)()
>
> [SetSize](#SetSize)()
>
> [SetWorkgroupSize](#SetWorkgroupSize)()
>
> [WaitForBuild](#WaitForBuild)()
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

### Build()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean OCLProgram:Build(boolean wait, string opts)
> ```
>
___

### CopyToBuffer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
size_t OCLProgram:CopyToBuffer(Image img, OCLMemory mem, size_t offset, boolean wait)
> ```
>
___

### CreateKernel()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int16 OCLProgram:CreateKernel(string name)
> ```
>
___

### Lock()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 OCLProgram:Lock()
> ```
>
___

### OCLProgram()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> OCLProgram constructor
>
> ```php
OCLProgram OCLProgram(OCLManager mgr, FusionDoc doc, string src, size_t len)
> ```
>
___

### Release()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 OCLProgram:Release()
> ```
>
___

### ReleaseMemory()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean OCLProgram:ReleaseMemory(OCLMemory mem)
> ```
>
___

### RunKernel()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean OCLProgram:RunKernel(int16 index, boolean block)
> ```
>
___

### SetSize()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 OCLProgram:SetSize(int xsize, int ysize)
> ```
>
___

### SetWorkgroupSize()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 OCLProgram:SetWorkgroupSize(int xsize, int ysize)
> ```
>
___

### WaitForBuild()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean OCLProgram:WaitForBuild(uint32 timeout)
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
> OCLProgram
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> OCLProgram
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

