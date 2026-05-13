# Cultural Debt™ Calculator
**Culture Shift Consulting Group**
cultureshiftconsultinggroup.com

---

## Overview

An interactive business intelligence tool built for VPs of Engineering and R&D to quantify the annual operational cost of cultural debt across their engineering organization. Built and maintained by Norrils Signature Consulting Inc.

---

## Your Live Tool URLs

**Calculator:**
`https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-calculator.html`

**VP Summary Report:**
`https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-vp-summary.html`

**AI Debt Calculator (standalone — linked from VP Summary):**
`https://Armers-ops.github.io/cultural-debt-calculator/ai-debt-calculator.html`

**Consulting Brief (internal use only):**
`https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-armers-brief.html`

---

## Files in This Repository

| File | Purpose |
|---|---|
| `cultural-debt-calculator.html` | Client-facing 3-step calculator |
| `cultural-debt-vp-summary.html` | Executive summary — auto-opens after submission |
| `ai-debt-calculator.html` | Standalone AI Debt diagnostic — linked from VP Summary |
| `cultural-debt-armers-brief.html` | Internal consulting brief — not for client distribution |
| `cscg-logo-white-text.png` | Culture Shift Consulting Group logo — white text for dark backgrounds |
| `index.html` | Redirects base URL to the calculator |
| `README.md` | This file |

---

## The Six Cultural Debt Drivers

| # | Driver | What It Measures |
|---|---|---|
| 1 | **Manager Capability Gap** | Root amplifier — creates and worsens all other debts |
| 2 | **Psychological Safety Deficit** | Voice Suppression + Failure Punishment Reflex combined (15% overlap discount) |
| 3 | **Decision Velocity Debt** | Cost of slow, unclear, or avoided decisions across engineering leadership |
| 4 | **Cross-Functional Friction Debt** | Misalignment and communication breakdown between engineering and adjacent functions |
| 5 | **Shadow Management** | VP time and salary consumed managing cultural friction instead of innovation |
| 6 | **Brilliant Jerk Immunity** | Tolerated toxicity driving attrition and suppressing team output |

---

## Calculation Methodology

### Base Variable
```
totalPayroll = employees × salary
```

### Driver Formulas

**1. Manager Capability Gap**
```
employees × managerPct × salary × 0.34
```
Source: Gallup 2025 — disengagement costs 34% of salary per affected employee

**2. Psychological Safety Deficit (Combined)**
```
rawVoiceCost   = employees × psychPct × salary × 0.19
rawFailureCost = totalPayroll × psychPct × 0.20
psychSafetyCost = (rawVoiceCost + rawFailureCost) × 0.85
```
0.85 discount eliminates the ~15% double-count on shared psychological safety root cause.
Sources: Google Project Aristotle 2016; McKinsey 2022

**3. Decision Velocity Debt**
```
totalPayroll × decisionPct × 0.15
```
Sources: McKinsey & Company, Reimagine Decision Making, 2020; McKinsey Global Tech Agenda, 2026

**4. Cross-Functional Friction Debt**
```
totalPayroll × crossFuncPct × 0.22
```
Sources: Standish Group CHAOS Report, 2020; McKinsey Digital Transformation Research, 2023

**5. Shadow Management — 3-Layer Formula**
```
Layer 1: $220,000 × shadowPct
Layer 2: totalPayroll × 0.08 × shadowPct
Layer 3: (employees ÷ 160,000,000) × $359,000,000,000 × shadowPct
shadowCost = Layer1 + Layer2 + Layer3
```
VP salary basis: $220,000 midpoint — PayScale 2026 ($189,022), Indeed 2026 ($211,505), Salary.com 2025 ($244,877).
Source: Harvard CEO Study 2018; CPP Inc./Myers-Briggs

**6. Brilliant Jerk Immunity**
```
employees × brilliantJerkPct × salary × 0.22
```
Source: Dylan Minor HBS 2015; Christine Porath Georgetown 2022

---

## How the Tool Works

1. VP completes Step 1 — workforce inputs
2. VP completes Step 2 — adjusts 6 cultural debt sliders
3. Results page shows total Cultural Debt™ cost broken down across all 6 drivers
4. VP enters email — VP Summary opens automatically in a new tab
5. VP Summary shows cost breakdown with research citations
6. VP clicks **Calculate AI Debt →** — passes headcount and salary to AI Debt Calculator
7. Armers receives BCC of every submission at armers@csc-grp.com

---

## EmailJS Configuration

| Setting | Value |
|---|---|
| Public Key | `kTIzJ4hpEYE4LWi-w` |
| Service ID | `service_mefsi0n` |
| Template ID | `fj6x3a8` |
| BCC | `armers@csc-grp.com` |

---

## WordPress Embed Code

```html
<iframe
  src="https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-calculator.html"
  width="100%"
  height="900px"
  frameborder="0"
  scrolling="yes"
  style="border:none; border-radius:12px; max-width:780px; display:block; margin:0 auto;">
</iframe>
```

---

## Intellectual Property

Cultural Debt™ and Cultural Debt Index™ are the exclusive intellectual property of Armers Moncure and Culture Shift Consulting Group. Not for redistribution without written permission.

---

## Built By

Norrils Signature Consulting Inc. (NSC)
LaVonne Norrils, Founder & CEO
norrilssignature.com
