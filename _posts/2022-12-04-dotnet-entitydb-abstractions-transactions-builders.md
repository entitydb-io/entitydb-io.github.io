---
title: EntityDb.Abstractions.Transactions.Builders Namespace
date: 2022-12-04 09:11:33 +00:00
categories: [test]
tags: [test]
---

# EntityDb.Abstractions.Transactions.Builders Namespace

TODO: Add Namespace Description

## Interfaces
<table><tr><td><a href='dotnet-entitydb-abstractions-transactions-builders-isingleentitytransactionbuilder`1'>ISingleEntityTransactionBuilder&lt;TEntity&gt;</a></td><td>
A transaction builder for a single entity.
</td></tr><tr><td><a href='dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1'>ITransactionBuilder&lt;TEntity&gt;</a></td><td>
Provides a way to construct an <a href='dotnet-entitydb-abstractions-transactions-itransaction'>ITransaction</a>. Note that no operations are permanent until
you call <a href='dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-build'>ITransaction Build(Id)</a> and pass the result to a transaction repository.
</td></tr><tr><td><a href='dotnet-entitydb-abstractions-transactions-builders-itransactionbuilderfactory`1'>ITransactionBuilderFactory&lt;TEntity&gt;</a></td><td>
Represents a type used to create instances of <a href='dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1'>ITransactionBuilder&lt;TEntity&gt;</a> or
<a href='dotnet-entitydb-abstractions-transactions-builders-isingleentitytransactionbuilder`1'>ISingleEntityTransactionBuilder&lt;TEntity&gt;</a>.
</td></tr></table>
