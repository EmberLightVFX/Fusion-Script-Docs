# SplineEditorView
 : [Object](Object.md) : [FuView](FuView.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [ZoomX](#ZoomX)
>
> [ZoomY](#ZoomY)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [DeleteGuides](#DeleteGuides)()
>
> [GetClipboard](#GetClipboard)()
>
> [GetGuides](#GetGuides)()
>
> [GoNextKeyTime](#GoNextKeyTime)()
>
> [GoPrevKeyTime](#GoPrevKeyTime)()
>
> [InZoomToRectMode](#InZoomToRectMode)()
>
> [Paste](#Paste)()
>
> [SetGuides](#SetGuides)()
>
> [ZoomFit](#ZoomFit)()
>
> [ZoomIn](#ZoomIn)()
>
> [ZoomOut](#ZoomOut)()
>
> [ZoomRectangle](#ZoomRectangle)()
>
> [ZoomToRect](#ZoomToRect)()
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
> [REGS_UIName](#REGS_UIName)
>
> [REGB_Unpredictable](#REGB_Unpredictable)
>
> [REGI_Version](#REGI_Version)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Properties: <!-- {docsify-ignore} -->

### ZoomX
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
___

### ZoomY
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
___


# Methods: <!-- {docsify-ignore} -->

### DeleteGuides()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Deletes guides between start and end
>
> ```php
 SplineEditorView:DeleteGuides([number start], [number end])
> ```
>
___

### GetClipboard()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieves the tool(s) on the clipboard, as tables and as ASCII text.
>
> ```php
table, string SplineEditorView:GetClipboard()
> ```
>
> *Se also: [SetClipboard()](#SetClipboard)*
___

### GetGuides()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of snapguide times & names
>
> ```php
table SplineEditorView:GetGuides([number start], [number end])
> ```
>
___

### GoNextKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Jumps to next key frame of the active spline
>
> ```php
 SplineEditorView:GoNextKeyTime()
> ```
>
___

### GoPrevKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Jumps to previous key frame of the active spline
>
> ```php
 SplineEditorView:GoPrevKeyTime()
> ```
>
___

### InZoomToRectMode()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Use TimeStretch
>
> ```php
boolean SplineEditorView:InZoomToRectMode()
> ```
>
___

### Paste()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Paste points to given splines at given time from the Clipboard
>
> ```php
boolean SplineEditorView:Paste(number desttime, object spline1, [object spline2...], [table points])
> ```
>
___

### SetGuides()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets snapguide
>
> ```php
 SplineEditorView:SetGuides([table guides], [boolean rem_prev])
> ```
>
___

### ZoomFit()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Changes scale to fit all displayed splines within the view
>
> ```php
 SplineEditorView:ZoomFit()
> ```
>
___

### ZoomIn()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Increases the scale (zoom) of the view
>
> ```php
 SplineEditorView:ZoomIn()
> ```
>
___

### ZoomOut()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Decreases the scale (zoom) of the view
>
> ```php
 SplineEditorView:ZoomOut()
> ```
>
___

### ZoomRectangle()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Fill the view with the specified rectangle
>
> ```php
 SplineEditorView:ZoomRectangle()
> ```
>
> ```php
 SplineEditorView:ZoomRectangle(number x1, number y1, number x2, number y2)
> ```
>
___

### ZoomToRect()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Zoom to Rectangle
>
> ```php
 SplineEditorView:ZoomToRect()
> ```
>
___


# Registry Attributes: <!-- {docsify-ignore} -->

### REGI_ClassType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 1638400 = CT_View
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
> SplineEditorView
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Spline
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 1000
>
___

### REGB_SupportsDoD
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGS_UIName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Spline
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

