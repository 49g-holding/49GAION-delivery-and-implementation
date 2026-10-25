# Delivery and Implementation · `[ORG]AIOC-DI`

The mother repository of the Library part **49GAION Delivery and Implementation**. In an `[ORG]AION`, the part is the AIOC `[ORG]AIOC-DI`, the last stage of the design chain. Public. It holds the mother blueprint, for any organisation, with no organisation's data (`49GAION/DR-0024`; Naming Standard R9, addition 4). It was written in the repository of the part's first instance and moved here unchanged at its pinned commit (`decisions/DR-0006`).

> **Reading (49GAION DR-0041, DR-0042).** The complete definition of 49GAION, approved by its governing seat on 25 October 2026, is `49GAION-FRAMEWORK.md` in `github.com/49g-holding/49GAION`, with the clarifications of the same day. Where this repository differs from it, the definition governs, and this text is read with it. This part designs an organisation of human positions; how human and how much AI the organisation is, is the `[ORG]AION`'s own design work, prepared by it and decided by the governance seat. Every rule here that names `[ORG]AIOC-OCO` or the human hub reads as the Top Management Group, the hub of the operation, human and AI. The panel is the organisation's own code interface, and the AI chat workspace is its back office. The readings are in [`decisions/DR-0006`](decisions/DR-0006-the-mother-repository-and-the-readings.md). Nothing here is removed.

> **Delivery and Implementation in one page**
>
> Delivery and Implementation (DI) takes an organisation's decided design into a running organisation, and stays to run and improve it with the organisation. It is the last stage of the design chain, after Process and Position Design.
>
> **What goes in:** the decided Process and Position Design release with the operating model it was designed from (mode A); a design made elsewhere, filed in Source Lifecycle (mode B); or no design, for a small business, built with its owner (mode C, switched on after the first two slices give evidence).
>
> **What comes out.** *Launch:* the gap report in two tiers; the health check; the procedures under each process; briefs and drafts for counsel and finance; the transition plan and the go-live criteria; the launch package, decided element by element and filed in Source Lifecycle. *Accompany:* the implementation plan by position, change impact, learning paths, readiness, rehearsals and the go or no-go package. *Operate:* the operating rhythm and its single logs, forum packs, measures, versions and acknowledgements, runnable checklists, quarterly priorities and the value register. *Improve:* process watching through a projection that removes who did the work, conformance, proposals, trials judged by another seat, reassessment, the quarterly health check, and the hand-over of its skills, proven by a yearly drill without it. *Always:* answers grounded in the decided design with verified citations, or "I do not know".
>
> **It decides nothing.** It reads and proposes; a draft enters a record only when a position inserts it; it applies a change itself only within a reversible class the owner position signed in advance; the go or no-go is the deciding position's; any accountable position can stop it at once. It works at the level of processes and units, never persons.

The writing repository of **`[ORG]AIOC-DI`, Delivery and Implementation**: the mother text of the 49GAION Library part of the same name (49GAION Standard §3.1, item 5, and its Protocol section §20). In each organisation this repository is named `<org>aioc-di` (Naming Standard R9). It is written for any organisation and holds no organisation data.

**Status: draft `v0.2.1`, 19 October 2026: the Chief of Staff takes its COS code `[ORG]CELL-COSDI` (`decisions/DR-0005`); it builds on `v0.2.0`, complete, slices 1 to 4, 18 October 2026 (`decisions/DR-0004`). Nothing here has run; every fixed test reads `NOT_RUN`.**

## Where to read

| File | What it is |
|---|---|
| [`blueprint/DI-BLUEPRINT.md`](blueprint/DI-BLUEPRINT.md) | the blueprint, on the 49GAION AIOC Blueprint Template `v1.6.0` at `acdcbe5`: identity, card, placement, positions, the stages of the launch and the service with their inputs, outputs and done-tests (§5.0), every capability, the human decisions (§13), Cells and Pods (§17), the parts and their field lists (Annex A), the gap checks (Annex F), the permission ladder (Annex G), records of work (Annex H) |
| [`tests/TEST-DI.md`](tests/TEST-DI.md) | the fixed test, written before use: 94 cases and the Delivery Lead's seat test |
| [`cards/`](cards/) | the unit cards of its seven Pods and twenty-seven Cells, and the bot identity cards of its twenty-six AI Cells, generated from the blueprint |
| [`docs/HISTORY.md`](docs/HISTORY.md) | why this stage exists |
| [`upstream/PROPOSALS.md`](upstream/PROPOSALS.md) | the changes this AIOC needs from Process and Position Design, the target operating model and Source Lifecycle |
| [`decisions/`](decisions/) | the decision records of this repository |

Returns follow the Library's design return contract, `library/contracts/design-return.schema.json` of `49GAION-protocol`.

## Mother and instance

- **The Library pins this text** by repository, path, version, commit and SHA-256 (`49GAION-protocol`, `library/README.md`). A new version reaches the Library only by a pull request that moves the pin.
- **Each organisation makes its own instance** from it, in its own writing repository, with its own values set; the organisation's values never come back here. The first instance keeps its own repository, which held this text before this repository existed; the Library points here from the pin that follows `decisions/DR-0006`.
- **The product's code and its requirements** (the PRD) live in each instance's code project. The blueprint cites the PRD by requirement ID.

## Checks

```
python3 tools/make_cards.py <49GAION-protocol>/spec/schemas
```

It must report 0 errors.

## How a change is made

A change is a pull request, reviewed by someone other than its writer. A decided text is never edited; a change is a new version that names what it supersedes.

*Powered by 49GAION*
