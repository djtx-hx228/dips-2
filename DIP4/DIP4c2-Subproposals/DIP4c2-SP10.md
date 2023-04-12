# DIP4c2-SP10: DIP0 Amendments

## Preamble

```
DIP4c2-SP#: 10
DIP to be Amended: DIP0
Author(s): @juanjuan
Contributors: @elprogreso @iammeeoh
Tags: dip-amendment
Status: Accepted
Date Proposed: 2021-01-18
Date Ratified: 2021-25-03
Dependencies: DIP38, DIP39, DIP40, DIP41, DIP4c2-SP12
```

## Sentence Summary

DIP4c2-SP10 amends DIP0 to be compatible with the Domain Framework DIP Set.

## Specification

### Motivation

This amendment DIP proposes edits to DIP0 that make it compatible with the newly proposed Domain Framework DIP set. The main changes remove the inbuilt functionality of DIP0 to onboard core personnel, and instead uses the DAO Primitives State to determine who has been onboarded as Governance Facilitators by Maker Governance, and then introduces logic that allows Governance Facilitators to designate DIP Editors.

### Amended Components

- **References**
    - Removed the references to Core Personnel onboarding and offboarding Subproposal templates.

- **Paragraph Summary**
    - Updated the summary to add that the DIP was edited to be compatible with the new Domain Framework.

- **Component Summary**
    - Removed the last two components related to Core Personnel onboarding and offboarding.

- **DIP0c1: Definitions of the Maker Improvement Proposal Framework**
    - Edited Governance Facilitator and DIP Editor entries to reflect that Governance Facilitators are selected through the new Domain Framework, and that DIP Editors are designated by elected Governance Facilitators.
    - Removed reference to the Maker Foundation

- **DIP0c8: DIP0 Domain Role Dependencies**
    - Edited details of the Governance Facilitator and DIP Editor to reflect that Governance Facilitators are selected through the new Domain Framework, and that DIP Editors are designated by elected Governance Facilitators.

- **DIP0c9: Grandfathered Core Personnel Role List**
    - Name changed to Grandfathered Core Personnel Role List
    - Description changed to reflect a list of hardcoded Core Personnel that are used for bootstrapping until a Governance Facilitator has been onboarded according to the logic of the new Domain Framework.
    - The Grandfathered Core Personnel are based on the previous list of currently active Core Personnel

- **DIP0c10: DIP Editor Role**
    - Edits to reflect that DIP Editors are designated by Governance Facilitators

- **DIP0c11: Governance Facilitator Role**
    - Added a line specifying abuse of the power to add/remove DIP Editors as grounds for removal


### Amendment Pull Request (PR)
   - Updated Version of DIP0 PR

### Relevant Information
   -  n/a
