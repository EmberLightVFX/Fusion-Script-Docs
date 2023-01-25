# PolylineMask
 : [Object](Object.md) : [Operator](Operator.md) : [ThreadedOperator](ThreadedOperator.md) : [MaskOperator](MaskOperator.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ConvertToBSpline](#ConvertToBSpline)()
>
> [ConvertToBezier](#ConvertToBezier)()
>
> [GetBezierPolyline](#GetBezierPolyline)()
>
### Registry Attributes
> [REGB_ControlView](#REGB_ControlView)
>
> [REGB_ForceCommonCtrls](#REGB_ForceCommonCtrls)
>
> [REGB_Hide](#REGB_Hide)
>
> [REGB_NoAutoProxy](#REGB_NoAutoProxy)
>
> [REGB_NoBlendCtrls](#REGB_NoBlendCtrls)
>
> [REGB_NoMotionBlurCtrls](#REGB_NoMotionBlurCtrls)
>
> [REGB_NoObjMatCtrls](#REGB_NoObjMatCtrls)
>
> [REGB_OpNoMask](#REGB_OpNoMask)
>
> [REGB_OperatorControl](#REGB_OperatorControl)
>
> [REGB_Source_AspectCtrls](#REGB_Source_AspectCtrls)
>
> [REGB_Source_GlobalCtrls](#REGB_Source_GlobalCtrls)
>
> [REGB_Source_SizeCtrls](#REGB_Source_SizeCtrls)
>
> [REGB_SupportsDoD](#REGB_SupportsDoD)
>
> [REGB_Unpredictable](#REGB_Unpredictable)
>
> [REGI_ClassType](#REGI_ClassType)
>
> [REGI_DataType](#REGI_DataType)
>
> [REGI_OpIcon](#REGI_OpIcon)
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
> [REGS_IconID](#REGS_IconID)
>
> [REGS_Name](#REGS_Name)
>
> [REGS_OpDescription](#REGS_OpDescription)
>
> [REGS_OpIconString](#REGS_OpIconString)
>
> [REGS_UIName](#REGS_UIName)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Methods: <!-- {docsify-ignore} -->

### ConvertToBSpline()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Converts to b-spline polyline
>
> ```php
 PolylineMask:ConvertToBSpline()
> ```
>
___

### ConvertToBezier()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Converts to Bezier polyline
>
> ```php
 PolylineMask:ConvertToBezier()
> ```
>
___

### GetBezierPolyline()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get a table of bezier polyline
>
> ```php
table PolylineMask:GetBezierPolyline(number time, [string which])
> ```
>
> ```
second argument:  Can be 'outter' in case of retrieving outter polyline (case sensitive)
Returns: table of Bezier polyline (converts to Bezier if necessary
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

### REGB_ForceCommonCtrls
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

### REGB_NoAutoProxy
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_NoBlendCtrls
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_NoMotionBlurCtrls
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_NoObjMatCtrls
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_OpNoMask
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_OperatorControl
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Source_AspectCtrls
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Source_GlobalCtrls
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Source_SizeCtrls
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
> 35 = CT_Mask
>
___

### REGI_DataType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> Mask
>
___

### REGI_OpIcon
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
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

### REGS_Category
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Mask
>
___

### REGS_FileName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> C:\Program Files\Blackmagic Design\Fusion 18\fusionoperators.dll
>
___

### REGS_HelpTopic
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Tools/Masks/Polygon
>
___

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> PolylineMask
>
___

### REGS_IconID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Icons.Tools.Icons.PolygonMask
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Polygon
>
___

### REGS_OpDescription
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Draw a Polyline
>
___

### REGS_OpIconString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Ply
>
___

### REGS_UIName
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Polygon
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

