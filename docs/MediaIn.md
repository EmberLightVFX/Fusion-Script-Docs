# MediaIn
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetMarkers](#GetMarkers)()
>
> [SetMarker](#SetMarker)()
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
> [REGS_Category](#REGS_Category)
>
> [REGS_FileName](#REGS_FileName)
>
> [REGS_HelpTopic](#REGS_HelpTopic)
>
> [REGS_ID](#REGS_ID)
>
> [REGS_Name](#REGS_Name)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Methods: <!-- {docsify-ignore} -->

### GetMarkers()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns a table of media markers.
>
> ```php
list MediaIn:GetMarkers([time timestamp])
> ```
>
> ```
This returns a list of media markers, each with a table/dict of attributes.
> ```
>
___

### SetMarker()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Creates or changes a media marker.
>
> ```php
 MediaIn:SetMarker(number timestamp, table marker data)
> ```
>
> ```
This will add or overwrite a media marker. Pass a table/dict of attributes, or nil to delete the marker.
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
> true
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
> 1
>
___

### REGS_Category
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> I/O
>
___

### REGS_FileName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> C:\Program Files\Blackmagic Design\Fusion 20\fusionoperators.dll
>
___

### REGS_HelpTopic
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Tools/IO/MediaIn
>
___

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> MediaIn
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Media In
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Nov  3 202515:53:50
>
___

