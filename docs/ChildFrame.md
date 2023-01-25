# ChildFrame
 : [Object](Object.md) : [FuFrame](FuFrame.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ActivateFrame](#ActivateFrame)()
>
> [ActivateNextFrame](#ActivateNextFrame)()
>
> [ActivatePrevFrame](#ActivatePrevFrame)()
>
> [GetControlViewList](#GetControlViewList)()
>
> [GetMainViewList](#GetMainViewList)()
>
> [GetViewLayout](#GetViewLayout)()
>
> [LoadLayout](#LoadLayout)()
>
> [ResetLayout](#ResetLayout)()
>
> [SaveLayout](#SaveLayout)()
>
> [SetScreenLayout](#SetScreenLayout)()
>
> [SetViewLayout](#SetViewLayout)()
>
> [SwitchControlView](#SwitchControlView)()
>
> [SwitchLayout](#SwitchLayout)()
>
> [SwitchMainView](#SwitchMainView)()
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

### ActivateFrame()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Activates this frame window
>
> ```php
 ChildFrame:ActivateFrame()
> ```
>
___

### ActivateNextFrame()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Activates the next frame window
>
> ```php
 ChildFrame:ActivateNextFrame()
> ```
>
___

### ActivatePrevFrame()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Activates the previous frame window
>
> ```php
 ChildFrame:ActivatePrevFrame()
> ```
>
___

### GetControlViewList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the list of views from the Controls tabs
>
> ```php
table ChildFrame:GetControlViewList()
> ```
>
> ```
where 'table' is a table of the FuView objects in the Controls view tabs,and entries are named by the view's ID string.
> ```
>
> *Se also: [SwitchControlView()](#SwitchControlView), [GetMainViewList()](#GetMainViewList)*
___

### GetMainViewList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the list of views from the Main tabs
>
> ```php
table ChildFrame:GetMainViewList()
> ```
>
> ```
where 'views' is a table of the FuView objects in the Main view tabs,and entries are named by the view's ID string.
> ```
>
> *Se also: [SwitchMainView()](#SwitchMainView), [GetControlViewList()](#GetControlViewList)*
___

### GetViewLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieves the current view layout
>
> ```php
table ChildFrame:GetViewLayout()
> ```
>
> ```
Returns a table describing the current view layout
> ```
>
___

### LoadLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ChildFrame:LoadLayout()
> ```
>
___

### ResetLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ChildFrame:ResetLayout()
> ```
>
___

### SaveLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 ChildFrame:SaveLayout()
> ```
>
___

### SetScreenLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### SetViewLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the current view layout from a table
>
> ```php
boolean ChildFrame:SetViewLayout(table layout)
> ```
>
> ```
Args:  table describing the view layout
> ```
>
___

### SwitchControlView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays a given view from the Control tabs
>
> ```php
 ChildFrame:SwitchControlView(string id)
> ```
>
> ```
where 'id' is the ID of one of the views in the Controls tab list.
e.g. 'ControlView', 'ModifierView'
> ```
>
> *Se also: [GetControlViewList()](#GetControlViewList), [SwitchMainView()](#SwitchMainView)*
___

### SwitchLayout()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### SwitchMainView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays a given view from the Main tabs
>
> ```php
 ChildFrame:SwitchMainView(string id)
> ```
>
> ```
where 'id' is the ID of one of the views in the Main tab list.
e.g. 'FlowView', 'ConsoleView', 'TimelineView', 'SplineEditorView'
> ```
>
> *Se also: [GetMainViewList()](#GetMainViewList), [SwitchControlView()](#SwitchControlView)*
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
> ChildFrame
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> ChildFrame
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

