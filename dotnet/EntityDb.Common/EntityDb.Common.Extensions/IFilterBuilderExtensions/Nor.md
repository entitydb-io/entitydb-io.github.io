# IFilterBuilderExtensions.Nor&lt;TFilter&gt; method

Returns a *TFilter* that excludes objects which do match any filter in a set of filters.

```csharp
public static TFilter Nor<TFilter>(this IFilterBuilder<TFilter> filterBuilder, 
    params TFilter[] filters)
```

| parameter | description |
| --- | --- |
| TFilter | The type of filter used by the repository. |
| filterBuilder | The filter builder. |
| filters | The set of filters. |

## Return Value

A *TFilter* that excludes objects which do match any filter in *filters*.

## See Also

* class [IFilterBuilderExtensions](../IFilterBuilderExtensions.md)
* namespace [EntityDb.Common.Extensions](../../EntityDb.Common.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Common.dll -->
