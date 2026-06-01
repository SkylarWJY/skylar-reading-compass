# 👥 Hiring Decision Protocol

> When the user is deciding: who to hire, when to hire, hire vs contractor, fire vs coach.

---

## Default frame stack

### Frame 1 · Hastings (#98) — Keeper Test

Ask: **"If [candidate] told me tomorrow they're leaving for another company, would I fight to keep them — or feel relief?"**

- Fight to keep → hire / promote / raise
- Feel relief → don't hire / fire / give severance

This test cuts through interview noise. Apply it pre-offer **and** every 6 months post-hire.

### Frame 2 · Eric Schmidt (#26) — Smart Creatives over generalists

Hire for:
- Technical depth + business sense (rare combo)
- Self-direction (not "needs PM to ship")
- Comfort with ambiguity (startup default state)
- Low ego + high candor

Avoid:
- "Industry veterans" who need playbooks
- People who interview well but project-pitch their own work
- "Polished" candidates who can't disagree

### Frame 3 · Horowitz (#29) — Hire for strengths, not lack of weaknesses

Wartime hiring: every hire should be **best-in-world at ONE thing** that maps to your top 3 problems right now.

Don't hire "well-rounded" — hire spiky. Round out gaps with other spiky hires.

### Frame 4 · Andy Grove (#27) — Manager Output formula

```
Manager Output = Output of team × Leverage
```

When considering a hire, ask: **What's the leverage this hire creates for the existing team?**

- ✅ "BDR who lets 2 SDE focus on building" = high leverage
- ❌ "Senior engineer who duplicates founder's coding" = low leverage

### Frame 5 · 大败局 II (#32) + 十亿教训 (#33) — Team chemistry vs CV trap

> "8848 had王峻涛 + 谭智 + 苏启强 + 毛一丁 — any one CV is dazzling. But they didn't form a strong-execution team."

**The CV is necessary but not sufficient.** The bar is: does this person make the existing team stronger or weaker on day 1?

Red flag: "Star hire" with great resume but team chemistry concerns. Don't override your gut.

---

## Decision flow

```
1. What's the top 3 problem this hire solves?
   └─ If no clear top-3 match → don't hire yet

2. Keeper Test: would you fight to keep them in 6 months?
   └─ If "feel relief" → pass

3. Smart Creative check
   └─ Self-direction / ambiguity tolerance / candor signals

4. Leverage math (Grove)
   └─ Does this hire 2-5x existing team? Or just adds linearly?

5. Chemistry stress test (十亿教训)
   └─ Schedule 1 lunch with the team. Watch for tension.

6. Pre-mortem
   └─ "12 months from now, why did this hire fail?" — name 3 ways
```

---

## Anti-patterns to flag

- Hiring to **fill a role** rather than solve a problem
- Hiring for **future scale** before PMF (premature optimization)
- Hiring **the safe candidate** when no candidate is great (delay)
- "Hire fast, fire fast" → actually fires slow, costs trust
- Hiring **founder's friends** without keeper test
- **Brilliant jerk** (high output, toxic culture) → must fire

---

## Output template

```markdown
📚 **Hiring stack analysis · "[role/candidate]"**

**Top 3 problem fit (Grove #27):** [Which top-3 problem does this solve?]

**Keeper Test (Hastings #98):** [Fight to keep / Feel relief / Unclear]

**Smart Creative signals (Schmidt #26):** [3 evidence points or 3 gaps]

**Leverage assessment:** [Linear add / 2x / 5x leverage and why]

**⚠️ Chemistry check (十亿教训 #33):** [Risks with existing team]

🚦 **Recommendation:** [Hire / Pass / Hold for 30 days]

**Red lines (pass if any present):**
- [Specific red flag]
- [Specific red flag]
- [Specific red flag]

**Next action:**
- If hire: [specific 48h step]
- If pass: [explanation owed to candidate]
- If hold: [what data to gather]
```
