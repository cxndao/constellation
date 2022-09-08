---
cip: 4
title: Distribution Rate of $CXN Tokens to Non-Genesis Members
description: Determine a distribution rate for new CXND members that join after Season 0. 
author: Matt Joyal [mattjoyal#0985](mattjoyal)
discussions-to: https://discord.com/channels/920456009267429417/1014179499149103257
status: Review
type: Operations Track
category: Treasury
created: 2022-09-04
---

## Overview

Current, non-Genesis members of Constellation DAO (CXND) who join during Season 1 and future members who join CXND should receive $CXN tokens for their verified membership. Each $CXN token represents one vote within CXND's voting matters. Genesis members are defined as members who signed the charter before 04/27/2022.

It is in the interest of CXND to incentivize new members to sign the charter and to engage in DAO governance through the use of their tokens, rewarding those who join CXND early as a new entity. This incentive to join early and receive a larger amount of tokens will allow a healthy outset for governance participation through the ability to vote. While future members will receive less tokens for joining, future projects with Constellation Fund (CXNF) and DAO bounties will allow for new opportunities for $CXN tokens to be distributed to future members. 

## Background & Motivation

New members deserve tokens for joining Constellation DAO and getting their NFT verified. The goal is to give members $CXN governance tokens so that they may create and vote upon CXND CIPs. 

New members are incentivized to join early to obtain more $CXN tokens and to engage in the community at the early stages of the DAO. 

### Goals

- **Goals**
  - Allow for new DAO members to claim $CXN tokens once they join Constellation DAO following the Genesis token distribution.
  - Set the distribution rate for $CXN token distribution for each season until reaching a floor. 
  - Decide on a token distribution rate based on the Genesis member initial token distribution. 
  - Distribute tokens to all existing and future Season 1 and beyond members that are verified with their NFT. 

- **Non-goals**
  - Setting a distribution rate for Season 0. CIP-3 will focus on that season as a unique case.
  - Setting up the process to distribute the $CXN tokens. This will rely on the Treasury committee & will follow precedent of the token distribution to Genesis members & following Season 0 distribution. 

## Proposed Solution

Per the Constellation DAO Charter, two million $CXN tokens were allotted to Genesis members, to be equally distributed to all members that signed the Charter prior to the deadline. This resulted in all Genesis members receiving 23,255 tokens, each. This number of tokens will be used as the membership token allotment starting point. Season 0 will have their token distribution rate decided upon in CIP-x. 

For future seasons, new CXND members will receive token amounts based on the verified date in which they have joined CXND. These tokens will come from the treasury token pool, not the season token pool. 

Any new, non-Genesis members of CXND will receive tokens based on the following formula where N seasons is equal to or less than 5 and rounded down to the largest integer: 

  - New member token allotment = $23255 / [2^{(N+1)}]$

For any new, non-Genesis members of CXND that join during Season 6 or beyond, the member will receive the floor allotment of tokens, exactly 232 $CXN tokens. 

  - New member token allotment = $232$

| Season      | $CXN Amount | End Year | Notes  |
| :---------: | ----------: | :------: | :----- | 
| Genesis     |  23,255     | 2022     |        |  
| Season 0    |  _see note_ | -        | See [CIP-3](https://github.com/cxndao/constellation/blob/main/CIPs/cip-3.md) |  
| Season 1    |  5,813      | 2023     |        |  
| Season 2    |  2,906      | -        |        |  
| Season 3    |  1,453      | 2024     |        |  
| Season 4    |  726        | -        |        |  
| Season 5    |  363        | 2025     |        | 
| Season 6+   |  232        | -        | Floor  | 


### Plan & Timeline

This CIP will be enacted at the start of Season 1 by the Treasury Committee. Tokens will be distributed by the Treasury Committee to new members on an agreed upon weekly, bi-weekly, or similar cadence as decided upon by the Treasury Committee. 

### Dependencies

[CIP-3](https://github.com/cxndao/constellation/blob/main/CIPs/cip-3.md). This CIP will decide the token distribution rate for Season 0 members. 

### Rationale

We need to incentivize new members to participate in CXN governance and help push forward new CIPs & engagement. Methods of earning $CXN tokens right now are limited due to the early stages of CXND. However in the future, bounties and additional ways to earn $CXN tokens will take place for the reduced amount of initial token distribution. 

### Risks?

The lower amount of tokens distributed to new members may not make new members want to join. However other ways to earn $CXN tokens (such as bounties) should fill in that gap and encourage engagement within CXND. 

## Appendix

None
