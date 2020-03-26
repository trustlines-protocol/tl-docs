---
layout: posts
title:  "Status update and the first proposed hard fork"
excerpt_separator: <!--more-->
categories: [Trustlines Blockchain]
---

Hello, Trustlines community!

The proposed grace period for validators to come online has now passed.

The time has come for the validators to make a choice on the hard fork that the Trustlines Foundation proposed. They will either choose to approve the proposal by updating their software to follow the changes or oppose them by not upgrading their nodes.

<!--more-->

[Earlier](../../11/25/reminder-to-inactive-validators-launch-recap-upcoming-1st-hard-fork-proposal), we reminded all the Trustlines Blockchain validators who got a slot in [the auction](https://blog.trustlines.network/trustlines-validator-spotlight-deep-dive-on-rewards-economics-and-opportunities-for-validators) to come online by the 5th of December. This heads-up was because the Trustlines Foundation [proposed](https://blog.trustlines.network/t-x-launching-the-trustlines-blockchain) a hard fork. The fork would switch validator handling from a list to a contract and remove inactive validators. Getting removed from the validator set would mean that removed validators are unable to earn block rewards. Still, their stake would not get slashed, but remain locked until the end of the validation period.

If the community, specifically the validators, chooses to accept the proposed hard fork, it will happen next week at block height 307703. This block should be produced approximately on Thursday the 12th of December 2019 at 11:45 AM CET, which gives the Validators about one week from the end of the grace period to update their nodes. The validator contract that would handle the active validator set on the Trustlines Blockchain can be found at address [0xf129765e99ec542bc49c81a9ef6c5fff10529322](https://explore.tlbc.trustlines.foundation/address/0xf129765e99ec542bc49c81a9ef6c5fff10529322/transactions) on the Trustlines Blockchain.

## Validator actions regarding the fork

Most of the validators have set up their nodes using the quickstart script provided. And with it, the watchtower component. If a validator is using watchtower no further action is required to upgrade their software to the proposed changes.

### Manually updating your node for the first hard-fork

For those not running watchtower and wish to follow the proposed hard fork, an update to the new chain specification file is required.

If you use docker you can stop the docker container, pull the new image, and restart the docker container the same way you started it previously.

The download for the new chain specification file can be found here

<https://github.com/trustlines-protocol/blockchain/blob/457790618933bfc3173640b20d0434105c9c5323/chain/tlbc/tlbc-spec.json>

## Validator activity recap

Only validators that never produced a block would get removed in this hard fork. All other validators have shown to be online and stable.

List of inactive validators includes these addresses:

```
0xdC0046B52e2E38AEe2271B6171ebb65cCD337518
0x663d3947f03eF5B387992b880aC85940057c13e3
0x3a16c4Ae8c82ebFB0AB475bB83C4BeD1c421aAa6
0x0863Be8F0abA8890922C50A75852085A7e324bd2
```

You can check validator activity as plotted here <https://plot.ly/~TrustlinesFoundation/1/>.

*You can double click on any addresses on the right side of the graph to only show the chart for a single address.*

## Need help?

Should validators encounter any problems in setting up their nodes during the preparation period, they can get technical help by approaching Trustlines Protocol contributors in the [Gitter chat](https://gitter.im/trustlines/community) or by leaving a comment below.

## Join the community

If you're a validator or interested in the Trustlines community, we want to encourage you to [follow Trustlines Foundation on Twitter](https://twitter.com/TrustlinesFound), [join the Trustlines Network Telegram group](https://t.me/trustlines_network) or [subscribe to the Trustlines Newsletter](http://eepurl.com/gHqYyX)!

*p.p. The Trustlines Foundation*
