# QueueManager
 : [Object](Object.md) : [LockableObject](LockableObject.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddItem](#AddItem)()
>
> [AddJob](#AddJob)()
>
> [AddRenderNode](#AddRenderNode)()
>
> [AddWatch](#AddWatch)()
>
> [DeleteItem](#DeleteItem)()
>
> [GetGroupList](#GetGroupList)()
>
> [GetID](#GetID)()
>
> [GetItemList](#GetItemList)()
>
> [GetJobFromID](#GetJobFromID)()
>
> [GetJobList](#GetJobList)()
>
> [GetJobs](#GetJobs)()
>
> [GetRenderNodeFromID](#GetRenderNodeFromID)()
>
> [GetRenderNodeList](#GetRenderNodeList)()
>
> [GetRenderNodes](#GetRenderNodes)()
>
> [GetRootData](#GetRootData)()
>
> [GetSchemaList](#GetSchemaList)()
>
> [LoadQueue](#LoadQueue)()
>
> [LoadRenderNodeList](#LoadRenderNodeList)()
>
> [Log](#Log)()
>
> [MoveJob](#MoveJob)()
>
> [NetJoinRender](#NetJoinRender)()
>
> [RemoveJob](#RemoveJob)()
>
> [RemoveRenderNode](#RemoveRenderNode)()
>
> [RemoveWatch](#RemoveWatch)()
>
> [SaveQueue](#SaveQueue)()
>
> [SaveRenderNodeList](#SaveRenderNodeList)()
>
> [ScanForRenderNodes](#ScanForRenderNodes)()
>
> [Start](#Start)()
>
> [Stop](#Stop)()
>
> [UpdateItem](#UpdateItem)()
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

### AddItem()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### AddJob()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a job to the list
>
> ```php
RenderJob QueueManager:AddJob(string filename, [string groups], [string frames], [string endscript])
> ```
>
> ```php
RenderJob QueueManager:AddJob(table args)
> ```
>
> ```
Arguments:
	Filename	Filename of comp or script to be queued
	Groups		RenderNode groups to assign the job to
	FrameRange	Range of frames to render
	EndScript	Script file to execute on completion
	Args		Table of named options, including:
			Filename, Groups, FrameRange, EndScript
			Start, End, QueuedBy, RenderStep, TimeOut
> ```
>
___

### AddRenderNode()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a RenderNode to the node list
>
> ```php
RenderNode QueueManager:AddRenderNode(string name, [string groups], [boolean unused])
> ```
>
> ```
Arguments:
   Name   - the node's hostname or IP address
   Groups - (optional) the render groups to join (default `all`)
   Unused - (optional) node will be added, but not used
> ```
>
___

### AddWatch()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### DeleteItem()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetGroupList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get a list of all node groups
>
> ```php
table QueueManager:GetGroupList()
> ```
>
___

### GetID()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetItemList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetJobFromID()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetJobList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the list of jobs to render
>
> ```php
table QueueManager:GetJobList()
> ```
>
___

### GetJobs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetRenderNodeFromID()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetRenderNodeList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get the list of available RenderNodes
>
> ```php
table QueueManager:GetRenderNodeList()
> ```
>
___

### GetRenderNodes()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetRootData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetSchemaList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### LoadQueue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Loads a list of jobs to do
>
> ```php
boolean QueueManager:LoadQueue(string filename)
> ```
>
___

### LoadRenderNodeList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Loads a list of RenderNodes to use
>
> ```php
boolean QueueManager:LoadRenderNodeList([string filename])
> ```
>
> ```
Arguments:
   filename - The file to load from (defaults to Queues:Slaves.slv)
> ```
>
___

### Log()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Writes a message to the Render Log
>
> ```php
 QueueManager:Log(string message)
> ```
>
___

### MoveJob()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Moves a job up or down the list
>
> ```php
 QueueManager:MoveJob(RenderJob job, number offset)
> ```
>
> ```
Arguments:
    job    - the RenderJob to move
    offset - how far up or down the job list to move it
             (negative offsets move the job up)
> ```
>
___

### NetJoinRender()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### RemoveJob()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Removes a job from the list
>
> ```php
 QueueManager:RemoveJob(RenderJob job)
> ```
>
___

### RemoveRenderNode()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Removes a RenderNode from the node list
>
> ```php
 QueueManager:RemoveRenderNode(RenderNode node)
> ```
>
> ```php
 QueueManager:RemoveRenderNode(string node)
> ```
>
> ```
Arguments:
   node  - the node object, or its hostname or IP address
> ```
>
___

### RemoveWatch()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### SaveQueue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Saves the current list of jobs
>
> ```php
boolean QueueManager:SaveQueue(string filename)
> ```
>
___

### SaveRenderNodeList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Saves the current list of RenderNodes
>
> ```php
boolean QueueManager:SaveRenderNodeList([string filename])
> ```
>
> ```
Arguments:
   filename - The file to save to (defaults to Queues:Slaves.slv)
> ```
>
___

### ScanForRenderNodes()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Scans local network for new RenderNodes
>
> ```php
 QueueManager:ScanForRenderNodes()
> ```
>
___

### Start()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### Stop()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### UpdateItem()
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
> QueueManager
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> QueueManager
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

