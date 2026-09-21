# Wesley (Lello) Tereciani

Independent Web3 developer building public, Testnet-focused projects across the Stellar/Soroban and EVM ecosystems.

My repositories combine smart contracts with React frontends and TypeScript/Node.js services. They include a Stellar explorer, a Stellar invoice and payment-verification application, Soroban attestation and token studies, and RWA and supply-chain prototypes.

This profile contains independent projects, study projects, Testnet experiments, and production-oriented prototypes. It does not claim client work, freelance engagements, users at scale, external audits, or commercial production usage unless explicitly documented.

## Engineering practices

- Specification-Driven Development: define scope, architecture, security boundaries, test scenarios, and explicit non-goals before implementation when the project requires it.
- Unit, negative, and integration testing across application and blockchain-related flows.
- Browser and end-to-end testing with Playwright where applicable.
- CI-based validation with GitHub Actions where configured.
- Security-oriented review of authorization, validation, state transitions, secrets, reentrancy, and operational limits.
- Fuzzing or invariant testing only where the specific repository contains and documents those tests.

## Technical focus / verified stack

The technologies below are evidenced by code, dependency manifests, or documentation in my public repositories:

- **Smart contracts:** Solidity and Foundry; Rust and Soroban; SEP-41-oriented token patterns in `braza`
- **Frontend:** React across `Projeto-Stellar-explorer`, `Projeto-EAS-Soroban`, `stellar-invoice`, and `RWAImob`; Vite in `Projeto-Stellar-explorer` and `Projeto-EAS-Soroban`; wagmi and Tailwind CSS in `RWAImob`
- **Stellar integration:** `@stellar/stellar-sdk` in `stellar-invoice`, `Projeto-Stellar-explorer`, and `Projeto-EAS-Soroban`; Horizon integration in `Projeto-Stellar-explorer` and `stellar-invoice`
- **Libraries and standards:** OpenZeppelin components in `Kaleido`, `RWAImob`, and `PharmaChain`; SEP-41 concepts in `braza`
- **Application architecture:** TypeScript/Node.js services, React interfaces, contract integration, payment verification, indexing, and blockchain data exploration
- **Development and testing:** Vitest, Cargo, and Tokio are used in the public repositories' JavaScript/TypeScript and Rust development and testing workflows
- **Project domains:** blockchain payments, attestations, tokenization, RWA, supply chain, and Testnet experimentation

## Additional learning

Vue.js is part of my self-directed learning. Python and pytest are part of my broader study and tooling knowledge. My NearX coursework and studies also cover `web3.py`, `viem`, the Foundry toolkit (`forge`, `anvil`, `cast`, and `chisel`), Hardhat, Docker/Docker Compose, DeFi, DEX development, ENS, Hyperledger Besu, and smart-contract security fundamentals. ethers.js and web3.js are associated with my NearX coursework and studies on Web3 libraries. These learning items are not presented here as verified dependencies of the public projects above.

## Featured work

- [stellar-invoice](https://github.com/LelloTereciani/stellar-invoice) — React-based Stellar Testnet invoice and payment-verification prototype using the Stellar SDK and Horizon
- [Projeto-Stellar-explorer](https://github.com/LelloTereciani/Projeto-Stellar-explorer) — full-stack Stellar explorer with a React/Vite frontend, Node.js/Express API, Horizon data, and Soroban contract queries
- [Projeto-EAS-Soroban](https://github.com/LelloTereciani/Projeto-EAS-Soroban) — EAS-like Stellar Testnet attestation study with a Soroban Rust contract, TypeScript API and indexer, and React/Vite frontend
- [braza](https://github.com/LelloTereciani/braza) — experimental Rust/Soroban token-contract study centered on SEP-41 concepts
- [RWAImob](https://github.com/LelloTereciani/RWAImob) — Sepolia RWA prototype using Solidity, Foundry, OpenZeppelin, React, wagmi, and Tailwind CSS
- [PharmaChain](https://github.com/LelloTereciani/PharmaChain) — experimental blockchain supply-chain study

Most projects are Testnet-only or experimental. See each repository README for scope, evidence, setup, and limitations.

## Possible next portfolio projects

These are proposed future projects, not current experience:

1. A Foundry escrow with fuzz and invariant tests, explicit dispute states, pause/recovery boundaries, and a Base Sepolia demo.
2. A Soroban asset and payment workflow showing trustlines, authorization, events, and integration tests.
3. A cross-chain asset transfer study that documents threat modeling, decimal handling, finality, failure recovery, and testnet-only limits.
4. A small on-chain treasury with role separation, proposal lifecycle, negative tests, and an auditable event model.
