# Mega Pack Retail Pilot Proposal — POS Sell-Through Measurement
**Prepared by Vera for Connor Smith / Alexander Foster**
**Date:** March 29, 2026 | **Status:** DRAFT — Ready for Internal Review

---

## Executive Summary

FRE needs real sell-through data to measure Mega Pack's impact on category lift vs. cannibalization. MSA shipment data and Nielsen estimates are insufficient — we need store-level POS data. This proposal recommends **Skupos (now PDI CStore Essentials)** as the POS data partner and outlines a controlled retail pilot design.

---

## The Problem

| Data Source | What It Measures | Limitation |
|---|---|---|
| MSA | Manufacturer shipments to distributors | ≠ consumer purchases; inventory lag |
| Nielsen | Syndicated panel estimates | Spotty c-store coverage; TPB historically undertrusted |
| Retailer self-report | Varies | Inconsistent format, delayed, no control group |

**What we need:** Weekly store-level scan data showing actual consumer purchases, by SKU, across test and control stores.

---

## Recommended Platform: Skupos / PDI CStore Essentials

### Why Skupos

| Criteria | Skupos | Crisp | Alloy.ai |
|---|---|---|---|
| **C-store/tobacco focus** | ✅ Built for it — 30K+ indie c-stores | ❌ Broad CPG/grocery | ❌ Broad CPG/supply chain |
| **Tobacco scan data programs** | ✅ Core product — Altria/RJR integrations | ❌ Not specialized | ❌ Not specialized |
| **Independent retailer coverage** | ✅ 60%+ independently owned stores | ⚠️ Limited | ⚠️ Limited |
| **POS integration** | ✅ Clover, 25+ POS systems | ✅ EDI/API | ✅ API |
| **Pricing (retailer side)** | $19-75/store/mo (retailer pays) | Enterprise pricing | Enterprise pricing |
| **Brand-side analytics** | ✅ Dashboard + scan data exports | ✅ Dashboard | ✅ Dashboard |
| **Tobacco-specific compliance** | ✅ Altria DTP requirements baked in | ❌ | ❌ |

**Verdict:** Skupos is the only platform purpose-built for tobacco in independent c-stores. Crisp/Alloy are better for grocery/DTC — wrong channel for FRE.

### Skupos Pricing (Brand Side)

- **Retailer-facing:** $19/store/mo (Scan Data Basic) to $75/store/mo (Tobacco Loyalty Plus)
- **Brand/manufacturer programs:** Negotiated; typically structured as scan data participation fees or co-funded promotions
- **Estimated brand cost for pilot:** $500–$2,000/mo for data access + analytics (varies by store count and program structure)
- **Key detail:** Many retailers already on Skupos for Altria/RJR scan data programs — TPB may be able to piggyback on existing infrastructure

### How It Works for TPB

1. **TPB enrolls as a brand partner** on PDI CStore Essentials platform
2. **Select pilot stores** already connected to Skupos (reduces onboarding friction)
3. **Weekly automated scan data** flows into Skupos dashboard — FRE SKU-level sell-through
4. **Vera builds analysis layer** on top of exported data (cannibalization metrics, category lift, velocity)

---

## Pilot Design

### Structure

| Parameter | Specification |
|---|---|
| **Test stores** | 20–25 stores carrying Mega Pack |
| **Control stores** | 20–25 matched stores (same chain/region, NO Mega Pack) |
| **Pre-period baseline** | 8 weeks before Mega Pack placement |
| **Test period** | 12–16 weeks active measurement |
| **Total duration** | ~6 months (incl. setup + analysis) |
| **Geography** | States where FRE has 10%+ share (maximize signal-to-noise) |
| **Store matching criteria** | ACV band, tobacco category volume, competitive set, urban/suburban mix |

### What We Measure

| Metric | Definition | Why It Matters |
|---|---|---|
| **FRE Mega Pack velocity** | Units/store/week | Core performance metric |
| **FRE standard can velocity** | Units/store/week (vs. control) | Cannibalization signal |
| **Total FRE brand volume** | All FRE SKUs combined | Net brand lift vs. format shift |
| **Category share** | FRE % of total nicotine pouch category | Competitive displacement |
| **Incrementality rate** | (Test total - Control total) / Control total | The headline number Connor needs |
| **Price sensitivity** | Velocity at different price points if varied | Pricing optimization |

### Success Criteria

| Outcome | Threshold | Implication |
|---|---|---|
| 🟢 Clear winner | >15% incremental FRE volume, <10% cannibalization | Scale nationally |
| 🟡 Mixed signal | 5-15% incremental, 10-25% cannibalization | Refine pricing/placement, extend pilot |
| 🔴 Net negative | <5% incremental OR >25% cannibalization | Rethink Mega Pack positioning |

---

## Budget Estimate

| Line Item | Low | High |
|---|---|---|
| Skupos brand partnership / data access | $3,000 | $8,000 |
| Store incentives / placement fees (50 stores × $100-200) | $5,000 | $10,000 |
| Mega Pack inventory for test stores | $8,000 | $15,000 |
| Vera analytics layer (built in-house — $0) | $0 | $0 |
| Contingency (10%) | $1,600 | $3,300 |
| **Total** | **$17,600** | **$36,300** |

Timeline: 4-month active pilot, 6 months total including setup and analysis.

---

## Reusability

This infrastructure isn't just for Mega Pack. Once established:

| Future Launch | Uses Same Infrastructure |
|---|---|
| Peppermint LTO | ✅ Same stores, same measurement framework |
| Smooth (permanent line) | ✅ Category lift measurement |
| FRE Labs SKUs | ✅ New brand/line velocity tracking |
| Retailer negotiations | ✅ "Here's proof FRE grows the category" |

**One investment → measurement capability for every future launch.**

---

## Recommended Next Steps

1. **Xander/Connor:** Review and approve pilot scope + budget range
2. **Xander:** Reach out to Skupos/PDI for brand partnership conversation (or have trade marketing initiate)
3. **Vera:** Build the analysis dashboard framework in parallel (ready before data flows)
4. **Trade team:** Identify 50 candidate stores in FRE-strong markets
5. **Target start:** June 2026 (pre-period baseline), August 2026 (Mega Pack placement)

---

*This proposal is Connor-ready. Sans-serif, bullets over prose, clear decision points.*
