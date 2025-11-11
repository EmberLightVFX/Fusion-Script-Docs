# GLViewer
 : [Object](Object.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AreControlsShown](#AreControlsShown)()
>
> [AreGuidesShown](#AreGuidesShown)()
>
> [EnableChecker](#EnableChecker)()
>
> [EnableLUT](#EnableLUT)()
>
> [GetAlphaOverlayColor](#GetAlphaOverlayColor)()
>
> [GetAspectCorrection](#GetAspectCorrection)()
>
> [GetChannel](#GetChannel)()
>
> [GetPos](#GetPos)()
>
> [GetPosTable](#GetPosTable)()
>
> [GetRot](#GetRot)()
>
> [GetRotTable](#GetRotTable)()
>
> [GetScale](#GetScale)()
>
> [IsCheckerEnabled](#IsCheckerEnabled)()
>
> [IsLUTEnabled](#IsLUTEnabled)()
>
> [LoadFile](#LoadFile)()
>
> [Redraw](#Redraw)()
>
> [ResetView](#ResetView)()
>
> [SaveFile](#SaveFile)()
>
> [SetAlphaOverlayColor](#SetAlphaOverlayColor)()
>
> [SetAspectCorrection](#SetAspectCorrection)()
>
> [SetChannel](#SetChannel)()
>
> [SetPos](#SetPos)()
>
> [SetRot](#SetRot)()
>
> [SetScale](#SetScale)()
>
> [ShowControls](#ShowControls)()
>
> [ShowGuides](#ShowGuides)()
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

### AreControlsShown()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if controls are being displayed on the view
>
> ```php
boolean GLViewer:AreControlsShown()
> ```
>
___

### AreGuidesShown()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if image guides are being displayed on the view
>
> ```php
boolean GLViewer:AreGuidesShown()
> ```
>
___

### EnableChecker()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables drawing a checker underlay
>
> ```php
 GLViewer:EnableChecker([boolean enable])
> ```
>
___

### EnableLUT()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 GLViewer:EnableLUT([boolean enable])
> ```
>
___

### GetAlphaOverlayColor()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Return which alpha overlay is being used
>
> ```php
number GLViewer:GetAlphaOverlayColor()
> ```
>
> ```
0 = None, 1 = Red, 2 = Green, 3 = Yellow, 4 = Blue, 5 = Cyan, 6 = Magenta, 7 = White.
> ```
>
___

### GetAspectCorrection()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if the viewer is correcting the aspect of images
>
> ```php
boolean GLViewer:GetAspectCorrection()
> ```
>
___

### GetChannel()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Return which channel is shown
>
> ```php
number GLViewer:GetChannel()
> ```
>
___

### GetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the position of the viewer
>
> ```php
number, number, number GLViewer:GetPos()
> ```
>
___

### GetPosTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the position of the viewer as a table
>
> ```php
table GLViewer:GetPosTable()
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

### GetRot()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the rotation angles of the view
>
> ```php
number, number, number GLViewer:GetRot()
> ```
>
___

### GetRotTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the rotation angles of the view as a table
>
> ```php
table GLViewer:GetRotTable()
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
> Get the scale (zoom) of the view
>
> ```php
number GLViewer:GetScale()
> ```
>
___

### IsCheckerEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### IsLUTEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### LoadFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Load and display the contents of a file
>
> ```php
 GLViewer:LoadFile(string filename)
> ```
>
___

### Redraw()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Refreshes the viewer
>
> ```php
 GLViewer:Redraw()
> ```
>
___

### ResetView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Resets the display to default position etc
>
> ```php
 GLViewer:ResetView()
> ```
>
___

### SaveFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save the currently displayed parameter
>
> ```php
 GLViewer:SaveFile(string filename)
> ```
>
___

### SetAlphaOverlayColor()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Select which alpha overlay to use
>
> ```php
 GLViewer:SetAlphaOverlayColor(number color)
> ```
>
> ```
0 = None, 1 = Red, 2 = Green, 3 = Yellow, 4 = Blue, 5 = Cyan, 6 = Magenta, 7 = White.
> ```
>
___

### SetAspectCorrection()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables aspect correction
>
> ```php
 GLViewer:SetAspectCorrection(boolean enable)
> ```
>
___

### SetChannel()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Select which channel to show
>
> ```php
 GLViewer:SetChannel(number channel, boolean toggle)
> ```
>
> ```
When `toggle` is true, the first SetChannel(CHAN_Z) call will set the viewer to Z, while the second SetChannel(CHAN_Z) call will set the viewer to CHAN_COLOR
> ```
>
___

### SetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the position of the viewer
>
> ```php
boolean GLViewer:SetPos(number x, number y, [number z])
> ```
>
___

### SetRot()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the rotation of the view
>
> ```php
 GLViewer:SetRot(number x, number y, number z)
> ```
>
___

### SetScale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the scale (zoom) of the view
Scale of 0 indicates Fit to View
>
> ```php
 GLViewer:SetScale(number scale)
> ```
>
___

### ShowControls()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Shows or hides controls on the view
>
> ```php
 GLViewer:ShowControls(boolean enable)
> ```
>
___

### ShowGuides()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Shows or hides guides on the view
>
> ```php
 GLViewer:ShowGuides(boolean enable)
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
> GLViewer
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> GLViewer
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 2025
>
___

