---
layout: page
title: How to withdraw your validator deposit
subtitle: Version 1.0
---

Validators are able to withdraw their deposits after the locking period ends.

## Checking that the locking period has ended
To withdraw your deposit from the contract, you will need to interact with the `DepositLocker` contract. The contract address on Ethereum is [0xd56a61ad1b16f1f0326785902593c7adbf733e34](https://etherscan.io/address/0xd56a61ad1b16f1f0326785902593c7adbf733e34).

Make sure the deposits are unlocked by checking that the `releaseTimestamp` has passed. To do this on the contract page, click on `contract`.

<center><a class="vdw_a" href="../../assets/images/validator_deposit_withdraw/validator_deposit01.png"><img class="vdw_img" src="../../assets/images/validator_deposit_withdraw/validator_deposit01.png"></a></center>

Continue to click on `read contract`.

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
