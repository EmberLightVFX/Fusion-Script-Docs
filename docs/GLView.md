# GLView
 : [Object](Object.md) : [FuView](FuView.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [CurrentViewer](#CurrentViewer)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddToolAction](#AddToolAction)()
>
> [DisableCurrentTools](#DisableCurrentTools)()
>
> [DisableSelectedTools](#DisableSelectedTools)()
>
> [EnableLUT](#EnableLUT)()
>
> [EnableStereo](#EnableStereo)()
>
> [GetBuffer](#GetBuffer)()
>
> [GetLocked](#GetLocked)()
>
> [GetPos](#GetPos)()
>
> [GetPosTable](#GetPosTable)()
>
> [GetPrefs](#GetPrefs)()
>
> [GetPreview](#GetPreview)()
>
> [GetRot](#GetRot)()
>
> [GetRotTable](#GetRotTable)()
>
> [GetScale](#GetScale)()
>
> [GetScaleFit](#GetScaleFit)()
>
> [GetSplit](#GetSplit)()
>
> [GetSplitTable](#GetSplitTable)()
>
> [GetStereoMethod](#GetStereoMethod)()
>
> [GetStereoSource](#GetStereoSource)()
>
> [GetViewerList](#GetViewerList)()
>
> [IsLUTEnabled](#IsLUTEnabled)()
>
> [IsStereoEnabled](#IsStereoEnabled)()
>
> [IsStereoSwapped](#IsStereoSwapped)()
>
> [IsWipeEnabled](#IsWipeEnabled)()
>
> [LoadLUTFile](#LoadLUTFile)()
>
> [LoadPrefs](#LoadPrefs)()
>
> [ResetView](#ResetView)()
>
> [SavePrefs](#SavePrefs)()
>
> [SetBuffer](#SetBuffer)()
>
> [SetLocked](#SetLocked)()
>
> [SetPos](#SetPos)()
>
> [SetRot](#SetRot)()
>
> [SetScale](#SetScale)()
>
> [SetSplit](#SetSplit)()
>
> [SetStereoMethod](#SetStereoMethod)()
>
> [SetStereoSource](#SetStereoSource)()
>
> [ShowLUTEditor](#ShowLUTEditor)()
>
> [ShowQuadView](#ShowQuadView)()
>
> [ShowSubView](#ShowSubView)()
>
> [ShowingQuadView](#ShowingQuadView)()
>
> [ShowingSubView](#ShowingSubView)()
>
> [SwapStereo](#SwapStereo)()
>
> [SwapSubView](#SwapSubView)()
>
> [WipeEnable](#WipeEnable)()
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

### CurrentViewer
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: GLViewer`
>
> *<span class="read_write">Read/Write</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### AddToolAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### DisableCurrentTools()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Pass-through the currently selected tools
>
> ```php
 GLView:DisableCurrentTools()
> ```
>
___

### DisableSelectedTools()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Pass-through the selected tools
>
> ```php
 GLView:DisableSelectedTools()
> ```
>
___

### EnableLUT()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables the current Monitor LUT
>
> ```php
 GLView:EnableLUT([boolean enable])
> ```
>
___

### EnableStereo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables 3D stereo display
>
> ```php
 GLView:EnableStereo([boolean enable])
> ```
>
___

### GetBuffer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns which buffer is shown
>
> ```php
number GLView:GetBuffer()
> ```
>
> ```
where 'buffer' is one of the following numbers:
   0 = A
   1 = B
   2 = A|B split
> ```
>
___

### GetLocked()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if the display is locked
>
> ```php
boolean GLView:GetLocked()
> ```
>
___

### GetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the position of the display
>
> ```php
number, number, number GLView:GetPos()
> ```
>
___

### GetPosTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the position of the display as a table
>
> ```php
table GLView:GetPosTable()
> ```
>
> ```
Returns:
       x = table[1]
       y = table[2]
       z = table[3]
> ```
>
___

### GetPrefs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieve a table of preferences for this view
>
> ```php
table GLView:GetPrefs()
> ```
>
> ```
Returns a table of Preference attributes
> ```
>
> *Se also: [ShowPrefs()](Fusion.md#ShowPrefs), [SetPrefs()](Fusion.md#SetPrefs)*
___

### GetPreview()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the buffer's Preview
>
> ```php
 GLView:GetPreview([number buffer])
> ```
>
> ```
where 'buffer' is one of the following numbers:
   0 = A
   1 = B
   2 = A|B split
If 'buffer' is not specified, the current Preview is returned.
> ```
>
___

### GetRot()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the x,y,z rotation of the display in degrees
>
> ```php
number, number, number GLView:GetRot()
> ```
>
___

### GetRotTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the x,y,z rotation of the display in degrees as a table
>
> ```php
table GLView:GetRotTable()
> ```
>
> ```
Returns:
       x = table[1]
       y = table[2]
       z = table[3]
> ```
>
___

### GetScale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the scale of the display
>
> ```php
number GLView:GetScale()
> ```
>
___

### GetScaleFit()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Indicates if the display is set to scale-to-fit
>
> ```php
boolean GLView:GetScaleFit()
> ```
>
___

### GetSplit()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the split position of the view
>
> ```php
number, number, number GLView:GetSplit()
> ```
>
___

### GetSplitTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the split position of the view as a table
>
> ```php
table GLView:GetSplitTable()
> ```
>
> ```
Returns:
   x = table[1]
   y = table[2]
   angle = table[3]
> ```
>
___

### GetStereoMethod()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the method and options being used for stereo display
>
> ```php
string, ,  GLView:GetStereoMethod()
> ```
>
> ```
method can be 'Quad Buffer', 'Anaglyph', 'Crosseyed', 'Interlaced', 'Checkerboard', 'Left Eye Only' or 'Right'
If method is 'Anaglyph':
	option1 can be 'Red/Cyan', 'Red/Green',	'Red/Blue', 'Amber/Blue' or 'Green/Magenta'
	option2 can be 'Monochrome', 'Half-color',	'Color', 'Optimised' or 'Dubois'
> ```
>
___

### GetStereoSource()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the source being used for stereo display
>
> ```php
boolean, boolean, string GLView:GetStereoSource()
> ```
>
> ```
ABsource is true if the A & B buffers are used for left & right
stacked is true if the two halves of the image are used
stackmethod will be 'Horizontal' or 'Vertical'
> ```
>
___

### GetViewerList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a list of available viewers
>
> ```php
table GLView:GetViewerList()
> ```
>
___

### IsLUTEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if the current Monitor LUT is enabled
>
> ```php
boolean GLView:IsLUTEnabled()
> ```
>
___

### IsStereoEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Indicates if stereo display is currently enabled
>
> ```php
boolean GLView:IsStereoEnabled()
> ```
>
___

### IsStereoSwapped()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Indicates if the left & right stereo eyes are currently swapped
>
> ```php
boolean GLView:IsStereoSwapped()
> ```
>
___

### IsWipeEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### LoadLUTFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Loads a LUT file, setting or LUT plugin ID into the Monitor LUT
>
> ```php
boolean GLView:LoadLUTFile(string pathname)
> ```
>
___

### LoadPrefs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Saves the current view prefs to a named configuration
>
> ```php
 GLView:LoadPrefs()
> ```
>
> ```php
 GLView:LoadPrefs(string configname)
> ```
>
___

### ResetView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Resets the display to default position etc
>
> ```php
 GLView:ResetView()
> ```
>
___

### SavePrefs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Saves the current view prefs to a named configuration
>
> ```php
 GLView:SavePrefs()
> ```
>
> ```php
 GLView:SavePrefs(string configname)
> ```
>
___

### SetBuffer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Show a particular buffer
>
> ```php
 GLView:SetBuffer(number buffer, [boolean toggle])
> ```
>
> ```
where 'buffer' is one of the following numbers:
   0 = A
   1 = B
   2 = A|B split
> ```
>
___

### SetLocked()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Lock or unlock the display
>
> ```php
 GLView:SetLocked([boolean enable])
> ```
>
___

### SetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the position of the display
>
> ```php
boolean GLView:SetPos(number x, number y, [number z])
> ```
>
___

### SetRot()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the x,y,z rotation of the display in degrees
>
> ```php
 GLView:SetRot(number x, number y, number z)
> ```
>
___

### SetScale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the scale of the display
>
> ```php
 GLView:SetScale(number scale)
> ```
>
___

### SetSplit()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the split position of the view
>
> ```php
 GLView:SetSplit(number x, number y, number angle)
> ```
>
___

### SetStereoMethod()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the method for stereo display
>
> ```php
 GLView:SetStereoMethod(string method, [ option1], [ option2])
> ```
>
> ```
method can be one of the following strings:
	'Quad Buffer'	Enable OpenGL quad-buffered stereo mode
	'Anaglyph'		Tint and combine views for anaglyph glasses
		option1 can be 'Red/Cyan', 'Red/Green',	'Red/Blue', 'Amber/Blue' or 'Green/Magenta'
		option2 can be 'Monochrome', 'Half-color',	'Color', 'Optimised' or 'Dubois' (forces 'Red/Cyan')
	'Crosseyed'		Display views side-by-side for crosseyed viewing
	'Interlaced'		Display views on alternate scanlines
	'Checkerboard'		Stereo support for checkerboard DLPs
		option1 is the value for gamma correction of the polariser screen
	'Left Eye Only'	Display left eye view only
	'Right Eye Only'	Display right eye view only
> ```
>
___

### SetStereoSource()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the source for the left & right stereo images
>
> ```php
 GLView:SetStereoSource(boolean ABsource, boolean stacked, [string stackmethod])
> ```
>
> ```
Pass true for ABsource to use the A and B buffers for left & right views.
Pass true for stacked to use the two halves of the image for left & right views.
stackmethod may be 'Horizontal' or 'Vertical' for side-by-side or over-under images, respectively.
> ```
>
___

### ShowLUTEditor()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Pops up the Editor window for the current Monitor LUT
>
> ```php
 GLView:ShowLUTEditor()
> ```
>
___

### ShowQuadView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Splits the view into four subviews
>
> ```php
 GLView:ShowQuadView([boolean enable])
> ```
>
___

### ShowSubView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables the inset SubView display
>
> ```php
 GLView:ShowSubView([boolean enable])
> ```
>
___

### ShowingQuadView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if the view is split into four
>
> ```php
boolean GLView:ShowingQuadView()
> ```
>
___

### ShowingSubView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if the inset SubView is currently being displayed
>
> ```php
boolean GLView:ShowingSubView()
> ```
>
___

### SwapStereo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Swaps left & right stereo eye views
>
> ```php
 GLView:SwapStereo()
> ```
>
> ```php
 GLView:SwapStereo([boolean enable])
> ```
>
___

### SwapSubView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Swaps the SubView with the Main View
>
> ```php
boolean GLView:SwapSubView()
> ```
>
___

### WipeEnable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
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
> 1638400 = CT_View
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 4294967196
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
> GLView
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> GLView
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

