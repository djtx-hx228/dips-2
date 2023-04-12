# DIP4c2-SP22: DIP41 Facilitator Offboarding Amendment

## Preamble

```
DIP4c2-SP#: 22
DIP to be amended: DIP41
Author(s): Sam MacPherson (@hexonaut)
Contributors:
Tags: DIP41, facilitator
Status: Withdrawn
Date Proposed: 2022-07-03
Date Ratified: N/A
Forum URL: https://forum.makerdao.com/t/dip4c2-sp22-dip41-facilitator-offboarding-amendment/16297
Extra: This proposal has been [withdrawn by its author](https://forum.makerdao.com/t/dip4c2-sp22-dip41-facilitator-offboarding-amendment/16297/36)
```

## Specification

### Motivation

Currently it is trivial to create offboarding proposals under an account with zero reputation attached. In theory a new account can be created and apart to post throttling this individual (or bot) could create offboardings for every single core unit all of which have to go to vote.

It is my opinion that due to the severity of this action we should have a minimal level of Sybil protection. Spam submissions haven't happened yet, but they likely will especially as conflicts in the DAO heat up under bear market conditions. I would like to get ahead of this by proposing a modest threshold to submit a facilitator offboarding requiring posting 1 MKR.

If the proposal succeeds then the user gets their MKR back, if it fails the MKR is forfeit. This will result in the user having to post financial stake to begin the offboarding process. The stake is low enough that if truly desired offboardings are there it is not hard to surmount and likely the user will get their MKR back. On the other hand this will prevent spam submissions from clogging up the governance process.

### Amended DIPs and Components

This DIP4c2 subproposal revises [DIP41](https://dips.makerdao.com/dips/details/DIP41) as well as related subcomponents [DIP41c5](https://dips.makerdao.com/dips/details/DIP41#DIP41c5).

### Amendment Pull Request

https://github.com/lasthyphen/dips/pull/603
