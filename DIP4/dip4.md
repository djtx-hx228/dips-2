# DIP4: DIP Amendment and Removal Process

## Preamble

```
DIP#: 4
Title: DIP Amendment and Removal Process
Author(s): Saleem Farid (@Dijets-Inc)
Contributors: @ForWisdom
Tags: process, dip-set, core-governance-dipset
Type: Process
Status: Accepted
Date Proposed: 2023-03-06
Date Ratified: 2023-04-02
Last Amended: 2023-04-10
Dependencies: n/a
Replaces: n/a
Ratification Poll URL:
Forum URL: https://forum.dijets.io
Extra: This DIP has been amended. See [DIP4c2-SP7](https://dips.makerdao.com/dips/details/DIP4c2SP7). The original version can be found [here](https://github.com/lasthyphen/dips/blob/5cabd4810ffca120355ae242161f99ba1dc8e7fc/DIP4/dip4.md).
Extra: This DIP has been made obsolete by the passage of [DIP102c2-SP1](https://dips.makerdao.com/dips/details/DIP102c2SP1)
  ```

## References

**[DIP4c2-Subproposal-Template.md](DIP4c2-Subproposal-Template.md)**
**[DIP4c3-Subproposal-Template.md](DIP4c3-Subproposal-Template.md)**
**[DIP4c4-Subproposal-Template.md](DIP4c4-Subproposal-Template.md)**

## Sentence Summary

DIP4 defines processes for the amendment and removal of accepted DIPs.

## Paragraph Summary

The Amendment and Removal Process-DIP outlines the process for very small and relatively superficial changes to DIPs. This DIP Contains two Process Components, the first dealing with the Removal of ratified DIPs, and the second dealing with Amending current active DIPs.

## Component Summary

**DIP4c1: Purpose Description**
Suggests the purpose of the amendment and removal processes and possible reasons for using each process.

**DIP4c2: Amendment Process for DIPs Older than 3 Months**
A process component which defines a method and template for the amendment of an accepted DIP older than 3 Months.

**DIP4c3: Amendment Process for DIPs Younger than 3 Months**
A process component which defines a method and template for the amendment of an accepted DIP younger than 3 Months.

**DIP4c4: DIP Removal Process**
A process component which defines a method and template for the removal of an accepted DIP.

## Motivation

The motivation behind this proposal is that changing small details to DIPs should not require the original DIP to become obsolete or replaced, so this Process-DIP is needed to define and outline the process behind making these changes to DIPs once they have already been ratified and implemented. Additionally, this DIP defines the process for the removal of DIPs that have become obsolete.

## Specification / Proposal Details

### DIP4c1: Purpose Description

**Amendments**
DIP Amendments that preserve the DIP number can be performed as long as there are no changes to the logic of the DIP or to the DIP's external output dependencies. They should only be used when minor changes are required.

Amendments to DIPs older than 3 months since acceptance will follow the normal process associated with the monthly governance cycle, with rules outlines in c2.

Amendments to DIPs younger than 3 months since acceptance will follow a different set of rules outlined in c3. These enable younger DIPs to be amended more quickly.

Amendments to multiple DIPs are allowed to be submitted as a single proposal if the changes are linked in some way like being part of a DIP set or part of a larger change that affects multiple DIPs.

**Validity**
The validity of DIP Amendments is ultimately up to the community but possible reasons for amendments could be (but are not limited to):

- A formatting change
- Typos
- Rewording/clarification

DIP Amendments are invalid if, based on the assessment of the community, the changes are so severe that they should be achieved through a DIP replacement instead.

**Removals**

DIP4 also enables the removal of one or multiple DIPs that become obsolete. If there are other DIPs that depend on a DIP that is being removed, they must also be removed or amended in the same governance cycle, otherwise the removal will be invalid.

Removal of multiple DIPs are allowed to be submitted as a single proposal if the changes are linked in some way like being part of a DIP set or part of a larger change that affects multiple DIPs.

### DIP4c2: Amendment Process for DIPs Older than 3 Months

DIP4c2 is a Process DIP component that regulates the amendment of one or multiple Accepted DIPs **that are older than 3 months.** DIP4c2 subproposals have the following parameters:

- **Default Feedback Period**: 3 month
- **Frozen Period**: 1 month
- **Governance Cycle**: Monthly
- **Other Requirements**: None.

All DIP4c2 subproposals must use the template located at **[DIP4c2-Subproposal-Template.md](DIP4c2-Subproposal-Template.md)**.

### DIP4c3: Amendment Process for DIPs Younger than 3 Months

DIP4c3 is a Process DIP component that regulates the amendment of one or multiple Accepted DIPs **that are Younger than 3 months.**

Amendment Subproposals must be submitted to RFC for one week, for the Default Feedback Period. This is followed by a one week duration Signal Request thread, during which the Amendment proposal cannot be changed, fulfilling the 1 week frozen period. DIP4c3 subproposals have the following parameters:

- **Default Feedback Period**: 1 week
- **Frozen Period**: 1 week
- **Governance Cycle**: Weekly
- **Other Requirements**: 7-day Signal Request Thread, passing with 51%.

All DIP4c3 subproposals must use the template located at **[DIP4c3-Subproposal-Template.md](DIP4c3-Subproposal-Template.md)**.

### DIP4c4: DIP Removal Process

DIP4c4 is a Process DIP component that allows the removal of an Accepted DIP or set of DIPs. DIP4c4 subproposals have the following parameters:

- **Default Feedback Period**: 3 months
- **Frozen Period**: 1 month
- **Governance Cycle**: Monthly
- **Other Requirements**: None.

DIP4c3 subproposals must use the template located at **[DIP4c4-Subproposal-Template.md](DIP4c4-Subproposal-Template.md)**. This template is considered ratified once this DIP moves to Accepted status.
