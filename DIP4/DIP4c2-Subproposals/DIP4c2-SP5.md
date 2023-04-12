# DIP4c2-SP5: DIP12 Amendments

## Preamble

```
DIP4c2-SP#: 5
DIP to be Amended: DIP12
Author(s): Charles St.Louis (@CPSTL), Rune Christensen (@Rune23) 
Contributors:
Tags: dip-amendment, collateral-onboarding
Status: Rejected
Date Proposed: 2020-07-08
Date Ratified: 
```

## Sentence Summary

DIP4c2-SP5 amends DIP12 to remove dependencies on DIP6, DIP8, and DIP9.

## Specification

### Motivation

This amendment DIP proposes a change to DIP12 to remove the dependencies on DIP6, DIP8, and DIP9 to improve further the efficiency of collateral onboarding to the Maker Protocol. Additionally, it adds two new components based on DIP17. The first component enables the use of DIP12 subproposals to adjust the Target Debt Ceiling and Target Risk Premium (DIP12c4). The second component creates a list of the enabled collateral types and their risk parameters (DIP12c5).

This amendment DIP impacts the DIP12 subproposal process. More specifically, it creates a process for collateral types to have their Target Debt Ceiling and Target Risk Premium (TRP) risk parameters adjusted (based on DIP17) and eliminates some dependencies that were inconsistent across the Collateral Onboarding DIPs Set (DIP6, DIP8, DIP9).

### Amended Components

- **Motivation**
    - Remove the specific reference of DIP9's involvement in the DIP12 process.

- **DIP12c1: Domain Team Requirements for Onboarding Collateral Type to the Maker Protocol**

    - Removal of DIP12 dependencies on DIP6, DIP9, DIP8 
        - **Reasoning:** As of today, there remain some inconsistencies within the Collateral Onboarding DIPs Set. More specifically, the DIP9 Community Greenlight Polls are non-binding and do not block Domain Greenlight (DIP8) or the ability for Domain teams to perform work on collateral types. Therefore, this makes a clear case to remove the dependencies to further improves the efficiency of collateral onboarding to the Maker Protocol.

- **DIP12c2: Proposing New Risk Parameters, Oracles, and Collateral Adapters**
    - Add minor phrasing updates to improve clarity.

- **Add DIP12c4 component - Creates the Target Debt Ceiling and Target Risk Premium Requirements**

    - This component defines the requirements for which collateral types can have their Target Debt Ceiling (TDC) and Target Risk Premium (TRP) risk parameters adjusted.
    - In short, DIP17 is a proposal that adds extra flexibility to collateral types that are DIP17 enabled, by giving Maker Governance the recurring option to dynamically adjust their Actual Debt Ceilings and Actual Risk Premiums based on the utilization of the collateral type. Note that only collateral types that have been specified as being DIP17 enabled through a DIP12c2 (Proposing New Risk Parameters, Oracles, and Collateral Adapters) have the Target Debt Ceiling and Target Risk Premium risk parameters.

- **Add DIP12c5 component - A list of DIP17 enabled collateral types, and their risk parameters**

    - This component defines explicitly the requirements for getting a collateral type added to the List Enabled Collateral Types. The list contains the current active DIP17 enabled collateral types, and their DIP17 risk parameters (TDC and TRP).

### Amendment Pull Request (PR)

- [Updated Version of DIP12 PR](https://github.com/lasthyphen/dips/pull/53)

### Relevant Information

- n/a

---
