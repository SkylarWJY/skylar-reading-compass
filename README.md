<div align="center">

# 📍 Reading Compass

### *Founder decisions, stacked through 61 books.*

> Built on the legendary [**行者**](#-credits) 100-book founder reading list  
> *([@行者](#-credits) · 小红书 · 抖音 · 百万博主)*  
> Distilled. Stack-analyzed. Shipped as a Claude skill.

**61 / 100 books distilled · 9 clusters · 5 decision protocols · 1 skill**

[![License: MIT](https://img.shields.io/badge/license-MIT-yellow)]()
[![Books](https://img.shields.io/badge/books-61%20%2F%20100-blue)](library/INDEX.md)
[![Source](https://img.shields.io/badge/source-行者书单-red)]()
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-black)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills)
[![中文](https://img.shields.io/badge/中文-README-green)](README.zh.md)

[**Install**](#-install-in-one-line) · [**Library**](library/INDEX.md) · [**Examples**](examples/) · [**中文**](README.zh.md)

</div>

---

## 🎬 The 30-second demo

**Founder, 11pm, staring at a term sheet:**
> Should I take $2M @ $12M post from this Tier-1 VC?

**Reading Compass replies:**
```
📚 Stack analysis · "$2M @ $12M term sheet"

▸ 十亿教训 (#33)  · Founder lands at 70% — borderline thin for next round
▸ Horowitz (#29)  · Firm fired 2 founders in 18mo — reference-call them
▸ Thiel (#21)     · Lower valuation + more runway > higher + same
▸ 大败局 II (#32)  · 5mo runway = NEGATIVE leverage in negotiation
▸ Doerr (#97)     · 1 VC + 2 founder + 0 independent board = imbalanced

🚦 TAKE — with 3 conditions:
   1. Reference-call the 2 fired founders (NOT VC's intros)
   2. Push for $2.5M @ $11M instead
   3. Add independent board trigger at Series A

⚠️  Walk lines: hostile fired-founder reports · pro-rata >100% · 
                participating preference

⏱  48h: email negotiation moves + 2 backup reference calls
```

**5 books. 30 seconds. Decision-grade analysis with red lines.**

Not a summary engine. A **disagreement engine**.

---

## 🔬 Why this is actually useful (not yet another book list)

**Every book is distilled across 5 angles, not 1.** That's the architectural decision that makes the skill genuinely useful — and what separates it from "I read a book, here's a summary."

```
                  📚 ONE BOOK
                        │
   ┌──────────┬─────────┼─────────┬──────────┐
   │          │         │         │          │
   ▼          ▼         ▼         ▼          ▼
公司战略    创业战术    个人现金流   失败红线   30/60/90
Company   Startup    Personal   Failure    Action
   │          │         │         │          │
   └──────────┴─────────┼─────────┴──────────┘
                        │
                        ▼
              + AI 时代改写
              + Cross-book stacking
```

### Sample: "Influence" (Cialdini #52) actually yields

> "Founder's work isn't to 'explain value' — it's to fire 6 psychological triggers in sequence. Sales cycle length = inverse of how completely you deploy the 6 principles."

| Angle | What the skill returns |
|---|---|
| 🏢 **Company** | Cold email 第一封必带 specific report (互惠激活), CTR ↑ 3x |
| 🚀 **Startup** | Target: 6 principles fully deployed → sales cycle 90 days → 30 days |
| 👤 **Personal** | 6 principles also a BS detector — spot which one is being run on YOU |
| ⚠️ **Red line** | Overuse = manipulation = trust reversal at 5x normal speed |
| ⏱ **48h action** | Audit your 5 most recent cold emails — name which principle each fires |
| 🤖 **AI era** | LLM lets you generate personalized互惠 reports at scale — but creepy line is real |

**One book. Six different lenses. Not philosophy — operating instructions.**

### Sample one-liners (Part 4 of every distillation)

The skill commits to a final "if you remember one sentence" line for each book. These are NOT summaries. They're calibrated for action:

> **#34 张小龙**: Product 经理不是加功能的人，是 standing-next-to-God 决定哪些功能不该存在的人。每一次"删"比每一次"加"更重要。

> **#36 梁宁**: 产品不是功能，是三层价值的组合 + 认知战 + 关系 4 次第。SaaS 天花板差异 100x 不在功能，在情绪和资产价值层是否做出来。

> **#92 Covey**: 高效能不是技巧，是 OS。Founder 这场仗 5 年看技巧，10 年看品格。

> **#98 Hastings**: 先建人才密度 → 再做极致坦诚 → 最后减管控。顺序不能跳。3 人时的 default 就是 500 人时的文化基因。

> **#32 大败局 II**: 做大不等于成功。所有失败者在 plummet 前都觉得自己势不可挡。成功是中间状态，不是终点。

> **#X1 谢胜子**: 利益锚点清晰 + 杠杆 + 苟着小赢 + 看破不说破 + 物种同频 = 中国语境下成年人操盘自己的 5 件法器。

### What this means for you

Most "AI book summary" tools give you **the book's TOC, rephrased**.

Reading Compass gives you:
- A 12-15 KB structured distillation per book (4 parts, 9 subsections)
- 5+ angles on every framework: 公司 / 创业 / 个人 / 失败 / 行动
- Cross-book stacking that surfaces productive tension
- AI-era recontextualization (every framework re-asked: "does this still hold post-GPT?")
- Concrete 30/60/90 actions, not vague principles

→ When you ask the compass a decision question, you don't get one book's flat answer. You get **5 books arguing productively + a committed verdict**.

---

## 🎯 Install in one line

```bash
git clone https://github.com/SkylarWJY/skylar-reading-compass.git ~/.claude/skills/reading-compass
```

Then ask Claude anything:

```
"用 reading compass 帮我分析：要不要 ship 这个 feature?"
"book stack analysis: should I quit my BigTech job?"
"compass me on pricing for our B2B AI tool"
"founder lens on co-founder equity split"
```

---

## 💡 Why this exists

> 「读100本书」是创业者最常听到的建议，也是最没用的建议之一。  
> 读到第 50 本，第 1 本的框架已经在脑子里消解了。

**The Reading Compass solves the retrieval problem of being well-read.**

行者老师整理的这份 100 本书单，是中文创业圈公认的 "founder-grade" 阅读路径。  
我（Skylar）作为 ANSIO 创始人，把这份书单的每本书 distill 进 Claude 技能 ——  
让它在 30 秒内，从 5 个独立角度，给你的具体决策做 stress test。

> Cagan would say smoke-test first. 张小龙 would say "can you NOT add this?"  
> Two different questions. One assumes you'll ship. The other tests whether to.  
>  
> A summary engine flattens this. **A compass surfaces it.**

---

## 📊 Progress · 61 / 100

```
█████████████████████████████████░░░░░░░░░░░░░  61%

Foundations    ████████████████████  5/5     ✅
China Context  ██████████████████░░  8/10
Failure Lib    █████████████████████ 3/3     ✅
Product        ████████████████████  5/5     ✅
Brand          ████████████████████  7/7     ✅
Growth         ████████████████████  7/7     ✅
Management     ████████████████████  6/6     ✅
Startup        ████████████████░░░░  9/12
Mental OS      ████████████████████  7/7     ✅
Finance        ███████░░░░░░░░░░░░░  3/10    (deep gap)
Bonus 番外      ████████████████████  2/2     ✅
```

40 books remain. Updated weekly. ⭐ the repo to follow along.

---

## 📖 The library — 9 clusters

| # | Cluster | Anchor authors | Pull when |
|---|---|---|---|
| 🏛 | **Macro & Foundations** | 黄奇帆 · Studwell · Greenspan | Market entry · field-level forces |
| 🇨🇳 | **China Context** | 雷军 · 段永平 · 柳井正 · 吴晓波 | China market · East Asian capital |
| 💥 | **Failure Library** | 大败局 I+II · 十亿教训 | **ALWAYS** — pre-mortem every move |
| 🛠 | **Product Methodology** | Cagan · 张小龙 · 梁宁 · 俞军 | Feature / Discovery / PM decisions |
| 🎨 | **Brand & Narrative** | Trout · 华杉 · Berger · Mark · Holt | Positioning · personal IP · messaging |
| 🧠 | **Growth & Persuasion** | Eyal · Cialdini · Ferrier · 杨飞 · 徐志斌 | Funnel · conversion · viral design |
| 👥 | **Management & Culture** | Grove · Doerr · Hastings · Schmidt · Covey | Hiring · OKR · team conflict |
| 🚀 | **Startup Classics** | Thiel · Horowitz · Ries · Christensen · 柳井正 | 0→1 · wartime · pivot decisions |
| 💭 | **Mental OS** | Covey · Knapp · Minto · 谢胜子 · 张亚勤 | Founder心法 · time · communication |

➕ **2 番外 picks** for timely intel: 谢胜子 (founder心法 · 公众号合集) · 张亚勤 (post-DeepSeek AI strategy)

[**See full 100-book index →**](library/INDEX.md)

---

## 📋 5 decision protocols

The compass runs differently for different decisions. Each protocol pulls a tailored 5-book stack:

| Protocol | Anchor question | Stack |
|----------|----------------|-------|
| 💰 [**Pricing**](protocols/PRICING.md) | What value layer am I at? | 梁宁 · 俞军 · Cialdini · 张小龙 · 大败局 II |
| 👥 [**Hiring**](protocols/HIRING.md) | Keeper Test + leverage | Hastings · Schmidt · Horowitz · Grove · 十亿教训 |
| 💵 [**Fundraising**](protocols/FUNDRAISING.md) | Cap table preservation | 十亿教训 · Horowitz · Thiel · 大败局 II · Doerr |
| 🛠 [**Feature go/no-go**](protocols/FEATURE-GO-NOGO.md) | Can you NOT add it? | 张小龙 · Cagan · 俞军 · 任天堂 · 张亚勤 |
| 🎤 [**Personal IP**](protocols/PERSONAL-IP.md) | 支点优势 + archetype | Trout · Mark · 谢胜子 · Berger |

---

## 🧠 Compass vs Generic AI

|  | Generic ChatGPT advice | Reading Compass |
|---|------------------|-----------------|
| **Source** | Internet aggregate | 61 distilled books (curated by 行者 + Skylar) |
| **Stance** | "It depends" | Commits to a verdict |
| **Output** | One framing | 3-5 frames, productively disagreeing |
| **Failure** | Skipped | Mandatory pre-mortem from 大败局 family |
| **Action** | Vague | One 48-hour concrete step |
| **Voice** | Generic | Bilingual, founder-direct, **拒绝鸡汤** |

---

## 🚀 Make it yours

The skill is **founder-agnostic** by default. Personalize with one file:

```bash
echo "I'm building [X] at [stage]. ICP: [Y]. Current bet: [Z]." \
  > ~/.claude/skills/reading-compass/MY_CONTEXT.md
```

The skill weights book frames against your specific context when stacking.

---

## 🗺 Roadmap

- [x] **v1.0** · 61 books · 9 clusters · 5 protocols
- [ ] **v1.1** · Complete the remaining 39 books (full 100)
- [ ] **v1.2** · Anti-pattern library (50 failure modes deep-dive)
- [ ] **v1.3** · Bilingual stack answers (full EN ↔ ZH parity)
- [ ] **v2.0** · Conversational decision interviewer (Claude asks the right clarifying questions before stacking)

PRs welcome. Bring your own books — fill a coverage gap and credit yourself.

---

## 👥 Credits

### 🌟 行者 — the curator of this list

This skill is built on **行者老师** 整理的 100 本创业系统读书书单 — 中文创业圈最系统、最被引用的一份阅读路径。

- 📕 小红书：[@行者](#) *(本人请补充链接)*
- 🎵 抖音：[@行者](#) *(本人请补充链接)*
- 👥 百万级粉丝 · 创业系统读书法

> Without 行者's curation, this skill would not exist. 这份书单不是我（Skylar）的功劳——是我作为读者+ builder，把行者老师的内容做了一层 distillation + tooling 的工作。

### 🛠 Skylar — the builder

**Skylar Wang** · Founder of [ANSIO](https://ansio.ai) — Bloomberg Terminal for AI founders.

> Ex-Morgan Stanley AVP. Columbia MS Applied Analytics. LA-based.  
> Distilling the books behind every ANSIO product decision.

[𝕏 @SkylarWJY](https://x.com/SkylarWJY) · [LinkedIn](https://linkedin.com/in/SkylarWJY) · [ansio.ai](https://ansio.ai)

### 📚 The authors

Cagan · Grove · Covey · Cialdini · Christensen · Thiel · Horowitz · Ries · Hastings · Doerr · Minto · Knapp · Gladwell · Berger · Mark · Holt · Trout · Studwell · Greenspan ·

吴晓波 · 黄奇帆 · 温铁军 · 吴敬琏 · 俞军 · 梁宁 · 张小龙 · 雷军 · 段永平 · 柳井正 · 松下幸之助 · 张亚勤 · 谢胜子 · 华杉 · 杨飞 · 徐志斌 · 关明生 · 张新民 ·

...and many more. The full attribution lives in [`library/INDEX.md`](library/INDEX.md).

---

## 📜 License

**MIT** — fork, remix, ship. Attribution appreciated but not required.

The books themselves remain the IP of their original authors. If a frame in this skill changes how you think — buy the original book. They earned it.

---

<div align="center">

### **If this saves you 100 hours of reading, ⭐ the repo.**
### **If it saves you 1 bad decision, tell someone.**

*Built with discipline. Maintained out of obsession.*  
*基于行者书单 · By Skylar Wang*

[**📕 中文版 README**](README.zh.md) · [**📚 Full Library Index**](library/INDEX.md) · [**💼 ANSIO**](https://ansio.ai)

</div>
