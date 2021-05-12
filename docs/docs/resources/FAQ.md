---
title: Frequently Asked Questions about the Trustlines Network
---

## Basics

!!! question "What's so special about Trustlines, and why use it?"
    Through the Trustlines Protocol, [Trustlines enables "People Powered Money"](https://blog.trustlines.network/people-powered-money-on-the-trustlines-protocol/) to be used by anyone anywhere.

    The Trustlines Protocol is an open-source technology stack that provides a highly usable medium of exchange. Its core idea is to provide an accounting system based on peer-to-peer credit. This is a remarkably accessible financial tool since any two people who trust each other can decide to open a credit line at any time, without typical restrictions like needing a bank account or identity documents. Credit is a powerful medium of exchange: Even if someone does not have access to the national currency (fiat money), this mutual credit could be used in its place.

    When designing a protocol for financial inclusion, it is essential to use accessible, decentralized technology. A feature of public blockchain technology is that they provide a permissionless and censorship-resistant platform. This is why Trustlines Protocol was designed to be implemented on a blockchain.

    The combination of an accessible medium of exchange and decentralized infrastructure makes Trustlines the starting point for a genuinely decentralized monetary system.

!!! question "What is a trustline?"

    A trustline can be defined as a bilateral credit/trust relationship between individual people or entities. It encompasses two credit lines (each party giving one to the other party) as well as a balance which indicates if and how much credit one party has drawn from the other.

!!! question "What is a credit line?"

    A credit line can be referred to as an (informal) agreement between two trusting users (e.g., friends), which allows one user to draw on credit given by the other. A credit line exists in the context of a currency network and, therefore, implicitly states the currency in which the accounting is done.

!!! question "What are IOUs (I Owe You)?"

    An IOU is defined as an informal acknowledgment issued in a trustline from one party to the other. An IOU reduces the amount of credit available to one party and increases the amount of credit available to the other. During a transfer, outstanding IOUs are set-off before the credit of a credit line is drawn.

!!! question "Who controls the credit (IOU) flow?"

    The two people who share a trustline control the flow of that trustline. When one person sends a payment request to another person, it is up to the receiver to accept or reject that credit.

    Your trustline credit balance can also change as a result of a [multi-hop payment](https://docs.trustlines.network/docs/resources/wp_content/how_trustlines_works.html#24-multi-hop-payment). This can happen if payments get rippled through you. This can not exceed a credit limit you have set for a trustline.

!!! question "What is a balance?"

    The balance refers to the value of an IOU within a trustline. If the value is 0, no IOU has been issued.

!!! question "What is a multi-hop payment?"

    A multi-hop payment refers to the mechanism used when multiple users in a currency network cooperate (implicitly as part of the agreement with the network) to facilitate a transfer between users that have no direct trustline agreement. The path encompasses all involved users and their trustlines. The IOU transfer is exclusively between the sender and receiver (who exchanged something of value to receive an IOU in one of their trustlines).

!!! question "What is a path?"

    A path refers to the trustlines used between the sender and receiver during a multihop payment (see multihop payment). The path encompasses all involved users and their involved trustlines.

!!! question "Can anyone issue a credit line, trustline, or create a currency network?""

    Yes.

!!! question "How do you use Trustlines?""

    Users are presumed to make use of the Trustlines Protocol (see [Trustlines Protocol](https://trustlines.foundation/protocol.html)) with an application.

!!! question "Can I change the credit I have given my friends?"

    Yes. You can update the amount of credit you want to trust your friend with at any point in time, except if your friend has already exceeded the new limit you want to set before you update it.

!!! question "Do I need to connect my bank account to my Trustlines account? / Is it planned to implement an option to transfer fiat money or crypto at some point?"

    No. The Trustlines concept uses only credit between two trusting entities, and settling balances should only happen rarely. Currently, there is no way to connect any other payment protocols to your Trustlines account, but this could change in the future. These connected accounts would only be used in the case of settling or closing trustlines.

!!! question "How do I settle a trustline with a friend?"

    1.  Agree on the conditions in the real world (e.g., your friend pays you with money for the amount of credit he's drawn, or you exchange a good or service in return for settlement)
    2.  Update the Trustline balance

!!! question "How can I be sure that I will get paid by the person I have a trustline with."

    Trustlines is based on the principle that you should only create trustlines with the people you actually know and trust. Thus there is no guarantee that you will be paid aside from your trusted relationship with a person. You can reduce the risks when setting up a credit limit. Set a maximum amount that you're willing to lend to someone. You can start with a small amount, and later you can increase the limit if needed.

!!! question "What happens if my friend won't pay me back (defaulting)?"

    Nothing will happen in the system, and you can continue using Trustlines. You may have lost some real-world value, which is why you should only give trustlines to people you trust and in amounts that you're, in the worst case, willing to lose.

!!! question "How do you close a trustline?"

    Reduce the balance of your trustline to 0. Once this is done, either party can close the trustline.

!!! question "Can friends change the credit I give them?"

    No. The person giving the credit line always sets the amount of credit they're willing to provide. Even though users can request a credit change, any change needs to be accepted by the creator/giver of the credit.

!!! question "Can the Trustlines Foundation, or any other entity, close my trustlines, block or delete my account?"

    This would depend on the currency network you had created the trustline in. All currency networks that the Trustlines Foundation would initially deploy are set up in a way that no other entity can close, block, or delete a user. Signing any transaction requires access to your private key, which nobody should have access to besides you. Please be sure that any application you use to interact with the Trustlines Blockchain does not give access to your private key to any third party.

!!! question "Can I leave currency networks?"

    Yes. To leave, you need to close (see close) all your trustlines.

## General

!!! question "What is the Trustlines Network?"

    The Trustlines Network is an ecosystem of individuals, projects, and entities aligned on the idea of mapping trust-based relationships on to trustless infrastructure. No single entity owns, is, or can be in charge of this construct.

!!! question "What's the difference between Trustlines Network and Trustlines Protocol?"

    The Trustlines Network aims to promote the financial and economic inclusion of all people through decentralized and open-source systems. It consists of all the people, organizations, and other entities, participating in creating and using the Trustlines Network ecosystem.

    The Trustlines Protocol represents a set of rules, processes, and definitions forged into deployable code, enabling the mapping of trust-based relationships onto trustless infrastructure. Read more about the protocol [here](wp_content/how_trustlines_works.md#4-trustlines-protocol-technology-stack-1).

!!! question "What problem are you solving?"

    The Trustlines Foundation is the promoting financial and economic inclusion of all people through decentralized peer-to-peer network protocols that serve common accounting.

!!! question "How transparent is Trustlines?"

    A significant level of transparency is achieved by using a public blockchain as a part of the Trustlines Protocol. Every address on the Trustlines Blockchain is a pseudo-anonymous as it is not linked to any other identity. Still, since every transaction on the blockchain is public, the address's history is always transparently visible to everyone. This means that if someone knows your address, they can view your transaction history. This allows full transparency and balance keeping of all addresses but cannot provide wholesome anonymity.

!!! question "Do you have a whitepaper?"

    We have some [whitepaper content](wp_content/abstract) here at the Trustlines Docs.

!!! question "When will all of this be live?"

    The Trustlines Blockchain went live on November 21st. You can read more about the launch in the [Launching the Trustlines Blockchain blog post](https://blog.trustlines.network/t-x-launching-the-trustlines-blockchain).

    A blockchain explorer for the Trustlines Blockchain can be found at <https://explore.tlbc.trustlines.foundation/>.

## Currency Networks

!!! question "What is a currency network?"

    The Trustlines currency networks are the fundamental infrastructure of the Trustlines functionalities and are implemented on-chain. This contract type is the core smart contract that end users can interact with. The contract records all properties a currency network has (e.g., symbol, name of currency network, and fee structure) and account information (e.g., users - blockchain addresses, balances, and trustlines). Trustlines are modeled as "accounts" within the currency networks and keep a record of the credit lines two parties have agreed upon as well as their current balance.

!!! question "Are transfers of currency network IOUs and transfers of collateralized tokens (e.g., Bitcoin) the same?"

    No. Collateralized tokens such as Bitcoin or Trustlines Network Coins (TLC) are backed by certain collateral such as hashing power (in the case of Bitcoin) or stake (in the case of TLC). Currency networks inherit their values from the trust that exists between the individual users on the network.

!!! question "Is it possible to use multiple currencies in one trustline?"

    No. A single trustline represents one denomination of credit between two people. It is possible to create multiple trustlines with the same person using numerous currency networks. Still, they each require a single trustline for balance keeping.

!!! question "How do I join a currency network?"

    To join a currency network, you need to send a Trustlines request to another person that is also using the Trustlines Blockchain.

!!! question "How do I create a currency network?"

    Follow the specification for currency network smart contracts on our [GitHub](https://github.com/trustlines-protocol).

!!! question "Is it possible to make a currency network with interests set on trustlines?"

    Yes, if this is enabled in the smart contract that defines the currency network, users can add interest rates on a trustline. This would allow the issuer of the IOU to increase his or her credit limit at the cost of an added interest fee.

!!! question "Is it possible to make a currency network with a limit on the no. of users that can join?"

    Yes, though, this must be defined in the currency network smart contract.

!!! question "With no governance such as central banks or government, how can monetary policy be enforced?"

    Smart contracts define the monetary policy of the currency network. A currency network creator can specify many conditions such as

    -   the maximum number of trustlines that a user can have
    -   the maximum value that a trustline can have
    -   whether interest can be added
    -   whether joining the network is open or permissioned/closed

## Relay Servers

!!! question "What are relay servers?"

    The relay servers are an optional bridge between client applications and the Trustlines Blockchain. They offer services that are not feasible to be implemented on-chain or within the client apps. They are a back-end service that implements main features to connect the users to the smart contract system:

    -   Forwarding user signed transactions from a mobile app to the Trustlines Blockchain
    -   Indexing and storing event information
    -   Sending relevant blockchain events (including push notifications) to the mobile app
    -   Discovering a path between the sender and receiver in the graph of trustlines by using [Dijkstra's Algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm), considering the shortest path in a number of hops.

    Users do not need to trust relay servers with their accounts (private keys), as transactions are signed locally on their device and validated by the currency networks on the Trustlines Blockchain.

!!! question "What are the requirements for running a Relay Server?"

    You can find the specifications needed to run a relay server on our [GitHub relay repository](https://github.com/trustlines-protocol/relay).

!!! question "Do users need to use a path that is calculated by a relay server, or are there alternatives?"

    It is possible to calculate and specify your own path or even use your own relay server. However, most users might prefer not to do so.

!!! question "How do relay servers collect topology for the pathfinding process?"

    If the relay server uses the code which is provided by the Trustlines Foundation via [GitHub](https://github.com/trustlines-protocol/relay), it will use Dijkstra's algorithm to find the shortest path between the sender and receiver.

## Blockchain

!!! question "Why are you using a blockchain?"

    Our design decision was to build the Trustlines Network as a decentralized P2P system. A blockchain is a natural fit for such a system because it is good at tamper-proof accounting, can, with the right design, provide censorship resistance, and allows for decentralized governance of the system.

!!! question "How does the sidechain work?"

    The Trustlines Blockchain will be a minimal viable Proof-of-Stake (mPoS) [Ethereum](https://ethereum.org/) sidechain based on [Parity's Aura consensus algorithm](https://wiki.parity.io/Aura). Aura (known from Kovan, poa.network, xDAI, and others) is usually used in Proof of Authority chains. We added the following features:

    1.  Anonymous validators
    2.  Staking and slashing mechanisms to combat equivocation
    3.  Hard forking as an additional defense mechanism

!!! question "How's the Trustlines Blockchain different from Delegated Proof of Stake?"

    Validator slots cannot be delegated; hence the Trustlines Blockchain does not support dPoS. Also, dPoS typically relies on social reputation systems, which is not the case for our approach.

## Validators

!!! question "What is a Trustlines validator?"

    A Trustlines validator is a person or entity that has won a slot in the validator auction and is part of the active validator set of the Trustlines Blockchain. Initially, the Trustlines Blockchain will have a maximum of 55 validator slots, which will have one Trustlines validator per slot. The number of validators and validator slots may increase or decrease in the future according to what the Trustlines community decides.

    The validators have the responsibility of ensuring the security of the Trustlines Blockchain by validating transactions and adding blocks to the existing blockchain. They earn Trustlines Network Coins in the form of transaction fees and block rewards in this process. Additionally, Trustlines validators monitor the Trustlines bridge to ensure Trustlines Network Token to Trustlines Network Coin transfers and decide on blockchain forks and resulting protocol changes with the rest of the Trustlines ecosystem. To ensure that a Trustlines validator is able to fulfill their role, we suggest that a validator should meet the following criteria:

    -   Be technologically minded and able to run a Trustlines Blockchain node without a dedicated UI
    -   Have the necessary financial means to take part in the validator auction
    -   Understand the operational and legal risks associated with this activity
    -   Understand the responsibilities of being a Trustlines validator

    !!! question "What are the requirements for becoming a Trustlines validator?

    1.  Sign up with us to be a part of the Validator candidate set
    2.  You'll get an email with more info and how to provide your Ethereum address to an independent third party
    3.  You'll be whitelisted to take part in the validator auction
    4.  Bid to stake TLN in the validator auction
    5.  If you have secured a validator slot, you can run the Trustlines Blockchain node to validate and earn TLC.

!!! question "Why do you need my email and name if validators are anonymous?"

    The Trustlines Foundation uses your email to notify you where you can whitelist an Ehereum address so that you may bid at the validator auction. Note that you do not need to use a personal email for this process and that the email addresses will be deleted afterward. We welcome that you use a throwaway email (see [google throwaway email](https://www.google.com/search?q=throwaway+email)), but note that the time at which you add your email and receive an email from the Trustlines Foundation can vary greatly (up to 9 months depending on when the next validator auction starts). Therefore, consider using an email you can access at a later point in time.

!!! question "How many Trustlines Network Coins will I earn?"

    The initial block reward will be 3 TLC. Transaction fees added to the block vary.

!!! question "I'm not good at checking my email; how do I keep up?"

    You can follow [Trustlines Foundation on Twitter](https://twitter.com/TrustlinesFound), subscribe to the [Trustlines Blog](https://trustlines.network/) or join the [Trustlines Forum](https://forum.trustlines.network/) for more updates!

!!! question "I won a slot at the auction, and I'm a Trustlines validator. What now?"

    -   Run a validator node\\
        Now you need to launch a Trustlines validator node. If you're unsure how to do this, start by familiarizing yourself with the process by watching the [How to Install a Trustlines Node for Laika Testnet video](https://youtu.be/ozB--QRiPvw). You can find the full [documentation](https://dev.trustlines.network/docs/blockchain/tlbc.html#setup-with-the-quickstart-script) at the [Trustlines Developer Docs](https://dev.trustlines.network).
    -   Participate in governance\\
        The Trustlines Foundation currently announces proposed forks on [the Trustlines Forum](https://forum.trustlines.network/), which you will need to familiarize yourself with. You can discuss the proposed forks and other governance topics on the Trustlines subreddit or any other forum that validators wish to use.

!!! question "What happens after nine months?"

    Once the nine months have passed, validators can withdraw their stake provided it didn't get slashed due to equivocation. A new auction will be announced to find the next set of validator candidates.

!!! question "How technically savvy should I be to run a Trustlines node?"

    You should know how to install a node and patch software updates regularly via your terminal.

!!! question "What happens if I win a slot, but I don't run a Trustlines node?"

    You will fail to propose any blocks and will subsequently not earn any Trustlines Network Coins (TLC). After some time of inactivity, active validators would most likely propose a fork that would remove you from the validator set. Keep in mind that this will not negatively affect your TLN staked on Ethereum. It does mean that the staked amount will still remain locked until the end of the validation period.

!!! question "What happens if I won a slot, but the Trustlines Protocol fails/people lose interest?"

    After the nine months have passed, you will still be able to reclaim your initial stake. Any other resources invested, such as paying for server uptime, will be your costs to bear, and you will not be able to ask for compensation. Please see the [Terms and Conditions](https://trustlines.foundation/terms-conditions.html) for details.

## Auction

!!! question "What is the Trustlines validator auction?"

    The Trustlines validator auction is a Dutch auction held to discover the fair opportunity cost value, i.e., price of a validator slot. The Ethereum addresses of successful bidders in a successful auction will be included in the validator set.

    Acceptable tokens for a bid: The auction is a smart contract on the Ethereum mainchain. Note that the smart contract will not accept any other tokens than TLN as a bid.

    Participation: To be able to participate in the auction, your Ethereum address must have been whitelisted by the Trustlines Foundation prior to the start of the auction. Every whitelisted Ethereum address can participate in the auction only once.

    Timing: The auction ends at the earliest of two full calendar weeks starting from the start date or when the maximum threshold of bids is reached. Whichever comes first.

    Threshold: If less than the amount of minimum threshold of bids have been received at the time the auction ends, it will fail. No validator slots will be awarded, and all participants can withdraw their bids.

    Limited validator slots: Each nine month validator period has a limited amount validator slots available through an auction.

!!! question "How can I whitelist my Eth address to participate in the auction?"

    Offline: To sign up offline, meet the Trustlines team in person at a meetup or conference. Follow us on [Twitter](https://twitter.com/TrustlinesFound) to see when and where the next possibilities to sign up occur.

    Online: Use [Proof-of-Sociability](https://blog.trustlines.network/become-a-trustlines-validator-candidate-using-proof-of-sociality). Send a DM with your email address to [@tl_validator](https://twitter.com/tl_validator) on Twitter.

!!! question "Why should I be a Trustlines validator?"

    The Trustlines Blockchain is a minimal viable Proof of Stake sidechain to Ethereum and is governed by a greenfield governance model. In this experimental consensus model, validators can gain technical and governance experience.

    Besides the technical validator capabilities mentioned above, validators will also receive block rewards (as to be defined within the chain spec, currently 3 TLC per block) in the form of Trustlines Network Coins. This only applies under the condition that they actively run their validator node and take part in block creation. They will also be in a position to charge transaction fees for transactions that are included within the blocks a validator creates.

    Note that receiving block rewards and transaction fees is dependent on a community of emerging validators and the potential users of the Trustlines Blockchain. The Trustlines Foundation cannot guarantee that a Trustlines Blockchain, including the chain spec as proposed by the Trustlines Foundation, actually emerges out of the actions of these third party stakeholders. Hence, participating in the auction and thereby agreeing to the [Terms and Conditions](https://trustlines.foundation/terms-conditions.html) does not entail a right or an entitlement in any way whatsoever to either becoming and/or remaining a validator or receiving block rewards and/or transaction fees.

!!! question "What happens when the auction ends?"

    The slot price is defined as the last successful bid. This amount will be locked as your stake for nine months. Consequently, you will need to start your Trustlines Blockchain node with validator rights and begin proposing blocks. Any amount you bid above the final slot price can be withdrawn once the auction smart contract is set in a withdrawal state. Please see the [auction page](https://trustlines.foundation/auction.html) for further details.

!!! question "What are the risks of bidding at the auction?"

    By participating in the auction, you expressly acknowledge and assume the following risks:

    -   Risk​ ​of​ ​losing​ a validator slot, TLN bid, or stake​ due​ ​to​ ​loss​ ​of​ private​ ​key(s);
    -   Risks​ ​associated​ ​with​ ​the​ ​Ethereum​ blockchain: any malfunction, breakdown, or abandonment of the Ethereum blockchain may have a material adverse effect on the smart contracts;
    -   Risk​ ​of​ ​mining​ ​attacks: the auction smart contract is susceptible to attacks by miners in the course of validating bids on the Ethereum blockchain, including, but not limited to, double-spend attacks, majority mining power attacks, and selfish-mining attacks. Any successful attacks present a risk to the auction including, but not limited to, accurate execution and recording of bids;
    -   Risk​ ​of​ ​hacking​ ​and​ ​security​ ​weaknesses: hackers or other malicious groups or organizations may attempt to interfere with the auction in a variety of ways, including, but not limited to, malware attacks, denial of service attacks, consensus-based attacks, sybil attacks, smurfing, and spoofing;
    -   Risk​ ​of​ ​uninsured​ ​losses: unlike bank accounts or accounts at financial institutions, the TLN held by the auction smart contract is uninsured unless you specifically obtain private insurance to insure them. Thus, in the event of loss or loss of utility value, there is no public insurer or private insurance arranged by the Trustlines Foundation to offer recourse to you;
    -   Risks​ ​associated​ ​with​ ​uncertain​ ​regulations​ ​and​ ​enforcement​ ​actions: the regulatory status of, including, but not limited to, the auction, the validator slots, and distributed ledger technology is unclear or unsettled in many jurisdictions. It is difficult to predict how or whether regulatory agencies may apply existing regulation with respect to such technology and its applications. It is likewise difficult to predict how or whether legislatures or regulatory agencies may implement changes to law and regulations affecting distributed ledger technology and its applications, including but not limited to the auction and the validator slots. Regulatory actions could negatively impact the whole Trustlines Protocol in various ways, including, for purposes of illustration only, that some or all of the parties involved in the Trustlines Protocol, in general, might require licensing or is subject to existing legislation;
    -   Risks​ ​arising​ ​from​ ​taxation; the tax characterization of acquiring a validator slot and/or acting as a validator is uncertain. You must seek your own tax advice in connection with your partaking in the auction, which may result in adverse tax consequences to you, including withholding taxes, income taxes, and tax reporting requirements.
    -   Unanticipated​ ​risks: blockchain technology and the Trustlines Protocol are new and untested technology. In addition to the risks referred to above, there are other risks associated with your partaking in the Trustlines auction, including unanticipated risks. Such risks may further materialize as unanticipated variations or combinations of the risks previously referred to.

## Tokens

!!! question "Are you going to do an ICO?"

    Trustlines Network Tokens are being distributed via a Merkle Drop to a wide range of recipients (see the [Merkle Drop Launch blog post](https://blog.trustlines.network/merkle-drop-launch/) for more details). We will also consider other distribution models in the future.

!!! question "What will the block reward be?"

    The initial block reward of the Trustlines Blockchain will be 3 Trustlines Network Coins (TLC) per block.

!!! question "Does Trustlines have tokens on Ethereum?"

    Yes. The Trustlines Network Token (TLN) is an ERC20 token on the [Ethereum](https://ethereum.org/) mainchain.

!!! question "Do new users need to buy the Trustlines Network Token in order to join the Trustlines Blockchain?"

    New users can choose to

    1.  Use existing delegate services to pay transaction fees for them. The delegate services use the logic of meta transactions so that users do not need to pay for transactions in Trustlines Network Coins but can agree on other payments with the person or entity running such delegate services.
    2.  Buy TLC on the market.
    3.  Buy TLN on the market and transfer them to the Trustlines Blockchain.

!!! question "Who will receive tokens in the Merkle Drop?"

    The Merkle drop aims to reach a broad audience covering early contributors, testers, developers, potential stakeholders, and, more generally, a wide audience from the crypto and community currency ecosystems. For the accessibility of Trustlines Network Tokens, the Foundation emphasized eligibility in groups that it sees as aligned with its mission.

    See the [Merkle Drop Launch blog post](https://blog.trustlines.network/merkle-drop-launch/) for more details.

## Use cases and cooperation

!!! question "What is Trustlines People-Powered Money (PPM)?"

    The Trustlines Network supports the creation of blockchain-based p2p currency networks. In dense societal networks and due to the transitive nature of financial relationships, one could imagine a plethora of financial use cases that employ these networks. Chief among them would be the ability to engage in economic transactions that could be viewed as a substitute for general payments of all kinds. This twist, i.e., the transition from a credit registry towards a system that could be used to facilitate payment-like transactions, is comparable to the principles of [LETS-systems](https://en.wikipedia.org/wiki/Local_exchange_trading_system) or, for example, the unofficial financial network ["Hawala."](https://en.wikipedia.org/wiki/Hawala)

    Read more in our [People Powered Money on the Trustlines Protocol blog post](https://blog.trustlines.network/people-powered-money-on-the-trustlines-protocol).

!!! question "Which other use cases are there?"

    The [Trustlines Protocol](https://trustlines.foundation/protocol.html) is open-source and may be used to develop any use case by anyone. To be supported by the Trustlines Foundation, the use case must align with the Foundation's mission.

    Currently, some examples include [Bill splitting](../../use_cases/bill_splitting/bill_splitting_on_trustlines) and [Time Credits](../../use_cases/time_credits/time_credits_on_trustlines) with more to follow.

!!! question "I'm a fan of Trustlines; how can I contribute?"

    [Follow the Trustlines Foundation on Twitter](https://twitter.com/TrustlinesFound), [subscribe to the Trustlines Blog](https://blog.trustlines.network/subscribe), or [join the Trustlines Forum](https://forum.trustlines.network/) to stay updated with the latest news. You can also sign up to be a Trustlines validator candidate, contribute to the code on [GitHub](https://github.com/trustlines-protocol), or take part in governance discussions.

!!! question "I'm building a dapp and want to integrate the Trustlines Protocol. Where do I start?"

    That's great! Feel free to let us know by [reaching out to us](mailto:info@trustlines.foundation). You can also start by going to the [Trustlines Protocol Github](https://github.com/trustlines-protocol) and read any relevant documentation. You can ask any technical questions at the [Trustlines Forum](https://forum.trustlines.network/c/protocol/5) or on [Gitter](https://gitter.im/trustlines/).

## Organizational

!!! question "What is the Trustlines Foundation's role?"

    The Trustlines Foundation is supporting research, development, deployment, governance, and adoption of complementary currency systems, with a focus on open-source protocols designed to be utilized by decentralized p2p currency network designs.

!!! question "Is there a trademark on Trustlines?"

    "Trustlines" and "Trustlines Network" are registered trademarks that are owned by the Trustlines Foundation. The purpose of the registration is to protect the usage of the terms "Trustlines" and "Trustlines Network" from inappropriate or malicious use. You can find the [Trustlines Trademark Guidelines](../../foundation/trademarks) here in the Docs with information on how a party may use the "Trustlines" and "Trustlines Network" trademarks.
