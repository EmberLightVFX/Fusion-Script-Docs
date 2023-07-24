# Object
The root class of all objects in FusionScript
The root class of all objects in FusionScript

___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Comp](#Comp)
>
> [RegNode](#RegNode)
>
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Comp](#Comp)()
>
> [Composition](#Composition)()
>
> [DoAction](#DoAction)()
>
> [GetData](#GetData)()
>
> [GetID](#GetID)()
>
> [GetReg](#GetReg)()
>
> [QueueAction](#QueueAction)()
>
> [SetData](#SetData)()
>
> [TriggerEvent](#TriggerEvent)()
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetComp](#GetComp)()
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

# Discovered Properties: <!-- {docsify-ignore} -->

### Comp
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: FusionDoc`
>
> *<span class="read_only">Read Only</span>*
>
___

### RegNode
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Registry`
>
> *<span class="read_only">Read Only</span>*
>
___


# Methods: <!-- {docsify-ignore} -->

### Comp()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Composition()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### DoAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get custom persistent data
>
> ```php
(number|string|boolean|table) Object:GetData([string name])
> ```
>
> *Se also: [SetData()](#SetData)*
___

### GetID()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetReg()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### QueueAction()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### SetData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set custom persistent data
>
> ```php
 Object:SetData(string name, (number|string|boolean|table) value)
> ```
>
> *Se also: [GetData()](#GetData)*
___

### TriggerEvent()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___


# Discovered Methods: <!-- {docsify-ignore} -->

### GetComp()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
FusionDoc Object:GetComp()
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
> Object
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Object
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

