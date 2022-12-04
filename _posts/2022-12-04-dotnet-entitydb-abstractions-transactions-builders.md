---
title: EntityDb.Abstractions.Transactions.Builders Namespace
date: 2022-12-04 09:57:15 +00:00
categories: [dotnet]
tags: []
---


TODO: Add Namespace Description

## Interfaces
<table><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-builders-isingleentitytransactionbuilder`1--><a href='#'>ISingleEntityTransactionBuilder&lt;TEntity&gt;</a></td><td>
A transaction builder for a single entity.
</td></tr><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1--><a href='#'>ITransactionBuilder&lt;TEntity&gt;</a></td><td>
Provides a way to construct an <!--/posts/dotnet-entitydb-abstractions-transactions-itransaction--><a href='#'>ITransaction</a>. Note that no operations are permanent until
you call <!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-build--><a href='#'>ITransaction Build(Id)</a> and pass the result to a transaction repository.
</td></tr><tr><td><!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilderfactory`1--><a href='#'>ITransactionBuilderFactory&lt;TEntity&gt;</a></td><td>
Represents a type used to create instances of <!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1--><a href='#'>ITransactionBuilder&lt;TEntity&gt;</a> or
<!--/posts/dotnet-entitydb-abstractions-transactions-builders-isingleentitytransactionbuilder`1--><a href='#'>ISingleEntityTransactionBuilder&lt;TEntity&gt;</a>.
</td></tr></table>
