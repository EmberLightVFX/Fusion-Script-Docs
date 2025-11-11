# PlainOutput
 : [Object](Object.md) : [LockableObject](LockableObject.md) : [Link](Link.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ClearDiskCache](#ClearDiskCache)()
>
> [EnableDiskCache](#EnableDiskCache)()
>
> [GetConnectedInputs](#GetConnectedInputs)()
>
> [GetDoD](#GetDoD)()
>
> [GetValue](#GetValue)()
>
> [ShowDiskCacheDlg](#ShowDiskCacheDlg)()
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

### ClearDiskCache()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Clears frames from the disk cache
>
> ```php
boolean PlainOutput:ClearDiskCache(number start, number end)
> ```
>
> ```
Start..End: Frame range to clear from the cache (inclusive)
> ```
>
> *Se also: [EnableDiskCache()](#EnableDiskCache)*
___

### EnableDiskCache()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Controls disk-based caching
>
> ```php
boolean, string PlainOutput:EnableDiskCache([boolean enable], [string path], [boolean lockcache], [boolean lockbranch], [boolean delete], [boolean prerender], [boolean usenetwork])
> ```
>
> ```
Args:
  Enable:     Enables or disables the cache
  Path:       Path to create the cache at
  LockCache:  Preserves the cache despite upstream changes (default false)
  LockBranch: Locks all upstream tools (default false)
  Delete:     Deletes the cache at <Path> (default false)
  PreRender:  Do a render now to create the cache (default true)
  UseNetwork: Use Network Rendering when PreRendering (default false)
> ```
>
> *Se also: [ClearDiskCache()](#ClearDiskCache), [ShowDiskCacheDlg()](#ShowDiskCacheDlg)*
___

### GetConnectedInputs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetDoD()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the Domain of Definition at the given time
>
> ```php
table PlainOutput:GetDoD([number time], [string layer], [number flags], [number proxy])
> ```
>
> ```
Args:
  time:     The frame to fetch the DoD for (default is the current time).
  layer:    The layer to fetch the DoD for (default is the default layer).
  reqflags: Quality flags (default is final quality).
  proxy:    Proxy level (default is no proxy).

Returns:
  may be nil, or a table containing { left,bottom,right,top } coords.
> ```
>
> *Se also: [GetValue()](#GetValue)*
___

### GetValue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the value at the given time
>
> ```php
Parameter, table PlainOutput:GetValue([number time], [string layer], [number flags], [number proxy])
> ```
>
> ```
Args:
  time:     The frame to fetch the value for (default is the current time).
  layer:    The layer to fetch the value for (default is the default layer).
  reqflags: Quality flags (default is final quality).
  proxy:    Proxy level (default is no proxy).

Returns:
  value may be nil, or a number of different types:
     Number - returns a number
     Point  - returns a table with X and Y members
     Text   - returns a string
     Clip   - returns the filename string
     Image  - returns an Image object
 attrs is a table with the following entries:
     Valid    - table with Start and End entries
     DataType - string ID for the parameter type
     TimeCost - time take to render this parameter
     DoD      - table of { left,bottom,right,top } coords
> ```
>
___

### ShowDiskCacheDlg()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays Cache-To-Disk dialog for user interaction
>
> ```php
boolean PlainOutput:ShowDiskCacheDlg()
> ```
>
> ```
Returns: boolean ok - true if user clicked OK/Pre-Render, false for Cancel
> ```
>
> *Se also: [EnableDiskCache()](#EnableDiskCache), [ClearDiskCache()](#ClearDiskCache)*
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
> PlainOutput
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> PlainOutput
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 2025
>
___

