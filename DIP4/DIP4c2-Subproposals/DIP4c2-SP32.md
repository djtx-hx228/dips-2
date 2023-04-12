# DIP4c2-SP32: Remove DIP14c4: Protocol DAI Transfer Ceiling

## Preamble

```
DIP4c2-SP#: 32
DIP to be amended: 14
Author(s): @Patrick_J
Contributors:
Tags: dip-amendment
Status: Accepted
Date Proposed: 2022-12-08
Date Ratified: 2023-01-23
Forum URL: https://forum.makerdao.com/t/dip4c2-sp32-remove-dip14c4-protocol-dai-transfer-ceiling/19093
Ratification Poll URL: https://vote.makerdao.com/polling/QmPHFiYP
```

## Specification

### Motivation

With the coming transition to the Endgame state, GovAlpha is anticipating an increase in funding requests through [DIP14: Protocol DAI Transfer](https://dips.makerdao.com/dips/details/DIP14) and [DIP55: Special Purpose Fund](https://dips.makerdao.com/dips/details/DIP55). [DIP14c4](https://dips.makerdao.com/dips/details/DIP14#DIP14c4) places a cap on the total amount of DAI that can be distributed through DIP14. The number chosen, 250,000 DAI, is arbitrary and amendment requires a full Monthly Governance Cycle.

Consequently, a failure state exists where the sum of all fund requests in a Governance Cycle through [DIP14](https://dips.makerdao.com/dips/details/DIP14) will exceed the ceiling and/or it will not be possible to raise with sufficient lead-time to distribute Maker Governance approved funds in a timely manner. Rather than dealing with sequential subproposals to raise the Protocol DAI Transfer Ceiling, or setting it to an arbitrarily high number that renders it useless, it makes more sense to simply remove this restriction.

The remaining content of [DIP14](https://dips.makerdao.com/dips/details/DIP14) remains appropriate, in my opinion. There is no need to replace the whole DIP.

### Amended DIPs and Components

- [DIP14c4](https://dips.makerdao.com/dips/details/DIP14#DIP14c4) is removed by this subproposal.

### Amendment Pull Request

- [Pull Request](https://github.com/lasthyphen/dips/pull/726)

### Relevant Information

We have already received two DIP14c2 proposals that sum to 182,454 DAI:

* [DIP14c2-SP1](https://dips.makerdao.com/dips/details/DIP14c2SP1)
* [DIP14c2-SP2](https://dips.makerdao.com/dips/details/DIP14c2SP2)

