---
layout: page
title: How to withdraw your validator deposit
subtitle: Version 2.0
---

Validators are able to withdraw their deposits after the locking period ends. This guide will walk you through how to withdraw the staked tokens.

_**Note**: Those who bid on an auction, can withdraw their excess from the bids after the auction closes. In the Dutch auction format used, the last bid is the final price for all participants. Due to this format, all bids before the last one will have excess to withdraw. At the bottom of the page you will find the details for the auction contracts._

## Details for the DepositLocker contracts

To withdraw your deposit from the contract, you will need to interact with the `DepositLocker` contract. The contract addresses on Ethereum are

| Auction number | Validator period | Stake unlocked | DepositLocker address | Staked token |
|:---:|:---:|:---:|:---:|:---:|
| 1 | November 2019 to July 2020 | 8th of July, 2020 | [0xD56a61aD1b16F1F0326785902593C7Adbf733E34](https://etherscan.io/address/0xD56a61aD1b16F1F0326785902593C7Adbf733E34) | ETH |
| 2 | July 2020 to March 2021 | 23rd of March, 2021 | [0x3f52Cb880B534D57F3C925F2bbB6b2750E2f415A](https://etherscan.io/address/0x3f52Cb880B534D57F3C925F2bbB6b2750E2f415A) | TLN |
| 3 | March 2021 to December 2021 | 17th of December, 2021 | [0x1FBeB7273E32dCE3Cf1eCe3D02f393E21d90BB46](https://etherscan.io/address/0x1FBeB7273E32dCE3Cf1eCe3D02f393E21d90BB46) | TLN |

___

## Checking that the locking period has ended

Make sure the deposits are unlocked by checking that the `releaseTimestamp` has passed. To do this on the contract page, click on `contract`.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit01.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit01.png"></a></center>

Continue to click on `Read contract`.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit02.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit02.png"></a></center>

You can find out the current **Unix timestamp** using a search engine of your choice.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit03.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit03.png"></a></center>

## Verifying that your address can withdraw from the contract
You will need to use the same address to withdraw that you used to bid.
To verify your address, you can use the third field, `canWithdraw`.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit04.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit04.png"></a></center>

Enter your address in the field and click `Query`. You will see `bool: true` if you are able to withdraw, or `bool: false` if not.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit05.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit05.png"></a></center>

### Withdrawing using MetaMask
Once you have verified that you’re entitled to withdraw, log-in to your MetaMask account. You should make sure you have the `Main Ethereum Network` network selected.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit06.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit06.png"></a></center>

Click on Write Contract, then, `Connect to Web3`. This will allow Etherscan to connect to MetaMask.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit07.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit07.png"></a></center>

For the actual withdrawal, click on `Write` under `2. withdraw`. MetaMask will then ask you to sign a transaction. The transaction should require less than 30k gas.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit08.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit08.png"></a></center>

Once this transaction is confirmed, you should receive your deposit back.

___

## Details for the auction contracts

If an auction is successful, the last bid's price is defined as the "slot price." In the Dutch auction format used, the last bid is the final price for all participants. Due to this format, all bids before the last one will have excess to withdraw. Every participant can withdraw the difference between the slot price and their bid by calling the `withdraw` function.

| Auction number | Auction period | Auction contract address | Staked token |
|:---:|:---:|:---:|:---:|:---:|
| 1 | 8th of October, 2019 to 22nd of October, 2019 | [0x7255E01F934307FfB7a41FC78B6b1688f5dc6845](https://etherscan.io/address/0x7255E01F934307FfB7a41FC78B6b1688f5dc6845) | ETH |
| 2 | 9th of June, 2020 to 23rd of June, 2020 | [0xED0FA720D4150F7b1572b68d1f8C708ddf9da5B7](https://etherscan.io/address/0xED0FA720D4150F7b1572b68d1f8C708ddf9da5B7) | TLN |
| 3 | 2nd of March, 2021 to 16th of March, 2021 | [0xCDB34843978684f8DD39B3eDE59e73Bf49d3FBf4](https://etherscan.io/address/0xCDB34843978684f8DD39B3eDE59e73Bf49d3FBf4) | TLN |

___

<div id="prev_next">
<div class="prev"><a href="../guides/tl_app_user_guide" class="prev_next_text">Previous</a></div>
<div class="prev"><a href="../guides/tl_app_user_guide" class="icon fas fa-arrow-left prev_next"></a><br></div>
<div class="prev"><a href="../guides/tl_app_user_guide" class="prev_next_text">User guide for Trustlines App</a></div>
</div>
<div id="prev_next">
<div><a href="how_to_claim_tln" class="prev_next_text">Next</a></div>
<div><a href="how_to_claim_tln" class="icon fas fa-arrow-right prev_next"></a><br></div>
<div><a href="how_to_claim_tln" class="prev_next_text">How to claim TLN</a></div>
</div>
