# TimelineView
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
> [ShowSortMenu](#ShowSortMenu)()
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
> [REGS_UIName](#REGS_UIName)
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
 TimelineView:DeleteGuides([number start], [number end])
> ```
>
___

### GetClipboard()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieves the tool(s) on the clipboard, as tables and as ASCII text.
>
> ```php
table, string TimelineView:GetClipboard()
> ```
>
> *Se also: [SetClipboard()](#SetClipboard)*
___

### GetGuides()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of snapguide times & names
>
> ```php
table TimelineView:GetGuides([number start], [number end])
> ```
>
___

### GoNextKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Jumps to next key frame of the active spline
>
> ```php
 TimelineView:GoNextKeyTime()
> ```
>
___

### GoPrevKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Jumps to previous key frame of the active spline
>
> ```php
 TimelineView:GoPrevKeyTime()
> ```
>
___

### InZoomToRectMode()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Use TimeStretch
>
> ```php
boolean TimelineView:InZoomToRectMode()
> ```
>
___

### Paste()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Paste points to given splines at given time from the Clipboard
>
> ```php
boolean TimelineView:Paste(number desttime, object spline1, [object spline2...], [table points])
> ```
>
___

### SetGuides()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets snapguide
>
> ```php
 TimelineView:SetGuides([table guides], [boolean rem_prev])
> ```
>
___

### ShowSortMenu()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Zoom to Rectangle
>
> ```php
 TimelineView:ShowSortMenu()
> ```
>
___

### ZoomFit()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Changes scale to fit all displayed splines within the view
>
> ```php
 TimelineView:ZoomFit()
> ```
>
___

### ZoomIn()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Increases the scale (zoom) of the view
>
> ```php
 TimelineView:ZoomIn()
> ```
>
___

### ZoomOut()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Decreases the scale (zoom) of the view
>
> ```php
 TimelineView:ZoomOut()
> ```
>
___

### ZoomRectangle()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Fill the view with the specified rectangle
>
> ```php
 TimelineView:ZoomRectangle()
> ```
>
> ```php
 TimelineView:ZoomRectangle(number x1, number y1, number x2, number y2)
> ```
>
___

### ZoomToRect()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Zoom to Rectangle
>
> ```php
 TimelineView:ZoomToRect()
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
> 1638400 = CT_View
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 1001
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
> TimelineView
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Timeline
>
___

### REGS_UIName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Timeline
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Aug 21 2024
>
___

