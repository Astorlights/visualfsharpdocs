---
title: Seq.take<'T> Function (F#)
description: Seq.take<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 183bf7d4-bd62-4f96-9965-c6dcb9fba432 
---

# Seq.take<'T> Function (F#)

Returns the elements of the sequence up to a specified count.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Seq

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
Seq.take : int -> seq<'T> -> seq<'T>

// Usage:
Seq.take count source
```

#### Parameters
*count*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)


The number of items to take.


*source*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T&gt;**


The input sequence.



**exceptions tag is not supported!!!!**
**The result sequence.**
## Remarks
[Seq.truncate](http://msdn.microsoft.com/en-us/library/1892dfeb-308e-45e2-857a-3c3405d02244) returns as many items as the sequence contains instead of throwing an exception.

This function is named **Take** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following example demonstrates the use of Seq.take and contrasts the behavior with Seq.truncate.**
[!code-fsharp[Main](snippets/fssequences/snippet16.fs)]
**1 4 9 16 25**
**1 4 9 16 25 36 49 64 81 100**
**1 4 9 16 25**
**1 4 9 16 25 36 49 64 81 100**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Seq Module &#40;F&#35;&#41;](Collections.Seq-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

