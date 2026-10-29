# Requirements analysis — Microsoft IQ bank demo

## Goal and evidence

Build a bank-oriented demonstration using Python and React. The primary bank actors and the task they should perform are **not specified**; both require an owner decision before design. The exact story is: “create a full demo for Microsoft IQ for a bank using python and react”.

The sole platform-issued source reference is `{source_type: "user_story", source_id: "user_story", locator: "characters 0-8000"}`. There are no supplied attachments, approved predecessor outputs, or matching curated knowledge references. The story supports the bank-demo and Python/React request; it does **not** itself enumerate IQ products, prescribe a bank process, or authorize real data. Following research, the owner chose an **integrated four-capability bank story**: Fabric IQ (business data and semantics), Foundry IQ (institutional knowledge and cited documents), Work IQ (work context), and Web IQ (public-web intelligence). The platform reference schema does not support an owner-decision reference, so capability-specific requirements have empty `source_references` arrays rather than invented IDs. The `user_story` references on REQ-001–REQ-003 support the broad demo and technology request; REQ-001's four-capability refinement comes from that owner decision.

The [assessment](../../.github/futuristic/4beaba61-ede1-4349-a56b-f41adc3bd1b0/assessment.md) and [research note](../../.github/futuristic/4beaba61-ede1-4349-a56b-f41adc3bd1b0/research.md) are local task context, not platform source references. Public Microsoft Learn research links, **not** approved `knowledge` references: [Microsoft IQ](https://learn.microsoft.com/en-us/microsoft-iq), [Fabric IQ](https://learn.microsoft.com/en-us/fabric/iq/overview), [Foundry IQ](https://learn.microsoft.com/en-us/azure/foundry/agents/concepts/what-is-foundry-iq), [Work IQ](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/work-iq), and [Web IQ](https://learn.microsoft.com/en-us/web-iq/). These describe capabilities, not an owner-selected bank workflow or authorized service access.

## Scope boundary

In scope is one coherent bank-oriented walkthrough in Python and React showing the **distinct** contributions of all four capabilities, with the status of illustrative versus actually retrieved evidence visible. An example briefing, aggregate signal, policy passage, handoff, or public news item is only a possible design illustration—not a prescribed banking use case. No live integration, real customer/employee record, bank policy, automated decision, deployment, metric, regulatory obligation, or quantitative service target is established. The mode and real-data boundaries below must be decided before implementation; the requirements are conditional on those decisions, not an assertion that access exists.

## Requirements and acceptance criteria

### REQ-001
**Statement:** The demo shall present an end-to-end bank-oriented walkthrough that connects the four IQ contributions to one owner-selected task.

**Acceptance criterion:** Given an owner-selected bank task and an agreed execution mode, when a viewer completes the walkthrough, then the viewer can identify how Fabric IQ, Foundry IQ, Work IQ, and Web IQ each contribute to that same task.

**Rationale and provenance:** The story requests a full bank demo (`user_story`, `characters 0-8000`); the four-capability interpretation is the later owner choice, not wording in the story. A concrete task and actor remain blocking decisions.

### REQ-002
**Statement:** The demo shall use executable Python code to provide scenario content consumed by the bank-oriented walkthrough.

**Acceptance criterion:** Given the agreed runnable demo configuration, when the walkthrough requests scenario content, then executing Python code supplies content that the walkthrough presents.

**Rationale and provenance:** The story expressly requests Python (`user_story`, `characters 0-8000`). This criterion makes its use observable without prescribing a framework, data source, or live Microsoft connection.

### REQ-003
**Statement:** The demo shall use a React interface to let a viewer navigate the bank-oriented walkthrough.

**Acceptance criterion:** Given the agreed runnable demo configuration, when a viewer opens the React interface and follows the walkthrough, then the viewer can reach the four capability contributions without editing application code.

**Rationale and provenance:** The story expressly requests React (`user_story`, `characters 0-8000`). No particular UI layout or actor is asserted.

### REQ-004
**Statement:** The demo shall show a bank-relevant business datum together with its defined business meaning as the Fabric IQ contribution.

**Acceptance criterion:** Given the selected bank scenario, when a viewer inspects the Fabric IQ contribution, then the viewer can see a scenario datum and a corresponding business definition or semantic relationship, with its illustrative or live status identified.

**Rationale and provenance:** Owner-chosen Fabric IQ role, informed by the public research link above; no platform citation exists for the owner decision or the research. The datum is not required to come from a real bank system.

### REQ-005
**Statement:** The demo shall show a relevant institutional-knowledge passage with an identifiable document citation as the Foundry IQ contribution.

**Acceptance criterion:** Given the selected bank scenario, when a viewer inspects the Foundry IQ contribution, then the viewer can see a passage connected to the task and a citation identifying its document, with example material labeled as illustrative rather than actual bank policy.

**Rationale and provenance:** Owner-chosen Foundry IQ role, informed by the public research link above; no platform citation exists for the owner decision or the research. A citation to an illustrative example document is not evidence of an actual bank policy.

### REQ-006
**Statement:** The demo shall show task-related collaboration or handoff context as the Work IQ contribution.

**Acceptance criterion:** Given the selected bank scenario, when a viewer inspects the Work IQ contribution, then the viewer can see a collaboration or handoff item relevant to the same task and can distinguish that work context from business data and institutional guidance.

**Rationale and provenance:** Owner-chosen Work IQ role, informed by the public research link above; no platform citation exists for the owner decision or the research. No employee data access is implied.

### REQ-007
**Statement:** The demo shall show an attributed public-web item relevant to the task as the Web IQ contribution.

**Acceptance criterion:** Given the selected bank scenario, when a viewer inspects the Web IQ contribution, then the viewer can identify the public source of a task-related item and distinguish it from internal business, document, and work context.

**Rationale and provenance:** Owner-chosen Web IQ role, informed by the public research link above; no platform citation exists for the owner decision or the research. Attribution does not imply live retrieval or establish internal truth.

### REQ-008
**Statement:** The demo shall distinguish illustrative scenario evidence from evidence retrieved through an actual service.

**Acceptance criterion:** Given an agreed illustrative, live, or mixed execution mode, when a viewer inspects each displayed contribution, then the viewer can tell whether its content is illustrative or actually retrieved, without an example being presented as a bank record, policy, employee interaction, or live public-web result.

**Rationale and provenance:** This scope safeguard follows the owner-selected integrated presentation and unresolved live-versus-illustrative choice. It has no separate platform source reference.

## Assumptions

- The owner chose an integrated four-capability bank story after the initial assessment: Fabric IQ for business data and semantics, Foundry IQ for cited institutional knowledge, Work IQ for work context, and Web IQ for public-web intelligence. The platform stage reference schema has no owner-decision source type, so this choice is documented without a fabricated source reference.
- A particular bank process, audience, actor, data set, or decision is not yet selected. Any example used during design is illustrative until the owner confirms it.
- The implementation mode is unresolved: synthetic representations, live services, or a combination are not assumed to have been approved. No access to real bank data, tenant resources, or Microsoft service integrations is established.
- There are no supplied attachments, approved predecessor outputs, or matching curated knowledge references. No quantitative, regulatory, security, availability, or performance targets are inferred from the story.

## Open questions

All four questions below are **blocking** within their stated scope:

1. **Which exact bank workflow, primary actors, and observable task should the integrated walkthrough demonstrate?** The story specifies a bank demo but no process or users; the research note's briefing is only an illustration, not a mandated use case.
2. **What counts as a full demo: a navigable end-to-end walkthrough, a locally runnable application, a deployed demonstration, live services, or some agreed combination?** The execution and completion boundary must be settled before implementation and end-to-end acceptance.
3. **For each of Fabric IQ, Foundry IQ, Work IQ, and Web IQ, must the demo use a live integration or a clearly labeled illustrative representation, and what tenant, subscription, credentials, licenses, costs, and preview access are available if live?** The four contributions are in scope by owner choice, but service connection and data provenance are not established.
4. **If real bank data, documents, employee work context, or live tenant services will be used, what authorization, data classification, privacy, access, retention, audit, geography, and organizational or regulatory constraints apply?** This blocks any real-data or live-service design; no such permissions or obligations can be inferred from the story.

No source contradictions were identified. Requirements analysis is not approval of a use case, implementation, integration, or data access.
