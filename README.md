# Bitcoin and Blockchain

## Introduction

This readme provides an overview of key concepts in blockchain technology, including Bitcoin, Ethereum, smart contracts, the Oracle Problem, Chainlink, Layer 2 scaling solutions, and common terminology used in the blockchain community.

## Table of Contents

1. [Bitcoin and Blockchain](#bitcoin-and-blockchain)
2. [Ethereum and Smart Contracts](#ethereum-and-smart-contracts)
3. [The Oracle Problem](#the-oracle-problem)
4. [Chainlink](#chainlink)
5. [Layer 2 Scaling Solutions](#layer-2-scaling-solutions)
6. [Terminology](#terminology)
   - [Common Terms](#common-terms)

## Bitcoin and Blockchain

Bitcoin is one of the first protocols to utilize the revolutionary blockchain technology. The Bitcoin Whitepaper, authored by the pseudonymous Satoshi Nakamoto, described how Bitcoin could facilitate peer-to-peer transactions within a decentralized network using cryptography. This gave rise to censorship-resistant finance and presented Bitcoin as a superior digital store of value, often referred to as digital gold. There is a fixed amount of Bitcoin, similar to the scarcity of gold.

## Ethereum and Smart Contracts

A few years after Bitcoin's creation, Vitalik Buterin and others founded Ethereum, which builds upon the blockchain infrastructure with additional capabilities. Ethereum allows for the creation of decentralized transactions, organizations, and agreements without a centralized intermediary through smart contracts.

Though the concept of smart contracts was originally conceived in 1994 by Nick Szabo, Ethereum made it a reality. Smart contracts are a set of instructions executed in a decentralized way without the need for a centralized or third-party intermediary.

Smart Contract functionality is the primary difference between blockchains like Ethereum and Bitcoin. Technically, Bitcoin does have smart contracts, but they're intentionally Turing incomplete.

## The Oracle Problem

Smart contracts face a significant limitation – they cannot interact with or access data from the real world. This is known as the Oracle Problem. Blockchains are deterministic systems, so everything happens within their ecosystem. To make smart contracts more useful and capable of handling real-world data, they need external data and computation.

Oracles serve this purpose. They are devices or services that provide data to blockchains or run external computation. To maintain decentralization, it's necessary to use a decentralized Oracle network rather than relying on a single source. This combination of on-chain logic with off-chain data leads to hybrid smart contracts.

## Chainlink

Chainlink is a popular decentralized Oracle network that enables smart contracts to access external data and computation. Chainlink is also blockchain agnostic, meaning it works with any chain.

## Layer 2 Scaling Solutions

As blockchains grow, they face scaling issues. Layer 2 (L2) solutions have been developed to address this. L2 solutions involve other blockchains hooking into the main blockchain, essentially allowing it to scale. There are two primary types of L2 solutions:

- **Optimistic Rollups**: e.g., Optimism, Arbitrum
- **Zero-Knowledge Rollups**: e.g., ZK Sync, Polygon ZK EVM

## Terminology

### Common Terms

- **Web3**: A term used to describe the new paradigm of the internet powered by blockchain and smart contracts. Unlike the previous versions of the web, Web3 is permissionless and relies on decentralized networks rather than centralized servers. This ushers in an era of censorship-resistant and transparent agreements and transactions, often called an ownership economy.
  - **Web1**: The permissionless open sources web with static content.
  - **Web2**: The permissioned web, with dynamic content where companies run your agreements on their servers.
  - **Web3**: The permissionless web with dynamic content. Decentralized censorship-resistant networks run your agreement and code. User-owned ecosystems where one owns a portion of the protocol they interact with instead of solely being the product.

## Conclusion

This readme provides a foundational understanding of Bitcoin, Blockchain, Ethereum, smart contracts, and other related technologies. 


