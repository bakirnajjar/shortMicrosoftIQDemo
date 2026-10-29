# T001 — Microsoft IQ bank-demo research and scope note

## Evidence and scope

The platform story is exactly “create a full demo for Microsoft IQ for a bank using python and react”; its approved platform reference is `{source_type:'user_story',source_id:'user_story',locator:'characters 0-8000'}`. No attachments, predecessor outputs, or matching curated knowledge were available. The [assessment](assessment.md) identifies the bank users, workflow, integrations, and meaning of “full” as unresolved. No `plan.md` was present in the run directory. After plan review, the owner chose an **integrated four-capability story**; that choice does not specify a banking workflow or live service connections. This note is research and a candidate scope, **not** the requirements contract or an approved implementation.

Microsoft [describes Microsoft IQ](https://learn.microsoft.com/en-us/microsoft-iq) as an enterprise intelligence layer with four distinct, complementary capabilities:

| Capability | Distinct contribution to a possible bank demonstration |
| --- | --- |
| [Fabric IQ](https://learn.microsoft.com/en-us/fabric/iq/overview) | Business state and meaning: governed data in OneLake, semantic models, and potentially an ontology (preview) express business entities, relationships, and trusted measures. In an illustrative bank view, this could explain a **synthetic** exposure or other aggregate indicator rather than imply access to a bank's real records. |
| [Foundry IQ](https://learn.microsoft.com/en-us/azure/foundry/agents/concepts/what-is-foundry-iq) | Institutional knowledge: a configurable knowledge base retrieves relevant organizational documents with citations and permission-aware responses. An illustrative policy excerpt could explain how to interpret the signal; its existence must not be represented as the bank's actual policy. Feature availability varies between general availability and preview. |
| [Work IQ](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/work-iq) | Work context: permission-aware understanding of people, collaboration, documents, and workflows through Microsoft 365 and supported business data. Illustrative team context could show who has discussed or reviewed the signal, without asserting actual employee data or authorization to access it. |
| [Web IQ](https://learn.microsoft.com/en-us/web-iq/) ([overview](https://learn.microsoft.com/en-us/web-iq/overview)) | External context: fresh web/news evidence that can be attributed to its public source. This is **not** a source of internal policy, customer truth, or an automatic decision. Live use depends on access to the service and its prerequisites. |

## Candidate integrated narrative, not a mandated bank process

A **proposed illustrative briefing** lets a bank reviewer see one synthetic business signal and its definition (Fabric IQ), a cited *example* internal guidance passage (Foundry IQ), an *example* collaboration or handoff context (Work IQ), and a separately attributed public news item (Web IQ). A React presentation could distinguish these four evidence types and their provenance; a Python component could serve or orchestrate example responses. The audience, signal, sequence, and exact Python/React responsibilities are suggestions for discussion, not story-derived requirements. No real risk decision, transaction, customer recommendation, bank-system integration, or automatic action is implied. The [financial-services Fabric guidance](https://learn.microsoft.com/en-us/industry/financial-services/microsoft-fabric-fsi) describes relevant data governance, lineage, analytics, and bank examples, but does **not** establish this particular bank's controls or authorize use of customer data.

## Decisions needed before design or acceptance criteria

- **Blocking:** Which bank actors and observable task should the demo represent? Is an internal briefing appropriate, or does the owner prefer another scenario?
- **Blocking:** What does “full” mean here—navigable end-to-end presentation, locally runnable example, four live capabilities, deployment, or something else? What should viewers be able to verify?
- **Blocking:** Are Fabric, Foundry, Work, and Web IQ expected to be *live integrations*, permissioned tenant demonstrations, or clearly labeled synthetic/illustrative representations? Which tenant, subscriptions, credentials, licenses, costs, and preview dependencies, if any, are available?
- **Blocking for real data or services:** What data classification, consent, identity and access rules, retention, audit, geographic, and regulatory or organizational requirements apply? None is supplied by the story or curated knowledge; do not infer compliance from product marketing.
- Confirm whether synthetic records and invented sample passages are acceptable; separate samples from actual bank data and real retrieved citations. Resolve freshness, failure behavior, and attribution expectations for external information, and keep public web context distinct from protected internal context.

These hyperlinks are **public Microsoft Learn research links**, not platform-approved `knowledge` source references: no knowledge `source_id` or `locator` was returned and none is claimed here. The only platform source reference above belongs to the user story.
