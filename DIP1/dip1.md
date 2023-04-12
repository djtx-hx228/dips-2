# DIP1: Dijets Test DIP

## Preamble

```
DIP#: 1
Title: Dijets Governance Paradigms
Author(s): Rune Christensen (@Rune23) and Charles St.Louis (@CPSTL)
Contributors: @LongForWisdom
Tags: process, governance, dip-set, core-governance-dipset
Type: Process
Status: Accepted
Date Proposed: 2023-03-06
Date Ratified: 2023-04-02
Dependencies: n/a
Replaces: n/a
Ratification Poll URL: 
Forum URL: https://forum.makerdao.com/t/dip1-maker-governance-paradigms/1903
Extra: The Problem Space has been amended. See [DIP1c4-SP1](https://dips.makerdao.com/dips/details/DIP1c4SP1). The original version can be found [here](https://github.com/lasthyphen/dips/blob/2634c131f47136e50ded3406728630e0f97a3b45/DIP1/dip1.md).
Extra: This DIP has been made obsolete by the passage of [DIP102c2-SP1](https://dips.makerdao.com/dips/details/DIP102c2SP1)
```

## References

**[DIP1c4-Subproposal-Template.md](DIP1c4-Subproposal-Template.md)**  

## Sentence Summary

DIP1 defines and describes Governance Paradigms and problem spaces.

## Paragraph Summary

A Governance Paradigm is a complete and specific group of DIP Sets that solves an entire problem space. A problem space is defined as a list of issues that must be addressed in order for the Maker Protocol to be able to sustain itself and grow into the future Maker governance.

## Component Summary

**DIP1c1: Definitions**  
Defines what is meant by a problem space and a Governance Paradigm.

**DIP1c2: The Initial Problem Space**  
Defines an initial list of problems that will need to be solved in order for there to be a complete Governance Paradigm.

**DIP1c3: Changing the Governance Paradigm**  
Defines DIPs and DIP Sets as the method used to amend or replace the Governance Paradigm.

**DIP1c4: Changing the Problem Space**  
A process component that provides a method and a template for adjusting the problem space.

## Motivation

The goal of having a defined governance paradigm is to give the community a complete overview of what specific DIPs are used to address specific problems. By having a Governance Paradigm in place, the community can reform and upgrade specific parts of the governance process while complexity and dependency issues are kept in check. At the same time, it also makes it more clear how the community can completely replace and overhaul the governance process, and create something new, while guaranteeing that all the problems that were solved by the old process are also fully solved by the new process.

It is important at all times to have the best possible estimate of what the long-term problem space list will look like. The current list defined within this DIP represents the problems that the Maker Foundation currently believes need to be addressed in order to enable MakerDAO to become self-sustainable. The expectation is that this list will be changed over time as practical experience of the community is gained. After the ratification of this DIP, the Maker community can use the subproposal process to change the list at any time. Therefore, the problem space list is not permanent. The problem space list serves as a best estimate for the problems the Maker community must solve for over the course of the next few years and is expected to change as more information become available. 

## Specification / Proposal Details

### DIP1c1: Definitions 

**Problem Space**

A problem space is the representation of a particular problem or field of problems that must be addressed in order for the Maker Protocol to be able to sustain itself. Examples of problem spaces would be the process of onboarding new collateral types or the Maker governance decision process. Both of these complex problems require their own guidelines and produce their own set of learning experiences.

Note that Problem Spaces do not define any persons or groups working in them, they are theoretical and largely static entities. Problem Spaces exist even if no one is working in that space.

**The Governance Paradigm Problem Space**

A complete list of known major issues, challenges, and opportunities that the Maker Community believes Maker Governance must be able to skillfully address and manage in order to continue to function and grow.

**The Governance Paradigm**

A complete set of processes, implemented through DIPs, that allows Maker Governance to address all of the items in the Governance Paradigm Problem Space.

**DIP Sets**

A DIP Set is a group of several DIPs that are interdependent, in which without the entire set of DIPs existing, one or more DIPs in the Set becomes inconsistent, invalid or nonsensical. The intention is for DIP sets to together describe a single complex behaviour in such a way that allows each individual DIP to be written following the principle of Specificity but work together as a cohesive modular whole. 

---

### DIP1c2: The Initial Problem Space

**Problem Space List**

The current Governance Paradigm Problem Space is defined as follows and is organized in loose order of priority from a risk and complexity perspective:

1. Constitution: The constitution is a DIP that contains the core tenets of the social contract and voter pre-agreements that stabilize the meta of the Endgame State.
2. Endgame Product DIPs: A set of DIPs that define each Endgame Product in as much detail as possible. Only products that are already detailed and defined in the Endgame Products DIPs can be added to the Maker Protocol.
3. Scope DIPs: The Scope DIPs are individual DIPs that each cover the 11 Scopes that define all Maker Governance processes and the expectations and KPIs of the Decentralized Workforce.
4. Metanomics: The Metanomics DIP provides an immutable and unambiguous definition of what the long-run, unchangeable tokenomics of the Endgame State will be. This includes MKR emissions, Maker surplus funnelling, MetaDAO emissions, and MetaDAO surplus funnelling.
5. Launch MetaDAO Activation: To trigger the Endgame Plan Launch, a Launch MetaDAO Activation DIP is required, as this authorizes the deployment and activation of the MetaDAO tokens and the MetaDAO token farms.

---

### DIP1c3: Changing the Governance Paradigm

**Amending the Governance Paradigm**

A Governance Paradigm can be amended by replacing specific DIPs, or an entire DIP Set, in the Governance Paradigm while maintaining correct interfacing with all other DIPs within the DIP set and wider Governance Paradigm.

**Replacing a Governance Paradigm**

A governance paradigm can be replaced in its entirety by replacing all DIPs in the Governance Paradigm with a complete grouping of new DIPs, contained in DIP Sets that fully address all items in the Governance Paradigm Problem Space

An individual DIP or DIP Set in the active Governance Paradigm cannot be replaced if the replacement doesn't properly interact with the other DIPs in the Governance Paradigm that the replaced DIP is dependent on, or that are dependent on the replaced DIP. Otherwise, the Governance Paradigm as a whole could break and DIPs could stop functioning correctly due to interdependency issues. Thus, you have to either replace an individual DIP or DIP Set in a Governance Paradigm or replace the entire Governance Paradigm with a completely new grouping of DIP Sets that fully address all items in the Governance Paradigm Problem Space.

---

### DIP1c4: Changing the Problem Space

If Maker Governance wishes to change the Governance Paradigm and processes more drastically, they need to alter the Governance Paradigm Problem Space. In most cases, this is done by expanding the Problem Space after practical experience makes it clear there are additional problems, challenges or opportunities that Maker Governance needs a clear predetermined process to deal with. However, it could also be reducing the scope of the Problem Space, or changing the language or logical grouping of some of its aspects.

DIP1c4 is a Process DIP component that allows the creation of subproposals that can add or delete items in the Governance Paradigm Problem Space. DIP1c4 subproposals have the following parameters:
-   **Feedback Period**: 3 months
-   **Frozen Period**: 1 month

DIP1c4 subproposals must use the template located at  **[DIP1c4-Subproposal-Template.md](DIP1c4-Subproposal-Template.md)**. This template is considered ratified once this DIP moves to Accepted status.


---
