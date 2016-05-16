---
title: LanguagePrimitives.GenericHashWithComparer<'T> Function (F#)
description: LanguagePrimitives.GenericHashWithComparer<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: ed8806fd-5fbd-47a6-8e44-22a6a52186c8 
---

# LanguagePrimitives.GenericHashWithComparer<'T> Function (F#)

Recursively hash a part of a value according to its structure.

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
GenericHashWithComparer : IEqualityComparer -> 'T -> int

// Usage:
GenericHashWithComparer comparer obj


```





#### Parameters
*comparer*
Type: **T:System.Collections.IEqualityComparer**


The comparison function.


*obj*
Type: **'T**


The input object.



**The hashed value.**
## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

