# AOXC | Verifiable Interoperability Infrastructure

> **Research-oriented cross-chain coordination with X Layer as the operational base and progressive multi-chain expansion as the long-term pathway.**

AOXC is a blockchain infrastructure initiative focused on deterministic interoperability across heterogeneous execution models. The project prioritizes verifiability, explicit trust boundaries, and reproducible state transition logic over short-cycle narrative claims.

---

## Strategic Scope (Phase-Based)

At the current stage, AOXC intentionally concentrates on three execution paradigms:

- **EVM**
- **Move / object-state systems**
- **UTXO-based systems**

This bounded scope is methodological, not terminal. If the initial architecture demonstrates sufficient correctness and operational resilience, AOXC will expand to additional chains in subsequent phases.

---

## Primary Operational Network: X Layer

In the present alpha cycle, **X Layer is the main execution and deployment domain** for AOXChain.

Protocol design is chain-aware in implementation, while the economic model is planned to evolve toward integration with AOXC’s native coin architecture as maturity increases.

---

## Live On-Chain Footprint (X Layer)

AOXChain already exposes verifiable public artifacts on X Layer:

- **Main Contract:** https://www.oklink.com/tr/x-layer/address/0x97bdd1fd1caf756e00efd42eba9406821465b365/contract
- **Proxy Token Contract:** https://www.oklink.com/tr/x-layer/token/0xeb9580c3946bb47d73aae1d4f7a94148b554b2f4?tab=contract
- **Multisig Contract:** https://www.oklink.com/tr/x-layer/address/0x20c0dd8b6559912acfac2ce061b8d5b19db8ca84/contract

These references indicate that the project is not purely conceptual and can be independently inspected at the network level.

---

## Ecosystem Repositories

- **[aoxcon](https://github.com/aoxc/aoxcon)** — Control plane and operational orchestration
- **[aoxcore-xlayer](https://github.com/aoxc/aoxcore-xlayer)** — EVM execution module (current primary domain)
- **[aoxcore-sui](https://github.com/aoxc/aoxcore-sui)** — Move/object-state execution module
- **[aoxcore-cardano](https://github.com/aoxc/aoxcore-cardano)** — UTXO validation-oriented module

---

## Maturity Statement

AOXC is in an **active alpha research phase**. Public repositories are open for technical scrutiny, and iterative changes are expected while protocol invariants and interoperability boundaries are being validated.
