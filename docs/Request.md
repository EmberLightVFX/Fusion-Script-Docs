# Request
 : [Object](Object.md) : [Message](Message.md)
___
### Discovered Properties  
Discovered properties might be available in many contexts, but most typically in Fuse scripts  
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> [BaseTime](#BaseTime)
>
> [SourceImg](#SourceImg)
>
> [SourceImgValid](#SourceImgValid)
>
> [Time](#Time)
>
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [ClearInputData](#ClearInputData)()
>
> [ClearInputFlags](#ClearInputFlags)()
>
> [ClearReqFlags](#ClearReqFlags)()
>
> [FreeAllInputs](#FreeAllInputs)()
>
> [FreeAllOutputs](#FreeAllOutputs)()
>
> [GetBaseTime](#GetBaseTime)()
>
> [GetDoD](#GetDoD)()
>
> [GetFlags](#GetFlags)()
>
> [GetInputAttrs](#GetInputAttrs)()
>
> [GetInputBaseTime](#GetInputBaseTime)()
>
> [GetInputData](#GetInputData)()
>
> [GetInputDataValid](#GetInputDataValid)()
>
> [GetInputDoD](#GetInputDoD)()
>
> [GetInputFlags](#GetInputFlags)()
>
> [GetInputRoI](#GetInputRoI)()
>
> [GetInputTime](#GetInputTime)()
>
> [GetOp](#GetOp)()
>
> [GetOutputData](#GetOutputData)()
>
> [GetOutputDataValid](#GetOutputDataValid)()
>
> [GetPending](#GetPending)()
>
> [GetPri](#GetPri)()
>
> [GetRoI](#GetRoI)()
>
> [GetTime](#GetTime)()
>
> [IsCompleted](#IsCompleted)()
>
> [IsFailed](#IsFailed)()
>
> [IsInputCurrent](#IsInputCurrent)()
>
> [IsInputSet](#IsInputSet)()
>
> [IsInteractive](#IsInteractive)()
>
> [IsIntermediate](#IsIntermediate)()
>
> [IsNoCache](#IsNoCache)()
>
> [IsNoMotionBlur](#IsNoMotionBlur)()
>
> [IsNoPreviewResize](#IsNoPreviewResize)()
>
> [IsOutputCurrent](#IsOutputCurrent)()
>
> [IsOutputSet](#IsOutputSet)()
>
> [IsPending](#IsPending)()
>
> [IsPlayback](#IsPlayback)()
>
> [IsPreCalc](#IsPreCalc)()
>
> [IsPreview](#IsPreview)()
>
> [IsProcessing](#IsProcessing)()
>
> [IsQuick](#IsQuick)()
>
> [IsQuiet](#IsQuiet)()
>
> [IsRemote](#IsRemote)()
>
> [IsSecondaryTime](#IsSecondaryTime)()
>
> [IsSerialised](#IsSerialised)()
>
> [IsStampOnly](#IsStampOnly)()
>
> [Lock](#Lock)()
>
> [LockInputData](#LockInputData)()
>
> [LockOutputData](#LockOutputData)()
>
> [SetAllOutputsCurrent](#SetAllOutputsCurrent)()
>
> [SetInputAttrs](#SetInputAttrs)()
>
> [SetInputBaseTime](#SetInputBaseTime)()
>
> [SetInputCurrent](#SetInputCurrent)()
>
> [SetInputData](#SetInputData)()
>
> [SetInputFlags](#SetInputFlags)()
>
> [SetInputTime](#SetInputTime)()
>
> [SetOp](#SetOp)()
>
> [SetOutputCurrent](#SetOutputCurrent)()
>
> [SetOutputData](#SetOutputData)()
>
> [SetPri](#SetPri)()
>
> [SetReqAttrs](#SetReqAttrs)()
>
> [SetReqFlags](#SetReqFlags)()
>
> [Unlock](#Unlock)()
>
> [UnlockInputData](#UnlockInputData)()
>
> [UnlockOutputData](#UnlockOutputData)()
>
### Tag Map
> InputAttrs
>
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> [OPRAO_ImageDoD](#OPRAO_ImageDoD)
>>
>> [OPRAO_ImageRoI](#OPRAO_ImageRoI)
>>
>> [OPRAO_NormalisedRoI](#OPRAO_NormalisedRoI)
>>
>> [OPRAO_RootImage](#OPRAO_RootImage)
>>
>> [OPRA_SkipProcess](#OPRA_SkipProcess)
>>
> ReqAttrs
>
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> [RQA_BaseTime](#RQA_BaseTime)
>>
>> [RQA_DestImg](#RQA_DestImg)
>>
>> [RQA_DestImgTags](#RQA_DestImgTags)
>>
>> [RQA_MultiLayer](#RQA_MultiLayer)
>>
>> [RQA_Request](#RQA_Request)
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

# Discovered Properties: <!-- {docsify-ignore} -->

### BaseTime
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___

### SourceImg
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: Parameter`
>
> *<span class="read_only">Read Only</span>*
>
___

### SourceImgValid
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: TimeExtent`
>
> *<span class="read_only">Read Only</span>*
>
___

### Time
> [!NOTE|labelVisibility:hidden|iconVisibility:hidden]
> `Type: float64`
>
> *<span class="read_only">Read Only</span>*
>
___


# Discovered Methods: <!-- {docsify-ignore} -->

### ClearInputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:ClearInputData(Input inp, int32 slot)
> ```
>
___

### ClearInputFlags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:ClearInputFlags(Input inp, uint32 flags, int32 slot)
> ```
>
___

### ClearReqFlags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:ClearReqFlags(uint32 flags)
> ```
>
___

### FreeAllInputs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:FreeAllInputs()
> ```
>
___

### FreeAllOutputs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:FreeAllOutputs()
> ```
>
___

### GetBaseTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 Request:GetBaseTime()
> ```
>
___

### GetDoD()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ImageDomain Request:GetDoD()
> ```
>
___

### GetFlags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
uint32 Request:GetFlags()
> ```
>
___

### GetInputAttrs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TagList Request:GetInputAttrs(Input inp, int32 slot)
> ```
>
___

### GetInputBaseTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeStamp Request:GetInputBaseTime(Input inp, int32 slot)
> ```
>
___

### GetInputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Parameter Request:GetInputData(Input inp, int32 slot)
> ```
>
___

### GetInputDataValid()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeExtent Request:GetInputDataValid(Input inp, int32 slot)
> ```
>
___

### GetInputDoD()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ImageDomain Request:GetInputDoD(Input inp, int32 slot)
> ```
>
___

### GetInputFlags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
uint32 Request:GetInputFlags(Input inp, int32 slot)
> ```
>
___

### GetInputRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ImageDomain Request:GetInputRoI(Input inp, int32 slot)
> ```
>
___

### GetInputTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeStamp Request:GetInputTime(Input inp, int32 slot)
> ```
>
___

### GetOp()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Operator Request:GetOp()
> ```
>
___

### GetOutputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
Parameter Request:GetOutputData(Output out)
> ```
>
___

### GetOutputDataValid()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
TimeExtent Request:GetOutputDataValid(Output out)
> ```
>
___

### GetPending()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int32 Request:GetPending()
> ```
>
___

### GetPri()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
int32 Request:GetPri()
> ```
>
___

### GetRoI()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
ImageDomain Request:GetRoI()
> ```
>
___

### GetTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
float64 Request:GetTime()
> ```
>
___

### IsCompleted()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsCompleted()
> ```
>
___

### IsFailed()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsFailed()
> ```
>
___

### IsInputCurrent()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsInputCurrent(Input inp, int32 slot)
> ```
>
___

### IsInputSet()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsInputSet(Input inp, int32 slot)
> ```
>
___

### IsInteractive()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsInteractive()
> ```
>
___

### IsIntermediate()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsIntermediate()
> ```
>
___

### IsNoCache()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsNoCache()
> ```
>
___

### IsNoMotionBlur()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsNoMotionBlur()
> ```
>
___

### IsNoPreviewResize()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsNoPreviewResize()
> ```
>
___

### IsOutputCurrent()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsOutputCurrent(Output out)
> ```
>
___

### IsOutputSet()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsOutputSet(Output out)
> ```
>
___

### IsPending()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsPending()
> ```
>
___

### IsPlayback()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsPlayback()
> ```
>
___

### IsPreCalc()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsPreCalc()
> ```
>
___

### IsPreview()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsPreview()
> ```
>
___

### IsProcessing()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsProcessing()
> ```
>
___

### IsQuick()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsQuick()
> ```
>
___

### IsQuiet()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsQuiet()
> ```
>
___

### IsRemote()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsRemote()
> ```
>
___

### IsSecondaryTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsSecondaryTime()
> ```
>
___

### IsSerialised()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsSerialised()
> ```
>
___

### IsStampOnly()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:IsStampOnly()
> ```
>
___

### Lock()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:Lock()
> ```
>
___

### LockInputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:LockInputData(Input inp, int32 slot)
> ```
>
___

### LockOutputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:LockOutputData(Output out)
> ```
>
___

### SetAllOutputsCurrent()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetAllOutputsCurrent(boolean current)
> ```
>
___

### SetInputAttrs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetInputAttrs(Input inp, TagList tags, int32 slot)
> ```
>
___

### SetInputBaseTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetInputBaseTime(Input inp, TimeStamp t, int32 slot)
> ```
>
___

### SetInputCurrent()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetInputCurrent(Input inp, boolean current, int32 slot)
> ```
>
___

### SetInputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetInputData(Input inp, Parameter param, TimeExtent te, int32 slot, uint32 flags)
> ```
>
___

### SetInputFlags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetInputFlags(Input inp, uint32 flags, int32 slot)
> ```
>
___

### SetInputTime()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetInputTime(Input inp, TimeStamp t, int32 slot)
> ```
>
___

### SetOp()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetOp(Operator op)
> ```
>
___

### SetOutputCurrent()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetOutputCurrent(Output out, boolean current)
> ```
>
___

### SetOutputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean Request:SetOutputData(Output out, Parameter param, TimeExtent te)
> ```
>
___

### SetPri()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:SetPri(int32 pri, int32 pending)
> ```
>
___

### SetReqAttrs()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:SetReqAttrs(TagList tags)
> ```
>
___

### SetReqFlags()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:SetReqFlags(uint32 flags)
> ```
>
___

### Unlock()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:Unlock()
> ```
>
___

### UnlockInputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:UnlockInputData(Input inp, int32 slot)
> ```
>
___

### UnlockOutputData()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 Request:UnlockOutputData(Output out)
> ```
>
___


# Tag Map: <!-- {docsify-ignore} -->

>## InputAttrs 
>### OPRAO_ImageDoD
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### OPRAO_ImageRoI
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### OPRAO_NormalisedRoI
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### OPRAO_RootImage
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### OPRA_SkipProcess
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
___

>## ReqAttrs 
>### RQA_BaseTime
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### RQA_DestImg
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### RQA_DestImgTags
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>### RQA_MultiLayer
>> [!ATTENTION|labelVisibility:hidden|iconVisibility:hidden]
>> `Type: boolean`
>>
>### RQA_Request
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
> Request
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Request
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jan 25 2023
>
___

