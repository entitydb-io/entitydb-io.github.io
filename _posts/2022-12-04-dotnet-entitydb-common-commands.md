---
title: EntityDb.Common.Commands Namespace
date: 2022-12-04 09:20:52 +00:00
categories: [test]
tags: [test]
---

# EntityDb.Common.Commands Namespace
Missing Summary Doc!
## Interfaces
<table><tr><td><!--/posts/dotnet-entitydb-common-commands-iaddleasescommand`1--><a href='#'>IAddLeasesCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to add any instances of <!--/posts/dotnet-entitydb-abstractions-leases-ilease--><a href='#'>ILease</a>, and the properties of the leases
are contained in the command and/or entity, a direct call to
<!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-add--><a href='#'>ITransactionBuilder&lt;TEntity&gt; Add(Id, ILease[])</a>
can be avoided by implementing this interface!
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-commands-iaddtagscommand`1--><a href='#'>IAddTagsCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to add any instances of <!--/posts/dotnet-entitydb-abstractions-tags-itag--><a href='#'>ITag</a>, and the properties of the tags
are contained in the command and/or entity, a direct call to
<!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-add--><a href='#'>ITransactionBuilder&lt;TEntity&gt; Add(Id, ITag[])</a>
can be avoided by implementing this interface!
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-commands-ideleteleasescommand`1--><a href='#'>IDeleteLeasesCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to delete any instances of <!--/posts/dotnet-entitydb-abstractions-leases-ilease--><a href='#'>ILease</a>, and the properties of the leases
are contained in the command and/or entity, a direct call to
<!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-delete--><a href='#'>ITransactionBuilder&lt;TEntity&gt; Delete(Id, ILease[])</a>
can be avoided by implementing this interface!
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-commands-ideletetagscommand`1--><a href='#'>IDeleteTagsCommand&lt;TEntity&gt;</a></td><td>
If a transaction needs to delete any instances of <!--/posts/dotnet-entitydb-abstractions-tags-itag--><a href='#'>ITag</a>, and the properties of the tags
are contained in the command and/or entity, a direct call to
<!--/posts/dotnet-entitydb-abstractions-transactions-builders-itransactionbuilder`1-delete--><a href='#'>ITransactionBuilder&lt;TEntity&gt; Delete(Id, ITag[])</a>
can be avoided by implementing this interface!
</td></tr></table>