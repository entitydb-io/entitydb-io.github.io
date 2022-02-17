# EntityDb.Abstractions assembly

## EntityDb.Abstractions.Agents namespace

| public type | description |
| --- | --- |
| interface [IAgent](./EntityDb.Abstractions.Agents/IAgent.md) | Represents an actor who can interact with transactions. |
| interface [IAgentAccessor](./EntityDb.Abstractions.Agents/IAgentAccessor.md) | Represents a type that can access an instance of [`IAgent`](./EntityDb.Abstractions.Agents/IAgent.md) within a service scope. |

## EntityDb.Abstractions.Annotations namespace

| public type | description |
| --- | --- |
| interface [IEntityAnnotation&lt;TData&gt;](./EntityDb.Abstractions.Annotations/IEntityAnnotation-1.md) | Represents data for a single entity that has already been committed, along with relevant information not contained in the data. |

## EntityDb.Abstractions.Commands namespace

| public type | description |
| --- | --- |
| interface [ICommand&lt;TEntity&gt;](./EntityDb.Abstractions.Commands/ICommand-1.md) | Represents the intent to modify a *TEntity*. |

## EntityDb.Abstractions.Disposables namespace

| public type | description |
| --- | --- |
| interface [IDisposableResource](./EntityDb.Abstractions.Disposables/IDisposableResource.md) | Marks a resource as disposable and provides a default implementation. |

## EntityDb.Abstractions.Entities namespace

| public type | description |
| --- | --- |
| interface [IEntityRepository&lt;TEntity&gt;](./EntityDb.Abstractions.Entities/IEntityRepository-1.md) | Encapsulates the transaction repository and the snapshot repository of an entity. |
| interface [IEntityRepositoryFactory&lt;TEntity&gt;](./EntityDb.Abstractions.Entities/IEntityRepositoryFactory-1.md) | Represents a type used to create instances of [`IEntityRepository`](./EntityDb.Abstractions.Entities/IEntityRepository-1.md) |

## EntityDb.Abstractions.Leases namespace

| public type | description |
| --- | --- |
| interface [ILease](./EntityDb.Abstractions.Leases/ILease.md) | Represents a single metadata property and the context in which the metadata property must be unique. |

## EntityDb.Abstractions.Loggers namespace

| public type | description |
| --- | --- |
| interface [ILogger](./EntityDb.Abstractions.Loggers/ILogger.md) | Represents a type that logs errors (and possibly other things in the future?). |
| interface [ILoggerFactory](./EntityDb.Abstractions.Loggers/ILoggerFactory.md) | Represents a type used to create a [`ILogger`](./EntityDb.Abstractions.Loggers/ILogger.md). |

## EntityDb.Abstractions.Queries namespace

| public type | description |
| --- | --- |
| interface [IAgentSignatureQuery](./EntityDb.Abstractions.Queries/IAgentSignatureQuery.md) | Abstracts a query on agentSignatures. |
| interface [ICommandQuery](./EntityDb.Abstractions.Queries/ICommandQuery.md) | Abstracts a query on commands. |
| interface [ILeaseQuery](./EntityDb.Abstractions.Queries/ILeaseQuery.md) | Abstracts a query on leases. |
| interface [IQuery](./EntityDb.Abstractions.Queries/IQuery.md) | Abstracts a query for an object repository. Possible objects include: agentSignatures, commands, facts, and leases. |
| interface [ITagQuery](./EntityDb.Abstractions.Queries/ITagQuery.md) | Abstracts a query on tags. |

## EntityDb.Abstractions.Queries.FilterBuilders namespace

| public type | description |
| --- | --- |
| interface [IAgentSignatureFilterBuilder&lt;TFilter&gt;](./EntityDb.Abstractions.Queries.FilterBuilders/IAgentSignatureFilterBuilder-1.md) | Builds a *TFilter* for a agentSignature query. |
| interface [ICommandFilterBuilder&lt;TFilter&gt;](./EntityDb.Abstractions.Queries.FilterBuilders/ICommandFilterBuilder-1.md) | Builds a *TFilter* for a command query. |
| interface [IFilterBuilder&lt;TFilter&gt;](./EntityDb.Abstractions.Queries.FilterBuilders/IFilterBuilder-1.md) | Builds a *TFilter* for an object repository. Possible objects include: agentSignatures, commands, facts, and leases. |
| interface [ILeaseFilterBuilder&lt;TFilter&gt;](./EntityDb.Abstractions.Queries.FilterBuilders/ILeaseFilterBuilder-1.md) | Builds a *TFilter* for a lease query. |
| interface [ITagFilterBuilder&lt;TFilter&gt;](./EntityDb.Abstractions.Queries.FilterBuilders/ITagFilterBuilder-1.md) | Builds a *TFilter* for a tag query. |

## EntityDb.Abstractions.Queries.Filters namespace

