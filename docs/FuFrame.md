# FuFrame
 : [Object](Object.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Composition](#Composition)
>
> [ConsoleView](#ConsoleView)
>
> [CurrentView](#CurrentView)
>
> [FlowView](#FlowView)
>
> [InfoView](#InfoView)
>
> [LeftView](#LeftView)
>
> [ModifierView](#ModifierView)
>
> [RightView](#RightView)
>
> [SplineView](#SplineView)
>
> [TimeRulerView](#TimeRulerView)
>
> [TimelineView](#TimelineView)
>
> [ToolView](#ToolView)
>
> [TransportView](#TransportView)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetPreviewList](#GetPreviewList)()
>
> [GetViewList](#GetViewList)()
>
> [SwitchView](#SwitchView)()
>
> [ViewOn](#ViewOn)()
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

### Composition
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's Composition
>
> *<span class="read_only">Read Only</span>*
>
> ```
The Composition variable represents the Composition object that thisframe window is displaying.
> ```
>
___

### ConsoleView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's console
>
> *<span class="read_only">Read Only</span>*
>
> ```
The ConsoleView variable represents the FuView object used to displayany scripting message, and to allow script commands to be entered.
> ```
>
___

### CurrentView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents the currently active view for this frame window
>
> *<span class="read_only">Read Only</span>*
>
> ```
The CurrentView variable represents the currently active view for this frame window.
> ```
>
___

### FlowView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's Flow view
>
> *<span class="read_only">Read Only</span>*
>
> ```
The FlowView variable represents the FuView object used to displaythe various tool connections for the frame's Composition.
> ```
>
___

### InfoView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's Info view
>
> *<span class="read_only">Read Only</span>*
>
> ```
The InfoView variable represents the FuView object used to displayany general notes for the frame's Composition.
> ```
>
___

### LeftView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's left display view
>
> *<span class="read_only">Read Only</span>*
>
> ```
The LeftView variable represents the left-hand GLView object used todisplay images, 3D scenes and other parameters output by a tool.
> ```
>
___

### ModifierView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's Modifier controls view
>
> *<span class="read_only">Read Only</span>*
>
___

### RightView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's right display view
>
> *<span class="read_only">Read Only</span>*
>
> ```
The RightView variable represents the right-hand GLView object used todisplay images, 3D scenes and other parameters output by a tool.
> ```
>
___

### SplineView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's spline editor view
>
> *<span class="read_only">Read Only</span>*
>
___

### TimeRulerView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's time ruler
>
> *<span class="read_only">Read Only</span>*
>
___

### TimelineView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's Timeline view
>
> *<span class="read_only">Read Only</span>*
>
___

### ToolView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's Tool controls view
>
> *<span class="read_only">Read Only</span>*
>
___

### TransportView
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents this frame window's transport controls view
>
> *<span class="read_only">Read Only</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### GetPreviewList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieves a table of previews
>
> ```php
table FuFrame:GetPreviewList([boolean include_globals])
> ```
>
___

### GetViewList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the list of views within this frame
>
> ```php
table FuFrame:GetViewList()
> ```
>
> ```
where 'table' is a table of the FuView objects in the frame,
and entries are named by the view's ID string.
> ```
>
> *Se also: [SwitchControlView()](ChildFrame.md#SwitchControlView), [GetMainViewList()](ChildFrame.md#GetMainViewList)*
___

### SwitchView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays a given view within this frame
>
> ```php
 FuFrame:SwitchView(string id)
> ```
>
> ```
where 'id' is the ID of one of the views in the frame.
 e.g. 'FlowView', 'ConsoleView', 'TimelineView', 'SplineEditorView'
> ```
>
> *Se also: [GetViewList()](#GetViewList)*
___

### ViewOn()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays a tool on a numbered view
>
> ```php
 FuFrame:ViewOn([Tool tool], [number view])
> ```
>
> ```
where 'view' is a number from 0..9.
If 'tool' is omitted, the currently active tool is used.
If 'tool' is nil, the view is cleared.
If no arguments are supplied, all views are cleared.
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
> FuFrame
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> FuFrame
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

