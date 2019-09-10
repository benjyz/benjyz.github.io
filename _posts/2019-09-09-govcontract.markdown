---
layout: post
title:  "Governance contracts"
date:   2019-09-09 10:00:00 +0700
categories: blockchain
---
The concept of smart contracts was invented by Nick Szabo in the 90’s. They have been implemented in Bitcoin as scripts and in Ethereum as more full fledged programs. These contracts are executed in an environment (i.e. the blockchain). In traditional paper based law contracts exist in a framework, such as contract law and governments to secure those relationships. Smart contracts are for agreements between one or more parties for individual transactions. Usually they should not effect the system as a whole.

Governance contracts as I propose them here are smart contracts which regulated macro-behavior of a system. For example in current democracies there are laws which define how voting works, who can hold an office, and many other things. Obviously currently these are paper based constructs and relevant within nation states. An example of governance contracts in the context of blockchains are those which “regulate” transaction validation itself. These ideas mostly come out of the proof-of-stake communities (notably Tendermint introduced the concept of bonding transactions [1]). Another example is equivalent of creating a company in the form of a distributed corporation. The incorporation itself could be a governance contract.

There also could exist governance contracts for change in source code. Presently this process is all out-of-band — there exist legal entities as foundations, which are not tied to commit rights of source code changes.
Consensus then would hypothetically be a kind of sum of all governance contracts, similar to a political system being the sum of the law (we’re ignoring the role of markets here). Decentralization of power can then mostly deal with good individual mechanisms, one of which is separate of powers in the sense of Montesquieu. One of many open questions is how individual smart contracts and a system of contract law can interact.

These ideas are partly based on Ethereum’s smart contract implementation and Proof-of-Stake research, although the core argument here fundamentally deviates as it proposes precise mechanisms for on-chain governance (see [2] and [3]). Better systems are possible when one generalizes the notion of stake for validation to governance contracts.

The concept of governance contracts could be useful in many other contexts as well (e.g. exchange listings in asset-registries).
[1] https://tendermint.com/static/docs/tendermint.pdf
[2] https://medium.com/@Vlad_Zamfir/the-history-of-casper-chapter-4-3855638b5f0e
[3] https://medium.com/@Vlad_Zamfir/against-on-chain-governance-a4ceacd040ca