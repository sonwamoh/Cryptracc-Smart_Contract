# Cryptracc-Smart_Contract

## Problem
Traditional contract signing lacks meaningful non-repudiation. Handwritten signatures can be forged or denied.

## Approaches
- Apply algorithms and concepts from CS 166 and relevant research.
- Create a solution that ensures non-repudiation in contract signing.

## Design
Digital signatures, specifically, offer non-repudiation properties and will be a key component of the solution.

## Research
Key areas of investigation include:
- Blockchain
- Digital wallets
- JBOK (Just a Bunch of Keys, private key!)
  
Blockchain transactions, signed using a private key, provide a strong foundation for non-repudiation.

### Added Benefit
The proposed solution is fault-tolerant.

## Architecture

### Client
A web frontend that facilitates user interactions with the application. Technologies used:
- React
- Ethers.js
- wagmi

### Smart Contract
A program that operates on a decentralized network. Technologies used:
- Hardhat
- Solidity
