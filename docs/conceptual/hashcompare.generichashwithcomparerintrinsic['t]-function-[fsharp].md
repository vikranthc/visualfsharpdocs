---
title: HashCompare.GenericHashWithComparerIntrinsic<'T> Function (F#)
description: HashCompare.GenericHashWithComparerIntrinsic<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 78a0dbc8-ec90-4005-96ff-fa4b76db58d2 
---

# HashCompare.GenericHashWithComparerIntrinsic<'T> Function (F#)

A primitive entry point used by the F# compiler for optimization purposes.

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives.HashCompare

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
GenericHashWithComparerIntrinsic : IEqualityComparer -> 'T -> int

// Usage:
GenericHashWithComparerIntrinsic comp input


```





#### Parameters
*comp*
Type: **T:System.Collections.IEqualityComparer**


The comparer object.


*input*
Type: **'T**


The object to generate a hash for.




## Remarks
This function is for use by compiled F# code and should not be used directly.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[LanguagePrimitives.HashCompare Module &#40;F&#35;&#41;](LanguagePrimitives.HashCompare-Module-%5BFSharp%5D.md)

[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives-Module-%5BFSharp%5D.md)

