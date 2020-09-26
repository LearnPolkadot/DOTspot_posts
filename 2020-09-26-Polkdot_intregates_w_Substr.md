---
title: "Polkadot’s Substrate 2.0 integrates oracles at a protocol level"
date: 2020-09-26T15:34:30-04:00
last_modified_at: 2020-09-26T15:34:30-04:00
categories:
  - Substrate
tags:
  - substrate
  - polkadot
sidebar:
  nav: "posts"
---

The Polkadot team released on Wednesday a major milestone for its Substrate blockchain framework, which now provides a way for blockchain applications to interface with the outside world without relying on external oracle providers.

Substrate is the name used for Polkadot’s blockchain building framework. It provides developers with a variety of tools to design their custom blockchain for a variety of possible applications. The blockchains can then be launched stand-alone or integrated in Polkadot’s network of shards, or “Parachains.”

The most important feature of Substrate 2.0 is the “off-chain worker,” a development module that lets blockchains perform advanced computations or make their own web requests to the outside world.

Off-chain workers leverage Substrate nodes to perform operations that would normally be outside of the blockchain’s capabilities. In a blockchain like Ethereum, a particular computation has to be quick and limited enough to fit into a block of instructions. This excludes many types of operations that are either non-deterministic — for example web requests that may fail — or are just too complex for the resources available. Substrate 2.0 allows developers to unload these operations to the nodes running the network, which are able to perform web requests, encryption and decryption, signing of data, random number generation and other CPU-intensive tasks.

This system would allow Polkadot developers to build complex systems like price feed providers entirely on-chain, removing some of the elements of trust involved. The issue of finding reliable data sources — the core of the “oracle problem” — would still remain, but developers would have maximum flexibility in the design of their DApps and blockchains.

By contrast, oracle systems like Chainlink have their data gathering logic entirely off-chain. Smart contract developers can only access the final data submitted by the oracles, necessitating a certain degree of trust in these providers that these types of solutions try to minimize.

Substrate 2.0 also introduces a variety of other developer-friendly tools in the form of Pallets, configurable modules that greatly simplify certain actions. For example, the “Democracy” pallet provides a simple way to introduce on-chain voting, while the “EVM” pallet replicates Ethereum’s Virtual Machine to let developers port its smart contracts to Polkadot.

While Substrate appears to be a significant technological leap forward over some existing solutions, it remains to be seen if developers and users will make the jump to Polkadot. The Web3 Foundation, which supports Polkadot, has been busy funding teams to build the infrastructure of the blockchain, ranging from [bridges to Ethereum](https://cointelegraph.com/news/a-new-polkadot-to-ethereum-bridge-could-enable-cross-chain-defi-composability) and other blockchains to [in-house decentralized finance projects](https://cointelegraph.com/news/eos-defi-project-sets-up-shop-on-polkadot).

A key part of Polkadot’s value proposition is sharding, which would let Substrate blockchains communicate with each other. However, cross-shard communication is [still at the testing stage](https://cointelegraph.com/news/polkadot-launches-testnet-for-sharding-cross-communication).
