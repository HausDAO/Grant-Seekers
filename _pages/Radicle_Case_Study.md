---
title: Radicle Case Study
author: [boilerrat]
date: 2022-10-01
category: Application
layout: post
tags: Grants
---

This is being done in support of a [Radicle Grant Application](https://hackmd.io/@daohaus/SkxBXRHcc/edit) in developing use cases.

Radicle uses a number of smart contracts in their protocol. Currently they use a modified compound governace.sol contract for governance.


## Hypothesis

There seems to be some entry points with the current smart contracts that Radicle uses for governance.

Perhaps one point would be to study the feasability of improving the typical compound contract with baal.sol, giving them everything they would currently enjoy plus the extended governance capabilities baal.

For example, I also notice that they have a number a  streaming and splits contracts, which I will examine in this doc. I am unsure now what they do, but my guess is they are used to pay contributors to repos.

The most obvious use case that I can imagine for an integration between DAOhaus and Radicle would be in providing a turn key DAO operation for code and repository teams. It may be possible for Radicle to use their current splits and streaming contracts into shamans to allow them to be directly integrated with DAO governance.

## Data Collection

### Contracts

https://github.com/radicle-dev/radicle-contracts/tree/master/contracts

#### Governance
*links will go to a hackmd file of completed AI analysis of the contract. A check mark indicate completion. No Check mark, no link*

+ [x] [governor.sol](https://hackmd.io/@boilerrat/rJL9_CY7s)
+ [ ] [RadicleToken.sol]()
+ [ ] [Timelock.sol]()
+ [ ] [Timelock.sol]()
+ [ ] [VestinToken.sol]()

#### Deploy

+ [ ] [phase0.sol]()

#### Libraries

+ [ ] [ProxyDeltas.sol]()
+ [ ] [ReceiverWeights.sol]()
+ [ ] [SafeMath.sol]()

#### Misc
+ [ ] [AttestationRegistry.sol]()
+ [ ] [Claims.sol]()
+ [ ] [ClaimsV2.sol]()
+ [ ] [DummyUpgradable.sol]()
+ [ ] [ErrorReporter.sol]()
+ [ ] [Pool.sol]()
+ [ ] [PoolTest.sol]()
+ [ ] [Proxy.sol]()
+ [ ] [ProxyAdminStorage.sol]()
+ [ ] [Registrar.sol]()
+ [ ] [TestDai.sol]()

### Drips Contracts

https://github.com/radicle-dev/drips-contracts/tree/master/src

+ [ ] [AddressDriver.sol]()
+ [ ] [Caller.sol]()
+ [x] [Drips.sol](https://hackmd.io/@boilerrat/rJhhszqmi)
+ [ ] [DripsHub.sol]()
+ [ ] [ImmutableSplitsDriver.sol]()
+ [ ] [Managed.sol]()
+ [ ] [NFTDriver.sol]()
+ [ ] [Reserve.sol]()
+ [ ] [Splits.sol]()
+ [ ] [Upgradeable.sol]()

#### How Pools Work

https://github.com/radicle-dev/drips-contracts/blob/master/docs/how_the_pool_works.md

## Competition

https://radicle.community/t/jokedao-grant-application/2884

joke DAO
![](https://i.imgur.com/1pyFWO0.png)
![](https://i.imgur.com/nOK5AwB.png)
