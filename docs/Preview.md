# Preview
 : [Object](Object.md) : [LockableObject](LockableObject.md) : [Link](Link.md) : [PlainInput](PlainInput.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [Close](#Close)()
>
> [Create](#Create)()
>
> [DisplayImage](#DisplayImage)()
>
> [IsPlaying](#IsPlaying)()
>
> [Open](#Open)()
>
> [Play](#Play)()
>
> [Seek](#Seek)()
>
> [Stop](#Stop)()
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

# Methods: <!-- {docsify-ignore} -->

### Close()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Closes the current clip
>
> ```php
 Preview:Close()
> ```
>
___

### Create()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Renders a new preview clip
>
> ```php
boolean Preview:Create(Tool tool, [string filename])
> ```
>
___

### DisplayImage()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Displays an Image object
>
> ```php
boolean Preview:DisplayImage(Image img)
> ```
>
___

### IsPlaying()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Indicates if the preview is currently playing
>
> ```php
boolean Preview:IsPlaying()
> ```
>
___

### Open()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Opens a filename for seeking and playback
>
> ```php
boolean Preview:Open(string filename)
> ```
>
___

### Play()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Plays the current clip
>
> ```php
 Preview:Play([boolean reverse])
> ```
>
___

### Seek()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Seeks to specified frame
>
> ```php
 Preview:Seek(number frame)
> ```
>
___

### Stop()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Stops playback
>
> ```php
 Preview:Stop()
> ```
>
___

### ViewOn()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Attaches a Preview to a Tool to display its output
>
> ```php
boolean Preview:ViewOn(Tool tool)
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
> Preview
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Preview
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

