# ICommandSortBuilder&lt;TSort&gt;.CommandProperty&lt;TCommand&gt; method

Returns a *TSort* that orders commands by a command expression.

```csharp
public TSort CommandProperty<TCommand>(bool ascending, 
    Expression<Func<TCommand, object>> commandExpression)
```

| parameter | description |
| --- | --- |
| TCommand | The type of command in the command expression. |
| ascending | Pass `true` for ascending order or `false` for descending order. |
| commandExpression | The command expression. |

## Return Value

A *TSort* that orders commands by *commandExpression*.

## See Also

* interface [ICommandSortBuilder&lt;TSort&gt;](../ICommandSortBuilder-1.md)
* namespace [EntityDb.Abstractions.Queries.SortBuilders](../../EntityDb.Abstractions.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
