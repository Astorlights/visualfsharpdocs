---
title: Seq.exists<'T> Function (F#)
description: Seq.exists<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 5a562a1c-5d44-4a90-8552-376593fe607f 
---

# Seq.exists<'T> Function (F#)

Tests if any element of the sequence satisfies the given predicate.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Seq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
Seq.exists : ('T -> bool) -> seq<'T> -> bool

// Usage:
Seq.exists predicate source
```

#### Parameters
*predicate*
Type: **'T -&gt;**[bool](https://msdn.microsoft.com/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


A function to test each item of the input sequence.


*source*
Type: [seq](https://msdn.microsoft.com/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T&gt;**


The input sequence.



**exceptions tag is not supported!!!!**
**The predicate is applied to the elements of the input sequence. If any application returns true then the overall result is true and no further elements are tested. Otherwise, returns false.**
## Remarks
This function is named **Exists** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use Seq.exists.**
<b>codeReference tag is not supported!!!!</b>
**Output**
**For sequence seq [0; 1; 2; 3], contains zero is true**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Seq Module &#40;F&#35;&#41;](Collections.Seq-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

