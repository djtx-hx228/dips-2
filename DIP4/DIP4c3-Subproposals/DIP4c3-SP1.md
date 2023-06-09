# DIP4c3-SP1: Amend DIP64 to clarify critical web bounty amount

## Preamble

```
DIP4c3-SP#: 1
DIP to be amended: DIP64
Author(s): @psychonaut
Contributors: @travinimmunefi
Tags: amendment
Status: Accepted
Date of Amendment Submission: 2022-02-24
Date of ratification: 2022-03-16
Forum URL: https://forum.makerdao.com/t/dip4c3-sp1-amend-dip64-to-clarify-critical-web-bounty-amount/13439
Ratification Poll URL: https://vote.makerdao.com/polling/QmQD5PDm#poll-detail
```
## Specification

### Motivation

The reward for *Critical website and application bug reports* was not specified as intended. The reward was specified at 100,000 DAI "if the impact leads to a direct loss in funds or a manipulation of the votes or the voting result, as well as the modification of its display leading to a misrepresentation of the result or vote." This part is clear. "All other impacts that would be classified as Critical would be rewarded no more than USD 50,000." The words *no more than* suggest that an inequality is intended. That is, `bounty <= $50k` instead of `bounty = $50k`.

We omit the words "*no more than*" to obtain the intended reward mechanics.

### Amended Components

- [DIP64](https://dips.makerdao.com/dips/details/DIP64)

### Amendment Pull Request

- [PR](https://github.com/lasthyphen/dips/pull/478)

### Amendment Signal Request Thread

- *Add link here after RFC period*

### Relevant Information

- N/A
