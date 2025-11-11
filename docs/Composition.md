# Composition
 : [Object](Object.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [ActiveTool](#ActiveTool)
>
> [AutoPos](#AutoPos)
>
> [CurrentFrame](#CurrentFrame)
>
> [CurrentTime](#CurrentTime)
>
> [UpdateMode](#UpdateMode)
>
> [XPos](#XPos)
>
> [YPos](#YPos)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AbortRender](#AbortRender)()
>
> [AbortRenderUI](#AbortRenderUI)()
>
> [AddMedia](#AddMedia)()
>
> [AddSettingAction](#AddSettingAction)()
>
> [AddTool](#AddTool)()
>
> [AddToolAction](#AddToolAction)()
>
> [AskRenderSettings](#AskRenderSettings)()
>
> [AskUser](#AskUser)()
>
> [ChooseAction](#ChooseAction)()
>
> [ChooseTool](#ChooseTool)()
>
> [ClearUndo](#ClearUndo)()
>
> [Close](#Close)()
>
> [Copy](#Copy)()
>
> [CopySettings](#CopySettings)()
>
> [DisableSelectedTools](#DisableSelectedTools)()
>
> [EndUndo](#EndUndo)()
>
> [Execute](#Execute)()
>
> [ExecuteFile](#ExecuteFile)()
>
> [ExpandZone](#ExpandZone)()
>
> [Export](#Export)()
>
> [FindTool](#FindTool)()
>
> [FindToolByID](#FindToolByID)()
>
> [GetCompPathMap](#GetCompPathMap)()
>
> [GetConsoleHistory](#GetConsoleHistory)()
>
> [GetData](#GetData)()
>
> [GetFrameList](#GetFrameList)()
>
> [GetMarkers](#GetMarkers)()
>
> [GetNextKeyTime](#GetNextKeyTime)()
>
> [GetPrefs](#GetPrefs)()
>
> [GetPrevKeyTime](#GetPrevKeyTime)()
>
> [GetPreviewList](#GetPreviewList)()
>
> [GetRedoStack](#GetRedoStack)()
>
> [GetToolList](#GetToolList)()
>
> [GetUndoStack](#GetUndoStack)()
>
> [GetViewList](#GetViewList)()
>
> [Heartbeat](#Heartbeat)()
>
> [IsLocked](#IsLocked)()
>
> [IsPlaying](#IsPlaying)()
>
> [IsReadOnly](#IsReadOnly)()
>
> [IsRendering](#IsRendering)()
>
> [IsViewShowing](#IsViewShowing)()
>
> [IsZoneExpanded](#IsZoneExpanded)()
>
> [Lock](#Lock)()
>
> [Loop](#Loop)()
>
> [MapPath](#MapPath)()
>
> [MapPathSegments](#MapPathSegments)()
>
> [NetRenderAbort](#NetRenderAbort)()
>
> [NetRenderEnd](#NetRenderEnd)()
>
> [NetRenderStart](#NetRenderStart)()
>
> [NetRenderTime](#NetRenderTime)()
>
> [Paste](#Paste)()
>
> [Play](#Play)()
>
> [Print](#Print)()
>
> [Redo](#Redo)()
>
> [Render](#Render)()
>
> [Reset](#Reset)()
>
> [ReverseMapPath](#ReverseMapPath)()
>
> [RunScript](#RunScript)()
>
> [Save](#Save)()
>
> [SaveAs](#SaveAs)()
>
> [SaveCopyAs](#SaveCopyAs)()
>
> [SaveVersion](#SaveVersion)()
>
> [SetActiveTool](#SetActiveTool)()
>
> [SetData](#SetData)()
>
> [SetMarker](#SetMarker)()
>
> [SetPrefs](#SetPrefs)()
>
> [SetReadOnly](#SetReadOnly)()
>
> [ShowView](#ShowView)()
>
> [StartUndo](#StartUndo)()
>
> [Stop](#Stop)()
>
> [Transcribe](#Transcribe)()
>
> [Undo](#Undo)()
>
> [Unlock](#Unlock)()
>
> [UpdateViews](#UpdateViews)()
>
> [_Output_Error](#_Output_Error)()
>
> [_Output_Print](#_Output_Print)()
>
> [_Save](#_Save)()
>
> [_SaveAs](#_SaveAs)()
>
> [_SaveCopyAs](#_SaveCopyAs)()
>
> [_SetCurrentTime](#_SetCurrentTime)()
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

### ActiveTool
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents the currently active tool on this comp
>
> `Type: Tool`
>
> *<span class="read_only">Read Only</span>*
>
___

### AutoPos
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_write">Read/Write</span>*
>
___

### CurrentFrame
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Represents the currently active frame for this composition
>
> `Type: FuFrame`
>
> *<span class="read_only">Read Only</span>*
>
___

### CurrentTime
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> The current time position for this composition
>
> `Type: number`
>
> *<span class="read_write">Read/Write</span>*
>
___

### UpdateMode
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> *<span class="read_write">Read/Write</span>*
>
___

### XPos
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number`
>
> *<span class="read_write">Read/Write</span>*
>
> *Se also: [YPos](#YPos)*
___

### YPos
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number`
>
> *<span class="read_write">Read/Write</span>*
>
> *Se also: [XPos](#XPos)*
___


# Methods: <!-- {docsify-ignore} -->

### AbortRender()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### AbortRenderUI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### AddMedia()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### AddSettingAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a .settings to the comp
>
> ```php
Tool Composition:AddSettingAction(string filename, [number xpos], [number ypos])
> ```
>
___

### AddTool()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a tool to the comp at a given position
>
> ```php
Tool Composition:AddTool(string id, [boolean defsettings], [number xpos], [number ypos])
> ```
>
> ```
Args:    id          - string type of tool to be created
         defsettings - boolean to use saved default settings
         xpos, ypos  - integer position on flow view
> ```
>
___

### AddToolAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a tool to the comp
>
> ```php
Tool Composition:AddToolAction(string id, [number xpos], [number ypos])
> ```
>
___

### AskRenderSettings()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### AskUser()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Present a custom dialog to the user, and return selected values
>
> ```php
table Composition:AskUser(string title, table controls)
> ```
>
> ```
Returns a table of result values, determined by individual control types
> ```
>
___

### ChooseAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays a dialog with a list of selectable actions
>
> ```php
string Composition:ChooseAction(boolean execute, object target)
> ```
>
> ```
Allows the user to select from a list of actions, and returns the action.
> ```
>
___

### ChooseTool()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays a dialog with a list of selectable tools
>
> ```php
string, string Composition:ChooseTool(boolean execute)
> ```
>
> ```
Allows the user to select from a list of tools, and returns the tool ID.
If a macro is selected, the path is also returned.
> ```
>
___

### ClearUndo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Clears the Undo/Redo history
>
> ```php
 Composition:ClearUndo()
> ```
>
> *Se also: [StartUndo()](#StartUndo), [EndUndo()](#EndUndo), [Undo()](#Undo), [Redo()](#Redo)*
___

### Close()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Close the composition
>
> ```php
 Composition:Close()
> ```
>
___

### Copy()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Copy a list of tools to the Clipboard
>
> ```php
boolean Composition:Copy()
> ```
>
> ```php
boolean Composition:Copy(Tool tool)
> ```
>
> ```php
boolean Composition:Copy(table toollist)
> ```
>
> ```
Can be passed a single tool or a table of tools.
If no args are given, the currently selected tools will be copied.
> ```
>
___

### CopySettings()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Copy a list of tools to a settings table
>
> ```php
table Composition:CopySettings()
> ```
>
> ```php
table Composition:CopySettings(Tool tool)
> ```
>
> ```php
table Composition:CopySettings(table toollist)
> ```
>
> ```
Can be passed a single tool or a table of tools.
If no args are given, the currently selected tools will be copied.
> ```
>
___

### DisableSelectedTools()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Pass-through the selected tools
>
> ```php
 Composition:DisableSelectedTools()
> ```
>
___

### EndUndo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> End an undo event
>
> ```php
 Composition:EndUndo(boolean keep)
> ```
>
> *Se also: [StartUndo()](#StartUndo), [Undo()](#Undo), [Redo()](#Redo)*
___

### Execute()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Executes a script string
>
> ```php
 Composition:Execute(string script text)
> ```
>
___

### ExecuteFile()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Executes a script file internally
>
> ```php
 Composition:ExecuteFile(string filename, table args)
> ```
>
___

### ExpandZone()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Export()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Exports the current composition to a file.
>
> ```php
boolean Composition:Export(string filename)
> ```
>
> ```
This saves the composition to an external .comp file, translating as required.
> ```
>
> *Se also: [Save()](#Save)*
___

### FindTool()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Finds first tool by name
>
> ```php
Tool Composition:FindTool(string name)
> ```
>
> *Se also: [FindToolbyID()](#FindToolbyID)*
___

### FindToolByID()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Finds tools of a given type
>
> ```php
Tool Composition:FindToolByID(string id, [Tool prev])
> ```
>
> ```
Args:    id   - string type of tool
         prev - optional tool to start search from
> ```
>
> *Se also: [FindTool()](#FindTool)*
___

### GetCompPathMap()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of all Composition path maps
>
> ```php
table Composition:GetCompPathMap([boolean built_ins], [boolean defaults])
> ```
>
> ```
Args:  built_ins - include built-in path maps (default: true)
       defaults  - include factory default path maps (default: true)
Returns: Table of path strings, keyed by map name.
> ```
>
___

### GetConsoleHistory()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get custom persistent data
>
> ```php
(number|string|boolean|table) Composition:GetData([string name])
> ```
>
> *Se also: [SetData()](#SetData)*
___

### GetFrameList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetMarkers()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of timeline markers.
>
> ```php
list Composition:GetMarkers([time timestamp])
> ```
>
> ```
This returns a list of timeline markers, each with a table/dict of attributes.
> ```
>
___

### GetNextKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Gets the next key time
>
> ```php
number Composition:GetNextKeyTime([number time], [Tool tool])
> ```
>
> ```
Returns: The timestamp of the keyframe after the given time
	for the specified tool, or for any tool, if none is specified.
	If no time is given, the first keyframe time is returned.
> ```
>
___

### GetPrefs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieve a table of preferences
>
> ```php
table Composition:GetPrefs([string prefname], [boolean exclude-defaults])
> ```
>
> *Se also: [SetPrefs()](#SetPrefs)*
___

### GetPrevKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Gets the previous key time
>
> ```php
number Composition:GetPrevKeyTime([number time], [Tool tool])
> ```
>
> ```
Returns: The timestamp of the keyframe before the given time
	for the specified tool, or for any tool, if none is specified.
	If no time is given, the last keyframe time is returned.
> ```
>
___

### GetPreviewList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrieves a table of previews
>
> ```php
table Composition:GetPreviewList([boolean include_globals])
> ```
>
___

### GetRedoStack()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetToolList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a list of all tools, or selected tools, in the composition
>
> ```php
table Composition:GetToolList([boolean selected], [string regid])
> ```
>
> ```
selected - pass 'true' to get only selected tools
regid    - pass a Registry ID string to get only tools of that type
> ```
>
___

### GetUndoStack()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetViewList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Heartbeat()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### IsLocked()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Composition:IsLocked()
> ```
>
> *Se also: [Unlock()](#Unlock), [Lock()](#Lock)*
___

### IsPlaying()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Composition:IsPlaying()
> ```
>
___

### IsReadOnly()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### IsRendering()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Composition:IsRendering()
> ```
>
___

### IsViewShowing()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### IsZoneExpanded()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Lock()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Lock the composition from updating
>
> ```php
 Composition:Lock()
> ```
>
> *Se also: [Unlock()](#Unlock)*
___

### Loop()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables looping interactive playback
>
> ```php
 Composition:Loop(boolean enable)
> ```
>
> ```php
 Composition:Loop(string mode)
> ```
>
> ```
where `mode` is one of the following:
   `none`
   `loop`
   `pingpong`
> ```
>
___

### MapPath()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Expands path mappings in a path string
>
> ```php
string Composition:MapPath(string path)
> ```
>
> ```
Returns the path string with all mappings expanded. Only the first path of a multipath is returned.
> ```
>
> *Se also: [ReverseMapPath()](#ReverseMapPath), [MapPathSegments()](#MapPathSegments), [MapPath()](Fusion.md#MapPath)*
___

### MapPathSegments()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Expands all path mappings in a multipath
>
> ```php
table Composition:MapPathSegments(string path)
> ```
>
> ```
Returns a table of path strings with all mappings expanded. All paths of a multipath are returned.
> ```
>
> *Se also: [ReverseMapPath()](#ReverseMapPath), [MapPath()](#MapPath), [MapPathSegments()](Fusion.md#MapPathSegments)*
___

### NetRenderAbort()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### NetRenderEnd()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### NetRenderStart()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### NetRenderTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Paste()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Paste tools from the Clipboard
>
> ```php
boolean Composition:Paste([table settings])
> ```
>
> ```
'settings' may contain the results of Copy() or Operator:SaveSettings()
If no args are given, the Clipboard will be pasted.
> ```
>
___

### Play()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Starts interactive playback
>
> ```php
 Composition:Play([boolean reverse])
> ```
>
___

### Print()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Redo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Redo one or more changes to the composition
>
> ```php
 Composition:Redo(number count)
> ```
>
> *Se also: [StartUndo()](#StartUndo), [EndUndo()](#EndUndo), [Undo()](#Undo)*
___

### Render()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Start a render
>
> ```php
boolean Composition:Render([boolean wait], [number start], [number end], [number proxy], [boolean hiq], [boolean motionblur])
> ```
>
> ```php
boolean Composition:Render(table settings)
> ```
>
___

### Reset()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### ReverseMapPath()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Collapses a path into best-matching path map
>
> ```php
string Composition:ReverseMapPath(string mapped)
> ```
>
> ```
Returns the path string relative to nearest applicable mapped path.
> ```
>
> *Se also: [MapPath()](#MapPath), [MapPathSegments()](#MapPathSegments), [ReverseMapPath()](Fusion.md#ReverseMapPath)*
___

### RunScript()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Run a script file externally
>
> ```php
 Composition:RunScript(string filename)
> ```
>
___

### Save()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save the composition
>
> ```php
boolean Composition:Save(string filename)
> ```
>
___

### SaveAs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save the composition
>
> ```php
 Composition:SaveAs()
> ```
>
___

### SaveCopyAs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save a copy of the composition
>
> ```php
 Composition:SaveCopyAs()
> ```
>
___

### SaveVersion()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save the composition
>
> ```php
boolean Composition:SaveVersion(string filename, [number version])
> ```
>
___

### SetActiveTool()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set the currently active tool
>
> ```php
 Composition:SetActiveTool(Tool tool)
> ```
>
___

### SetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set custom persistent data
>
> ```php
 Composition:SetData(string name, (number|string|boolean|table) value)
> ```
>
> *Se also: [GetData()](#GetData)*
___

### SetMarker()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Creates or changes a timeline marker.
>
> ```php
 Composition:SetMarker(number timestamp, table marker data)
> ```
>
> ```
This will add or overwrite a timeline marker. Pass a table/dict of attributes, or nil to delete the marker.
> ```
>
___

### SetPrefs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set preferences from a table of attributes
>
> ```php
 Composition:SetPrefs(string prefname, value val)
> ```
>
> ```php
 Composition:SetPrefs(table prefs)
> ```
>
> *Se also: [GetPrefs()](#GetPrefs)*
___

### SetReadOnly()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### ShowView()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### StartUndo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Start an undo event
>
> ```php
 Composition:StartUndo(string name)
> ```
>
> *Se also: [EndUndo()](#EndUndo), [Undo()](#Undo), [Redo()](#Redo)*
___

### Stop()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Stops interactive playback
>
> ```php
 Composition:Stop()
> ```
>
___

### Transcribe()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Fetches transcription data for given media.
>
> ```php
table Composition:Transcribe(string media ID, [boolean detect speaker])
> ```
>
> ```
Resolve: This takes a media ID string, performs transcription on the media, then returns a table of text and timing.
> ```
>
___

### Undo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Undo one or more changes to the composition
>
> ```php
 Composition:Undo(number count)
> ```
>
> *Se also: [StartUndo()](#StartUndo), [EndUndo()](#EndUndo), [Redo()](#Redo)*
___

### Unlock()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Unlock the composition
>
> ```php
 Composition:Unlock()
> ```
>
> *Se also: [Lock()](#Lock)*
___

### UpdateViews()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### _Output_Error()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### _Output_Print()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### _Save()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### _SaveAs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save the composition
>
> ```php
 Composition:_SaveAs()
> ```
>
___

### _SaveCopyAs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save a copy of the composition
>
> ```php
 Composition:_SaveCopyAs()
> ```
>
___

### _SetCurrentTime()
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
> Composition
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Composition
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 2025
>
___

