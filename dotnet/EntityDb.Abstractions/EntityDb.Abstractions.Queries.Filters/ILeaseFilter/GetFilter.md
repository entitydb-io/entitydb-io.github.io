# ILeaseFilter.GetFilter&lt;TFilter&gt; method

Returns a *TFilter* built from a lease filter builder.

```csharp
public TFilter GetFilter<TFilter>(ILeaseFilterBuilder<TFilter> builder)
```

| parameter | description |
| --- | --- |
| TFilter | The type of filter used by the repository. |
| builder | The lease filter builder. |

## Return Value

A *TFilter* built from *builder*.

## See Also

* interface [ILeaseFilterBuilder&lt;TFilter&gt;](../../EntityDb.Abstractions.Queries.FilterBuilders/ILeaseFilterBuilder-1.md)
* interface [ILeaseFilter](../ILeaseFilter.md)
* namespace [EntityDb.Abstractions.Queries.Filters](../../EntityDb.Abstractions.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
