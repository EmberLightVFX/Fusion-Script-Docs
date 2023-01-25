# Operator
 : [Object](Object.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Composition](#Composition)
>
> [FillColor](#FillColor)
>
> [ID](#ID)
>
> [Name](#Name)
>
> [ParentTool](#ParentTool)
>
> [TextColor](#TextColor)
>
> [TileColor](#TileColor)
>
> [UserControls](#UserControls)
>
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Document](#Document)
>
> [IsBeingLoaded](#IsBeingLoaded)
>
> [Override](#Override)
>
> [ProgressCount](#ProgressCount)
>
> [ProgressScale](#ProgressScale)
>
> [Status](#Status)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddModifier](#AddModifier)()
>
> [ConnectInput](#ConnectInput)()
>
> [Delete](#Delete)()
>
> [FindMainInput](#FindMainInput)()
>
> [FindMainOutput](#FindMainOutput)()
>
> [GetChildrenList](#GetChildrenList)()
>
> [GetControlPageNames](#GetControlPageNames)()
>
> [GetCurrentSettings](#GetCurrentSettings)()
>
> [GetData](#GetData)()
>
> [GetInput](#GetInput)()
>
> [GetInputList](#GetInputList)()
>
> [GetKeyFrames](#GetKeyFrames)()
>
> [GetOutputList](#GetOutputList)()
>
> [LoadSettings](#LoadSettings)()
>
> [Refresh](#Refresh)()
>
> [SaveSettings](#SaveSettings)()
>
> [SetCurrentSettings](#SetCurrentSettings)()
>
> [SetData](#SetData)()
>
> [SetInput](#SetInput)()
>
> [ShowControlPage](#ShowControlPage)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddControlPage](#AddControlPage)()
>
> [AddOutput](#AddOutput)()
>
> [AddSeparator](#AddSeparator)()
>
> [AddSpacer](#AddSpacer)()
>
> [AddSubInputs](#AddSubInputs)()
>
> [BeginControlNest](#BeginControlNest)()
>
> [EndControlNest](#EndControlNest)()
>
> [EndUndo](#EndUndo)()
>
> [FindInput](#FindInput)()
>
> [FindOutput](#FindOutput)()
>
> [FindSubInputs](#FindSubInputs)()
>
> [GetNextKeyTime](#GetNextKeyTime)()
>
> [GetPrevKeyTime](#GetPrevKeyTime)()
>
> [GetRegion](#GetRegion)()
>
> [GetSourceTool](#GetSourceTool)()
>
> [IsGPUEnabled](#IsGPUEnabled)()
>
> [RemoveControlPage](#RemoveControlPage)()
>
> [SetProgress](#SetProgress)()
>
> [SetRegion](#SetRegion)()
>
> [StartUndo](#StartUndo)()
>
> [UpdateControls](#UpdateControls)()
>
> [_AddInput](#_AddInput)()
>
> [_CloneInput](#_CloneInput)()
>
### Tag Map
> ControlPage
>
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> [CTID_DIB_ID](#CTID_DIB_ID)
>>
>> [CTID_ID](#CTID_ID)
>>
>> [CTS_FullName](#CTS_FullName)
>>
>> [CTS_Name](#CTS_Name)
>>
>> [CT_AlwaysFullSaturation](#CT_AlwaysFullSaturation)
>>
>> [CT_NoExtraSpace](#CT_NoExtraSpace)
>>
>> [CT_Priority](#CT_Priority)
>>
>> [CT_Visible](#CT_Visible)
>>
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
> The composition that this tool belongs to
>
> `Type: Composition`
>
> *<span class="read_only">Read Only</span>*
>
___

### FillColor
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: table`
>
> *<span class="read_write">Read/Write</span>*
>
> ```
Examples: tool.FillColor = { R=0.5, G=0.3, B=0.2}
          tool.FillColor = nil
> ```
>
> *Se also: [TileColor](#TileColor), [TextColor](#TextColor)*
___

### ID
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Registry ID of this tool
>
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___

### Name
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Friendly name of this tool
>
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___

### ParentTool
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> The parent tool of this tool
>
> `Type: Tool`
>
> *<span class="read_only">Read Only</span>*
>
___

### TextColor
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Color of a tool's icon text in the Flow view
>
> `Type: table`
>
> *<span class="read_write">Read/Write</span>*
>
> ```
Examples: tool.TextColor = { R=0.5, G=0.3, B=0.2}
          tool.TextColor = nil
> ```
>
> *Se also: [TileColor](#TileColor), [FillColor](#FillColor)*
___

### TileColor
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Color of a tool's icon in the Flow view
>
> `Type: table`
>
> *<span class="read_write">Read/Write</span>*
>
> ```
Examples: tool.TileColor = { R=0.5, G=0.3, B=0.2}
          tool.TileColor = nil
> ```
>
> *Se also: [TextColor](#TextColor), [FillColor](#FillColor)*
___

### UserControls
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Table of user-control definitions
>
> `Type: table`
>
> *<span class="read_write">Read/Write</span>*
>
___


# Discovered Properties: <!-- {docsify-ignore} -->

### Document
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: FusionDoc`
>
> *<span class="read_only">Read Only</span>*
>
___

### IsBeingLoaded
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### Override
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: uint32`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ProgressCount
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: uint16`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ProgressScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: uint16`
>
> *<span class="read_write">Read/Write</span>*
>
___

### Status
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### AddModifier()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Creates a modifier and connects it to an input
>
> ```php
boolean Operator:AddModifier(string input, string modifier)
> ```
>
> ```
Arguments:
	input	- ID of the input to be connected to
	modifier	- ID of the modifier to be created
> ```
>
> *Se also: [Input()](#Input)*
___

### ConnectInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Connect or disconnect an Input
>
> ```php
boolean Operator:ConnectInput(string input, (Tool|Output|nil) target)
> ```
>
> ```
Arguments:
	input	- ID of the input to be connected/disconnected
	target	- Tool or Output to connect the Input to, or nil to disconnect
> ```
>
> *Se also: [Input()](#Input), [Output()](#Output)*
___

### Delete()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Delete this tool
>
> ```php
 Operator:Delete()
> ```
>
___

### FindMainInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the tool's main (visible) input
>
> ```php
Input Operator:FindMainInput(number index)
> ```
>
> ```
Arguments:
	index	- Input index value of 1 or greater
> ```
>
> *Se also: [Input()](#Input)*
___

### FindMainOutput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the tool's main (visible) output
>
> ```php
Output Operator:FindMainOutput(number index)
> ```
>
> ```
Arguments:
	index	- Output index value of 1 or greater
> ```
>
> *Se also: [Output()](#Output)*
___

### GetChildrenList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a list of all children tools, or selected children tools
>
> ```php
table Operator:GetChildrenList([boolean selected], [string regid])
> ```
>
> ```
Arguments:
   selected - pass 'true' to get only selected tools
   RegID    - pass a Registry ID string to get only tools of that type
> ```
>
___

### GetControlPageNames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of control page names
>
> ```php
table Operator:GetControlPageNames()
> ```
>
> ```
Returns: table of control page names, indexed by page number
> ```
>
___

### GetCurrentSettings()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the index of the tool's current settings slot
>
> ```php
number Operator:GetCurrentSettings()
> ```
>
> *Se also: [SetCurrentSettings()](#SetCurrentSettings)*
___

### GetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get custom persistent data
>
> ```php
(number|string|boolean|table) Operator:GetData([string name])
> ```
>
> *Se also: [SetData()](#SetData)*
___

### GetInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Fetches the value of an input at a given time
>
> ```php
(number|string|Parameter) Operator:GetInput(string id, [number time])
> ```
>
> ```
Arguments:
	id	- ID of input
	time	- keyframe to fetch (not required for non-animated inputs)
> ```
>
> *Se also: [SetInput()](#SetInput)*
___

### GetInputList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Return a table of all inputs on this tool
>
> ```php
table Operator:GetInputList([string type])
> ```
>
> *Se also: [GetOutputList()](#GetOutputList)*
___

### GetKeyFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Return a table of all keyframe times for this tool
>
> ```php
table Operator:GetKeyFrames()
> ```
>
> *Se also: [GetKeyFrames()](PlainInput.md#GetKeyFrames)*
___

### GetOutputList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Return a table of all outputs on this tool
>
> ```php
table Operator:GetOutputList([string type])
> ```
>
> *Se also: [GetInputList()](#GetInputList)*
___

### LoadSettings()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Load the tools's settings from a file or table
>
> ```php
boolean Operator:LoadSettings(string filename)
> ```
>
> ```php
boolean Operator:LoadSettings(table settings)
> ```
>
> *Se also: [SaveSettings()](#SaveSettings)*
___

### Refresh()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Refreshes the tool, showing updated user controls
>
> ```php
 Operator:Refresh()
> ```
>
> ```
Returns: handle to the new (refreshed) tool
> ```
>
___

### SaveSettings()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Save the tool's current settings to a file or table
>
> ```php
boolean Operator:SaveSettings(string filename)
> ```
>
> ```php
table Operator:SaveSettings(boolean customdata)
> ```
>
> *Se also: [LoadSettings()](#LoadSettings)*
___

### SetCurrentSettings()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the tool's current settings slot
>
> ```php
number Operator:SetCurrentSettings()
> ```
>
> *Se also: [GetCurrentSettings()](#GetCurrentSettings)*
___

### SetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set custom persistent data
>
> ```php
 Operator:SetData(string name, (number|string|boolean|table) value)
> ```
>
> *Se also: [GetData()](#GetData)*
___

### SetInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the value of an input at a given time
>
> ```php
 Operator:SetInput(string id, (number|string|Parameter) value, number time)
> ```
>
> ```
Arguments:
	inputID	- ID of input
	value	- number, string or Parameter object to set
	time	- keyframe to set (not required for non-animated inputs)
> ```
>
> *Se also: [GetInput()](#GetInput)*
___

### ShowControlPage()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Makes the specified control page visible
>
> ```php
 Operator:ShowControlPage(string name)
> ```
>
> ```
Arguments:
	name	- Control page to show
> ```
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### AddControlPage()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int32 Operator:AddControlPage(string name, TagList tags)
> ```
>
___

### AddOutput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Output Operator:AddOutput(string name, string id, TagList tags)
> ```
>
___

### AddSeparator()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Input Operator:AddSeparator(string id, TagList tags)
> ```
>
___

### AddSpacer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Input Operator:AddSpacer(string id, TagList tags)
> ```
>
___

### AddSubInputs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
SubInputs Operator:AddSubInputs(string subid, TagList tags)
> ```
>
___

### BeginControlNest()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Input Operator:BeginControlNest(string name, string id, boolean expand, TagList tags)
> ```
>
___

### EndControlNest()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Operator:EndControlNest()
> ```
>
___

### EndUndo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Operator:EndUndo(boolean keep)
> ```
>
___

### FindInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Input Operator:FindInput(string name)
> ```
>
___

### FindOutput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Output Operator:FindOutput(string name)
> ```
>
___

### FindSubInputs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
SubInputs Operator:FindSubInputs(string name)
> ```
>
___

### GetNextKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeStamp Operator:GetNextKeyTime(TimeStamp t)
> ```
>
___

### GetPrevKeyTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeStamp Operator:GetPrevKeyTime(TimeStamp t)
> ```
>
___

### GetRegion()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeRegion Operator:GetRegion()
> ```
>
___

### GetSourceTool()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Operator Operator:GetSourceTool(string name)
> ```
>
___

### IsGPUEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Operator:IsGPUEnabled(Request req)
> ```
>
___

### RemoveControlPage()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Operator:RemoveControlPage(string name)
> ```
>
___

### SetProgress()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Operator:SetProgress(float64 prog)
> ```
>
___

### SetRegion()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Operator:SetRegion(TimeRegion tr)
> ```
>
___

### StartUndo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Operator:StartUndo(string name)
> ```
>
___

### UpdateControls()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Operator:UpdateControls()
> ```
>
___

### _AddInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Input Operator:_AddInput(string name, string id, TagList tags)
> ```
>
___

### _CloneInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Input Operator:_CloneInput(Input from, string id, TagList tags)
> ```
>
___


# Tag Map: <!-- {docsify-ignore} -->

>## ControlPage 
>### CTID_DIB_ID
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### CTID_ID
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### CTS_FullName
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### CTS_Name
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### CT_AlwaysFullSaturation
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### CT_NoExtraSpace
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### CT_Priority
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### CT_Visible
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
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
> Operator
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Operator
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

