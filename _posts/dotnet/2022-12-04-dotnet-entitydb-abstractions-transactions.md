---
title: EntityDb.Abstractions.Transactions Namespace
date: 2022-12-04 10:11:00 +00:00
categories: [dotnet]
tags: []
---


TODO: Add Namespace Description

## Interfaces
<table><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-itransaction--><a href='#'>ITransaction</a></td><td>
Represents a set of objects which must be committed together or not at all. Possible objects include:
agentSignatures,
commands, leases, and tags.
</td></tr><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-itransactionrepository--><a href='#'>ITransactionRepository</a></td><td>
Represents an explicit set of objects which represent a complete history of a set of entities.
</td></tr><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-itransactionrepositoryfactory--><a href='#'>ITransactionRepositoryFactory</a></td><td>
Represents a type used to create instances of <!--/posts/dotnet-entitydb-abstractions-transactions-itransactionrepository--><a href='#'>ITransactionRepository</a>.
</td></tr><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-itransactionsubscriber--><a href='#'>ITransactionSubscriber</a></td><td>
Represents a type that reacts to transactions that have been committed.
</td></tr></table>
