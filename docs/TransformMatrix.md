# TransformMatrix
 : [Object](Object.md) : [Parameter](Parameter.md)
___
### Properties  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [Depth](#Depth)
>
> [Field](#Field)
>
> [Height](#Height)
>
> [OriginalHeight](#OriginalHeight)
>
> [OriginalWidth](#OriginalWidth)
>
> [OriginalXScale](#OriginalXScale)
>
> [OriginalYScale](#OriginalYScale)
>
> [ProxyScale](#ProxyScale)
>
> [Width](#Width)
>
> [XOffset](#XOffset)
>
> [XScale](#XScale)
>
> [YOffset](#YOffset)
>
> [YScale](#YScale)
>
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [OriginalIXScale](#OriginalIXScale)
>
> [OriginalIYScale](#OriginalIYScale)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ApplyTransform](#ApplyTransform)()
>
> [ImageConcatenate](#ImageConcatenate)()
>
> [MergeConcatenate](#MergeConcatenate)()
>
> [TransformMatrix](#TransformMatrix)()
>
### Tag Map
> Map
>
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> [MTX_BgAddSub](#MTX_BgAddSub)
>>
>> [MTX_BgAlphaGain](#MTX_BgAlphaGain)
>>
>> [MTX_BgZOffset](#MTX_BgZOffset)
>>
>> [MTX_Blend](#MTX_Blend)
>>
>> [MTX_ClampCoverage](#MTX_ClampCoverage)
>>
>> [MTX_DoZ](#MTX_DoZ)
>>
>> [MTX_EdgeMode](#MTX_EdgeMode)
>>
>> [MTX_FgAddSub](#MTX_FgAddSub)
>>
>> [MTX_FgAlphaGain](#MTX_FgAlphaGain)
>>
>> [MTX_FgApplyMode](#MTX_FgApplyMode)
>>
>> [MTX_FgApplyOp](#MTX_FgApplyOp)
>>
>> [MTX_FgBlueGain](#MTX_FgBlueGain)
>>
>> [MTX_FgBurnIn](#MTX_FgBurnIn)
>>
>> [MTX_FgGreenGain](#MTX_FgGreenGain)
>>
>> [MTX_FgRedGain](#MTX_FgRedGain)
>>
>> [MTX_FgZOffset](#MTX_FgZOffset)
>>
>> [MTX_FilterMethod](#MTX_FilterMethod)
>>
>> [MTX_FilterWindow](#MTX_FilterWindow)
>>
>> [MTX_Flatten](#MTX_Flatten)
>>
>> [MTX_FlipX](#MTX_FlipX)
>>
>> [MTX_FlipY](#MTX_FlipY)
>>
>> [MTX_Invert](#MTX_Invert)
>>
>> [MTX_MotionBlurBG](#MTX_MotionBlurBG)
>>
>> [MTX_NoAreaSampling](#MTX_NoAreaSampling)
>>
>> [MTX_NoBGFlatten](#MTX_NoBGFlatten)
>>
>> [MTX_NoBlendInput](#MTX_NoBlendInput)
>>
>> [MTX_NoCache](#MTX_NoCache)
>>
>> [MTX_NoDummy](#MTX_NoDummy)
>>
>> [MTX_NoMaskInput](#MTX_NoMaskInput)
>>
>> [MTX_NoMotionBlur](#MTX_NoMotionBlur)
>>
>> [MTX_NoTransform](#MTX_NoTransform)
>>
>> [MTX_PreCalc](#MTX_PreCalc)
>>
>> [MTX_RotOrder](#MTX_RotOrder)
>>
>> [MTX_UseOpenCL](#MTX_UseOpenCL)
>>
>> [MTX_XAngle](#MTX_XAngle)
>>
>> [MTX_XAxis](#MTX_XAxis)
>>
>> [MTX_XOffset](#MTX_XOffset)
>>
>> [MTX_XSize](#MTX_XSize)
>>
>> [MTX_YAngle](#MTX_YAngle)
>>
>> [MTX_YAxis](#MTX_YAxis)
>>
>> [MTX_YOffset](#MTX_YOffset)
>>
>> [MTX_YSize](#MTX_YSize)
>>
>> [MTX_ZAngle](#MTX_ZAngle)
>>
>> [MTX_ZAxis](#MTX_ZAxis)
>>
>> [MTX_ZOffset](#MTX_ZOffset)
>>
>> [MTX_ZSize](#MTX_ZSize)
>>
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
> [REGS_ID](#REGS_ID)
>
> [REGS_Name](#REGS_Name)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Properties: <!-- {docsify-ignore} -->

### Depth
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Image depth indicator (not in bits)
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
> ```
Depth will be one of the following values:

	1 - alpha only  8 bit integer
	2 - alpha only 16 bit integer
	3 - alpha only 16 bit float
	4 - alpha only 32 bit float
	5 - RGBA        8 bit integer
	6 - RGBA       16 bit integer
	7 - RGBA       16 bit float
	8 - RGBA       32 bit float
> ```
>
___

### Field
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Field indicator
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
> ```
Field will be one of the following values:

	-1 - Full Frames, no fields
	 0 - Odd (NTSC) field
	 1 - Even (PAL/HD) field
> ```
>
___

### Height
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Actual image height, in pixels
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### OriginalHeight
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Unproxied image height, in pixels
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### OriginalWidth
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Unproxied image width, in pixels
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### OriginalXScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Unproxied pixel X Aspect
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### OriginalYScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Unproxied pixel Y Aspect
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### ProxyScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Image proxy scale multiplier
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
> ```
ProxyScale may be any positive integer, where 1 indicates no proxy.
> ```
>
___

### Width
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Actual image width, in pixels
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### XOffset
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Image X Offset
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### XScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Pixel X Aspect
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### YOffset
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Image X Offset
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___

### YScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> Pixel Y Aspect
>
> `Type: number`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Properties: <!-- {docsify-ignore} -->

### OriginalIXScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___

### OriginalIYScale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### ApplyTransform()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Image TransformMatrix:ApplyTransform(TagList tags)
> ```
>
___

### ImageConcatenate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TransformMatrix:ImageConcatenate(TagList tags)
> ```
>
___

### MergeConcatenate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 TransformMatrix:MergeConcatenate(Parameter fg, TagList tags)
> ```
>
___

### TransformMatrix()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> TransformMatrix constructor
>
> ```php
TransformMatrix TransformMatrix(Parameter img, Request req, Input inp, int32 slot, TimeStamp time)
> ```
>
___


# Tag Map: <!-- {docsify-ignore} -->

>## Map 
>### MTX_BgAddSub
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_BgAlphaGain
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_BgZOffset
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_Blend
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_ClampCoverage
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_DoZ
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_EdgeMode
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: TransformMatrix.EdgeMode`
>>
>> Possible EdgeMode values
>> - Canvas
>> - Wrap
>> - Duplicate
>>
>### MTX_FgAddSub
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FgAlphaGain
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FgApplyMode
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: TransformMatrix.ApplyMode`
>>
>> Possible ApplyMode values
>> - Merge
>> - Screen
>> - Dissolve
>> - Multiply
>> - Overlay
>> - SoftLight
>> - HardLight
>> - ColorDodge
>> - ColorBurn
>> - Darken
>> - Lighten
>> - Difference
>> - Exclusion
>> - Hue
>> - Saturation
>> - Color
>> - Luminosity
>> - DarkerColor
>> - LighterColor
>> - LinearDodge
>> - LinearBurn
>> - VividLight
>> - LinearLight
>> - PinLight
>> - Hypotenuse
>> - Geometric
>>
>### MTX_FgApplyOp
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: TransformMatrix.ApplyOperator`
>>
>> Possible ApplyOperator values
>> - Over
>> - In
>> - HeldOut
>> - Atop
>> - XOr
>> - Conjoint
>> - Disjoint
>> - Mask
>> - Stencil
>> - Under
>>
>### MTX_FgBlueGain
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FgBurnIn
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FgGreenGain
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FgRedGain
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FgZOffset
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FilterMethod
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: TransformMatrix.FilterType`
>>
>> Possible FilterType values
>> - TopLeft
>> - Nearest
>> - Box
>> - BiLinear
>> - BiCubic
>> - BSpline
>> - CatmulRom
>> - Gaussian
>> - Mitchell
>> - Lanczos
>> - Sinc
>> - Bessel
>>
>### MTX_FilterWindow
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: TransformMatrix.WindowType`
>>
>> Possible WindowType values
>> - Kaiser
>> - Hanning
>> - Hamming
>> - Blackman
>>
>### MTX_Flatten
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_FlipX
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_FlipY
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_Invert
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_MotionBlurBG
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoAreaSampling
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoBGFlatten
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoBlendInput
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoCache
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoDummy
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoMaskInput
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoMotionBlur
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_NoTransform
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_PreCalc
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_RotOrder
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_UseOpenCL
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### MTX_XAngle
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_XAxis
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_XOffset
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_XSize
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_YAngle
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_YAxis
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_YOffset
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_YSize
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_ZAngle
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_ZAxis
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_ZOffset
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### MTX_ZSize
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
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
> 1507328 = CT_Parameter
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
> TransformMatrix
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> TransformMatrix
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

