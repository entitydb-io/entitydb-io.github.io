# IAgentSignatureFilterBuilder&lt;TFilter&gt;.AgentSignatureTypeIn method

Returns a *TFilter* that only includes agentSignatures whose type is contained in a set of agentSignature types.

```csharp
public TFilter AgentSignatureTypeIn(params Type[] agentSignatureTypes)
```

| parameter | description |
| --- | --- |
| agentSignatureTypes | The agentSignature types. |

## Return Value

A *TFilter* that only includes agentSignatures whose type is contained in *agentSignatureTypes*.

## See Also

* interface [IAgentSignatureFilterBuilder&lt;TFilter&gt;](../IAgentSignatureFilterBuilder-1.md)
* namespace [EntityDb.Abstractions.Queries.FilterBuilders](../../EntityDb.Abstractions.md)

<!-- DO NOT EDIT: generated by xmldocmd for EntityDb.Abstractions.dll -->
