---
title: EntityDb.Common.Exceptions Namespace
date: 2022-12-04 09:20:52 +00:00
categories: [test]
tags: [test]
---

# EntityDb.Common.Exceptions Namespace
Missing Summary Doc!
## Classes
<table><tr><td><!--/posts/dotnet-entitydb-common-exceptions-cannotresolvetypeexception--><a href='#'>CannotResolveTypeException</a></td><td>
The exception that is thrown when a <!--/posts/dotnet-entitydb-common-typeresolvers-ityperesolver--><a href='#'>ITypeResolver</a> cannot resolve a type.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-cannotwriteinreadonlymodeexception--><a href='#'>CannotWriteInReadOnlyModeException</a></td><td>
The exception that is thrown when an actor passes a <!--/posts/dotnet-entitydb-abstractions-transactions-itransaction--><a href='#'>ITransaction</a> to an
<!--/posts/dotnet-entitydb-abstractions-transactions-itransactionrepository--><a href='#'>ITransactionRepository</a> that was created for read-only mode.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-deserializeexception--><a href='#'>DeserializeException</a></td><td>
The exception that is thrown when an object envelope cannot be deserialized. Possible objects include:
agentSignatures,
commands, facts, and leases.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-entityalreadyknownexception--><a href='#'>EntityAlreadyKnownException</a></td><td>
The exception that is thrown when an actor passes an entity id to
<!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-load--><a href='#'>ITransactionBuilder&lt;TEntity&gt; Load(Id, TEntity)</a>
with an entity id that has already been loaded.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-noagentexception--><a href='#'>NoAgentException</a></td><td>
The exception that is thrown when the <!--/posts/dotnet-entitydb-abstractions-agents-iagentaccessor--><a href='#'>IAgentAccessor</a> cannot return an instance of
<!--/posts/dotnet-entitydb-abstractions-agents-iagent--><a href='#'>IAgent</a>.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-optimisticconcurrencyexception--><a href='#'>OptimisticConcurrencyException</a></td><td>
The exception that is logged when an actor passes a <!--/posts/dotnet-entitydb-abstractions-transactions-itransaction--><a href='#'>ITransaction</a> to an
<!--/posts/dotnet-entitydb-abstractions-transactions-itransactionrepository--><a href='#'>ITransactionRepository</a> with a
<!--/posts/dotnet-entitydb-abstractions-transactions-steps-iappendcommandtransactionstep-previousentityversionnumber--><a href='#'>VersionNumber PreviousEntityVersionNumber</a> that is not the actual
previous version number.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-serializeexception--><a href='#'>SerializeException</a></td><td>
The exception that is thrown when an object envelope cannot be serialized. Possible objects include:
agentSignatures,
commands, leases, and tags.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-snapshotpointerdoesnotexistexception--><a href='#'>SnapshotPointerDoesNotExistException</a></td><td>
The exception that is thrown when an actor requests a snapshot that does not exist.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-exceptions-versionzeroreservedexception--><a href='#'>VersionZeroReservedException</a></td><td>
The exception that is thrown when an actor passes an <!--/posts/dotnet-entitydb-abstractions-transactions-itransaction--><a href='#'>ITransaction</a> to
<!--/posts/dotnet-entitydb-abstractions-transactions-itransactionrepository-puttransaction--><a href='#'>Task&lt;Boolean&gt; PutTransaction(ITransaction, CancellationToken)</a> with on a
<!--/posts/dotnet-entitydb-abstractions-transactions-steps-itransactionstep--><a href='#'>ITransactionStep</a> that implements <!--/posts/dotnet-entitydb-abstractions-transactions-steps-iappendcommandtransactionstep--><a href='#'>IAppendCommandTransactionStep</a>
and the value of <!--/posts/dotnet-entitydb-abstractions-transactions-steps-itransactionstep-entityversionnumber--><a href='#'>VersionNumber EntityVersionNumber</a> is equal to `0`.
</td></tr></table>
