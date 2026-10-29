# Phase 1 assessment: requirements analysis

## Business goal and evidence

The requester wants a full bank-oriented demo of "Microsoft IQ" using Python and React. The intended bank users and their tasks are not identified. The sole story source is `user_story` at `characters 0-8000`: "create a full demo for Microsoft IQ for a bank using python and react".

- Supplied attachments: none.
- Approved earlier stage outputs: none.
- Curated knowledge search for Microsoft IQ, banking demo scope and organizational standards: no results; no knowledge reference is available.
- Repository context: `README.md` contains only the project title and creation note; no product specification or application behavior is documented there. This is context, not a cited source for product requirements.

## Supported scope and gaps

The story supports requirements for a bank-oriented demonstration, a Python component and a React component. "Full demo" does not specify observable banking workflows, integration depth, representative actors, sample data, deployment or success criteria; these must not be inferred. No sourced security, compliance, performance, accessibility or availability targets are available. Scope beyond the three stated elements is unresolved rather than implicitly in or out.

Before defining functional behaviors, confirm which product or capability "Microsoft IQ" denotes, which banking scenario and actors the demo must illustrate, and what constitutes a "full" demo (including whether live Microsoft services or simulated data are expected). These are potentially blocking design questions. Clarify data sensitivity and any required organizational or regulatory constraints before specifying data handling or integrations. There are no contradictory sources to reconcile.

## Next phase

Plan an evidence-traceable requirements contract and readable document using stable `REQ-NNN` identifiers and Given/When/Then acceptance criteria. Keep unsupported implementation details as explicit assumptions or open questions, not facts. Do not write product outputs until the plan is approved.
