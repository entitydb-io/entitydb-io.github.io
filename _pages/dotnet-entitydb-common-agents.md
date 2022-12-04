---
title: EntityDb.Common.Agents Namespace
date: 2022-12-04 08:44:15 +00:00
categories: []
tags: []
---

# EntityDb.Common.Agents Namespace
Missing Summary Doc!
## Classes
<table><tr><td><a href='dotnet-entitydb-common-agents-agentaccessorchain'>AgentAccessorChain</a></td><td>
Represents a type that chains together multiple instances of <a href='dotnet-entitydb-abstractions-agents-iagentaccessor'>IAgentAccessor</a> and returns the
<a href='dotnet-entitydb-abstractions-agents-iagent'>IAgent</a> returned by the first <a href='dotnet-entitydb-abstractions-agents-iagentaccessor'>IAgentAccessor</a> that does not throw an exception.
If all instances of <a href='dotnet-entitydb-abstractions-agents-iagentaccessor'>IAgentAccessor</a> throw an exception, this type will throw a
<a href='dotnet-entitydb-common-exceptions-noagentexception'>NoAgentException</a>.
</td></tr><tr><td><a href='dotnet-entitydb-common-agents-agentaccessorchainoptions'>AgentAccessorChainOptions</a></td><td>
Options for configuring the <a href='dotnet-entitydb-common-agents-agentaccessorchain'>AgentAccessorChain</a>.
</td></tr><tr><td><a href='dotnet-entitydb-common-agents-unknownagentaccessor'>UnknownAgentAccessor</a></td><td>
Represents a type that indicates there is no known actor.
</td></tr><tr><td><a href='dotnet-entitydb-common-agents-unknownagentsignature'>UnknownAgentSignature</a></td><td>
Represents the signature of an unknown actor.
</td></tr></table>
