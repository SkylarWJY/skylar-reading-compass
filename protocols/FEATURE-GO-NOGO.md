# 🛠 Feature Go/No-Go Protocol

> When the user is deciding: ship this feature, add this AI capability, expand scope, build vs buy.

---

## Default frame stack

### Frame 1 · 张小龙 (#34) — Can you NOT add this?

Default answer: **NO, don't add it.**

Force yourself through the 7 张小龙 questions:
1. Can users explain this feature in 1 sentence?
2. Would 30%+ of users be angry if we removed it 90 days post-launch?
3. Does it activate a clear human-7-sin? (Greed/Envy/Sloth/Vanity)
4. Does it work in the first 60 seconds without onboarding?
5. Does it make users want to share?
6. Does it preserve product character (Sage / minimalist / focused)?
7. What gets deprioritized to ship this?

If 3+ answers are "no/unclear" → don't ship.

### Frame 2 · Cagan (#42) — Discovery before Delivery

Run all 4 discovery tests before engineering:

| Test | Tool | Time |
|------|------|------|
| Value test | Smoke landing page + "Sign up for early access" | 1 week |
| Usability test | Figma prototype + 5-user test | 3 days |
| Feasibility test | SDE 1-week spike | 5 days |
| Business test | Unit economics math | 2 days |

**No engineering until all 4 pass.**

### Frame 3 · 俞军 (#37) — Replacement cost math

User value = New exp - Old exp - **Replacement cost**

For new features, replacement cost includes:
- User has to learn the new feature (5-30 min)
- Existing workflow disruption
- Risk of confusion / regret

If new exp - old exp < 3x replacement cost → users won't switch even if you build it.

### Frame 4 · 任天堂 (#41) — First 60 seconds test

Every new feature needs:
- **Intuitive layer**: discoverable without tutorial
- **Surprise layer**: at least 1 hidden "金币时刻"
- **Story layer**: fits into larger 12-month user narrative

If feature can't pass first 60 seconds for a new user → ship 内部 only as power-user feature.

### Frame 5 · 大败局 II (#32) — Scope creep red line

If this feature pushes you to:
- 3+ product lines simultaneously → DECLINE
- Different ICP than current → DECLINE
- Different pricing tier mechanics than current → DECLINE
- 6+ months engineering for unknown demand → DECLINE

战线过长 is the #1 killer of post-PMF companies.

---

## Decision flow

```
1. 张小龙 7-question audit
   └─ 3+ "no" → kill the idea

2. Smoke test FIRST
   └─ Build the landing page in 1 day
   └─ Run for 1 week
   └─ Sign-up rate < 5% → kill

3. Replacement cost math
   └─ Is new exp 3x+ better than old?
   └─ If no, build onboarding instead of feature

4. 60-second test
   └─ Can a new user grok in 60s?
   └─ If no, scope down

5. Scope creep check
   └─ Does this push us to 3+ product lines?
   └─ If yes, REPLACE an existing feature, don't add
```

---

## Anti-patterns to flag

- **"Customer asked for it"** — single customer ≠ market signal
- **"Competitor has it"** — you're not them, your moat is different
- **"AI hot, we should add AI"** — feature chasing buzzword
- **"It's only X engineering days"** — opportunity cost > absolute cost
- **"We can always remove it later"** — never happens, users get attached
- **"Investor said we need it"** — investors aren't users

---

## Output template

```markdown
📚 **Feature stack analysis · "[feature name + brief description]"**

**张小龙 7-question (#34):** [Score X/7 + worst-scoring questions]

**Discovery test status (Cagan #42):**
- Value test: [done/pending + result]
- Usability test: [done/pending + result]
- Feasibility test: [done/pending + result]
- Business test: [done/pending + result]

**Replacement cost (俞军 #37):** [User pain to switch + does new exp justify?]

**60s test (任天堂 #41):** [Pass / Fail + what needs simplification]

**⚠️ Scope creep (大败局 II #32):** [Product line count + ICP drift risk]

🚦 **Recommendation:** [Ship / Kill / Smoke-test-first / Replace-existing]

**Red lines (kill if any present):**
- Smoke test conversion < 5%
- Engineering estimate > 6 weeks
- ICP would shift

**Next action (48h):**
- [Concrete: e.g., "Build smoke landing page, run for 1 week"]
```
