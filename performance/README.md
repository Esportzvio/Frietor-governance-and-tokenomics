# Performance benchmarks

This document presents a summary of performance benchmarks for Frietor Saar production release.

| Transaction Type | TPS Sent | TPS Mined | Gas per Second | Gas per Transaction |
|-------------------|----------|-----------|-----------------|----------------------|
| EOA to EOA        | 3,000    | 2,577     | 54,117,000      | 21,000               |
| ERC20             | 820      | 813       | 23,005,250      | 28,297               |
| ERC721            | 750      | 746       | 37,393,367      | 50,125               |

# #Test Environment

The performance tests were conducted in a controlled environment to ensure accuracy and consistency in the results.

## Transaction Types
The tests were performed using three different types of transactions to assess the network's capability to handle various use cases:

* EOA to EOA: Representing simple value transfers between user accounts.
* ERC20: Token transfers, simulating the exchange of tokens on the network.
* ERC721: Non-fungible token (NFT) transfers representing the exchange of unique digital assets.

## Performance Metrics
The following key performance metrics were considered during the tests:

* Transactions per second (TPS) sent: The number of transactions submitted to the network per second.
* Transactions per second (TPS) mined: The number of transactions successfully processed and included in the blockchain per second.
* Gas per transaction: The amount of gas consumed by each transaction, representing the computational cost.
* Gas per second: The total amount consumed per second indicates the network's overall computational capacity.