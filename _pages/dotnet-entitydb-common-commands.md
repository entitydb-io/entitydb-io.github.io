---
title: EntityDb.Common.Commands Namespace
date: 2022-12-04 08:08:51 +00:00
categories: []
tags: []
---

# EntityDb.Common.Commands Namespace
Missing Summary Doc!
## Interfaces
<table><tr><td><a href='dotnet/entitydb-common-commands-iaddleasescommand`1'>IAddLeasesCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to add any instances of <a href='dotnet/entitydb-abstractions-leases-ilease'>ILease</a>, and the properties of the leases
are contained in the command and/or entity, a direct call to
<a href='dotnet/entitydb-abstractions-transactions-builders-itransactionbuilder`1-add'>ITransactionBuilder&lt;TEntity&gt; Add(Id, ILease[])</a>
can be avoided by implementing this interface!
</td></tr><tr><td><a href='dotnet/entitydb-common-commands-iaddtagscommand`1'>IAddTagsCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to add any instances of <a href='dotnet/entitydb-abstractions-tags-itag'>ITag</a>, and the properties of the tags
are contained in the command and/or entity, a direct call to
<a href='dotnet/entitydb-abstractions-transactions-builders-itransactionbuilder`1-add'>ITransactionBuilder&lt;TEntity&gt; Add(Id, ITag[])</a>
can be avoided by implementing this interface!
</td></tr><tr><td><a href='dotnet/entitydb-common-commands-ideleteleasescommand`1'>IDeleteLeasesCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to delete any instances of <a href='dotnet/entitydb-abstractions-leases-ilease'>ILease</a>, and the properties of the leases
are contained in the command and/or entity, a direct call to
<a href='dotnet/entitydb-abstractions-transactions-builders-itransactionbuilder`1-delete'>ITransactionBuilder&lt;TEntity&gt; Delete(Id, ILease[])</a>
can be avoided by implementing this interface!
</td></tr><tr><td><a href='dotnet/entitydb-common-commands-ideletetagscommand`1'>IDeleteTagsCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to delete any instances of <a href='dotnet/entitydb-abstractions-tags-itag'>ITag</a>, and the properties of the tags
are contained in the command and/or entity, a direct call to
<a href='dotnet/entitydb-abstractions-transactions-builders-itransactionbuilder`1-delete'>ITransactionBuilder&lt;TEntity&gt; Delete(Id, ITag[])</a>
can be avoided by implementing this interface!
</td></tr></table>
