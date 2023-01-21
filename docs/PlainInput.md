# PlainInput
 : [Object](Object.md) : [LockableObject](LockableObject.md) : [Link](Link.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ConnectTo](#ConnectTo)()
>
> [GetConnectedOutput](#GetConnectedOutput)()
>
> [GetExpression](#GetExpression)()
>
> [GetKeyFrames](#GetKeyFrames)()
>
> [HideViewControls](#HideViewControls)()
>
> [HideWindowControls](#HideWindowControls)()
>
> [SetExpression](#SetExpression)()
>
> [ViewControlsVisible](#ViewControlsVisible)()
>
> [WindowControlsVisible](#WindowControlsVisible)()
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
> [REGB_Unpredictable](#REGB_Unpredictable)
>
> [REGI_Version](#REGI_Version)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Methods: <!-- {docsify-ignore} -->

### ConnectTo()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Connect the Input to an Output
>
> ```php
boolean PlainInput:ConnectTo()
> ```
>
> ```php
boolean PlainInput:ConnectTo(Output out)
> ```
>
___

### GetConnectedOutput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the output that this input is connected to
>
> ```php
Output PlainInput:GetConnectedOutput()
> ```
>
___

### GetExpression()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetKeyFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Return a table of all keyframe times for this input
>
> ```php
table PlainInput:GetKeyFrames()
> ```
>
> *Se also: [GetKeyFrames()](Operator.md#GetKeyFrames)*
___

### HideViewControls()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Hides or shows the view controls for this input
>
> ```php
 PlainInput:HideViewControls(boolean hide)
> ```
>
> ```
Args: Hide - 'true' (default) will hide the controls, 'false' will show them.
      Hides/Shows can be nested.
> ```
>
___

### HideWindowControls()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Hides or shows the window controls for this input
>
> ```php
 PlainInput:HideWindowControls(boolean hide)
> ```
>
> ```
Args: Hide - 'true' (default) will hide the controls, 'false' will show them.
      Hides/Shows can be nested.
> ```
>
___

### SetExpression()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### ViewControlsVisible()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the visible state of the view controls for this input
>
> ```php
boolean PlainInput:ViewControlsVisible()
> ```
>
___

### WindowControlsVisible()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the visible state of the window controls for this input
>
> ```php
boolean PlainInput:WindowControlsVisible()
> ```
>
___


# Registry Attributes: <!-- {docsify-ignore} -->

### REGI_ClassType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0 = CT_Any
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
> PlainInput
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> PlainInput
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
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

