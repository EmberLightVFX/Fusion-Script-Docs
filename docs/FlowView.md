# FlowView
 : [Object](Object.md) : [FuView](FuView.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [DeleteBookmark](#DeleteBookmark)()
>
> [FlushSetPosQueue](#FlushSetPosQueue)()
>
> [FrameAll](#FrameAll)()
>
> [GetBookmark](#GetBookmark)()
>
> [GetBookmarkList](#GetBookmarkList)()
>
> [GetPos](#GetPos)()
>
> [GetPosTable](#GetPosTable)()
>
> [GetScale](#GetScale)()
>
> [GoToBookmark](#GoToBookmark)()
>
> [InsertBookmark](#InsertBookmark)()
>
> [ManageBookmarks](#ManageBookmarks)()
>
> [QueueSetPos](#QueueSetPos)()
>
> [Select](#Select)()
>
> [SetBookmarkList](#SetBookmarkList)()
>
> [SetPos](#SetPos)()
>
> [SetScale](#SetScale)()
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

# Methods: <!-- {docsify-ignore} -->

### DeleteBookmark()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Deletes an existing bookmark
>
> ```php
 FlowView:DeleteBookmark(number|string index|name)
> ```
>
___

### FlushSetPosQueue()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Moves all tools queued for positioning with QueueSetPos
>
> ```php
 FlowView:FlushSetPosQueue()
> ```
>
> *Se also: [QueueSetPos()](#QueueSetPos), [SetPos()](#SetPos)*
___

### FrameAll()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
___

### GetBookmark()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Retrives bookmark information
>
> ```php
table FlowView:GetBookmark(number|string name|index)
> ```
>
___

### GetBookmarkList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a list of all bookmarks
>
> ```php
table FlowView:GetBookmarkList()
> ```
>
___

### GetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the position of a tool
>
> ```php
number, number FlowView:GetPos(object Tool)
> ```
>
___

### GetPosTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the position of a tool as a table
>
> ```php
table FlowView:GetPosTable(object tool)
> ```
>
> ```
Returns:
       number x = table[1]
       number y = table[2]
> ```
>
___

### GetScale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the current scale of the contents
>
> ```php
number FlowView:GetScale()
> ```
>
___

### GoToBookmark()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Jumps to a bookmark
>
> ```php
 FlowView:GoToBookmark(number|string|table index|name|bookmark)
> ```
>
___

### InsertBookmark()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a bookmark
>
> ```php
 FlowView:InsertBookmark([number index], [string name], [number x], [number y], [number scale])
> ```
>
___

### ManageBookmarks()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Manage bookmarks
>
> ```php
 FlowView:ManageBookmarks()
> ```
>
___

### QueueSetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Queues the moving of a tool to a new position
>
> ```php
 FlowView:QueueSetPos(object tool, number x, number y)
> ```
>
> *Se also: [FlushSetPosQueue()](#FlushSetPosQueue), [SetPos()](#SetPos)*
___

### Select()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Selects or deselects a tool
>
> ```php
 FlowView:Select(object tool, [boolean select])
> ```
>
___

### SetBookmarkList()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the complete list of bookmarks
>
> ```php
 FlowView:SetBookmarkList(table bookmarks)
> ```
>
___

### SetPos()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Moves a tool to a new position
>
> ```php
 FlowView:SetPos(object tool, number x, number y)
> ```
>
> *Se also: [QueueSetPos()](#QueueSetPos), [FlushSetPosQueue()](#FlushSetPosQueue)*
___

### SetScale()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Change the scale of the contents
>
> ```php
 FlowView:SetScale(number scale)
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
> 10000
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
> FlowView
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Flow
>
___

### REGS_UIName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Flow
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

