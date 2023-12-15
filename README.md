---
title: Welcome to tinychain
---
# Welcome to tinychain

Want to experiment with new blockchain designs? Sick and tired of the 2000 page War And Peace -style docs to get setup with OP Stack? 

Introducing **tinychain**.

Tinychain is an ultra-lightweight blockchain core, written in Python.

In under 1000 LOC:
- cryptography
- transactions
- consensus - Nakamoto POW, Tendermint PoS
- VM's - Lisp, Brainfuck, EVM
- state machine
- gas markets
- protocol, RPC, and P2P networking

Let the devs do what they do best - building cool stuff.

## Brainfuck-based blockchain

The first network to be deployed using tinychain will be **Brainnet**, a Brainfuck-based blockchain.

**Quotes**

"This is plausible the most perverted blockchain project in history." - Vinay Gupta, co-ran the Ethereum launch

"cannot wait to write a constant product AMM in Brainfuck" - Sam, Robot Labs.

![fe5f2450-7b82-49d0-8a66-414f96adcc35](https://github.com/tinychainorg/tinychainorg.github.io/assets/584141/2f8d97f9-6883-49c4-9982-06ec5d7c215a)

| **Area**     | **Description**                                                                                                                                                                                                                                                                                            | **Status**  |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| VM           | [Brainfuck](https://en.wikipedia.org/wiki/Brainfuck) smart contracts                                                                                                                                                                                                                                       | ✅⚠️ 60% Done |
| Consensus    | Bitcoin / Nakamoto / POW with ZK-friendly hash function                                                                                                                                                                                                                                                    | ⚠️ WIP       |
| Tokenomics   | Ethereum-like - native token + fixed exchange rate to gas                                                                                                                                                                                                                                                  | ✅ Done      |
| Cryptography | ECDSA wallets, SECP256k1 curve (same as BTC), SHA-2 256 bit hash function                                                                                                                                                                                                                                  | ✅ Done      |
| Networking   | P2P and RPC servers both use HTTP, gossip network architecture                                                                                                                                                                                                                                             | ✅ Done       |
| ZK proofs    | ZK for compression of tinychain. Use either [groth16](https://github.com/erhant/zkbrainfuck) or [halo2](https://github.com/cryptape/ckb-bf-zkvm) SNARK proofs for brainfuck. TBA we will rework consensus/crypto to use SNARK-friendly tech (MiMC/Poseidon hash function, SNARK-friendly signature scheme) |             |


## What else can I do with Tinychain?

 * Create your own proof-of-work blockchain network, in ~1min.
 * Experiment with new **data availability** tech:
   * Celestia.
   * Google Sheets.
 * Experiment with new **consensus** modules:
   * Nakamoto
   * Tendermint
   * Narwhal/Bullshark
 * Experiment with new **gas/payment mechanisms**
   * SaaS-style pricing for transactions - $x/month!
   * Free transactions for hodlers of NFT's
   * Points
 * Experiment with new **VM designs**:
   * Brainfuck
   * RISC V
   * GPU / [MLIR](https://mlir.llvm.org/)
 * Experiment with other random stuff:
   * [zero-knowledge shuffle protocols](https://github.com/nalinbhardwaj/curdleproofs.pie/)







