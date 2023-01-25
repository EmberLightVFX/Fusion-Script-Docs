# GLImageViewer
 : [Object](Object.md) : [GLViewer](GLViewer.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [DragRoI](#DragRoI)()
>
> [EnableLUT](#EnableLUT)()
>
> [EnableRoI](#EnableRoI)()
>
> [ExportTo3DLUT](#ExportTo3DLUT)()
>
> [IsDoDShown](#IsDoDShown)()
>
> [IsEnableRoI](#IsEnableRoI)()
>
> [IsLUTEnabled](#IsLUTEnabled)()
>
> [IsShowGainGamma](#IsShowGainGamma)()
>
> [LoadLUTAction](#LoadLUTAction)()
>
> [LoadLUTFile](#LoadLUTFile)()
>
> [LockRoI](#LockRoI)()
>
> [SaveLUTFile](#SaveLUTFile)()
>
> [SetRoI](#SetRoI)()
>
> [ShowDoD](#ShowDoD)()
>
> [ShowGainGamma](#ShowGainGamma)()
>
> [ShowLUTEditor](#ShowLUTEditor)()
>
> [ShowRoI](#ShowRoI)()
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
> [REGS_UIName](#REGS_UIName)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Methods: <!-- {docsify-ignore} -->

### DragRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Lets the user drag out an RoI rectangle
>
> ```php
 GLImageViewer:DragRoI()
> ```
>
___

### EnableLUT()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables the current View LUT
>
> ```php
 GLImageViewer:EnableLUT([boolean enable])
> ```
>
___

### EnableRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables the current View RoI
>
> ```php
 GLImageViewer:EnableRoI([boolean enable])
> ```
>
___

### ExportTo3DLUT()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Exports the current LUTs to a 3D LUT file
>
> ```php
boolean, string GLImageViewer:ExportTo3DLUT([string pathname], [number cubesize], [number precision], [number rangemin], [number rangemax])
> ```
>
> ```
Exports a 3D LUT with cubesize x cubesize x cubesize entries (default 33x33x33).
Passing nil or no pathname displays a dialog to the user.
For precision, pass 1 for uint8, 2 for uint16 or 9 for float32 (default float32).
For HDR LUTs, pass rangemin/rangemax (default is 0.0 to 1.0).
Returns: boolean success, and the saved LUT's filename.
> ```
>
___

### IsDoDShown()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### IsEnableRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### IsLUTEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if the current View LUT is enabled
>
> ```php
boolean GLImageViewer:IsLUTEnabled()
> ```
>
___

### IsShowGainGamma()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### LoadLUTAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Used by the Action system to load a LUT file into the View LUT
>
> ```php
boolean GLImageViewer:LoadLUTAction([string pathname])
> ```
>
___

### LoadLUTFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Loads a LUT file, setting or LUT plugin ID into the View LUT
>
> ```php
boolean GLImageViewer:LoadLUTFile([string pathname])
> ```
>
___

### LockRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Locks or unlocks the View RoI
>
> ```php
 GLImageViewer:LockRoI([boolean enable])
> ```
>
___

### SaveLUTFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Saves current LUTs into a .viewlut file
>
> ```php
boolean GLImageViewer:SaveLUTFile([string pathname])
> ```
>
___

### SetRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the current View RoI region
>
> ```php
 GLImageViewer:SetRoI()
> ```
>
> ```php
 GLImageViewer:SetRoI(table rect)
> ```
>
> ```php
 GLImageViewer:SetRoI(boolean auto)
> ```
>
___

### ShowDoD()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables drawing the current View DoD rectangle
>
> ```php
 GLImageViewer:ShowDoD([boolean enable])
> ```
>
___

### ShowGainGamma()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### ShowLUTEditor()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Pops up the Editor window for the current View LUT
>
> ```php
 GLImageViewer:ShowLUTEditor()
> ```
>
___

### ShowRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables drawing the current View RoI rectangle
>
> ```php
 GLImageViewer:ShowRoI([boolean enable])
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
> 2359296 = CT_GLViewer
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 100
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
> GLImageViewer
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> 2D Viewer
>
___

### REGS_UIName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> 2D Viewer
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

