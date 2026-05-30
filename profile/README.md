# DOT Protocol ◉

**The open eye. Protocols, not platforms.**

A DOT is a **153-byte signed, chained, verifiable observation** — the smallest unit of attributable truth. That's the entire primitive:

```
[  0 .. 31]  pubkey      Ed25519 public key      — WHO
[ 32 .. 95]  signature   Ed25519 over the rest   — PROOF
[ 96 ..127]  chain       SHA-256 of the prev DOT — SEQUENCE
[128 ..135]  timestamp   Unix ms, big-endian     — WHEN
[136]        type        visibility              — public / circle / private / ephemeral
[137 ..152]  payload     16 bytes                — WHAT (or a hash pointer to more)
```

Identity, money, reputation, communication, and storage are all just *what goes in the payload* — with no company in the middle that owns the data, and nothing to trust that you can't verify yourself. The empty DOT — zero payload — is a **ping**: the default. Content is the exception.

Free forever. Apache-2.0 / MIT / public-domain across the stack. The math, once published, cannot be seized.

## The principle

**Verify, don't trust. No hosted middle.** Signing and verification happen on your device. A relay passes 153 bytes without understanding, storing, or owning them — the network is dumb pipes; the truth is in the signature. A DOT created in JavaScript verifies in Python and vice-versa: same 153 bytes, everywhere.

## Start here

```bash
npm install @dotprotocol/sdk      # sign, verify, chain, compress, identity
pip install dot-python            # the 153-byte format in Python
```

All npm packages live under [`@dotprotocol`](https://www.npmjs.com/org/dotprotocol); `@dotprotocol/sdk` is the one-install entry.

## Repos

| Repo | What it is |
|------|-----------|
| [`dot`](https://github.com/dot-protocol/dot) | The monorepo — wire format, chain, identity, mesh, CLI, compression |
| [`dot-python`](https://github.com/dot-protocol/dot-python) | The 153-byte signed observation format in Python |
| [`pipernet`](https://github.com/dot-protocol/pipernet) | Federated, agent-native communication protocol |
| [`piperchat`](https://github.com/dot-protocol/piperchat) | p2p chat — two browsers, one message, no server in the middle |
| [`dotdrop`](https://github.com/dot-protocol/dotdrop) | Federated, agent-native file drop |
| [`dot-words`](https://github.com/dot-protocol/dot-words) | Sovereign, reversible BIP39 geocoding (a What3Words replacement) |
| [`republic-spec`](https://github.com/dot-protocol/republic-spec) | Specification for personal sovereign computing |
| [`variance-detection`](https://github.com/dot-protocol/variance-detection) | Cancer is a defector, not an invader. Variance detects it. |

---

*The protocol is free forever. The act of contact leaves its dot.*
