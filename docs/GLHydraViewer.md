# GLHydraViewer
 : [Object](Object.md) : [GLViewer](GLViewer.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [CenterSelected](#CenterSelected)()
>
> [EnableLighting](#EnableLighting)()
>
> [FitAll](#FitAll)()
>
> [FitSelected](#FitSelected)()
>
> [GetLighting](#GetLighting)()
>
> [GetShading](#GetShading)()
>
> [IsLightingEnabled](#IsLightingEnabled)()
>
> [SetLighting](#SetLighting)()
>
> [SetShading](#SetShading)()
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
> [REGB_Utility_Toggle](#REGB_Utility_Toggle)
>
> [REGI_ClassType](#REGI_ClassType)
>
> [REGI_Priority](#REGI_Priority)
>
> [REGI_Version](#REGI_Version)
>
> [REGS_FileName](#REGS_FileName)
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

### CenterSelected()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Centers this view on the selected object
>
> ```php
 GLHydraViewer:CenterSelected()
> ```
>
___

### EnableLighting()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Enables or disables lighting of objects
>
> ```php
 GLHydraViewer:EnableLighting([boolean enable])
> ```
>
___

### FitAll()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Fits this view to the entire scene
>
> ```php
 GLHydraViewer:FitAll()
> ```
>
___

### FitSelected()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Fits this view to the selected object
>
> ```php
 GLHydraViewer:FitSelected()
> ```
>
___

### GetLighting()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the current type of lighting of objects
>
> ```php
 GLHydraViewer:GetLighting([string type])
> ```
>
> ```
Type should be one of:
	enable
	scene
	cam
	shadows
	smaterials
	skydome
> ```
>
___

### GetShading()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the current object shading method
>
> ```php
 GLHydraViewer:GetShading()
> ```
>
> ```
Returns one of:
	points
	wireframe
	wireframeonsurface
	flatshading
	smoothshading
	geometryonly
	geometryflat
	geometrysmooth
> ```
>
___

### IsLightingEnabled()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns boolean state of lighting mode
>
> ```php
 GLHydraViewer:IsLightingEnabled()
> ```
>
___

### SetLighting()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Controls the type of lighting of objects
>
> ```php
 GLHydraViewer:SetLighting([string type], [boolean enable])
> ```
>
> ```
Type should be one of:
	enable
	scene
	cam
	shadows
	smaterials
	skydome
> ```
>
___

### SetShading()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the object shading method
>
> ```php
 GLHydraViewer:SetShading(string method)
> ```
>
> ```
Method should be one of:
	points
	wireframe
	wireframeonsurface
	flatshading
	smoothshading
	geometryonly
	geometryflat
	geometrysmooth
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

### REGB_Utility_Toggle
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
> 2359296 = CT_GLViewer
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

### REGS_FileName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> C:\Program Files\Blackmagic Design\Fusion 18\Plugins\Blackmagic\USD\USD.plugin
>
___

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> GLHydraViewer
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Hydra
>
___

### REGS_UIName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Hydra
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

