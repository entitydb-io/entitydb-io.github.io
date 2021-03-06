# IEntityRepository&lt;TEntity&gt;.PutTransaction method

Inserts a single transaction with an atomic commit.

```csharp
public Task<bool> PutTransaction(ITransaction<TEntity> transaction)
```

| parameter | description |
| --- | --- |
| transaction | The transaction. |

## Return Value

`true` if the insert succeeded, or `false` if the insert failed.

## See Also

* interface [ITransaction&lt;TEntity&gt;](../../EntityDb.Abstractions.Transactions/ITransaction-1.md)
* interface [IEntityRepository&lt;TEntity&gt;](../IEntityRepository-1.md)
* namespace [EntityDb.Abstractions.Entities](../../EntityDb.Abstractions.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
