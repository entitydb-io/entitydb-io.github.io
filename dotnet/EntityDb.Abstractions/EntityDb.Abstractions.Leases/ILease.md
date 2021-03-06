# ILease interface

Represents a single metadata property and the context in which the metadata property must be unique.

```csharp
public interface ILease
```

## Members

| name | description |
| --- | --- |
| [Label](ILease/Label.md) { get; } | The name of the metadata property. |
| [Scope](ILease/Scope.md) { get; } | The context in which the metadata property must be unique. |
| [Value](ILease/Value.md) { get; } | The value of the metadata property. |

## Remarks

The transaction repository is responsible for enforcing the uniqueness constraint. If a lease needs to be unique in a global context, a constant should be used as the [`Scope`](./ILease/Scope.md) for all instances of the lease. If a lease does not need to be unique in a global context, the entity id (or some other id which is unique to the entity) should be included in the [`Scope`](./ILease/Scope.md) for all instances of the lease. A lease may have additional properties, but they are not directly relevant to the uniqueness constraint.

## See Also

* namespace [EntityDb.Abstractions.Leases](../EntityDb.Abstractions.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
