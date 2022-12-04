---
title: EntityDb.Abstractions.Transactions Namespace
date: 2022-12-04 07:56:01 +00:00
categories: []
tags: []
---

# EntityDb.Abstractions.Transactions Namespace

TODO: Add Namespace Description

## Interfaces
<table><tr><td><a href='dotnet./entitydb.abstractions.transactions.itransaction'>ITransaction</a></td><td>
Represents a set of objects which must be committed together or not at all. Possible objects include:
agentSignatures,
commands, leases, and tags.
</td></tr><tr><td><a href='dotnet./entitydb.abstractions.transactions.itransactionrepository'>ITransactionRepository</a></td><td>
Represents an explicit set of objects which represent a complete history of a set of entities.
</td></tr><tr><td><a href='dotnet./entitydb.abstractions.transactions.itransactionrepositoryfactory'>ITransactionRepositoryFactory</a></td><td>
Represents a type used to create instances of <a href='dotnet./entitydb.abstractions.transactions.itransactionrepository'>ITransactionRepository</a>.
</td></tr><tr><td><a href='dotnet./entitydb.abstractions.transactions.itransactionsubscriber'>ITransactionSubscriber</a></td><td>
Represents a type that reacts to transactions that have been committed.
</td></tr></table>
