---
layout: posts
title:  "Reminder to inactive validators, launch recap, upcoming 1st hard fork proposal"
excerpt_separator: <!--more-->
categories: [Trustlines Blockchain]
---

Hey Trustlines enthusiasts!

Below you find an update on the recent launch of the Trustlines Blockchain, an analysis of inactive validators and a heads-up for the upcoming first proposed hard fork. We recommend all inactive validators to [set up their nodes](https://www.reddit.com/r/Trustlines/comments/dwclk6/trustlines_blockchain_set_up_your_validator_nodes/) before the end of the grace period to ensure not being forked out.

<!--more-->

## Launch recap

The Trustlines Blockchain [launched successfully](https://twitter.com/TrustlinesFound/status/1197470399220637696) on 21st of November. Out of the 45 validators of the Trustlines Blockchain, 35 successfully produced at least one block so far. 34 validators are creating enough blocks and are stable enough to be considered entirely online at this time.

## Analysis of inactive/ unstable validators

Validator `0x421c65B17a331deFee0aa401fe2541F8D1cAf46D` failed to produce blocks at the start of the chain but has been stable since at least the beginning of Saturday the 23rd. Validator `0xf176B51FDe516bCD8aab3778FBc4ac970423419e` produced 127 blocks at the time of writing, spaced out in time, but that is not enough to be considered stable.

If we include the validators that did not produce a single block, we have the following list of validators that are currently considered offline:

```
0x008d2ce9d8134ceb368c5aeeacd04aef6020c3a0
0x0863be8f0aba8890922c50a75852085a7e324bd2
0x1a35cac5ad61ed5ad42ae322cd71b915bddb6619
0x236daa98f115caa9991a3894ae387cdc13eaad1b
0x3a16c4ae8c82ebfb0ab475bb83c4bed1c421aaa6
0x663d3947f03ef5b387992b880ac85940057c13e3
0x9e557934b1f2488d37c1f739ac34ee1907c562c0
0xba594f053be04ee8942d0d3fa05766f49c5516f8
0xdc0046b52e2e38aee2271b6171ebb65ccd337518
0xedbfa87722f7eeff9d711ca5b084c6c00ca0765f
0xf176b51fde516bcd8aab3778fbc4ac970423419e
```

## Upcoming 1st hard fork proposal and end of "grace period"

As outlined in the [Trustlines Blockchain launch blog post](https://medium.com/trustlines-foundation/t-x-launching-the-trustlines-blockchain-ffeb82b6989b), the Trustlines Foundation will propose a first hard fork after a "grace period" of two weeks post blockchain launch, which will switch validator handling from a list to a contract and will remove inactive validators.

This means that at the end of the grace period on the 5th of December, and unless they become stable until then, the above listed validators should be removed from the validator set due to inactivity.

Again, it is very important that all validators set up their node correctly before the end of the grace period to not be forked out of the validator set due to inactivity! If validators fail to set up their node until then, they might be forked out of the validator set, unable to earn block rewards while their stake will remain locked until the end of the validation period.

## Need help?

Should validators encounter any problems in setting up their nodes during the preparation period, they can get technical help by approaching Trustlines Protocol contributors in the [Gitter chat](https://gitter.im/trustlines/community) or by leaving a comment below.

*The Trustlines Foundation*
