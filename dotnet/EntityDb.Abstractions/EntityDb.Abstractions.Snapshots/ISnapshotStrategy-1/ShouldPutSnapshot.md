# ISnapshotStrategy&lt;TEntity&gt;.ShouldPutSnapshot method

Determines if the next version of an entity should be put into snapshot storage.

```csharp
public bool ShouldPutSnapshot(TEntity? previousEntity, TEntity nextEntity)
```

| parameter | description |
| --- | --- |
| previousEntity | The previous version of the entity, if it exists. |
| nextEntity | The next version of the entity. |

## Return Value

`true` if the next version of the entity should be put into snapshot storage, or `false` if the next version of the entity should not be put into snapshot storage.

## See Also

* interface [ISnapshotStrategy&lt;TEntity&gt;](../ISnapshotStrategy-1.md)
* namespace [EntityDb.Abstractions.Snapshots](../../EntityDb.Abstractions.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
