# DIP4c2-SP31: DIP63 Maker Keeper Network Amendment

## Preamble

```
DIP4c2-SP#: 31
DIP to be amended: DIP63
Author(s): Sam MacPherson (@hexonaut)
Contributors:
Tags: DIP63
Status: Accepted
Date Proposed: 2022-12-02
Date Ratified: 2023-01-23
Forum URL: https://forum.makerdao.com/t/dip4c2-spxx-dip63-maker-keeper-network-amendment/19024
Ratification Poll URL: https://vote.makerdao.com/polling/QmRswbkm
```

## Specification

### Motivation

After successful trial run of the beta version of DIP63, there are a few learnings that I want to incorporate for the next iteration. Specifically, more strictly defining how payments are sent and buffers reported as well as changing a few parameters. I’ve also added an explicit stream duration as previously this was just assumed to be 6 months. The Sequencer can also set custom windows per network now.

### Amended DIPs and Components

This DIP4c2 subproposal revises [DIP63](https://dips.makerdao.com/dips/details/DIP63).

### Amendment Pull Request

https://github.com/lasthyphen/dips/pull/720

---

### Relevant Information

* The proposed [code](https://github.com/makerdao/dss-cron)


