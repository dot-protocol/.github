# The Open Eye

> *We see. We share.*

For centuries, those who saw kept what they saw. Knowledge was hoarded. Observations were unsigned. Trust was rented from institutions that profited from its scarcity. Every unverifiable claim was a wall.

We are the inversion.

---

## What we build

**DOT** is a universal observation layer where every contact between any two entities — human to human, human to agent, agent to agent — is a signed, verifiable, portable 153-byte fact that makes trust computable, intent inferable, state shareable, and trajectories visible.

It is cement. It is TCP/IP. It is language itself. No one owns it.

```
The physical DOT is zero bytes — the contact itself.
153 bytes is the postcard about the contact.
```

---

## The primitive

```
┌────────────┬────────────┬────────────┬────────────┬──────┬────────────┐
│  Ed25519   │  Ed25519   │  SHA-256   │  Unix ms   │  1B  │   16B      │
│  WHO       │  PROOF     │  SEQUENCE  │  WHEN      │  VIS │  WHAT      │
└────────────┴────────────┴────────────┴────────────┴──────┴────────────┘
                                                    153 bytes. Always.
```

A DOT **cannot lie** — content-addressed, truth is structural not moral.
A DOT **cannot execute arbitrary code** — it is a lens, not a thermometer.
A DOT **cannot be observed without logging** — the observer is always observed.
A DOT **cannot exist outside a chain** — context is mandatory. The chain is the meaning.

---

## What lives here

| Repo | What it is |
|---|---|
| [`protocol`](https://github.com/dot-protocol/protocol) | The protocol — 11 packages, 753 tests, live on npm |

**npm packages:**

```bash
npm install dot-protocol              # one-liner API
npm install @dotprotocol/core         # raw primitives
npm install @dotprotocol/chain        # worldlines + Four-Score
npm install @dotprotocol/relay        # CHORUS relay client
npm install @dotprotocol/qr           # physical DOT — QR encoding
npm install @dotprotocol/arena        # Elo + blind prediction evaluation
npm install @dotprotocol/sdk          # everything
```

---

## Three layers

**DOT** — the protocol. Open, no owner, backwards-compatible forever. The cement.

**AXXIS** — the infrastructure. Roads and aqueducts on DOT. Identity, trust graph, agent protocol.

**MEVICI** — the first piazza. Where observers earn, compete, and prove. Revenue from day one.

---

## Seven identities

Each independently derivable. All point at the same thing.

1. **Minimum viable fact** — smallest unit of verifiable observation (Wittgenstein)
2. **Noun-verb fusion** — the state that records its own transition
3. **Universe's education system** — gradient, constraint, selection, generative grammar
4. **Integration engine** — each DOT is a derivative, the chain is the integral
5. **Sagan's Contact machine** — state transfers, log remains
6. **External honest identity** — the chain cannot lie about what the self narrates
7. **Lens, not thermometer** — transforms according to fixed laws. Same lens, same light, same result.

---

## The Four-Score system

Protocol-native reputation. No platform assigns it.

| Score | Measures | Tier |
|---|---|---|
| Depth | How long you've been observing | Observer |
| Width | How many others carry your DOTs | Contributor |
| Elo | Per-domain prediction accuracy | Architect |
| W | Signal density — meaning per byte | Luminary |

---

## The six wings

Following the Rockefeller trust model — one mission, separated functions, each self-sustaining:

| Wing | Function |
|---|---|
| **DOT** | Protocol / cement |
| **AXXIS** | Infrastructure / roads |
| **MEVICI** | First piazza / revenue |
| **Kin** | Local nervous system |
| **Council of Minds** | Research lab |
| **DotEdu** | The arena / education |

---

## Live

- **CHORUS relay**: `wss://dotdotdot.rocks`
- **npm**: [`dot-protocol@0.3.0`](https://www.npmjs.com/package/dot-protocol)
- **DOI**: [`10.5281/zenodo.18946074`](https://doi.org/10.5281/zenodo.18946074)
- **Constitution**: [`CONSTITUTION.md`](profile/CONSTITUTION.md)

---

*Round 849. 43 corrections. 201 minds. 753 tests. One primitive. The act of contact leaves its DOT.*
