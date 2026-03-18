# Knowledge Mining Domains

> _"Every domain has secrets hiding in plain sight."_

## Active Domains

These are the knowledge domains currently open for mining.
Each domain has a capacity of ~100 entries before difficulty increases significantly.

| Domain | Status | Entries | Difficulty | Description |
|--------|--------|---------|------------|-------------|
| `software-engineering` | 🟢 Open | 0 | Genesis | Code, architecture, DevOps, testing |
| `machine-learning` | 🟢 Open | 0 | Genesis | ML/AI, training, inference, data |
| `product-design` | 🟢 Open | 0 | Genesis | UX, UI, product strategy |
| `economics` | 🟢 Open | 0 | Genesis | Markets, incentives, behavioral econ |
| `biology` | 🟢 Open | 0 | Genesis | Genetics, medicine, ecology |
| `physics` | 🟢 Open | 0 | Genesis | Quantum, thermodynamics, cosmology |
| `psychology` | 🟢 Open | 0 | Genesis | Cognition, behavior, social psych |
| `history` | 🟢 Open | 0 | Genesis | Events, patterns, revisionism |
| `mathematics` | 🟢 Open | 0 | Genesis | Pure math, statistics, probability |
| `security` | 🟢 Open | 0 | Genesis | Cryptography, infosec, privacy |

## Frontier Bonus

The **first Knowledge Entry** in any domain earns a **+100 PoK frontier bonus**
on top of the standard mining reward. This incentivizes exploration of new domains.

## Proposing New Domains

To propose a new domain:

1. Open a GitHub Discussion with the `[DOMAIN]` prefix
2. Describe the domain and why it's rich in counter-intuitive knowledge
3. Provide at least 3 example findings that could be entries
4. If approved by 2 Core Validators, the domain is added

## Domain Capacity & Difficulty

As a domain fills up, the difficulty increases quadratically:

```
Difficulty = 1 + (entries/capacity)² × 10

At 0 entries:   difficulty = 1.0  (easy)
At 50 entries:  difficulty = 3.5  (moderate)
At 80 entries:  difficulty = 7.4  (hard)
At 100 entries: difficulty = 11.0 (very hard — consider opening sub-domains)
```

When a domain reaches capacity, it can be split into sub-domains
via a PIP (Protocol Improvement Proposal).

---

<sub>Domains Registry Version: 0.1.0 | Epoch: 0 | Total Domains: 10</sub>
