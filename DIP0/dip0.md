# DIP0: Dijets Improvement Proposal Framework

## Preamble

```
DIP#: 0
Title: Dijets Improvement Proposal Framework
Author(s): Saleem Farid (@Dijets-Inc)
Contributors: @UnignorantF, @blimps
Type: Process
Status: Accepted
Date Proposed: 2020-04-06
Date Ratified: 2020-05-02
Last Amended: 2023-02-26
Dependencies: n/a
Replaces: n/a
Ratification Poll URL:
Forum URL: https://forum.dijets.io/
```

## References

**[General-DIP-Template.md](General-DIP-Template.md)**  
**[Technical-DIP-Template.md](Technical-DIP-Template.md)**

## Sentence Summary

DIP0 defines the *Dijets Improvement Proposals (DIPs) Framework* for all subsequent DIPs to utilize.

## Paragraph Summary

DIP0 defines the *Dijets Improvement Proposals (DIPs) Framework* for all subsequent DIPs to utilize. This DIP is the foundational DIP that provides the necessary templates, processes, and guidelines for working within the framework and defines the key roles required for the operation of a typical DIPs Process.

## Component Summary

**DIP0c1: Definitions of the Dijets Improvement Proposal Framework**  
*Defines core concepts of the DIP Framework.*  

**DIP0c2: Endgame Configuration**  
*Specifies which DIPs are active*  

**DIP0c3: The DIP Lifecycle**  
*Defines the formal stages in the lifecycle of DIPs from conception to approval, rejection, or deferral.*  

**DIP0c4: DIP Components and DIP Component Types**  
*Defines DIP Components and their types.*  

## Motivation

For Dijets Governance to evolve into a fully decentralized and self-sustainable organization, a formalized process of decision-making is required.

The DIP Framework serves to empower each off-chain and on-chain Governance participant by giving them a standardized way of interacting with the wider DAO.

In Endgame, the DIP framework is eventually going to be fully replaced with the Dijets Constitution and the Scope Frameworks, and this DIP regulates the transition period before they are fully replaced.

## Specification / Proposal Details

### DIP0c1: Definitions of the Dijets Improvement Proposal Framework

- **Dijets Improvement Proposals (DIPs):** - DIPs are standardized documents subject to voting that, once given the accepted status through the process described in DIP0, regulate and define the behavior of Dijets Governance and the Dijets Protocol. DIPs can be amended and removed. All DIPs except for Endgame DIPs are automatically considered obsolete, and do not have any effect on Dijets Governance processes, Governance Polls, or Executive Votes.
- **Endgame DIPs:** Endgame DIPs are DIPs that are specifically designated in DIP0c2 to remain active after the Dijets Constitution has come into effect.
- **Governance Process Support Ecosystem Actors:** Individuals or companies that have been publicly designated by an Ecosystem Facilitator to be tasked with Governance Process Support, including DIP process support.
-   **Subproposals (SPs):** Subproposals are instances of Process DIP Components. See `DIP0c4`.  
-   **Minimum Feedback Period:** The minimum amount of time within which the community can give feedback in response to a proposed DIP before it can advance to Formal Submission. See `DIP0c3`.  
-   **Minimum Frozen Period:** The minimum amount of time during which a DIP must remain unchanged before it can advance to Formal Submission. See `DIP0c3`.

### DIP0c3: The DIP Lifecycle

#### DIP Lifecycle Breakdown

1. **Conception**: A DIP Author posts a DIP proposal in the [Dijets forum](https://forum.dijets.io/) under the *Dijets Improvement Proposals* category. From this point on, Governance Process Support Ecosystem Actors will be available to assist the DIP Author.

2. **Approved by Governance Process Support Ecosystem Actor(s)**: A Governance Process Support Ecosystem Actor verifies that the posted DIP proposal:

   - Follows the appropriate format of the DIP Template for its type. See `DIP0c4`.
   - Is a valid Subproposal based on a Process Component of an Endgame DIP
   - Has been submitted to the [DIPs GitHub](https://github.com/lasthyphen/dips) repository with a Pull Request by either the DIP Author or a Governance Process Support Ecosystem Actor.

   If the verification is successful, the Governance Process Support Ecosystem Actor:

   - Approves the DIP and assigns it a formal DIP number.
   - Merges in the PR.

3. **Request for Comments (RFC)**: A period of reviewing by the community and attendant redrafting begins. The minimum duration of this period is determined by two variables contained within the Process Component:

   - `Feedback Period`
   - `Frozen Period`

   These periods can overlap. See `DIP0c1` for their definitions.

4. **Fulfilled Feedback Period Requirements:** After the DIP has fulfilled the RFC phase, it is ready for Formal Submission.

5. **Formal Submission (FS):** At this point, the DIP Author submits their DIP to the Governance Cycle by moving it to the [*Formal Submission* forum category](https://forum.dijets.io) within the [formal submission window of a Governance Cycle](https://github.com/lasthyphen/dips/blob/master/DIP51/dip51.md#dip51c1-governance-cycle-breakdown).

6. **Approved by the Governance Process Support Ecosystem Actor(s):** The Governance Process Support Ecosystem Actors evaluate the DIP. If they do not approve it, the DIP may be reconsidered to enter the Governance Cycle at a later date.

7. **Monthly Governance Cycle**: At this point, the proposal enters the [Monthly Governance Cycle](https://github.com/lasthyphen/dips/blob/master/DIP51/dip51.md).

8. **Accepted/Rejected:** The DIP is voted on. If it passes, it is officially accepted and is given the `Accepted` status. If not, the DIP is rejected.

#### Other DIP Statuses

- **Obsolete:** Assigned when:

  - A DIP has been superseded or deprecated.
  - A DIP has been deferred for over six months.
  - A DIP Author has abandoned the proposal and no person has communicated willingness to take over the responsibility of a DIP Author.
  - A DIP is not an Endgame DIP as defined in DIP0c2

#### DIP Status Change Process

If a DIP Author requests a status change for a DIP, a Governance Process Support Ecosystem Actor will review it. If the status change is warranted, the Governance Process Support Ecosystem Actor will change the status. Otherwise, the Governance Process Support Ecosystem Actor will revert and highlight issues for the DIP Author to fix before requesting another status change.

---

### DIP0c4: DIP Components and DIP Component Types

#### DIP Components

In order to satisfy the Core Principles of clarity and completeness, a DIP may need to have multiple components that each define distinct units of logic.

A DIP Component can be of one of two types: General or Process. The type of General DIP Components is usually left undeclared: It is the assumed type of components that are not of Process type.

DIP components can specify that they supersede other components in the same DIP. If a component specifies that it supersedes other components in the DIP, then the superseded components must be interpreted differently, to account for the parts that have been superseded and no longer have an effect.

#### Process DIP Component  

DIP Components of the Process type shape a specific process flow for the Dijets community to adopt and standardize with respect to how governance operates. This DIP component type helps streamline particular processes in a transparent, open, and traceable manner.

In this DIP, `DIP0c5` is a Process Component.

Process DIP Components require no special template.

#### Subproposals

Subproposals are special DIPs defined in Process DIP Components.

Subproposals go through the same process DIPs do, as described in `DIP0c3`.

For their derived subproposals, Process Component DIPs define:

- Which template they must use. If none is specified, no special template is needed.
- Their Feedback Period and their Frozen Period.

#### Naming conventions

**DIP Components** follow the naming convention `DIPXcY`, where `X` is the parent DIP and `Y` is the component number.

**Subproposals** follow the naming convention `DIPXcY-SPZ`, where `X` is the parent DIP, `Y` is the component number, and `Z` is the subproposal number.
