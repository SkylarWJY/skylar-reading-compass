# 💵 Fundraising / Term Sheet Protocol

> When the user is deciding: take this term sheet, raise vs bootstrap, valuation negotiation, VC selection.

---

## Default frame stack

### Frame 1 · 十亿教训 (#33) — Cap table preservation

**"Most 2000s Chinese internet billion-dollar failures had founders who lost control of their companies before they had a chance to win."**

Healthy cap table targets:

| Stage | Founder(s) total | Option pool | VC + Angel |
|-------|-----------------|-------------|-----------|
| Pre-seed | 80%+ | 10% | 10% |
| Seed | 65-70% | 15% | 15-20% |
| Series A | 50-55% | 15% | 30-35% |
| Series B | 35-40% | 15% | 45-50% |

**If your cap table deviates by 10%+ from these benchmarks → red flag.**

### Frame 2 · Horowitz (#29) — Choose the partner, not the firm

The VC's brand doesn't help you. The partner who sits on your board does.

Ask:
- Do they show up on weekends when shit hits the fan?
- Have they fired founders before? (Track record matters)
- Do they have other portfolio companies in your space that could conflict?
- What's their reputation among **failed** portfolio founders?

The last question is the most revealing. Most VCs are nice to winners. The signal is in how they treat the losers.

### Frame 3 · Thiel (#21) — Valuation as commitment

Higher valuation = higher growth expectation = more pressure to spend.

Counter-intuitive: **A lower valuation with more runway often beats a higher valuation with same runway.** Because:
- You retain more equity
- Lower bar for next round
- Less death-march growth pressure

### Frame 4 · 大败局 II (#32) — The fundraising-dependence trap

If you NEED to raise to survive in 12 months → you have negative leverage. VCs smell this.

Red lines:
- Burning at 1.5x revenue runway = need to fundraise within 6 months
- 0 revenue + 12 month runway = need to fundraise within 3 months
- Negative net retention = even raising won't save you

**Best fundraising posture: raise when you don't need to.**

### Frame 5 · Doerr (#97) — OKR-able terms

Every term sheet term should be testable against future OKRs:

- Liquidation preference 1x non-participating ✅ standard
- Liquidation preference 2x participating ❌ predatory
- Board seat: 1 VC + 2 founder + 1 independent ✅ healthy
- Board seat: 2 VC + 1 founder ❌ founder loses control
- Pro-rata rights: standard ✅
- Drag-along: needs founder threshold ✅
- Anti-dilution: weighted average (broad) ✅; ratchet ❌

---

## Decision flow

```
1. Do you NEED this money in next 6 months?
   └─ If yes → negative leverage, may need to take worse terms
   └─ If no → walk-away power, optimize terms

2. Cap table check
   └─ Where will founder % land post-money?
   └─ Compare to stage benchmarks

3. Partner due diligence
   └─ Reference call 3 founders the VC backed who FAILED
   └─ Ask: "What would you wish you'd known before signing?"

4. Terms audit
   └─ Run every term against "predatory vs standard" checklist
   └─ Push back on 1-2 terms even if you'd accept (signals you're sharp)

5. Pre-mortem
   └─ 24 months from now this deal is a regret because ___ (fill in 3)
```

---

## Anti-patterns to flag

- **Valuation lust** — taking the highest number from the worst partner
- **Brand chasing** — "Sequoia said yes" used as social proof, even with bad partner
- **Liquidation preference creep** — letting 2x or participating slip in
- **Pro-rata waiver** — never waive your pro-rata
- **Founder vesting reset** — VCs sometimes propose; usually unnecessary
- **Tranching with vague milestones** — measurable milestones only
- **Information rights without protection** — never give un-NDA'd financial detail to non-investors

---

## Output template

```markdown
📚 **Fundraising stack analysis · "[term sheet / decision]"**

**Cap table impact (十亿教训 #33):** [Post-money founder % + benchmark comparison]

**Partner quality (Horowitz #29):** [Reference signals + concerns]

**Valuation vs runway (Thiel #21):** [Is higher valuation actually worth it?]

**⚠️ Dependency check (大败局 II #32):** [Need-to-raise vs want-to-raise]

**Predatory terms scan (Doerr #97 OKR-able):**
- ✅ [Standard term]
- ⚠️ [Term to negotiate]
- ❌ [Term to refuse]

🚦 **Recommendation:** [Take / Negotiate / Walk]

**Red lines (walk if any present):**
- [e.g., 2x participating liquidation preference]
- [e.g., VC majority board]
- [e.g., Mandatory founder vesting reset]

**Negotiation moves (48h):**
1. [Specific term to push back on]
2. [Specific term to add]
3. [Backup option if they refuse]
```
