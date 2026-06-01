<div align="center">

# 📍 Reading Compass

### **Founder decisions, stacked through 60 books.**

Cagan · Trout · Cialdini · Christensen · Thiel · Horowitz · Hastings  
黄奇帆 · 吴晓波 · 俞军 · 梁宁 · 张小龙 · 雷军 · 谢胜子 · 张亚勤

**One Claude skill. 30 seconds. Every decision stress-tested.**

[![License: MIT](https://img.shields.io/badge/license-MIT-yellow)]()
[![Books](https://img.shields.io/badge/books-60_distilled-blue)](#-the-library)
[![Clusters](https://img.shields.io/badge/clusters-9-purple)]()
[![Protocols](https://img.shields.io/badge/protocols-5-orange)]()
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-black)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills)

[**Install**](#-install-in-one-line) · [**Library**](library/INDEX.md) · [**Examples**](examples/) · [**Why**](#-why-this-exists)

</div>

---

## 🧪 The 30-second demo

**Founder, 11pm, staring at term sheet:**
> Should I take this $2M @ $12M post from Sequoia?

**Reading Compass:**
```
📚 Stack analysis · "$2M @ $12M term sheet"

▸ 十亿教训 (#33)  · Cap table will land at 70% founder — borderline thin
▸ Horowitz (#29)  · Firm fired 2 founders in 18 months — reference-call them
▸ Thiel (#21)     · Lower valuation + more runway > higher valuation + same
▸ 大败局 II (#32)  · 5 months runway = NEGATIVE leverage in negotiation
▸ Doerr (#97)     · 1 VC + 2 founder + 0 independent board = imbalanced

🚦 TAKE — with 3 conditions:
   1. Reference-call the 2 fired founders (not VC's intros)
   2. Push for $2.5M @ $11M instead
   3. Add independent board trigger at Series A

⚠️  Walk lines: fired founders report partner hostile · 
                pro-rata >100% · participating preference

⏱  48h action: email negotiation moves + 2 backup reference calls
```

5 books. 30 seconds. Decision-grade analysis with red lines.

---

## 🎯 Install in one line

```bash
git clone https://github.com/SkylarWJY/skylar-reading-compass.git ~/.claude/skills/reading-compass
```

Then ask Claude anything:

```
用 reading compass 帮我分析：要不要 ship 这个 feature?
book stack analysis: should I quit my BigTech job?
compass me on pricing for our B2B AI tool
founder lens on co-founder equity split
```

---

## 🧬 Why this exists

Every founder is told to "read 100 books." The advice is correct and useless — by book 50, book 1's framework has decayed.

**The Reading Compass solves the retrieval problem.**

Read once. Distill. Stack. The skill pulls the right 3-5 frames against your decision in seconds. Not summary. **Disagreement.**

> Cagan says smoke-test first. 张小龙 would say "can you NOT add this at all?"  
> Two different questions. One assumes you'll ship. The other pressure-tests whether to.  
>  
> A summary engine flattens this. **A compass surfaces it.**

---

## 📖 The library — 60 books, 9 clusters

| Cluster | # | Anchor authors |
|---|---|---|
| 🏛 **Macro & Foundations** | 5 | 黄奇帆 · Studwell · Greenspan · 温铁军 · 吴敬琏 |
| 🇨🇳 **China Context** | 8 | 雷军 · 段永平 · 柳井正 · 沃尔顿 · 吴晓波 |
| 💥 **Failure Library** | 3 | 大败局 I+II · 十亿教训 |
| 🛠 **Product Methodology** | 5 | Cagan · 张小龙 · 梁宁 · 俞军 · 玉树真一郎 |
| 🎨 **Brand & Narrative** | 7 | Trout · 华杉 · Berger · Gladwell · Mark · Holt |
| 🧠 **Growth & Persuasion** | 7 | Eyal · Cialdini · Ferrier · 杨飞 · 徐志斌 |
| 👥 **Management & Culture** | 6 | Grove · Doerr · Hastings · Schmidt · McCord · Covey |
| 🚀 **Startup Classics** | 9 | Thiel · Horowitz · Ries · Christensen · 柳井正 |
| 💭 **Mental OS** | 7 | Covey · Knapp · Minto · Browne · 谢胜子 · 张亚勤 |
| 📊 **Finance & Data** | 3 | Croll · 张新民 · Desai |

➕ **2 timely picks** in `番外`: 谢胜子 (founder心法 · 公众号合集) + 张亚勤 (post-DeepSeek AI strategy)

**Want the full one-line index?** → [`library/INDEX.md`](library/INDEX.md)

---

## 📋 5 decision protocols

The compass runs differently for different decisions. Each protocol pulls a tailored 5-book stack:

| Protocol | Anchor question | Stack composition |
|----------|----------------|-------------------|
| 💰 [**Pricing**](protocols/PRICING.md) | What value layer am I at? | 梁宁 · 俞军 · Cialdini · 张小龙 · 大败局 II |
| 👥 [**Hiring**](protocols/HIRING.md) | Keeper Test + leverage | Hastings · Schmidt · Horowitz · Grove · 十亿教训 |
| 💵 [**Fundraising**](protocols/FUNDRAISING.md) | Cap table preservation | 十亿教训 · Horowitz · Thiel · 大败局 II · Doerr |
| 🛠 [**Feature go/no-go**](protocols/FEATURE-GO-NOGO.md) | Can you NOT add it? | 张小龙 · Cagan · 俞军 · 任天堂 · 张亚勤 |
| 🎤 [**Personal IP**](protocols/PERSONAL-IP.md) | 支点优势 + archetype | Trout · Mark · 谢胜子 · Berger · 谢胜子 |

---

## 🧠 How a compass differs from a chatbot

|  | Generic AI advice | Reading Compass |
|---|------------------|-----------------|
| **Source** | Internet aggregate | 60 books, curated by a founder |
| **Stance** | "It depends" | Commits to a verdict |
| **Output** | One framing | 3-5 frames, productively disagreeing |
| **Failure** | Skipped | Mandatory pre-mortem from 大败局 family |
| **Action** | Vague | One 48-hour concrete step |
| **Voice** | Generic | Bilingual, founder-direct, 拒绝鸡汤 |

---

## 🚀 Make it yours

The skill is **founder-agnostic** by default. Personalize with one file:

```bash
echo "I'm building [X] at [stage]. ICP: [Y]. Current bet: [Z]." \
  > ~/.claude/skills/reading-compass/MY_CONTEXT.md
```

The skill will weight book frames against your specific context when stacking.

---

## 🗺 Roadmap

- [x] **v1.0** · 60 books · 9 clusters · 5 protocols
- [ ] **v1.1** · +20 books (VC playbook + engineering management)
- [ ] **v1.2** · Anti-pattern library (50 failure modes deep-dive)
- [ ] **v1.3** · Bilingual stack answers (full EN/ZH output)
- [ ] **v2.0** · Conversational decision interviewer (Claude asks the right clarifying questions before stacking)

PRs welcome. Bring your own books.

---

## 👤 Curator

**Skylar Wang** · Founder of [ANSIO](https://ansio.ai) — Artificial Narrative & Signal Intelligence OS for AI GTM.

> Ex-Morgan Stanley AVP. Columbia MS Applied Analytics. Based in LA.  
> Building the Bloomberg Terminal for AI founders.  
> This skill is the reading discipline behind it.

[𝕏 @SkylarWJY](https://x.com/SkylarWJY) · [LinkedIn](https://linkedin.com/in/SkylarWJY) · [ansio.ai](https://ansio.ai)

---

## 📜 License

**MIT** — fork, remix, ship. Attribution appreciated but not required.

The books themselves remain the IP of their authors. If a frame in this skill changes how you think — buy the original book. They earned it.

---

<div align="center">

**If this saves you 100 hours of reading, ⭐ the repo.**  
**If it saves you 1 bad decision, tell someone.**

*Built with discipline. Maintained out of obsession.*

</div>