| public type | description |
| --- | --- |
| interface [IAgentSignatureFilter](./EntityDb.Abstractions.Queries.Filters/IAgentSignatureFilter.md) | Represents a type that supplies filtering for a [`IAgentSignatureQuery`](./EntityDb.Abstractions.Queries/IAgentSignatureQuery.md). |
| interface [ICommandFilter](./EntityDb.Abstractions.Queries.Filters/ICommandFilter.md) | Represents a type that supplies filtering for a [`ICommandQuery`](./EntityDb.Abstractions.Queries/ICommandQuery.md). |
| interface [ILeaseFilter](./EntityDb.Abstractions.Queries.Filters/ILeaseFilter.md) | Represents a type that supplies filtering for a [`ILeaseQuery`](./EntityDb.Abstractions.Queries/ILeaseQuery.md). |
| interface [ITagFilter](./EntityDb.Abstractions.Queries.Filters/ITagFilter.md) | Represents a type that supplies filtering for a [`ITagQuery`](./EntityDb.Abstractions.Queries/ITagQuery.md). |

## EntityDb.Abstractions.Queries.SortBuilders namespace

| public type | description |
| --- | --- |
| interface [IAgentSignatureSortBuilder&lt;TSort&gt;](./EntityDb.Abstractions.Queries.SortBuilders/IAgentSignatureSortBuilder-1.md) | Builds a *TSort* for a agentSignature query. |
| interface [ICommandSortBuilder&lt;TSort&gt;](./EntityDb.Abstractions.Queries.SortBuilders/ICommandSortBuilder-1.md) | Builds a *TSort* for a command query. |
| interface [ILeaseSortBuilder&lt;TSort&gt;](./EntityDb.Abstractions.Queries.SortBuilders/ILeaseSortBuilder-1.md) | Builds a sort for a lease query. |
| interface [ISortBuilder&lt;TSort&gt;](./EntityDb.Abstractions.Queries.SortBuilders/ISortBuilder-1.md) | Builds a sort for an object repository. Possible objects include: agentSignatures, commands, facts, and leases. |
| interface [ITagSortBuilder&lt;TSort&gt;](./EntityDb.Abstractions.Queries.SortBuilders/ITagSortBuilder-1.md) | Builds a sort for a tag query. |

## EntityDb.Abstractions.Snapshots namespace

| public type | description |
| --- | --- |
| interface [ISnapshotRepository&lt;TEntity&gt;](./EntityDb.Abstractions.Snapshots/ISnapshotRepository-1.md) | Represents a collection of *TEntity* snapshots. |
| interface [ISnapshotRepositoryFactory&lt;TEntity&gt;](./EntityDb.Abstractions.Snapshots/ISnapshotRepositoryFactory-1.md) | Represents a type used to create instances of [`ISnapshotRepository`](./EntityDb.Abstractions.Snapshots/ISnapshotRepository-1.md) |
| interface [ISnapshotStrategy&lt;TEntity&gt;](./EntityDb.Abstractions.Snapshots/ISnapshotStrategy-1.md) | Represents a type used to determine if the next version of an entity should be put into snapshot storage. |

## EntityDb.Abstractions.Tags namespace

| public type | description |
| --- | --- |
| interface [ITag](./EntityDb.Abstractions.Tags/ITag.md) | Represents a single metadata property, which can be used to query the current state of an entity. |

## EntityDb.Abstractions.Transactions namespace

| public type | description |
| --- | --- |
| interface [ITransaction&lt;TEntity&gt;](./EntityDb.Abstractions.Transactions/ITransaction-1.md) | Represents a set of objects which must be committed together or not at all. Possible objects include: agentSignatures, commands, leases, and tags. |
| interface [ITransactionMetaData&lt;TMetaData&gt;](./EntityDb.Abstractions.Transactions/ITransactionMetaData-1.md) | Represemts a set of metadata for a single entity. |
| interface [ITransactionRepository&lt;TEntity&gt;](./EntityDb.Abstractions.Transactions/ITransactionRepository-1.md) | Represents an explicit set of objects which represent a complete history of a set of entities. |
| interface [ITransactionRepositoryFactory&lt;TEntity&gt;](./EntityDb.Abstractions.Transactions/ITransactionRepositoryFactory-1.md) | Represents a type used to create instances of [`ITransactionRepository`](./EntityDb.Abstractions.Transactions/ITransactionRepository-1.md). |
| interface [ITransactionStep&lt;TEntity&gt;](./EntityDb.Abstractions.Transactions/ITransactionStep-1.md) | Represents a set of modifiers for a single entity. |
| interface [ITransactionSubscriber&lt;TEntity&gt;](./EntityDb.Abstractions.Transactions/ITransactionSubscriber-1.md) | Represents a type that reacts to transactions that have been committed. |

## EntityDb.Abstractions.TypeResolvers namespace

| public type | description |
| --- | --- |
| interface [ITypeResolver](./EntityDb.Abstractions.TypeResolvers/ITypeResolver.md) | Represents a type that resolves a Type. |

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
