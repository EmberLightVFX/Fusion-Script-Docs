# ChannelStyle
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [BevelType](#BevelType)
>
> [BgColor](#BgColor)
>
> [BlurType](#BlurType)
>
> [Color](#Color)
>
> [ColorGradient](#ColorGradient)
>
> [ColorImage](#ColorImage)
>
> [ColorImageBevel](#ColorImageBevel)
>
> [ColorImageEdges](#ColorImageEdges)
>
> [ColorImageSample](#ColorImageSample)
>
> [ColorMapping](#ColorMapping)
>
> [ColorMappingAngle](#ColorMappingAngle)
>
> [ColorMappingAspect](#ColorMappingAspect)
>
> [ColorMappingSize](#ColorMappingSize)
>
> [ImageTransform](#ImageTransform)
>
> [Level](#Level)
>
> [Opacity](#Opacity)
>
> [SoftnessBlend](#SoftnessBlend)
>
> [SoftnessGlow](#SoftnessGlow)
>
> [SoftnessImage](#SoftnessImage)
>
> [SoftnessX](#SoftnessX)
>
> [SoftnessY](#SoftnessY)
>
> [Type](#Type)
>
> [TypeName](#TypeName)
>
> [TypeNamePtr](#TypeNamePtr)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [GetImageTransformInverse](#GetImageTransformInverse)()
>
> [IsRenderCompatibleWith](#IsRenderCompatibleWith)()
>
> [RequiresNewImage](#RequiresNewImage)()
>
> [ChannelStyle](#ChannelStyle)()
>
___

# Discovered Properties: <!-- {docsify-ignore} -->

### BevelType
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_write">Read/Write</span>*
>
___

### BgColor
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: FltPixel`
>
> *<span class="read_write">Read/Write</span>*
>
___

### BlurType
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_write">Read/Write</span>*
>
___

### Color
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: FltPixel`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorGradient
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Gradient`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorImage
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Image`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorImageBevel
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Image`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorImageEdges
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorImageSample
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorMapping
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: int32`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorMappingAngle
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorMappingAspect
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ColorMappingSize
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### ImageTransform
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Matrix4`
>
> *<span class="read_write">Read/Write</span>*
>
___

### Level
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_write">Read/Write</span>*
>
___

### Opacity
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### SoftnessBlend
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### SoftnessGlow
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### SoftnessImage
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_write">Read/Write</span>*
>
___

### SoftnessX
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### SoftnessY
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### Type
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_write">Read/Write</span>*
>
___

### TypeName
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___

### TypeNamePtr
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### GetImageTransformInverse()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Matrix4 ChannelStyle:GetImageTransformInverse()
> ```
>
___

### IsRenderCompatibleWith()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean ChannelStyle:IsRenderCompatibleWith(ChannelStyle cs)
> ```
>
___

### RequiresNewImage()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean ChannelStyle:RequiresNewImage(int line, int tab, int word, int ch)
> ```
>
___

### ChannelStyle()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ChannelStyle constructor
>
> ```php
ChannelStyle ChannelStyle()
> ```
>
___

