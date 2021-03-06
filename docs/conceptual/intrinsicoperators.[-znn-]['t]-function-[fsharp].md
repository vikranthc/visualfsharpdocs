---
title: IntrinsicOperators.( ~&& )<'T> Function (F#)
description: IntrinsicOperators.( ~&& )<'T> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: d54d2158-cbdf-4fc3-8ef6-936a2a4e4e86 
---

# IntrinsicOperators.( ~&& )<'T> Function (F#)

Takes the address of the argument as a native pointer. Uses of this value may result in the generation of unverifiable code.

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives.IntrinsicOperators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
( ~&& ) : 'T -> nativeptr<'T> (requires unmanaged)

// Usage:
&& obj


```





#### Parameters
*obj*
Type: **'T**


The input object.



**The unmanaged pointer.**
## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[LanguagePrimitives.IntrinsicOperators Module &#40;F&#35;&#41;](LanguagePrimitives.IntrinsicOperators-Module-%5BFSharp%5D.md)

[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives-Module-%5BFSharp%5D.md)

