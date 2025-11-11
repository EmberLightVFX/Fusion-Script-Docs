# Link
 : [Object](Object.md) : [LockableObject](LockableObject.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [ID](#ID)
>
> [Name](#Name)
>
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Owner](#Owner)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetData](#GetData)()
>
> [GetDefaultLayer](#GetDefaultLayer)()
>
> [GetLayerList](#GetLayerList)()
>
> [GetTool](#GetTool)()
>
> [HasLayer](#HasLayer)()
>
> [SetData](#SetData)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [IsConnected](#IsConnected)()
>
### Tag Map
> Create
>
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> [LINKID_AddAfterID](#LINKID_AddAfterID)
>>
>> [LINKID_AddBeforeID](#LINKID_AddBeforeID)
>>
>> [LINKID_AllowedDataType](#LINKID_AllowedDataType)
>>
>> [LINKID_ID](#LINKID_ID)
>>
>> [LINKID_LegacyID](#LINKID_LegacyID)
>>
>> [LINKP_OwnerOp](#LINKP_OwnerOp)
>>
>> [LINKS_Name](#LINKS_Name)
>>
>> [LINK_DoNotSave](#LINK_DoNotSave)
>>
>> [LINK_DrawBoldConnection](#LINK_DrawBoldConnection)
>>
>> [LINK_ForceSave](#LINK_ForceSave)
>>
>> [LINK_Main](#LINK_Main)
>>
>> [LINK_NotColored](#LINK_NotColored)
>>
>> [LINK_Version](#LINK_Version)
>>
>> [LINK_Visible](#LINK_Visible)
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

### ID
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> ID of this Link
>
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___

### Name
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Friendly name of this Link
>
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Properties: <!-- {docsify-ignore} -->

### Owner
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Operator`
>
> *<span class="read_only">Read Only</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### GetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get custom persistent data
>
> ```php
(number|string|boolean|table) Link:GetData([string name])
> ```
>
> *Se also: [SetData()](#SetData)*
___

### GetDefaultLayer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Obtains the default layer name
>
> ```php
string Link:GetDefaultLayer()
> ```
>
___

### GetLayerList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns available layers
>
> ```php
table Link:GetLayerList()
> ```
>
___

### GetTool()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the Tool object that owns this Link
>
> ```php
Tool Link:GetTool()
> ```
>
___

### HasLayer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Checks if a layer is available
>
> ```php
boolean Link:HasLayer(string layername)
> ```
>
___

### SetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set custom persistent data
>
> ```php
 Link:SetData(string name, (number|string|boolean|table) value)
> ```
>
> *Se also: [GetData()](#GetData)*
___


# Discovered Methods: <!-- {docsify-ignore} -->

### IsConnected()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Link:IsConnected()
> ```
>
___


# Tag Map: <!-- {docsify-ignore} -->

>## Create 
>### LINKID_AddAfterID
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINKID_AddBeforeID
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINKID_AllowedDataType
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINKID_ID
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINKID_LegacyID
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINKP_OwnerOp
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINKS_Name
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINK_DoNotSave
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### LINK_DrawBoldConnection
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### LINK_ForceSave
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### LINK_Main
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINK_NotColored
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### LINK_Version
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### LINK_Visible
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
> Link
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Link
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 2025
>
___

