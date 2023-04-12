# DIP2: Launch Period

## Preamble

```
DIP#: 2
Title: DIP Launch Period
Author(s): Rune Christensen (@Rune23), Charles St.Louis (@CPSTL)
Contributors: @LongForWisdom
Tags: process, governance, dip-set, core-governance-dipset
Type: Process
Status: Accepted
Date Proposed: 2023-04-06
Date Ratified: 2023-04-10
Dependencies: DIP0, DIP1
Replaces: n/a
Ratification Poll URL:
Forum URL: https://forum.makerdao.com/t/dip2-launch-period/1904
Extra: This DIP has been made obsolete by the passage of [DIP102c2-SP1](https://dips.makerdao.com/dips/details/DIP102c2SP1)
```

## References

No referenced materials.

## Sentence Summary

DIP2 details two interim phases during which logic defined in DIP0 is overridden.

## Paragraph Summary

This proposal details the process of how Maker Governance can bootstrap the setup and implementation of the first Governance Paradigm. More specifically, it defines two phases:
1. **Phase 1:** when a core governance framework is put in place and a functional collateral onboarding process is ratified.
2. **Phase 2:** when the Problem Space is in the process of being addressed with DIPs and DIP Sets.

Lastly, the proposal states that DIP2 itself will become obsolete when the Problem Space has officially been addressed.

## Component Summary

**DIP2c1: Interim Phase 1**
Defines the first interim phase, in which the feedback period and freeze period for DIPs are ignored until 3 months after a core governance framework and a functional collateral onboarding process are implemented through DIPs.

**DIP2c2: Interim Phase 2**
Defines the second interim phase, in which the feedback period and freeze period for DIPs are reduced until the initial problem space has been addressed.

**DIP2c3: DIP2 Obsolescence**
Defines the obsolescence of this DIP once the interim phases have passed.

## Motivation

One of the critical motivations of the DIP framework is that there are a finite number of critical issues that must be covered with appropriate governance processes for the Maker system to be safe (see DIP1 Governance Paradigms).

At the same time, the goal is also to ensure that the process of implementing and altering critical governance process logic is done at a pace that gives the community enough time to scrutinize and understand specific ideas.

However, these two goals contradict each other in the initial "launch period" where there isn't a formal governance framework in place yet. As a result, the need to "cover all bases" by having a robust, simple solution for governance processes in place for all critical risks takes precedent over the goal of slowing down and deeply scrutinizing all proposals. Without proactive solutions in place, the community could be forced into undesirable reactive decision making in the event a critical problem or an opportunity occurs that doesn't yet have a defined process. Reactive decision making has the potential of bad precedents that weren’t fully understood at the time.

As a result, the community should prioritize getting the initial processes in place that will cover all the critical risks and opportunities that are built as a formalization of existing processes or knowledge in the community and Maker Foundation. Once the initial governance paradigm is in place the community can amend or replace it as necessary to build a more permanent and robust paradigm, taking advantage of the practical knowledge gained in the interim period.

## Specification / Proposal Details

### DIP2c1: Interim Phase 1

**Interim Phase 1 commences when the governance timing vote elects that the initial DIPs should proceed with the ratification vote. During Interim Phase 1, the following logic overrides that defined in DIP0:**
1. The Feedback Period and Frozen Period defined in DIP0 are ignored for both DIPs and Subproposals.
2. Multiple DIPs and Subproposals and can be voted in with a single vote.
	- Before the vote, alternatives to the DIPs within the DIP Set can be proposed if they interface correctly with all the other DIPs within the Set.

**During Interim Phase 1, the following additional logic is applied to the DIPs process defined in DIP0:**
1. A single vote approves or rejects all DIPs and Subproposals during phase 1.
2. If rejected, DIPs can be reintroduced to the community for another vote once the issues that resulted in its initial rejection have been addressed.

Interim Phase 1 ends 3 months after there is a formal a core governance framework in place and a functional collateral onboarding process.

---
### DIP2c2: Interim Phase 2

Interim Phase 2 commences as Interim Phase 1 ends.

**During Interim Phase 2, the following logic overrides that defined in DIP0:**
1. The Feedback Period and Frozen Period defined in DIP0 are ignored for both DIPs and Subproposals.

**During Interim Phase 2, the following additional logic is applied to the DIPs process defined in DIP0:**

1. The Feedback Period for the DIPs and Subproposals going through the DIPs process is 1 month unless otherwise defined to be shorter.
2. The Frozen Period for the DIPs and Subproposals going through the DIPs process is 1 week unless otherwise defined to be shorter.
3. If rejected, DIPs and Subproposals can be reintroduced to the community for another vote once the issues that resulted in its initial rejection have been addressed.

Interim Phase 2 ends when the Problem Space has been addressed. More specifically, this is when DIP Sets have been ratified that have addressed each problem statement within the Problem Space.

---
### DIP2c3: DIP2 Obsolescence

Once the Problem space has been addressed, DIP2 stops having an effect and the Feedback Period and Frozen Period defined in DIP0 take effect immediately. Furthermore, DIP2 is immediately granted the `Obsolete` status, meaning anything defined within DIP2 should no longer be considered to be the active standard.
