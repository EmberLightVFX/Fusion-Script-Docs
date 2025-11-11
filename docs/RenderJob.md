# RenderJob
 : [Object](Object.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ClearCompletedFrames](#ClearCompletedFrames)()
>
> [GetFailedSlaves](#GetFailedSlaves)()
>
> [GetFrames](#GetFrames)()
>
> [GetRenderReport](#GetRenderReport)()
>
> [GetSlaveList](#GetSlaveList)()
>
> [GetUnrenderedFrames](#GetUnrenderedFrames)()
>
> [IsRendering](#IsRendering)()
>
> [RetryRenderNode](#RetryRenderNode)()
>
> [SetFrames](#SetFrames)()
>
> [_Heartbeat](#_Heartbeat)()
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

### ClearCompletedFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Clears the list of completed frames, restarting the render
>
> ```php
 RenderJob:ClearCompletedFrames()
> ```
>
___

### GetFailedSlaves()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Lists all slaves that failed this job
>
> ```php
table RenderJob:GetFailedSlaves()
> ```
>
___

### GetFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the total set of frames to be rendered
>
> ```php
string RenderJob:GetFrames()
> ```
>
> ```
Returns a string of frame numbers in the form '1..10,15,20'
> ```
>
___

### GetRenderReport()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetSlaveList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Gets a table of slaves assigned to this job
>
> ```php
table RenderJob:GetSlaveList()
> ```
>
___

### GetUnrenderedFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the remaining frames to be rendered
>
> ```php
string RenderJob:GetUnrenderedFrames()
> ```
>
> ```
Returns a string of frame numbers in the form '1..10,15,20'
> ```
>
___

### IsRendering()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns true if job is currently rendering
>
> ```php
boolean RenderJob:IsRendering()
> ```
>
___

### RetryRenderNode()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Attempts to reuse slaves that have previously failed
>
> ```php
 RenderJob:RetryRenderNode([RenderNode node])
> ```
>
> ```
Arguments:
    node - the RenderNode object to retry
If 'node' is not specified, all failed RenderNodes are retried
> ```
>
___

### SetFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Specifies the set of frames to render
>
> ```php
 RenderJob:SetFrames(string frames)
> ```
>
> ```
Arguments:
    frames - a list in the form '1..10,15,20'
> ```
>
___

### _Heartbeat()
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
> RenderJob
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> RenderJob
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 2025
>
___

