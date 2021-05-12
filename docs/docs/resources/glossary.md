---
layout: page
title: Trustlines Glossary
---

## General

!!! info "A trustline / multiple trustlines"

    A trustline can be defined as a bilateral credit/trust relationship between individual people or entities. It encompasses two credit lines (each party giving one to the other party) as well as a balance which indicates if and how much credit one party has drawn from the other.

!!! info "Credit line"

    An (informal) agreement between two trusting users (e.g., friends) that allows one user to draw on credit given by the other. A credit line exists in the context of a currency network and, therefore, implicitly states the currency in which the accounting is done.

!!! info "IOU (I Owe You)"

    An informal acknowledgment issued in a trustline from one party to the other. An IOU reduces the amount of credit available to one party and increases the amount of credit available to the other. During a transfer, outstanding IOUs are set-off before the credit of a credit line is drawn.

!!! info "Multi-hop payment (rippling)"

    A multi-hop payment refers to the mechanism used when multiple users in a currency network cooperate (implicitly as part of the agreement with the network) to facilitate a transfer between users that have no direct trustline agreement. The path encompasses all involved users and their trustlines. The IOU transfer is exclusively between the sender and receiver (who exchanged something of value to receive an IOU in one of their trustlines).

!!! info "Trustline balance"

    The trustline balance accounts for what two parties to a trustline agreement owe each other. The party with a negative balance issued the IOU, whereas the party with the positive balance received the IOU. If the value is 0, no IOU has been issued.

!!! info "Network of trustlines"

    The actual network topology created by all actors using a deployed instance of the Trustlines Protocol is referred to as a network of trustlines. Such a network of trustlines is also sometimes referred to as A trustlines network, and should not be confused with THE Trustlines Network ecosystem.

!!! info "Trustlines validator"

    A Trustlines validator is a person or entity that is part of the active validator set of the Trustlines Blockchain. The validators have the responsibility of ensuring the security of the Trustlines Blockchain by validating transactions and adding blocks to the existing blockchain. Additionally, Trustlines validators monitor the Trustlines bridge to ensure a Trustlines Network Token to Trustlines Network Coin transfer and decide on blockchain forks and resulting protocol changes with the rest of the  Trustlines ecosystem.

!!! info "Trustlines delegate"

    A Trustlines delegate is a person or entity that uses identity contracts to enable the feature that users do not have to pay for their transaction costs in the Trustlines native coin (Trustlines Network Coin) but instead can let the person who is running a delegate service pay for their transactions in return for a fee in another form. This can be used by, e.g., businesses that want to create specific use cases in which they pay for the transactions of their customers or third parties that want to encourage users to use the Trustlines Blockchain without them needing to deal with the transaction cost.

!!! info "Merkle drop"

    A smart contract deployed on the Ethereum blockchain that contains a list of addresses and claimable Trustlines Network Tokens per address in the form of a Merkle root. People can provide a Merkle proof to this contract and withdraw tokens they are entitled to. The Trustlines Foundation has a web service that allows people to either claim their tokens via a web3 integration (e.g., Metamask) or calculate the needed proof.

## Technical terms

!!! note "Currency network"

    The currency networks form the basis of the Trustlines functionalities and are implemented on-chain. This contract type is the core smart contract that end users can interact with. The contract records all properties a currency network has (e.g., symbol, name of currency network and fee structure) and account information (e.g., users - blockchain addresses, balances, and trustlines). Trustlines are modeled as "accounts" within the currency networks and keep a record of the credit lines two parties have agreed upon as well as their current balance.

!!! note "Relay server"

    The relay servers are an optional bridge between client apps and the Trustlines Blockchain. They offer services that are not feasible to be implemented on-chain or within the client apps. Relay servers calculate optimal paths and relay transactions.

!!! note "Bridge"

    A unidirectional bridge between the Ethereum blockchain and the Trustlines Blockchain operated by the Trustlines validators. It allows Trustlines Network Token holders to transfer these tokens to the Trustlines Blockchain in return for Trustlines Network Coins.

## Tokens

!!! abstract "Trustlines Network Coin (TLC)"

    Similar to the Ethereum chain, the Trustlines Blockchain requires transaction fees to be paid in a cryptocurrency native to the blockchain. These tokens will be called Trustlines Network Coins - TLC.

!!! abstract "Trustlines Network Token (TLN)"

    TLN are ERC20 tokens on the Ethereum chain, which can be converted to TLC by sending them to the Trustlines Blockchain bridge.
