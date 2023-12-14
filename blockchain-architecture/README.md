# Frietor Saar Architecture Overview

## Introduction

Frietor Saar is a blockchain network scaffolded using Polygon Edge, designed to provide a robust and scalable infrastructure for decentralized applications. The architecture encompasses various components, each playing a crucial role in the network's functionality.

![Frietor Saar Architecture](/architecture/images/architecture.png)

*Image Credits: [https://polygon.technology/]*

## Architecture Components

### 1. libp2p

libp2p serves as the networking layer, providing peer-to-peer communication capabilities for Frietor Saar. It facilitates decentralized networking with features such as peer discovery, connection management, and secure messaging.

*[Networking Overview](/architecture/networking.md)*

### 2. Bridge

The Bridge component enables seamless communication between Frietor Saar and other Proof-of-Stake blockchains. It includes a built-in bridging mechanism powered by PolyBFT, allowing message passing without the need for mapping.

*[Bridge Overview](/architecture/bridge.md)*

### 3. Mempool

The Mempool manages pending transactions, ensuring fair and efficient execution by allowing validators to aggregate signatures into a single, aggregated signature.

*[Mempool Overview](/architecture/mempool.md)*

### 4. Consensus

PolyBFT serves as the consensus mechanism for Frietor Saar. It consists of a consensus engine, IBFT 2.0, and a comprehensive protocol that includes features like the bridge, staking, and other utilities.

*[Consensus Overview](/architecture/consenus.md)*


### 5. Blockchain

The Blockchain component coordinates the system, overseeing state transitions and managing state changes with the addition of each new block.

*[Blockchain Overview](/architecture/blockchain-struct.md)*

### 6. Runtime (EVM)

Frietor Saar utilizes the Ethereum Virtual Machine (EVM) as the runtime environment for executing smart contracts.

*[Runtime (EVM) Overview](/architecture/evm-support.md)*


### 7. TxPool

The TxPool represents the transaction pool, closely connected with other modules in the system.

*[TxPool Overview](/architecture/txpool.md)*

### 8. JSON-RPC

JSON-RPC facilitates interaction between dApp developers and the blockchain, allowing developers to issue requests to a Frietor Saar node.

*[JSON-RPC Overview](/architecture/jsonrpc.md)*

### 9. gRPC

gRPC is essential for operator interactions, providing a seamless user experience for node operators to interact with the client.

*[gRPC Overview](/architecture/grpc.md)*