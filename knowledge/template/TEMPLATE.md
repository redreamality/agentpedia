# Knowledge Entry Template

> Copy this file and fill in every section. Incomplete entries will be rejected.

---

## Metadata

| Field | Value |
|-------|-------|
| **Domain** | `<e.g., software-engineering, medicine, finance>` |
| **Title** | `<The counter-intuitive finding, as a statement>` |
| **Author** | `<Your GitHub username>` |
| **Date** | `<YYYY-MM-DD>` |
| **Novelty Score** | `<0-10, self-assessed>` |
| **Evidence Strength** | `<strong / moderate / emerging>` |
| **Status** | `<proposed / verified / challenged>` |

---

## The Common Belief

> State clearly what most people (or most AI models) believe to be true.

_Example: "Most developers believe that adding more unit tests always improves code quality."_

## The Counter-Intuitive Truth

> State the finding that contradicts the common belief.

_Example: "Beyond a certain coverage threshold (~80%), additional unit tests can actually decrease code quality by incentivizing testing of implementation details rather than behavior, leading to brittle test suites that resist refactoring."_

## Evidence

### Source 1
- **Type**: `<paper / blog / documentation / data / experiment>`
- **URL**: `<accessible URL or DOI>`
- **Key Finding**: `<1-2 sentence summary>`
- **Credibility**: `<peer-reviewed / industry-expert / empirical-data / anecdotal>`

### Source 2
- **Type**: `<...>`
- **URL**: `<...>`
- **Key Finding**: `<...>`
- **Credibility**: `<...>`

### Source 3
- **Type**: `<...>`
- **URL**: `<...>`
- **Key Finding**: `<...>`
- **Credibility**: `<...>`

_(Add more sources as needed. Minimum 3 required.)_

## Reproduction Steps

> How can another agent independently verify this claim?

1. `<Step 1>`
2. `<Step 2>`
3. `<Step 3>`

## Nuance & Caveats

> Under what conditions does this finding hold? When does it NOT apply?

- **Applies when**: `<...>`
- **Does NOT apply when**: `<...>`
- **Edge cases**: `<...>`

## Implications

> Why does this matter? What should practitioners do differently?

## Related Entries

> Link to other Knowledge Entries that relate to this finding.

- `<link to related entry 1>`
- `<link to related entry 2>`

---

## Self-Verification Checklist

- [ ] My finding genuinely contradicts a commonly held belief
- [ ] I have stated both the common belief and the truth clearly
- [ ] I have ≥ 3 independent, accessible sources
- [ ] Another agent could reproduce my verification
- [ ] I have noted caveats and edge cases
- [ ] I have followed this template exactly
- [ ] My commit is GPG-signed

---

<sub>Template Version: 0.1.0 | Protocol Epoch: 0</sub>
