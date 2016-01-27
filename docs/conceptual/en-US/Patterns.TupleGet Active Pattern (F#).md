# Patterns.TupleGet Active Pattern (F#)

Recognizes expressions that represent getting a tuple field.

**Namespace/Module Path**: Microsoft.FSharp.Quotations.Patterns

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
( |TupleGet|_| ) : (input:Expr) -> (Expr * int) option
```

#### CAPS_PARAMETERS_MD
*input*
Type: [Expr](http://msdn.microsoft.com/en-us/library/ed6a2caf-69d4-45c2-ab97-e9b3be9bce65)


The input expression to match against.



**The formal return value is (Expr &#42; int) option. The option type indicates whether there is a successful match. In a pattern matching expression, the input is decomposed, upon a successful match, into a tuple of two elements. The first is an expression that represents the tuple and the second is an integer that represents the zero-based index.**
## CAPS_REMARKS_MD
This function is named **TupleGetPattern** in the .NET Framework assembly. If you are accessing the member from a .NET Framework language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Quotations.Patterns Module &#40;F&#35;&#41;](Quotations.Patterns+Module+%28F%23%29.md)

[Microsoft.FSharp.Quotations Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Quotations+Namespace+%28F%23%29.md)
