---
layout: posts
title:  "Update #4 - Try new quickstart script & test the Görli <> Laika bridge"
excerpt_separator: <!--more-->
categories: [Trustlines Laika Testnet]
---

Dear Laika testnet validators!

A new update is available for validators that use the quickstart script to set up their validator node. The script can be found at quickstart.laika.trustlines.foundation or downloaded and executed in one line with bash <!--more-->`<(curl -L` [`quickstart.laika.trustlines.foundation`](https://quickstart.laika.trustlines.foundation/)`)`. If you run `bash <(curl -L quickstart.laika.trustlines.foundation)`, you should run it in the same place you ran the previous quickstart script.

The main goal of this update is to collect feedback on the new version of the quickstart script before it is used by validators for the Trustlines Blockchain (mainnet).

The second goal of this update is to test the bridge as it will be deployed on the Trustlines Blockchain. To do this, a foreign bridge contract was deployed on the Görli testnet at address: `0x22bb53a8dc4ebefe66451e0b65878afe8aa13b29` bridging the token at address: `0xc59636130365C6723e760Dd55436BE54495c6133` to the Laika testnet coin.

The corresponding home bridge contract on Laika was deployed at address `0x7eeb97f2e1d3278813d4f134226346c722126be3`.

Validators are thus encouraged to run the bridge-client when prompted by the new quickstart script.

Please note: It is not mandatory for validators to use the new quickstart script to keep on validating blocks on Laika. Running the bridge requires either access to a JSON RPC for the Görli chain or to run a Görli light node. In case you do not have access to a Görli node, the quickstart script will set one up for you, which could increase the hardware requirements for validators. If you decide to run a light node in addition to the required validator services, we recommended having at least 2GB of available memory on your machine.

Note also that the quickstart script will now automatically start the tlbc-monitor service, monitoring the Laika testnet and producing reports for inactive or equivocating validators.

Bridged token on Görli: <https://goerli.etherscan.io/address/0xc59636130365c6723e760dd55436be54495c6133#code>

Foreign bridge on Görli: <https://goerli.etherscan.io/address/0x22bb53a8dc4ebefe66451e0b65878afe8aa13b29>

Home bridge on Laika: <https://explore.laika.trustlines.foundation/address/0x7eeb97f2e1d3278813d4f134226346c722126be3/transactions>

You can get in touch with the Trustlines Protocol contributors, ask any technical question or tell us about problems you encounter on [Gitter](https://gitter.im/trustlines/community) or by leaving a comment below.
