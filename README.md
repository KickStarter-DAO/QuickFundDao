# Quickfund DAO(Decentralized Autonomous Organization)

---

## What is it?

A QuickFund decentralised autonomous organisation (QuickFundDAO), is a blockchain-based system that enables Founders and investors to coordinate and self-govern themselves through a set of self-executing rules published on a public blockchain.
DAOs are regarded as being the most decentralised because they rely on a decentralised infrastructure without centralize servers (a public blockchain). Second, because they rely on certain decentralized governance mechanisms, so the decision-making process relies on the collective agreement of its members. This process typically relies on some form of voting, in which the DAO members can participate.

---

## Why QuickFund Dao?

1. Instant Transactions

2. Peer-to-peer transaction

3. Enhanced Security

4. Automated process

5. Onchain voting

## overview

---

## SmartContract

#### 1.FundProject.sol

_Investors and Project Founder intract peer to peer through smartContract. After verification of project by DAO, ipfs hash of projects store on blockchain and founder will get specific projectID. Using projectId Voters can do vote on projects by using QFD governor token. DAO has authority to diapprove the projects in case of scam._

#### 2.GovernanceToken.sol

_QFD is the standard ERC-20 fungible token of QuickFund DAO._

#### 3.GovernerContract.sol

_The Governor contract is responsible for managing DAO proposals.It monitors the progress of ideas and counts the votes to determine whether they are approved. If a proposal is approved, the Governor puts it into action on-chain._

_The primary advantage of the Governor structure is that all of the DAO's decisions are made entirely on-chain. Because the smart contract handles everything totally on-chain, token voters don't need to put their trust in a third party to tally their votes or carry out their transactions._

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [Nodejs](https://nodejs.org/en/)
  - You'll know you've installed nodejs right if you can run:
    - `node --version` and get an ouput like: `vx.x.x`
- [Yarn](https://yarnpkg.com/getting-started/install) instead of `npm`
  - You'll know you've installed yarn right if you can run:
    - `yarn --version` and get an output like: `x.x.x`
    - You might need to [install it with `npm`](https://classic.yarnpkg.com/lang/en/docs/install/) or `corepack`

## Quickstart

```
git clone https://github.com/KickStarter-DAO/QuickFundDao
cd QuickFundDao
yarn
```

# Useage

## Testing

```
yarn hardhat test
```

## Testing on Testnets

To test our contract on mumbai testnet you'll need these environment variables:
`MUMBAI_RPC_URL`,`PRIVATE_KEY`
for more check the .env.example file

### Test Coverage

```
yarn hardhat coverage
```

### Estimate gas cost in USD

To get a USD estimation of gas cost, you'll need a `COINMARKETCAP_API_KEY` environment variable. You can get one for free from [CoinMarketCap](https://pro.coinmarketcap.com/signup).

Then, uncomment the line `coinmarketcap: COINMARKETCAP_API_KEY,` in `hardhat.config.ts` to get the USD estimation.

## visualize Smart Contract

## ![fund](https://user-images.githubusercontent.com/82324643/202600396-1c242463-61f9-4be4-b962-26653a183e62.svg)

![token](https://user-images.githubusercontent.com/82324643/197370082-31213bac-5a68-4b76-93fd-930d10130af4.svg)

---

![govermentContract](https://user-images.githubusercontent.com/82324643/197370115-f623112f-ab0a-4f42-bfe9-814cfb0fc5f6.svg)

---

![timelock](https://user-images.githubusercontent.com/82324643/197370137-bdd2217f-f491-4feb-8719-3abc8d4d2b93.svg)
