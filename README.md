# AOXC | High-Integrity Interoperability for Multi-Model Chains

> **A research-led infrastructure program for deterministic coordination across EVM, Move, and UTXO ecosystems.**

AOXC develops trust-minimized coordination infrastructure for heterogeneous blockchain environments. The guiding premise is methodological: cross-chain systems should be designed as **verifiable distributed systems** with explicit trust boundaries, reproducible state transitions, and auditable operational control.

---

## Research Scope and Progressive Expansion

The current architecture intentionally focuses on a bounded set of execution paradigms—EVM, Move/object-state, and UTXO—to establish rigorous interoperability baselines before broader network expansion.

This is a deliberate experimental strategy: once correctness, resilience, and operational repeatability are validated across these initial domains, AOXC plans to extend to additional chains and integration surfaces in a controlled manner.

---

## Primary Network Orientation: X Layer

Within the present phase, **X Layer functions as the primary operational anchor** for AOXChain deployments and coordination experiments.

While the execution path is chain-specific at this stage, the economic layer is designed with forward integration in mind: AOXC’s native token model is intended to converge with the project’s own coin architecture as the protocol matures.

---

## Current Live Presence (X Layer References)

AOXChain already maintains an observable on-chain footprint on X Layer:

- **Main Contract:** https://www.oklink.com/tr/x-layer/address/0x97bdd1fd1caf756e00efd42eba9406821465b365/contract  
- **Proxy Token Contract:** https://www.oklink.com/tr/x-layer/token/0xeb9580c3946bb47d73aae1d4f7a94148b554b2f4?tab=contract  
- **Multisig Contract:** https://www.oklink.com/tr/x-layer/address/0x20c0dd8b6559912acfac2ce061b8d5b19db8ca84/contract

These records indicate that AOXChain is not positioned as a purely conceptual framework; it is being iterated through live-network artifacts that can be independently inspected.

---

## Ecosystem Architecture

The ecosystem is organized into specialized repositories with clear functional boundaries:

- **[aoxcon](https://github.com/aoxc/aoxcon)** — **Control Plane & Operations**  
  Administrative surface for orchestration, policy flow, and lifecycle management.

- **[aoxcore-xlayer](https://github.com/aoxc/aoxcore-xlayer)** — **EVM Execution Module**  
  Solidity-oriented execution components optimized for EVM-compatible environments, with X Layer as the current primary domain.

- **[aoxcore-sui](https://github.com/aoxc/aoxcore-sui)** — **Move/Object-State Module**  
  Object-centric logic aligned with Sui-style semantics and decentralized storage integration.

- **[aoxcore-cardano](https://github.com/aoxc/aoxcore-cardano)** — **UTXO Validation Module**  
  Validation-centric components informed by Plutus/Aiken-style formalism for deterministic UTXO workflows.

---

## Maturity and Evaluation Guidance

AOXC is in an **active alpha research phase**. Public repositories are available for technical scrutiny, and iterative change should be expected while invariants, interfaces, and governance pathways are refined.

For evaluators, the present release should be read as a research-grade baseline: practically instantiated, empirically testable, and intentionally structured for progressive extension.
