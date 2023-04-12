# DIP4c2-SP17: Rapid Payment for Small Bug Bounties (DIP64, DIP40c3-SP42 Amendment)

## Preamble

```
DIP4c2-SP#: 17
DIP to be amended: DIP64, DIP40c3-SP42
Author(s): @psychonaut
Contributors: @travinimmunefi
Tags: dip-amendment
Status: Accepted
Date of Amendment Submission: 2022-01-26
Date of ratification: 2022-03-28
Ratification Poll URL: https://vote.makerdao.com/polling/QmRdVByP?network=mainnet#poll-detail
Forum URL: https://forum.makerdao.com/t/dip4c2-sp17-rapid-payment-for-small-bug-bounties-dip64-dip40c3-sp42-amendment/12869
```
## Specification

### Motivation

The current bug bounty payment process is adequate for large payouts, but inconvenient for small payouts. This DIP adds a small payout process.

- Small payouts can be made without delay from the Core Unit's operational wallet. No need for bounty hunters to wait for a monthly executive spell.
- IS-001 Core Unit decides which payment process to use.

This amendment would increase the CU's budget by `100 000 * 115% = 115 000 DAI` per month.

In addition, there are some minor corrections:

- Add a budget line item for gas fees
- Round up the Facilitator's compensation to a round number of USD (no cents)

### Amended DIPs and Components

- [Immunefi Security CU DAI budget](https://dips.makerdao.com/dips/details/DIP40c3SP42)
- [Bug Bounty Program](https://dips.makerdao.com/dips/details/DIP64)

### Amendment Pull Request

- [PR containing the amendment](https://github.com/lasthyphen/dips/pull/463)
