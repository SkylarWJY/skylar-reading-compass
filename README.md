<div align="center">

# 📚 Skylar's Reading Compass

### *55 founder-grade books, distilled into one Claude skill.*

**Stop reading 55 books. Just ask the compass.**

Route any product/pricing/team/IP/fundraising decision through a stacked perspective from Cagan + Trout + Cialdini + Christensen + 黄奇帆 + 吴晓波 + 俞军 + 谢胜子 + 张亚勤 — in seconds.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Books: 55](https://img.shields.io/badge/books-55_distilled-blue.svg)](#-the-library)
[![Status: Active](https://img.shields.io/badge/status-active-brightgreen.svg)]()
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange.svg)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills)

</div>

---

## 🎯 Why this exists

Every founder is told to "read 100 books." The advice is correct and useless — by the time you finish book 50, book 1's framework has decayed.

This skill solves the **retrieval problem** of being well-read.

I'm Skylar — AI founder (ANSIO), ex-Morgan Stanley AVP, Columbia Applied Analytics. Over 6 months I distilled 55 books that matter for founders into a single Claude skill that returns **multi-book stacked perspectives on any decision in seconds**.

**Before**: "Should I take this term sheet?" → 3 days of Twitter, podcasts, and gut-feel.
**After**: One question → stacked answer from Doerr (OKR cadence) + 大败局 II (cap table traps) + Cagan (PM mini-CEO clause) + 谢胜子 (利益锚点) + Christensen (next-curve thinking).

---

## ⚡ Quick start

### Option 1: Install as a Claude skill

```bash
git clone https://github.com/SkylarWJY/skylar-reading-compass.git ~/.claude/skills/skylar-reading-compass
```

Then in Claude:

```
用 reading compass 帮我分析：要不要接受这个 a16z term sheet?
```

Or trigger by phrase:
- `"book stack analysis for [decision]"`
- `"founder lens on [problem]"`
- `"用我的读书库看一下 [情境]"`
- `"what would the library say about [tradeoff]"`

### Option 2: Use as a reading list

Browse [`library/INDEX.md`](library/INDEX.md) for the 55-book curated list, organized into 9 clusters. Each book has a one-line distilled core + when-to-read trigger.

---

## 📖 The library (9 clusters · 55 books)

| Cluster | Books | When to invoke |
|---------|-------|----------------|
| **🏛 Macro & Foundations** | 5 | Understanding the field your startup operates in |
| **🇨🇳 China Context** | 5 | Anything involving Chinese markets, founders, or capital |
| **💥 Failure Case Library** | 3 | Pre-mortem before any major move |
| **🛠 Product Methodology** | 5 | Feature / Discovery / PM decisions |
| **🎨 Brand & Narrative** | 7 | Positioning / Marketing / Personal IP |
| **🧠 Growth & Persuasion** | 7 | Funnel / Conversion / Influence design |
| **👥 Management & Culture** | 6 | Hiring / OKR / Team design |
| **🚀 Startup Classics** | 8 | 0→1 / Founder strategy / Operator playbook |
| **💭 Mental OS** | 7 | Personal operating system / decision quality |
| **📊 Finance & Data** | 3 | Cap table / financials / measurement |

Plus **2 extra picks** (`X1`, `X2`) for time-sensitive intel (latest AI strategy + Chinese founder心法).

[See full index →](library/INDEX.md)

---

## 🧬 How the compass works

```
                    Your decision
                          │
                          ▼
              ┌───────────────────────┐
              │  Skylar's Reading     │
              │  Compass              │
              └───────────┬───────────┘
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
        ▼                 ▼                 ▼
   📚 Relevant      📋 Decision        ⚠️ Failure
   book frames     protocol           case match
        │                 │                 │
        └─────────────────┼─────────────────┘
                          ▼
                ┌─────────────────┐
                │ Stacked answer  │
                │ (3-5 angles +   │
                │  red lines +    │
                │  next action)   │
                └─────────────────┘
```

The skill doesn't paraphrase books. It does **stack analysis**:

1. **Pattern match** your decision to the right book clusters
2. **Pull frames** from 3-5 books that disagree productively
3. **Cross-check** against the failure case library (大败局 / 十亿教训 / 创业之殇)
4. **Apply protocols** (`protocols/PRICING.md`, `HIRING.md`, etc.)
5. **Return** an actionable answer with red lines

---

## 💡 Example: "Should we add this AI feature?"

**Without the compass:**
> Yeah, let's ship it. Users keep asking.

**With the compass:**

```markdown
📚 Stack analysis · "Add AI auto-outreach feature?"

▸ Cagan (Inspired #42): Run smoke test first. Fake-door, 
  measure CTR before engineering.
▸ 张小龙 (#34): "能不能不加?" → Test deletion before addition.
▸ 俞军 (#37): User value = new exp - old exp - 替换成本. 
  Replacement cost here is high (workflow disruption).
▸ 大败局 II (#32): "战线过长" red flag — already at 2 product 
  lines, this makes 3.
▸ 张亚勤 (X2) 3R: Auto-execute violates Resilient (human-in-loop). 
  Compliance bar for enterprise customers.

🚦 Verdict: NO — but build the smoke test landing page 
   this week and revisit in 30 days based on signal.
   
⚠️ Red lines: If you build it, must include human-approve gate.
```

5 sources. 60 seconds. Multi-angle stress test.

---

## 📂 What's inside

```
skylar-reading-compass/
├── SKILL.md              ← Claude skill entry (the engine)
├── README.md             ← You are here
├── library/
│   ├── INDEX.md          ← 55-book index, one-line cores
│   └── *.md              ← Per-cluster deep notes
├── protocols/
│   ├── PRICING.md        ← Pricing decision flow
│   ├── HIRING.md         ← Hiring decision flow
│   ├── FUNDRAISING.md    ← Term sheet & cap table protocol
│   ├── FEATURE-GO-NOGO.md
│   └── PERSONAL-IP.md
├── examples/
│   ├── 01-term-sheet.md
│   ├── 02-feature-bloat.md
│   └── 03-pricing-tier.md
└── LICENSE (MIT)
```

---

## 🛠 Customize for your founder context

The compass is **founder-agnostic** by default. To personalize:

1. Fork this repo
2. Add a `MY_CONTEXT.md` with your: company stage, ICP, current OKRs, recent decisions
3. The skill will weight book frames against your context when stacking

```bash
echo "I'm building [X] at [stage]. ICP is [Y]. Current bet: [Z]." > MY_CONTEXT.md
```

---

## 🗺 Roadmap

- [x] v1.0 · 55 books across 9 clusters
- [x] 5 decision protocols (pricing / hiring / fundraising / feature / IP)
- [ ] v1.1 · Add 20 more books (finance / VC / governance cluster)
- [ ] v1.2 · Voice trigger ("hey compass...")
- [ ] v1.3 · Anti-pattern library (50 failure modes from 大败局 family)
- [ ] v2.0 · Multi-language (EN/ZH bilingual stack answers)

PRs welcome for: new books, new protocols, fixes.

---

## ✍️ Credits

This skill stands on the shoulders of (incomplete):

Marty Cagan · Andy Grove · Stephen Covey · Robert Cialdini · Clay Christensen · Peter Thiel · Ben Horowitz · Eric Ries · Geoffrey Moore · Reed Hastings · John Doerr · Barbara Minto · Jake Knapp · Malcolm Gladwell · Jonah Berger · Margaret Mark · Joe Studwell · Greenspan ·

吴晓波 · 黄奇帆 · 温铁军 · 吴敬琏 · 俞军 · 梁宁 · 张小龙 · 雷军 · 张亚勤 · 谢胜子 · 华杉 · 杨飞 · 徐志斌 · 任正非 (via others) · 段永平 ·

— and many more. See [`library/INDEX.md`](library/INDEX.md) for the full attribution.

---

## 📬 About the curator

**Skylar Wang** — Founder of [ANSIO](https://ansio.ai) (Artificial Narrative & Signal Intelligence OS for AI GTM). Ex-Morgan Stanley AVP. Columbia MS Applied Analytics. Based in LA.

Building the Bloomberg Terminal for AI founders. This skill is the reading discipline behind it.

- 🐦 [@SkylarWJY](https://x.com/SkylarWJY)
- 💼 [LinkedIn](https://linkedin.com/in/SkylarWJY)
- 🌐 [ANSIO](https://ansio.ai)

---

## 📜 License

MIT — fork, remix, share, ship. Attribution appreciated but not required.

<div align="center">

**If this saves you 100 hours of reading, ⭐ the repo.**

*Built with discipline. Maintained out of obsession.*

</div>
