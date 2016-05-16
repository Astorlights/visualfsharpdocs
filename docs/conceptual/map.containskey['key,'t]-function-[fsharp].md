---
title: Map.containsKey<'Key,'T> Function (F#)
description: Map.containsKey<'Key,'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 0f977555-1e43-4271-9193-c9783776e467 
---

# Map.containsKey<'Key,'T> Function (F#)

Tests if an element is in the domain of the map.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Map

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
Map.containsKey : 'Key -> Map<'Key,'T> -> bool (requires comparison)

// Usage:
Map.containsKey key table


```





#### Parameters
*key*
Type: **'Key**


The input key.


*table*
Type: [Map](http://msdn.microsoft.com/en-us/library/975316ea-55e3-4987-9994-90897ad45664)**&lt;'Key,'T&gt;**


The input map.



**true if the map contains the key.**
## Remarks
This function is named **ContainsKey** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use Map.containsKey.**
[!code-fsharp[Main](snippets/fsmaps/snippet3.fs)]
**Output**
**The specified map contains the key 1.**
**The specified map does not contain the key 0.**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Map Module &#40;F&#35;&#41;](Collections.Map-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

