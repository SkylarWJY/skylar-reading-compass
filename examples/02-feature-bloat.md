# Example 02 · "Should we add AI auto-outreach?"

> When the founder wants to ship; the compass pressure-tests it.

---

## The decision

**Founder asks:**

> "Our AI GTM platform helps founders find alpha creators. Three customers asked us to add a feature: auto-generate AND auto-send cold emails to identified creators. Engineering says 4 weeks. The CEO of customer A said 'this is the killer feature.' Should we ship?"

---

## Compass output

```markdown
📚 **Feature stack analysis · "Add AI auto-outreach (auto-generate + auto-send)?"**

**张小龙 7-question (#34):** Score 2/7
- ❌ Can users explain in 1 sentence? Yes — "AI sends my cold emails"
- ❌ Would 30% be angry if removed? Probably yes, but...
- ✅ Activates which 7-sin? Sloth (skip manual work)
- 🚨 Works in 60 seconds? NO — requires email integration + 信誉 setup
- 🚨 Make users want to share? NO — embarrassing if AI sends bad emails
- 🚨 Preserves Sage character? NO — auto-execute = magic-box, not insight
- 🚨 What gets deprioritized? You'd need to name it before shipping

**Discovery test status (Cagan #42):**
- ❌ Value test: NOT DONE — 3 customer asks ≠ smoke test
- ❌ Usability test: NOT DONE — no prototype shown to non-asking customers
- ⚠️ Feasibility test: 4 weeks estimated — but no spike done
- ❌ Business test: NOT DONE — what's CAC impact? LTV impact?

**Replacement cost (俞军 #37):**
- Old experience: founder writes cold emails (10 min each)
- New experience: AI writes + sends (30 seconds)
- Switching cost: HIGH — email reputation, account setup, trust in AI quality
- New exp must be 3x+ better than old: tight, depends on quality

**60s test (任天堂 #41):**
- ❌ Cannot pass 60s test — requires email account integration
- A "draft mode" version might pass — generate + show, user approves

**⚠️ Scope creep (大败局 II #32):**
- Current product = find alpha creators (1 product line)
- Adding auto-outreach = 2nd product line (outbound automation)
- Different ICP signal: alpha-finders ≠ outreach-automators
- 战线过长 ALERT

**⚠️ Bonus frame (张亚勤 X2 · 3R Principle):**
- R1 Robust: AI-generated emails fail QA frequently
- R2 Responsible: Cold email auto-send is borderline spam (CAN-SPAM concerns)
- R3 Resilient: AUTO-SEND violates human-in-the-loop principle
- → Enterprise customers (Anthropic/Scale-tier) will REJECT this on compliance

---

🚦 **Verdict:** NO to auto-send. YES to AI-draft-with-human-approve.

**Red lines (kill the auto-send version entirely):**
- Any customer reporting a recipient threatened legal action
- Spam classification rate > 5% in test cohort  
- Enterprise customer says compliance can't approve

**What to build instead (next 4 weeks):**
1. **Week 1**: Smoke landing page for "AI Draft Outreach (Human Approve)" — measure CTR
2. **Week 2**: Build draft generator + approval UI (NOT auto-send)
3. **Week 3**: Roll out to 3 asking customers as beta — track approval rate
4. **Week 4**: If approval rate > 80% AND no complaints → ship public

**Next action (48h):**
- Email 3 asking customers: "We're shipping AI-draft-with-approve in 4 weeks. 
  Auto-send is on roadmap pending compliance review. Does draft-mode unblock 
  you now?" → measures whether they REALLY want auto-send or just want the 
  drafting help.
```

---

## Why this output works

**Reframes the decision:**
- Founder's question: "Should we ship auto-outreach?"
- Compass reframes: "Is the autonomous part actually what customers need, or do they want AI drafting + human approval?"

**Names the 战线过长 trap:**
- Adding outreach automation = 2nd product line = different ICP
- This is the #1 post-PMF killer (大败局 II frame)

**Compliance check from new tech:**
- 张亚勤 X2's 3R principle catches what classic product books miss
- For B2B AI in 2025+, compliance is the new moat-breaker

**Tests the customer ask:**
- "3 customers asked" → reframed as "have you tested the cheaper version?"
- 1 specific outreach to 3 customers can resolve this in 48 hours

**Commits direction:**
- Not "it depends on your engineering capacity"
- Specific: NO to auto-send, YES to draft-with-approve, 4-week plan

---

## The reading library value

Without the compass, the founder might have:
- Spent 4 weeks shipping auto-send
- Triggered spam complaints
- Lost enterprise customers on compliance
- Diluted product focus to 2 product lines

With the compass (60 seconds of analysis): saved 4 weeks + preserved focus + identified the actual product (draft-with-approve) customers needed.

**ROI of a compass:** roughly 200x the time spent.
