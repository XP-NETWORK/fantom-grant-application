Please make sure to submit your grant application as an issue

# XP.network NFT Multi-Chain Bridge

## Project Description

- The first of the kind [NFT multi-chain bridge](https://bridge.xp.network/) connecting a wide range of EVM to a number of Non-EVM chains. At the moment of writing, the bridge allows transferring NFTs to and from:
  - Ethereum
  - Binance Smart Chain
  - Avalanche
  - Polygon
  - Algorand (non-EVM)
  - Tron  (semi-EVM)
  - Elrond  (non-EVM)
  - Tezos  (non-EVM)
  - Velas
  - IoTeX
  - xDai
  - Aurora
  - Fuse

## Problem / Solution
Fantom is becoming an important player in the blockchain industry. But much more importantly, Fantom is developing a rich NFT ecosystem populated with professionally developed Marketplaces, promising NFT projects and talented content providers.<br/>
However, they will all be detached from the global NFT market and will require a gateway for their assets for entering and exiting the blockchain. `XP Network NFT Bridge` is the Silk Road or the `Spice trade route` of today's NFT industry. We connect the otherwise isolated markets whose potential is limited to the insular communities of individual chains.<br/>
The bridge makes cross-chain marketplaces, NFT oriented games and defi projects possible. It integrates Fantom to the global NFT ecosystem openning it for otherwise impossible possibilites of development and growth.


## Detailed product description
Our groundbreaking technology has several advantages. We support a wide range of EVM and Non-EVM protocols at once
- The intuitive interface of the applications ensures a pleasant user experience
- We have developed a cross-chain NFT listing tool
- Our JavaScript API library allows partnered dApps to use our instruments from any programming language behind the scenes (TypeScript, Python, C#, Java, C++, Swift, etc.)
- We work with multiple token standards and conveniently convert one standard to another while transferring assets across networks.
- We allow our users to select the tokens they want to pay the transaction fees with, taking the burden of currency conversion.
- We support transfers in batches to save on transaction fees.
- We have set up a layered security system around our solutions to provide maximal protection of the assets of our users.
- We allow transferring NFTs with the smart contract logic they had in the original chain.


## Go-to-Market plan
The bridge has been built to satisfy the needs of different groups of users on Fantom. Therefore, it consists of several components.

The Bridge **User Interface** is available at https://bridge.xp.network. It is designed for non-coding users such as NFT owners, traders, investors, collectors, and artistic content creators.

The bridge **JavaScript library** available at https://www.npmjs.com/package/xp.network can be utilized by:

1. **The cross-chain games** with teams of players spread across the blockchains whose raging armies of militant invaders or peaceful treasure hunters and gold miners can travel from one blockchain to another, either gaining value or getting annihilated by superior forces of the aborigen inhabitants. 

2. **Cross-chain marketplaces** save hundreds of thousands of dollars and developer-hours by using the ever-growing library allowing the users to buy Solana NFTs from Elrond and pay for the assets and the transaction fees with a currency of the customer's choice.

3. **NFT Projects** preferring global over local presence expose the freshly minted collections with groundbreaking logic or breathtaking design to tens or, eventually, hundreds of communities at once enjoying previously unprecedented demand and sales volumes.

The bridge **REST API** service supports developers in Python, Java, C#, C++, or any other programming languages to use the functionality of the bridge by calling POST requests with the function call parameters stored in the body of the requests. In return, the service returns valid for the chain of interest but unsigned transactions the users can sign and submit from the application of the third parties.


## Value capture for Fantom ecosystem

`XP Network NFT Bridge` is the only NFT gateway for several chains (Elrond, Algorand, Tezos, Velas, Fuse) and by keeping integrating more and more chains we're becoming a one stop solution for the global NFT ecosystem.

In order for wrapped NFTs to be treated as "native" on foreign chains they must be minted according to the standard of the target chains. The bridge converts Native NFTs of the chain of departure to the following standards on the chain of destination:
1. ERC-721/BEP-721/TRC-721/HRC-721 in the EVM compatible blockchains
2. ERC-1155/BEP-1155/TRC-1155/HRC-1155 in the EVM compatible blockchains
3. ESDT for Elrond
4. ASA-003 for Algorand
5. FA2 for Tezos

## Team members
[XP Network Team](https://xp.network/team/)

- [Dima Briukhanov](https://github.com/dima-brook) CTO
- [Rupansh Sekar](https://github.com/rupansh) Blockchain Developer
- [Sumit Kumar](https://github.com/imsk17) Blockchain Developer
- [Xueming Zheng](https://github.com/rocalex) Blockchain Developer
- [Yura Dukhno](https://github.com/YuraDQuigon) Front-End Developer
- [Alexey Adoniev](https://github.com/AlexeyAdoniev) FullStack Developer

## Team Website	
- [XP Network Website](https://xp.network/)

## Team's experience
The currently functioning [NFT Bridge](https://bridge.xp.network/) is a living example of the team's maturity and readiness for integrating Nervous to the global NFT family.

Our teams has already bridged 10+ chains. For many chains our bridge is the only one allowing to transfer NFTs:
  - Ethereum
  - Binance Smart Chain
  - Avalanche `(No other NFT bridge, but XP Network)`
  - Polygon
  - Algorand `(No other NFT bridge, but XP Network)`
  - Tezos `(No other NFT bridge, but XP Network)`
  - Tron `(No other NFT bridge, but XP Network)`
  - Elrond `(No other NFT bridge, but XP Network)`
  - IoTeX `(No other NFT bridge, but XP Network)`
  - Velas `(No other NFT bridge, but XP Network)`
  - xDai `(No other NFT bridge, but XP Network)`
  - Fuse `(No other NFT bridge, but XP Network)`

## Team Code Repos
- [XP Network GitHub repository](https://github.com/XP-NETWORK)
- [XP Network Brige JavaScrip library](https://github.com/XP-NETWORK/xpjs)
- [The Bridge Interface](https://github.com/XP-NETWORK/bridge-interface)
- [Smart Contracts Audits](https://github.com/XP-NETWORK/audits)
- The key repos are private & can be shared with the Fantom Team on request

## Team LinkedIn Profiles
- [Dima Briukhanov - CTO](https://www.linkedin.com/in/dmitry-briukhanov-60b2ab45/)
- [Dima Ulianov - CBO](https://www.linkedin.com/in/dimaulyanov/)
- [Rupansh Sekar Blockchain](https://www.linkedin.com/in/rupansh-sekar-10941b16a/)
- [Sumit Kumar - Blockchain](https://www.linkedin.com/in/imsk17/)
- [Xueming Zheng - Blockchain](https://www.linkedin.com/in/xuemingzheng/)
- [Yura Dukhno - FE](https://www.linkedin.com/in/yuradukhno/)
- [Alexey Adoniev - FS](https://www.linkedin.com/in/alex-adoniev-a04022176/)

# Development Roadmap

## `Milestone 1` — Integrating into the Bridge Components

| Delivery Length | Deliverable | Specification |
|-|-|-|
| 2 weeks | Validators, Backend, Frontend | 1. Validation - we will add the validation logic relevant for the Fantom part of the bridge<br/>2. NFT-Indexer - we will develop search for NFTs by a user account <br/>3. TX fee estimation - we will integrate Fantom to the TX fee estimator<br/>4. Heartbeat - we will plug Fantom to the bridge heartbeat<br/>5.Node integration - we will plug to a node, start event listening and TX submission<br/>6. UI - we will integrate Fantom in the bridge UI<br/>7. JS library - we will add Fantom to the bridge<br/>8. REST API - we will add Fantom to the REST API<br/>9. Widget - we will add Fantom to the bridge widget|

## `Milestone 2` — Testnet Integration

| Delivery Length | Deliverable | Specification |
|-|-|-|
| 1 week | Testnet Integration | 1. Testnet contract deployment - we will deploy smart contracts on the mainnet.<br/>2. JS Library integration - we will integrate Fantom in the testnet-validators. Testnet-NFT-Lister<br/>3.We will run extensive tests and debug the bridge components after adding Fantom|

## `Milestone 3` — Mainnet Integration

| Delivery Length | Deliverable | Specification |
|-|-|-|
| 1 week | Mainnet Integration | 1. Mainnet contract deployment - we will deploy smart contracts on the mainnet.<br/>2. JS Library integration - we will integrate Fantom in the mainnet validators. NFT-Lister, <br/>3. We will make announcements about integrating Fantom in the bridge|

## `Future Plans`

Our long term plans include:
1. Mainnet integration to Cardano, Solana, Cosmos ecosystem chains, EOS compatible chains, NEO
2. Forged NFT detection on all the bridged chains
3. NFT explorer for finding NFT’s with deleted storage
4. NFT meta backup to secure transactions
5. Distributed NFT’s hosting (better than IPFS)
6. NFT Search (search by any parameter)
7. Retention protection tool

## `Additional Information`

We've already received grants for integration from:
1. [Harmony](https://talk.harmony.one/t/nft-bridge-connecting-harmony-to-10-evm-non-evm-chains/10293)
2. [Velas](https://github.com/XP-NETWORK/Velas-Grant-Delivery/blob/main/README.md)
3. [IoTeX](https://community.iotex.io/t/quigon-multi-chain-nft-bridge/5988)
4. [Aurora](https://aurora.dev/ecosystem#bridges) (Layer-2 of NEAR)
5. [Secret Network](https://github.com/SecretFoundation/Grants/issues/39)
6. [VeChain](https://github.com/vechain/grant-program/blob/master/applications/xp_network_nft_bridge.md)
7. [Nervos Network](https://talk.nervos.org/t/xp-network-nft-multi-chain-bridge/6497)
8. Internet Computer
9. GateChain (Gate.io)
  
<br/>We've already received financial support for integration from:
1. Tezos - additionally, we became a Backer (validator)
2. Fuse
