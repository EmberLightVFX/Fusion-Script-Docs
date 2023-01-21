# TextStyleFontMetrics
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [CharWidthAverage](#CharWidthAverage)
>
> [CharWidthSpace](#CharWidthSpace)
>
> [DoStrikeout](#DoStrikeout)
>
> [DoUnderline](#DoUnderline)
>
> [FontSize](#FontSize)
>
> [Scale](#Scale)
>
> [StrikeoutOffset](#StrikeoutOffset)
>
> [StrikeoutThickness](#StrikeoutThickness)
>
> [TextAscent](#TextAscent)
>
> [TextDescent](#TextDescent)
>
> [TextExternalLeading](#TextExternalLeading)
>
> [TextInternalLeading](#TextInternalLeading)
>
> [TypeName](#TypeName)
>
> [TypeNamePtr](#TypeNamePtr)
>
> [UnderlineOffsetH](#UnderlineOffsetH)
>
> [UnderlineThickness](#UnderlineThickness)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [CalcCharacterWidth](#CalcCharacterWidth)()
>
> [CharacterKerning](#CharacterKerning)()
>
> [CharacterWidth](#CharacterWidth)()
>
> [GetError](#GetError)()
>
> [WordWidth](#WordWidth)()
>
> [TextStyleFontMetrics](#TextStyleFontMetrics)()
>
___

# Discovered Properties: <!-- {docsify-ignore} -->

### CharWidthAverage
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### CharWidthSpace
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### DoStrikeout
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_write">Read/Write</span>*
>
___

### DoUnderline
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_write">Read/Write</span>*
>
___

### FontSize
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### Scale
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### StrikeoutOffset
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### StrikeoutThickness
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### TextAscent
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### TextDescent
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### TextExternalLeading
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### TextInternalLeading
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
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

### UnderlineOffsetH
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___

### UnderlineThickness
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_write">Read/Write</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### CalcCharacterWidth()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 TextStyleFontMetrics:CalcCharacterWidth(int32 ch)
> ```
>
___

### CharacterKerning()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 TextStyleFontMetrics:CharacterKerning(char32_t first, char32_t second)
> ```
>
___

### CharacterWidth()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 TextStyleFontMetrics:CharacterWidth(char32_t ch)
> ```
>
___

### GetError()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
uint32 TextStyleFontMetrics:GetError()
> ```
>
___

### WordWidth()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 TextStyleFontMetrics:WordWidth(string str, int direction)
> ```
>
___

### TextStyleFontMetrics()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> TextStyleFontMetrics constructor
>
> ```php
TextStyleFontMetrics TextStyleFontMetrics(TextStyleFont font, int direction)
> ```
>
___

