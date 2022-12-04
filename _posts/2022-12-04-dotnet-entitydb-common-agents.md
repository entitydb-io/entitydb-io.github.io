---
title: EntityDb.Common.Agents Namespace
date: 2022-12-04 09:20:52 +00:00
categories: [test]
tags: [test]
---

# EntityDb.Common.Agents Namespace
Missing Summary Doc!
## Classes
<table><tr><td><!--/posts/dotnet-entitydb-common-agents-agentaccessorchain--><a href='#'>AgentAccessorChain</a></td><td>
Represents a type that chains together multiple instances of <!--/posts/dotnet-entitydb-abstractions-agents-iagentaccessor--><a href='#'>IAgentAccessor</a> and returns the
<!--/posts/dotnet-entitydb-abstractions-agents-iagent--><a href='#'>IAgent</a> returned by the first <!--/posts/dotnet-entitydb-abstractions-agents-iagentaccessor--><a href='#'>IAgentAccessor</a> that does not throw an exception.
If all instances of <!--/posts/dotnet-entitydb-abstractions-agents-iagentaccessor--><a href='#'>IAgentAccessor</a> throw an exception, this type will throw a
<!--/posts/dotnet-entitydb-common-exceptions-noagentexception--><a href='#'>NoAgentException</a>.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-agents-agentaccessorchainoptions--><a href='#'>AgentAccessorChainOptions</a></td><td>
Options for configuring the <!--/posts/dotnet-entitydb-common-agents-agentaccessorchain--><a href='#'>AgentAccessorChain</a>.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-agents-unknownagentaccessor--><a href='#'>UnknownAgentAccessor</a></td><td>
Represents a type that indicates there is no known actor.
</td></tr><tr><td><!--/posts/dotnet-entitydb-common-agents-unknownagentsignature--><a href='#'>UnknownAgentSignature</a></td><td>
Represents the signature of an unknown actor.
</td></tr></table>
