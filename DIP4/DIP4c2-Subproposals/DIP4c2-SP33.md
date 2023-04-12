# DIP4c2-SP33: Amend DIP62 to Allow for Changing Communication Responsibilities

## Preamble

```
DIP4c2-SP#: 33
DIP to be amended: DIP62
Author(s): @LongForWisdom
Contributors:
Tags: dip-amendment
Status: Accepted
Date Proposed: 2023-01-11
Date Ratified: 2023-02-27
Forum URL: https://forum.makerdao.com/t/dip4c2-sp33-amend-dip62-to-allow-for-changing-communication-responsibilities/19381
Ratification Poll URL: https://vote.makerdao.com/polling/QmQjv36P#vote-breakdown
```

## Specification

### Motivation

This amendment is intended to:
* Replace GovComms as the responsible party for communicating offboardings through DIP62.
* Prevent the requirement for a token vote in the event we run into this same issue in the future.

### Amended DIPs and Components

* DIP62c2 (Modified)
* DIP62c3 (Modified)
* DIP62c5 (Added)

### Patch Notes

* Replaced references to GovComms with references to a 'Communication Coordinator' defined in new component DIP62c5.
* DIP62c5 defines GovAlpha as the new Communication Coordinator.
* DIP62c5 allows DIP Editors to modify DIP62c5 without a governance vote to refer to a new Communication Coordinator if:
    * The previous coordinator is unwilling or unable to fulfill the responsibility.
    * A new coordinator is willing to take on the communication role.
* DIP62c5 requires public communication of any modifications by DIP Editors.
* Fixed some minor formatting stuff in the DIP component summary.

### Amendment Pull Request

https://github.com/lasthyphen/dips/pull/741

### Relevant Information

N/A
