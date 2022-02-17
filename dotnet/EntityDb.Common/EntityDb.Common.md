# EntityDb.Common assembly

## EntityDb.Common.Entities namespace

| public type | description |
| --- | --- |
| interface [IEntity&lt;TEntity&gt;](./EntityDb.Common.Entities/IEntity-1.md) | Provides basic functionality for the common implementations. |

## EntityDb.Common.Exceptions namespace

| public type | description |
| --- | --- |
| class [CannotResolveTypeException](./EntityDb.Common.Exceptions/CannotResolveTypeException.md) | The exception that is thrown when a ITypeResolver cannot resolve a type. |
| class [CannotWriteInReadOnlyModeException](./EntityDb.Common.Exceptions/CannotWriteInReadOnlyModeException.md) | The exception that is thrown when an actor passes a ITransaction to an ITransactionRepository that was created with [`ReadOnly`](./EntityDb.Common.Transactions/TransactionSessionOptions/ReadOnly.md) equal to `true`. |
| class [EntityAlreadyCreatedException](./EntityDb.Common.Exceptions/EntityAlreadyCreatedException.md) | The exception that is thrown when an actor passes a command to [`Create`](./EntityDb.Common.Transactions/TransactionBuilder-1/Create.md) with an entity id which is known to already be created. |
| class [EntityAlreadyLoadedException](./EntityDb.Common.Exceptions/EntityAlreadyLoadedException.md) | The exception that is thrown when an actor passes an entity id to [`Load`](./EntityDb.Common.Transactions/TransactionBuilder-1/Load.md) with an entity id that has already been loaded. |
| class [EntityNotCreatedException](./EntityDb.Common.Exceptions/EntityNotCreatedException.md) | The exception that is thrown when an actor passes an entity id to [`Load`](./EntityDb.Common.Transactions/TransactionBuilder-1/Load.md) with an entity id that loads with a version number of zero. |
| class [EntityNotLoadedException](./EntityDb.Common.Exceptions/EntityNotLoadedException.md) | The exception that is thrown when an actor passes a command to [`Append`](./EntityDb.Common.Transactions/TransactionBuilder-1/Append.md) with an entity id which has not been loaded. |
| class [NoAgentException](./EntityDb.Common.Exceptions/NoAgentException.md) | The exception that is thrown when the IAgentAccessor cannot return an instance of IAgent. |
| class [OptimisticConcurrencyException](./EntityDb.Common.Exceptions/OptimisticConcurrencyException.md) | The exception that is logged when an actor passes a ITransaction to an ITransactionRepository with a PreviousEntityVersionNumber that is not the actual previous version number. |
| class [VersionZeroReservedException](./EntityDb.Common.Exceptions/VersionZeroReservedException.md) | The exception that is thrown when an actor passes an ITransaction to ITransaction with any NextEntityVersionNumber equal to zero. |

## EntityDb.Common.Extensions namespace

| public type | description |
| --- | --- |
| static class [EntityExtensions](./EntityDb.Common.Extensions/EntityExtensions.md) | Extension methods for entities. |
| static class [IFilterBuilderExtensions](./EntityDb.Common.Extensions/IFilterBuilderExtensions.md) | Extensions for filter builders. |
| static class [IQueryExtensions](./EntityDb.Common.Extensions/IQueryExtensions.md) | Extensions for queries. |
| static class [IServiceCollectionExtensions](./EntityDb.Common.Extensions/IServiceCollectionExtensions.md) | Extensions for service collections. |
| static class [ISortBuilderExtensions](./EntityDb.Common.Extensions/ISortBuilderExtensions.md) | Extensions for sort builders. |

## EntityDb.Common.Leases namespace

| public type | description |
| --- | --- |
| record [Lease](./EntityDb.Common.Leases/Lease.md) |  |

## EntityDb.Common.Queries.Modified namespace

| public type | description |
| --- | --- |
| record [ModifiedQueryOptions](./EntityDb.Common.Queries.Modified/ModifiedQueryOptions.md) | Options for modified queries, which can be created via [`IQueryExtensions`](./EntityDb.Common.Extensions/IQueryExtensions.md). |

## EntityDb.Common.Snapshots namespace

| public type | description |
| --- | --- |
| record [SnapshotSessionOptions](./EntityDb.Common.Snapshots/SnapshotSessionOptions.md) | Represents the agent's use case for the snapshot repository. |

## EntityDb.Common.Tags namespace

| public type | description |
| --- | --- |
| record [Tag](./EntityDb.Common.Tags/Tag.md) |  |

## EntityDb.Common.Transactions namespace

| public type | description |
| --- | --- |
| class [SingleEntityTransactionBuilder&lt;TEntity&gt;](./EntityDb.Common.Transactions/SingleEntityTransactionBuilder-1.md) | A transaction builder for a single entity. |
| class [TransactionBuilder&lt;TEntity&gt;](./EntityDb.Common.Transactions/TransactionBuilder-1.md) | Provides a way to construct an ITransaction. Note that no operations are permanent until you call [`Build`](./EntityDb.Common.Transactions/TransactionBuilder-1/Build.md) and pass the result to a transaction repository. |
| class [TransactionSessionOptions](./EntityDb.Common.Transactions/TransactionSessionOptions.md) | Represents the agent's use case for the transaction repository. |
| abstract class [TransactionSubscriber&lt;TEntity&gt;](./EntityDb.Common.Transactions/TransactionSubscriber-1.md) | Represents an asynchronous subscription to transactions. |

## EntityDb.Common.TypeResolvers namespace

| public type | description |
| --- | --- |
| interface [IPartialTypeResolver](./EntityDb.Common.TypeResolvers/IPartialTypeResolver.md) | Represents a type that resolves a Type or returns null. |

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Common.dll -->
