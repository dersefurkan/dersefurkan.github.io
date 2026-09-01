# Furkan Derse — Attack-Test & Security Review Engineer

Independent attack-test and security review engineer for DeFi protocols.
**The deliverable is a repo with green `forge test` output, not a PDF.**

## Services

- **Foundry invariant suites** — stateful fuzzing harnesses around the identity that actually moves money
- **Mainnet fork fuzz** — fork tests against live deployments or pinned commits, adversarial call sequences
- **Upgrade / diff review** — focused passes over what changed
- **Adversarial test packs** — "how would you drain this vault" as runnable failing-then-fixed tests
- **zkVM / coprocessor boundary** — guest program + on-chain verifier binding (image ID pinning, journal commitment, replay resistance)

Full engagement terms: [SERVICES.md](https://github.com/dersefurkan/dersefurkan/blob/main/SERVICES.md)

## Public work

- [split-ledger-vault-demo](https://github.com/dersefurkan/split-ledger-vault-demo) — money-moving identity bug: directed PoC + conservation invariants
- [pool-invariant-suite-demo](https://github.com/dersefurkan/pool-invariant-suite-demo) — handler-based invariant suite + killed-bug showcase + fork fuzz
- [risc0-onchain-verify-demo](https://github.com/dersefurkan/risc0-onchain-verify-demo) — zkVM seam end-to-end: Rust guest → Groth16 receipt → Solidity verifier
- [zkvm-guest-bug-notes](https://github.com/dersefurkan/zkvm-guest-bug-notes) — curated map of zkVM guest-program and onchain-binding bug classes

## Contact

Telegram [@FURY_Fn](https://t.me/FURY_Fn) · dersefurkan32@gmail.com — replies within 24 hours.
Free 30-minute scope call; fixed quote within 24 hours after it.
