---
title: EntityDb.Common.Exceptions Namespace
date: 2022-12-04 08:08:51 +00:00
categories: []
tags: []
---

# EntityDb.Common.Exceptions Namespace
Missing Summary Doc!
## Classes
<table><tr><td><a href='dotnet/entitydb-common-exceptions-cannotresolvetypeexception'>CannotResolveTypeException</a></td><td>
The exception that is thrown when a <a href='dotnet/entitydb-common-typeresolvers-ityperesolver'>ITypeResolver</a> cannot resolve a type.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-cannotwriteinreadonlymodeexception'>CannotWriteInReadOnlyModeException</a></td><td>
The exception that is thrown when an actor passes a <a href='dotnet/entitydb-abstractions-transactions-itransaction'>ITransaction</a> to an
<a href='dotnet/entitydb-abstractions-transactions-itransactionrepository'>ITransactionRepository</a> that was created for read-only mode.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-deserializeexception'>DeserializeException</a></td><td>
The exception that is thrown when an object envelope cannot be deserialized. Possible objects include:
agentSignatures,
commands, facts, and leases.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-entityalreadyknownexception'>EntityAlreadyKnownException</a></td><td>
The exception that is thrown when an actor passes an entity id to
<a href='dotnet/entitydb-abstractions-transactions-builders-itransactionbuilder`1-load'>ITransactionBuilder&lt;TEntity&gt; Load(Id, TEntity)</a>
with an entity id that has already been loaded.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-noagentexception'>NoAgentException</a></td><td>
The exception that is thrown when the <a href='dotnet/entitydb-abstractions-agents-iagentaccessor'>IAgentAccessor</a> cannot return an instance of
<a href='dotnet/entitydb-abstractions-agents-iagent'>IAgent</a>.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-optimisticconcurrencyexception'>OptimisticConcurrencyException</a></td><td>
The exception that is logged when an actor passes a <a href='dotnet/entitydb-abstractions-transactions-itransaction'>ITransaction</a> to an
<a href='dotnet/entitydb-abstractions-transactions-itransactionrepository'>ITransactionRepository</a> with a
<a href='dotnet/entitydb-abstractions-transactions-steps-iappendcommandtransactionstep-previousentityversionnumber'>VersionNumber PreviousEntityVersionNumber</a> that is not the actual
previous version number.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-serializeexception'>SerializeException</a></td><td>
The exception that is thrown when an object envelope cannot be serialized. Possible objects include:
agentSignatures,
commands, leases, and tags.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-snapshotpointerdoesnotexistexception'>SnapshotPointerDoesNotExistException</a></td><td>
The exception that is thrown when an actor requests a snapshot that does not exist.
</td></tr><tr><td><a href='dotnet/entitydb-common-exceptions-versionzeroreservedexception'>VersionZeroReservedException</a></td><td>
The exception that is thrown when an actor passes an <a href='dotnet/entitydb-abstractions-transactions-itransaction'>ITransaction</a> to
<a href='dotnet/entitydb-abstractions-transactions-itransactionrepository-puttransaction'>Task&lt;Boolean&gt; PutTransaction(ITransaction, CancellationToken)</a> with on a
<a href='dotnet/entitydb-abstractions-transactions-steps-itransactionstep'>ITransactionStep</a> that implements <a href='dotnet/entitydb-abstractions-transactions-steps-iappendcommandtransactionstep'>IAppendCommandTransactionStep</a>
and the value of <a href='dotnet/entitydb-abstractions-transactions-steps-itransactionstep-entityversionnumber'>VersionNumber EntityVersionNumber</a> is equal to `0`.
</td></tr></table>
