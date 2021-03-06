---
title: Set.isProperSuperset<'T> Function (F#)
description: Set.isProperSuperset<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 6c11f07a-38ad-4864-a000-644a6d4dedea 
---

# Set.isProperSuperset<'T> Function (F#)

Evaluates to **true** if all elements of the second set are in the first, and at least one element of the first is not in the second.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Set

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
Set.isProperSuperset : Set<'T> -> Set<'T> -> bool (requires comparison)

// Usage:
Set.isProperSuperset set1 set2


```





#### Parameters
*set1*
Type: [Set](http://msdn.microsoft.com/en-us/library/50cebdce-0cd7-4c5c-8ebc-f3a9e90b38d8)**&lt;'T&gt;**


The potential superset.


*set2*
Type: [Set](http://msdn.microsoft.com/en-us/library/50cebdce-0cd7-4c5c-8ebc-f3a9e90b38d8)**&lt;'T&gt;**


The set to test against.



**True if set1 is a proper superset of set2.**
## Remarks
This function is named **IsProperSuperset** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code illustrates the use of the Set.isProperSuperset function.**
[!code-fsharp[Main](snippets/fssets/snippet9.fs)]
**Output**
**set [1; 2; 3; 4; 5; 6; 7; 8; 9] is a proper superset of set [1; 2; 3; 4; 5; 6]: true**
**set [1; 2; 3; 4; 5; 6] is a proper superset of set [1; 2; 3; 4; 5; 6]: false**
**set [5; 6; 7; 8; 9; 10] is a proper superset of set [1; 2; 3; 4; 5; 6]: false**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Set Module &#40;F&#35;&#41;](Collections.Set-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

