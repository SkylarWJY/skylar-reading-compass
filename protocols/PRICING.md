# 💰 Pricing Decision Protocol

> When the user is deciding: pricing tier, price point, free-vs-paid, enterprise vs PLG.

---

## Default frame stack

Pull these 4-5 books for any pricing decision:

### Frame 1 · 俞军 (#37) — User value formula

```
User value = New experience - Old experience - Replacement cost
```

The **replacement cost** is the killer term most pricing decisions ignore. Ask:
- What is the user's current workflow? (Excel, Notion, manual, competitor)
- What's the switching effort? (Data migration, team training, habit)
- Is our delta > 5x the switching cost? If not, price near zero or invest in onboarding.

### Frame 2 · 梁宁 (#36) — Three value layers

```
Product value = Functional value + Emotional value + Asset value
```

- Pricing at **functional value only** → commodity → race to bottom
- Pricing at **functional + emotional** → SaaS standard ($X-$XX/mo)
- Pricing at **functional + emotional + asset** → Bloomberg-tier ($XXX-$XXXX/mo)

Where is your product positioned? If you're trying to charge Bloomberg pricing but only delivering functional value, you'll fail.

### Frame 3 · Cialdini (#52) — Anchoring + scarcity

- **Anchor high then discount**: $999 → $299 founding member = better than $299 outright
- **Limited tier**: "First 50 customers" creates urgency (works only if real)
- **3-tier psychology**: Cheap / Mid / Premium → most pick Mid. Design Premium specifically to make Mid look reasonable.

### Frame 4 · 张小龙 (#34) — Simplicity discipline

Pricing pages with 4+ tiers reduce conversion. 80% of B2B SaaS overcomplicates.

Default: **3 tiers max** + "Contact sales" for enterprise.

### Frame 5 · 大败局 II (#32) — The庞氏化 red flag

If your pricing requires:
- Continuous new customer acquisition to cover existing customer cost
- LTV/CAC < 1.5 even at scale
- "We'll figure out monetization later"

→ You're not pricing, you're delaying death. Re-architect.

---

## Decision flow

```
1. What value layer are you delivering? (Functional/Emotional/Asset)
   └─ Mismatch with price = wrong tier

2. What's the replacement cost for your user?
   └─ High switching → price near zero OR invest in migration
   └─ Low switching → can price higher

3. Run anchoring math
   └─ What's the natural anchor? (Competitor / replacement cost / cost saved)
   └─ Design tiers to make middle look "obvious"

4. Failure case check
   └─ Will you survive if monetization is delayed 18 months? (大败局 II red flag)

5. Commit
   └─ Default for SaaS B2B: $99 / $299 / $999 + custom enterprise
```

---

## Anti-patterns to flag

- **Pricing by competitor** without unit economics check
- **Free forever tier** without paywall trigger (death by infrastructure cost)
- **Annual-only** for early product (users won't commit to unproven)
- **Per-seat without value-add** (commodity-feeling)
- **Custom pricing for everyone** (PMF signal failure — you don't know what you're worth)

---

## Output template

When the user asks a pricing question, return:

```markdown
📚 **Pricing stack analysis · "[their question]"**

**Value layer (梁宁 #36):** [Functional / Emotional / Asset assessment]

**Replacement cost (俞军 #37):** [High / Medium / Low + what they switch from]

**Anchoring frame (Cialdini #52):** [Suggested anchor]

**Tier design (张小龙 #34):** [Recommended # of tiers and rationale]

**⚠️ Failure check (大败局 II):** [庞氏化 risk assessment]

🚦 **Recommended pricing:** [Specific number(s)]

**Red lines:**
- If [X], drop tier 1 to $0
- If [Y], add usage cap
- If [Z], pause pricing experiment

**Next action:** [One thing this week]
```
