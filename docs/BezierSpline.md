# BezierSpline
 : [Object](Object.md) : [Operator](Operator.md) : [Spline](Spline.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AdjustKeyFrames](#AdjustKeyFrames)()
>
> [DeleteKeyFrames](#DeleteKeyFrames)()
>
> [GetKeyFrames](#GetKeyFrames)()
>
> [SetKeyFrames](#SetKeyFrames)()
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
> [REGI_OpIcon](#REGI_OpIcon)
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

### AdjustKeyFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set, Offset or Scale a range of key frames
>
> ```php
 BezierSpline:AdjustKeyFrames(number start, number end, number x, number y, string operation, [number pivotx], [number pivoty])
> ```
>
> ```
start, end: Time range of keypoints to adjust (inclusive)
x, y:       Time and Value offsets/factors
operation:  Can be 'set', 'offset' or 'scale' (case sensitive)
pivotx, pivoty: optional values to scale around. Default is zero
> ```
>
___

### DeleteKeyFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Delete key frames
>
> ```php
 BezierSpline:DeleteKeyFrames(number start, [number end])
> ```
>
___

### GetKeyFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Get a table of keyframes
>
> ```php
table BezierSpline:GetKeyFrames()
> ```
>
___

### SetKeyFrames()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Set a table of keyframes
>
> ```php
 BezierSpline:SetKeyFrames(table keyframes, [boolean replace])
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
> 69 = CT_Spline
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

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> BezierSpline
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> BezierSpline
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

