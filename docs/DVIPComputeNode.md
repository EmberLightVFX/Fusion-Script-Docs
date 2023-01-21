# DVIPComputeNode
___
### Discovered Methods  
Discovered methods might be available in many contexts, but most typically in Fuse scripts  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddInput](#AddInput)()
>
> [AddOutput](#AddOutput)()
>
> [AddSampler](#AddSampler)()
>
> [ForceRebuild](#ForceRebuild)()
>
> [GetErrorLog](#GetErrorLog)()
>
> [GetKernelName](#GetKernelName)()
>
> [GetKernelParams](#GetKernelParams)()
>
> [GetParamsHash](#GetParamsHash)()
>
> [RunSession](#RunSession)()
>
> [SetGlobalSize](#SetGlobalSize)()
>
> [SetParamStructCopy](#SetParamStructCopy)()
>
> [SetWorkSize](#SetWorkSize)()
>
> [DVIPComputeNode](#DVIPComputeNode)()
>
___

# Discovered Methods: <!-- {docsify-ignore} -->

### AddInput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:AddInput(string name, Image img)
> ```
>
___

### AddOutput()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:AddOutput(string name, Image img)
> ```
>
___

### AddSampler()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:AddSampler(string name, int filterMode, int addressMode, int normCoordsMode)
> ```
>
___

### ForceRebuild()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:ForceRebuild()
> ```
>
___

### GetErrorLog()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
string DVIPComputeNode:GetErrorLog()
> ```
>
___

### GetKernelName()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
string DVIPComputeNode:GetKernelName()
> ```
>
___

### GetKernelParams()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
string DVIPComputeNode:GetKernelParams()
> ```
>
___

### GetParamsHash()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
uint32 DVIPComputeNode:GetParamsHash(string paramStr)
> ```
>
___

### RunSession()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
boolean DVIPComputeNode:RunSession(Request req)
> ```
>
___

### SetGlobalSize()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:SetGlobalSize(int w, int h, int d)
> ```
>
___

### SetParamStructCopy()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:SetParamStructCopy(void params, size_t size)
> ```
>
___

### SetWorkSize()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> ```php
 DVIPComputeNode:SetWorkSize(int w, int h, int d)
> ```
>
___

### DVIPComputeNode()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> DVIPComputeNode constructor
>
> ```php
DVIPComputeNode DVIPComputeNode(Request req, string kernelName, string source, string kernelParamsName, string kernelParams)
> ```
>
___

