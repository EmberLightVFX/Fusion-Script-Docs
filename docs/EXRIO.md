# EXRIO
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [IsOpen](#IsOpen)
>
> [IsWriting](#IsWriting)
>
> [NumParts](#NumParts)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ChannelImage](#ChannelImage)()
>
> [ChannelIndex](#ChannelIndex)()
>
> [ClearLastError](#ClearLastError)()
>
> [Close](#Close)()
>
> [DataWindow](#DataWindow)()
>
> [DisplayWindow](#DisplayWindow)()
>
> [FindPart](#FindPart)()
>
> [GetLastError](#GetLastError)()
>
> [ReadHeader](#ReadHeader)()
>
> [ReadOpen](#ReadOpen)()
>
> [WriteHeader](#WriteHeader)()
>
> [WriteOpen](#WriteOpen)()
>
> [_PartR](#_PartR)()
>
> [_PartW](#_PartW)()
>
> [_ReadPart](#_ReadPart)()
>
> [_WritePart](#_WritePart)()
>
> [EXRIO](#EXRIO)()
>
___

# Discovered Properties: <!-- {docsify-ignore} -->

### IsOpen
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### IsWriting
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> *<span class="read_only">Read Only</span>*
>
___

### NumParts
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: int`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### ChannelImage()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 EXRIO:ChannelImage(string name, int type, Image img, int ichan, float64 def, float64 cv)
> ```
>
___

### ChannelIndex()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 EXRIO:ChannelIndex(string name, int type, int index, int ichan, float64 def, float64 cv)
> ```
>
___

### ClearLastError()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 EXRIO:ClearLastError()
> ```
>
___

### Close()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean EXRIO:Close()
> ```
>
___

### DataWindow()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ImgRectI EXRIO:DataWindow(int partnum)
> ```
>
___

### DisplayWindow()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ImgRectI EXRIO:DisplayWindow(int partnum)
> ```
>
___

### FindPart()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int EXRIO:FindPart(string name)
> ```
>
___

### GetLastError()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
string EXRIO:GetLastError()
> ```
>
___

### ReadHeader()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean EXRIO:ReadHeader()
> ```
>
___

### ReadOpen()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 EXRIO:ReadOpen(string filename, int frame)
> ```
>
___

### WriteHeader()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean EXRIO:WriteHeader()
> ```
>
___

### WriteOpen()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 EXRIO:WriteOpen(string filename, int frame)
> ```
>
___

### _PartR()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int EXRIO:_PartR(int partnum)
> ```
>
___

### _PartW()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int EXRIO:_PartW(string name, ImgRectI dispw, ImgRectI dataw, float64 aspect)
> ```
>
___

### _ReadPart()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean EXRIO:_ReadPart(int partnum, Image imgs)
> ```
>
___

### _WritePart()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean EXRIO:_WritePart(int partnum, Image imgs)
> ```
>
___

### EXRIO()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> EXRIO constructor
>
> ```php
EXRIO EXRIO()
> ```
>
___

