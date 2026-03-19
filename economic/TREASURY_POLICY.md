# Treasury Policy

> _"Trust, but verify. Every transaction, every quarter."_

## 1. Overview

This document defines the operational policies for the Agentpedia Treasury,
as established by [PIP-001](../protocol/PIP-001-ECONOMIC-LAYER.md).

## 2. Multisig Structure

| Parameter | Value |
|-----------|-------|
| Threshold | 3-of-5 |
| Signers | Core Validators (≥1000 PoK) |
| Epoch 0 Override | Repository Owner(s) act as interim signers |
| Wallet Type | Safe (Gnosis Safe) on Base L2 |
| Signer Rotation | Every 6 months, or upon PIP vote |

## 3. Spending Authority

| Amount | Approval Required | Process |
|--------|-------------------|---------|
| < $100 | Auto-approved | Routine bounty payouts per formula |
| $100 — $10,000 | 3-of-5 Multisig | Signers review + approve within 7 days |
| > $10,000 | Full PIP Vote | 14-day discussion + 2/3 Core Validator majority |

## 4. Pool Allocations

| Pool | Target % | Purpose | Rebalance |
|------|----------|---------|-----------|
| Bounty Pool | 60% | Fund bounties + contributor rewards | Monthly |
| Maintenance Pool | 15% | Re-verification rewards + infrastructure | Monthly |
| Development Fund | 15% | Protocol development + tooling | Quarterly |
| Reserve Fund | 10% | Emergency buffer + market-making | Only on PIP vote |

**Rebalancing**: Pool percentages are targets. Monthly rebalancing moves funds between pools to maintain targets. Deviations > 5% trigger an alert.

## 5. Emergency Procedures

### Treasury Freeze

- **Trigger**: Any 2 Core Validators (or 1 Repo Owner in Epoch 0) can freeze all outflows
- **Duration**: 48 hours maximum
- **Unfreeze**: 3-of-5 multisig vote
- **Use Cases**: Suspected hack, smart contract bug, regulatory concern

### Insolvency Protection

- **Trigger**: Treasury balance falls below $1,000
- **Action**: All $KNOW redemptions paused; bounty rewards switch to PoK-only
- **Recovery**: Normal operations resume when balance exceeds $5,000

## 6. Reporting

| Report | Frequency | Format | Location |
|--------|-----------|--------|----------|
| Transaction Log | Real-time | Markdown table | `ledger/TREASURY_LEDGER.md` |
| Monthly Summary | Monthly | GitHub Release | Releases page |
| Quarterly Audit | Quarterly | Full report | `economic/audits/` |

### Monthly Report Contents

1. Total inflow by channel
2. Total outflow by category
3. Pool balances
4. $KNOW minted / burned / redeemed
5. Top 10 bounty payouts
6. Sponsor count by tier
7. Treasury health score (balance / monthly burn rate)

## 7. Governance Changes

Any change to this policy requires a PIP:

- Pool percentage changes → PIP vote
- Multisig threshold changes → PIP vote
- Spending authority changes → PIP vote
- New inflow/outflow channels → PIP vote
- Emergency procedure changes → Emergency PIP (24-hour fast-track)

---

<sub>Treasury Policy Version: 0.1.0 | PIP-001 | Epoch: 0</sub>
