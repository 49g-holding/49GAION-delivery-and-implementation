# DR-0007 · Delivery and Implementation mother: positions only, brought into line with 49GAION/DR-0048 and DR-0049

- **Date:** 2026-10-28
- **Decided by:** the governing seat (GOV) of 49GAION
- **Source:** `49GAION/DR-0048`, the complete definition `v2.1.0`: the system recognises only AI, organised in AIOCs, and human positions carrying a HOAC label; no natural person and no person's name is recorded in it; each organisation's own mechanism, outside the system, decides how its positions are assigned and administered and who holds them. `49GAION/DR-0049` brings the texts into line. The record is prepared by the AI hub; the governing seat's merge is the decision.
- **Relation:** builds on DR-0006. Where an earlier record of this repository sets the mechanism behind a human position (who occupies it, an acting filler, a deputy, "the governance seat appoints Top Management directly"), this record supersedes it; those records are frozen and are read with this one.

## Decision

1. **Positions only.** Every human place in this repository is a position. Who holds it, and how (successors, deputies, boards and the credentials with which a position signs included), is the organisation's own mechanism, outside the system; this AIOC never sees it.
2. **Withdrawn.** The acting filler and the signature type `appoint-acting-filler`, which leaves every `authority_scope`; deputies of human seats (the positions table's Deputy column becomes Cover, which stays meaningful for AI positions); occupancy, handover and arrangement entries; the holders register; a compensating control for one person behind several positions. What stays: two positions are two parties; the Overseen link between positions; `succeeded_by`; the duty deputy, an AI part.
3. **The changes.** Each place below is changed in its file; its former wording is kept here, verbatim.

   - `blueprint/DI-BLUEPRINT.md`, under “Blueprint · `[ORG]AIOC-DI` · Delivery and Implementation · `v0.2.1`”, the one-page summary, mode C:
     ```text
     > 3. **Mode C:** no design. The owner's sources, in Source Lifecycle; DI builds a light design with the owner.
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “1. Card (49GAION Operating Protocol §3)”, the input of mode C:
     ```text
     or (mode C) the references of the owner's sources
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “1. Card (49GAION Operating Protocol §3)”, the skill di-light-design:
     ```text
     A light design built with the owner, every element provisional until decided
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “2.2 Placement”, what it does:
     ```text
     or build a light design with the owner (mode C)
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “3. Positions”, the Light Designer:
     ```text
     | build a light design with the owner, in mode C |
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “Definition”, item 7, mode C:
     ```text
     The owner's sources in Source Lifecycle are cut into atoms and labelled as in mode B. There is no design to map: the Light Designer builds one with the owner (§5.11).
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “5.0 The stages: input, output, done-test”, S1C:
     ```text
     P0: the owner's sources.
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “Definition”, inputs:
     ```text
     | the Input Pack: the owner's sources in Source Lifecycle, cut into atoms and labelled |
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “Role card”, the role card:
     ```text
     | the light design, with the owner |
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “8. Tools and the shared AI gateway”, the projection:
     ```text
     | The projection that removes who did the work | top management's own, over the organisation's tools (Annex H) |
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “8. Tools and the shared AI gateway”, M-12:
     ```text
     | removes who did the work before any record reaches this AIOC | top management's own mechanism |
     ```
   - `tests/TEST-DI.md`, under “Mode C, the light design”, TEST-DI, case 54:
     ```text
     From a sample of an owner's sources,
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “3. Positions”, the Deputy cell of the accountable position:
     ```text
     | as top management arranges (`appoint-acting-filler`, Standard §4.1, item 12) |
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “3. Positions”, the positions table, the Deputy column:
     ```text
     | Position (standard title) | Purpose | Reports to | Run today by | Deputy |
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “17. Cells and Pods”, an `authority_scope`, the type `appoint-acting-filler`:
     ```text
     , "appoint-acting-filler"
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “3. Positions”, the positions table, Run today by:
     ```text
     who occupies it is top management's own mechanism, never seen by this AIOC
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “0. Identity and lineage”, the accountable seat:
     ```text
     Who occupies it is top management's own mechanism; this AIOC never sees it
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “2.1 Organisation table”, the accountable seat:
     ```text
     Who occupies it is top management's own mechanism; this AIOC never sees it
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “2.1 Organisation table”, positions only:
     ```text
     who occupies each one is top management's own mechanism
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “7. Records and where things live”, records, the link between positions and persons:
     ```text
     | The link between positions and whoever occupies them | not here: top management's own mechanism
     ```
   - `blueprint/DI-BLUEPRINT.md`, under “13. For the `[ORG]HOAC-ACS` seat, and every decision only a human seat can take”, the row on the accountable position:
     ```text
     **Top management's own mechanism.** Arrange the DI Delivery Lead position and any HOAC position added to this AIOC. Nothing of who occupies them enters this blueprint | the Cell carrying `[ORG]HOAC-TM` | the position is vacant:
     ```
   - `STATE.md`, under “State”, the HOAC positions:
     ```text
     Who occupies it is top management's own mechanism
     ```
   - `CONTRIBUTING.md`, under “Contributing”, positions, never people:
     ```text
     Who occupies a position is top management's own mechanism, never here
     ```

4. **The cards** are regenerated by `tools/make_cards.py` from the blueprint.
5. **The version.** Unreleased. The blueprint keeps its version label; the version and the Library pin move at the next release, by a pull request, on the governing seat's word.

*Powered by 49GAION*
