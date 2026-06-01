<div align="center">

# 📍 Reading Compass

### **Same book. Your angle.**

> **61 books × 6 reader personas = 366 distilled takeaways.**  
> Based on **[@行者](https://xhslink.com/m/92fI81VQlmM)** 的 100 本创业书单 (小红书 · **4.4M 赞收藏**)

You don't read 60 books in the same way at 25, 35, or 45. The same book hits differently if you're at Google vs. running a 3-person startup vs. building a personal brand.

This skill takes 61 books from 行者老师's legendary reading list and **re-frames every takeaway for who YOU actually are right now** — in 最直白的话.

[![License: MIT](https://img.shields.io/badge/license-MIT-yellow)]()
[![Books](https://img.shields.io/badge/books-61%20%2F%20100-blue)](library/INDEX.md)
[![Personas](https://img.shields.io/badge/personas-6-purple)]()
[![Source](https://img.shields.io/badge/行者-4.4M%20likes-red)](https://xhslink.com/m/92fI81VQlmM)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-black)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills)
[![中文](https://img.shields.io/badge/中文-README-green)](README.zh.md)

[**Install**](#-install) · [**Personas**](#-pick-your-persona) · [**Library**](library/INDEX.md) · [**中文**](README.zh.md)

</div>

---

## 🎬 The killer demo · One book, 6 readers

Take **《影响力》(Cialdini)** — the same 6 psychological principles. Now watch how the takeaway changes by who's asking:

| Persona | What this book actually means for you |
|---------|---------------------------------------|
| 🏢 **大厂员工 / 打工人** | 老板让你"承诺"做一件事 → 一致性原则在被用在你身上。**先别立刻答应**。说"让我想想"。承诺一旦说出口，就回不去了。 |
| 🚀 **创业者** | Cold email 第一封必带一份 specific report (互惠激活) → 回复率 ×3。不送先要 = 你在裸奔。 |
| 👥 **管理者 / 中层** | 团队"自愿"加班 = 你激活了承诺一致 + 社会认同。**这是权力，不是文化**。别自我感动。 |
| 🎤 **个人 IP / 创作者** | 每条帖子 trigger ≥ 1 个原则。最高 ROI：社会认同（"已有 X 人订阅" / 数字社会证明）。 |
| 💰 **投资人** | Founder pitch 用了几条原则 = 信号。用 1-2 条 = 自然。用 5 条以上 = 操纵嫌疑，pass。 |
| 🔄 **转型期 / 跳槽** | 谈薪资先用稀缺 ("我手上还有 2 个 offer") + 权威 (前司 title)。**直接谈数字 = 输掉**。 |

**Same 6 principles. 6 different action items. 0 paraphrasing.**

That's what "为你读书" actually means.

---

## 🎯 Install

```bash
git clone https://github.com/SkylarWJY/skylar-reading-compass.git ~/.claude/skills/reading-compass
```

Then tell Claude who you are, then ask anything:

```
"我是 Meta 的 Senior PM. 用 reading compass 告诉我《七个习惯》对我有什么用。"
"我在做副业,《影响力》6 原则我怎么用?"
"我是 VC,如何用《创业维艰》看 founder 的 wartime 能力?"
"我刚毕业,《OKR》对个人成长怎么应用?"
```

---

## 👤 Pick your persona

The skill **adapts to your stage**. Pick one (or let Claude detect):

<table>
<tr>
<td width="33%" valign="top">

### 🏢 大厂员工
**Big Tech IC / 打工人**

锚定问题：  
*"这本书怎么帮我升职 / 不被裁 / 做出影响力？"*

Anchor concerns:  
- 向上管理
- 影响圈 vs 关注圈
- 不卷又能升职
- 跨部门协作

</td>
<td width="33%" valign="top">

### 🚀 创业者
**Founder / 老板**

锚定问题：  
*"这本书怎么帮我 ship + 活下来 + 不犯前人犯过的错？"*

Anchor concerns:  
- 0→1 / PMF
- Cap table / VC
- 招人 / 文化
- 失败模式 pre-mortem

</td>
<td width="33%" valign="top">

### 👥 管理者 / 中层
**Manager / Team Lead**

锚定问题：  
*"这本书怎么帮我带团队 + 立威 + 不变成讨厌的领导？"*

Anchor concerns:  
- OKR 落地
- 1:1 / 反馈
- Performance review
- 留住关键人才

</td>
</tr>
<tr>
<td width="33%" valign="top">

### 🎤 个人 IP / 创作者
**Creator / Solopreneur**

锚定问题：  
*"这本书怎么帮我涨粉 / 涨收入 / 不被算法绑架？"*

Anchor concerns:  
- 定位 / 人设
- 内容裂变
- 私域沉淀
- 把读者变收入

</td>
<td width="33%" valign="top">

### 💰 投资人
**VC / Angel / 散户**

锚定问题：  
*"这本书怎么帮我看 founder / 看赛道 / 看周期？"*

Anchor concerns:  
- Founder 评估
- 行业判断
- 失败模式识别
- 周期 vs 趋势

</td>
<td width="33%" valign="top">

### 🔄 转型期 / 学生
**Transitioner / Student**

锚定问题：  
*"这本书怎么帮我决定下一步 / 不踩坑 / 长期复利？"*

Anchor concerns:  
- 跳槽 / 创业决策
- 副业起步
- 个人现金流
- 5 年地图

</td>
</tr>
</table>

---

## 📖 Sample · 《七个习惯》across 6 personas

Watch how Stephen Covey's classic gets re-cut depending on who's reading:

### Original (Covey 的原话)
> *"消极被动的人，言语中就会流露出推卸责任的个性。例如：'我就是这样。'仿佛是说：这辈子注定改不了。"*

### What it means for YOU:

**🏢 大厂员工读到的是**：  
"我就是这样" = 中层魔咒。每次说 "我们公司就这样" / "老板就这样" / "团队就这样" 你的影响圈就缩小一寸。**3 年后你还在这个位置就是因为这个**。

**🚀 创业者读到的是**：  
Founder 唯一不能有的口头禅就是"市场就是这样"。市场是你创造的——你说"市场就这样"那就是你认输了。这一句话能筛掉 80% 不该投的项目。

**👥 管理者读到的是**：  
团队说"我就这样"时，你不能接住。接住 = 默认。要在 1:1 里直接 challenge：**"那你打算怎么变？"** 不给他逃跑路径。

**🎤 创作者读到的是**：  
不要再发 "我就是这样写" 的内容。粉丝不为你的 "this is who I am" 买单——他们为你的"变化"买单。每个月迭代你的 voice，关注圈才会扩张。

**💰 投资人读到的是**：  
Founder 第一次 pitch 时如果说"市场就这样" / "竞争太激烈" / "时机不好"——直接 pass。他没意识到自己在关注圈里。**这种 founder 救不了**。

**🔄 转型期读到的是**：  
"我已经 30 了，转不动了" / "我背景不对" / "我没人脉"——每说一次就给自己缩一寸影响圈。**Covey 用一生证明：影响圈是你能控制的。每个月扩 1 寸，5 年后是另一个人**。

---

## 🔬 The 9 angles per book (each persona's lens)

Every book in the library is distilled across the same 9 angles. Your persona changes which angles get emphasized:

| # | Angle | 大厂 | 创业 | 管理 | 创作 | 投资 | 转型 |
|---|-------|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | 决策框架（N 步过滤器） | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| 2 | 公司 / 项目诊断 | ⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐ |
| 3 | 客户工作启示 | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐ |
| 4 | AI 时代机会扫描 | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| 5 | 个人赚钱机会 | ⭐⭐⭐ | ⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| 6 | 反共识洞察 | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| 7 | 30/60/90 行动 | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| 8 | 警惕清单（这本书可能误导你的地方） | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| 9 | Cross-book stacking | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ |

⭐⭐⭐ = 你应该读的角度 · ⭐⭐ = 顺便看 · ⭐ = 跳过没关系

---

## 📚 The library — 61 / 100 books, 9 clusters

| Cluster | # | 大厂 | 创业 | 管理 | 创作 | 投资 | 转型 |
|---------|---|:---:|:---:|:---:|:---:|:---:|:---:|
| 🏛 Macro & Foundations | 5 | · | ✅ | · | · | ✅✅ | · |
| 🇨🇳 China Context | 8 | ✅ | ✅✅ | ✅ | ✅ | ✅✅ | ✅ |
| 💥 Failure Library | 3 | ✅ | ✅✅✅ | ✅ | ✅ | ✅✅✅ | ✅✅ |
| 🛠 Product Methodology | 5 | ✅✅ | ✅✅ | ✅✅ | ✅ | ✅ | · |
| 🎨 Brand & Narrative | 7 | · | ✅✅ | · | ✅✅✅ | ✅ | ✅ |
| 🧠 Growth & Persuasion | 7 | ✅ | ✅✅ | ✅ | ✅✅✅ | ✅ | ✅ |
| 👥 Management & Culture | 6 | ✅✅ | ✅✅ | ✅✅✅ | · | ✅ | ✅ |
| 🚀 Startup Classics | 9 | ✅ | ✅✅✅ | ✅ | · | ✅✅ | ✅✅ |
| 💭 Mental OS | 7 | ✅✅ | ✅✅ | ✅✅ | ✅✅ | ✅✅ | ✅✅✅ |

[**See full 61-book index →**](library/INDEX.md)

✅✅✅ = 这个人设必读 · ✅✅ = 高 ROI · ✅ = 可以看

---

## 📊 Progress · 61 / 100

```
█████████████████████████████████░░░░░░░░░░░░░  61%

宏观地基       ████████████████████  5/5     ✅
中国语境       ██████████████████░░  8/10
失败案例库     █████████████████████ 3/3     ✅
产品方法论     ████████████████████  5/5     ✅
品牌叙事       ████████████████████  7/7     ✅
增长说服       ████████████████████  7/7     ✅
管理文化       ████████████████████  6/6     ✅
创业经典       ████████████████░░░░  9/12
心智 OS        ████████████████████  7/7     ✅
财务数据       ███████░░░░░░░░░░░░░  3/10    (深度 gap)
```

剩 39 本。每周更新。⭐ this repo 跟进。

---

## 🧠 Why this works · Compass vs Generic AI

|  | Generic AI summary | Reading Compass |
|---|---|---|
| **Output** | Book's TOC, rephrased | 9 angles, your persona, 直白话 |
| **Source** | Wikipedia + GPT | 61 books, actually read |
| **Personalization** | None | 6 personas, dynamic switching |
| **Voice** | 鸡汤 + jargon | 大白话 + action item |
| **Cross-book** | None | Stacked perspective from 3-5 books |
| **Failure check** | None | 大败局 / 十亿教训 pre-mortem mandatory |

---

## 🚀 Personalize it further

The skill detects your persona from your first message. To lock it in:

```bash
echo "I'm a [persona]. I work on [domain]. My current bet is [thing]." \
  > ~/.claude/skills/reading-compass/MY_CONTEXT.md
```

The skill will weight every book stack accordingly.

---

## 🗺 Roadmap

- [x] **v1.0** · 61 books · 9 clusters · 5 decision protocols
- [x] **v1.2** · 6 reader personas · 直白话 takeaway engine
- [ ] **v1.3** · Complete remaining 39 books (full 100)
- [ ] **v1.4** · Add 50-failure-mode anti-pattern library
- [ ] **v2.0** · Voice-of-author mode (Claude responds AS the author you ask)

PRs welcome. Bring your book, fill a gap.

---

## 👥 Credits

### 🌟 行者老师 · 这份书单的原创者

This skill is built on **行者老师** integrated 100 本创业系统读书书单 — 中文创业圈最系统、被引用最多的一份阅读路径。

**📕 [@行者 on 小红书](https://xhslink.com/m/92fI81VQlmM)** · **4.4M 赞与收藏**

> Without 行者's curation, this skill would not exist.  
> 没有行者老师的 curation 这个 skill 不会存在。如果你觉得这个 skill 有用，请去关注行者老师本人。  
> *(整理书单、写读书法、答粉丝问题——这些是行者老师做的工作。我只是把它工程化了。)*

### 🛠 Skylar · Distillation + Engineering

**Skylar Wang** · Founder of [ANSIO](https://ansio.ai) — Bloomberg Terminal for AI founders.

> Ex-Morgan Stanley AVP. Columbia MS Applied Analytics. LA-based.

[𝕏 @SkylarWJY](https://x.com/SkylarWJY) · [LinkedIn](https://linkedin.com/in/SkylarWJY) · [ansio.ai](https://ansio.ai)

### 📚 The 50+ authors

Cagan · Grove · Covey · Cialdini · Christensen · Thiel · Horowitz · Ries · Hastings · Doerr · Minto · Knapp · Gladwell · Berger · Mark · Holt · Trout · Studwell · Greenspan ·

吴晓波 · 黄奇帆 · 温铁军 · 吴敬琏 · 俞军 · 梁宁 · 张小龙 · 雷军 · 段永平 · 柳井正 · 松下幸之助 · 张亚勤 · 谢胜子 · 华杉 · 杨飞 · 徐志斌 · 关明生 · 张新民 ·

[Full attribution → `library/INDEX.md`](library/INDEX.md)

---

## 📜 License

**MIT** — fork, remix, ship. Attribution appreciated but not required.

If a frame in this skill changes how you think — **buy the original book**. The authors earned it.

---

<div align="center">

### **Same book. Your angle.**

**If this saves you 100 hours of reading, ⭐ the repo.**  
**If it changes one decision, tell a friend.**

*基于 [@行者](https://xhslink.com/m/92fI81VQlmM) 创业书单 · Distilled by Skylar Wang*

[**📕 中文 README**](README.zh.md) · [**📚 Library Index**](library/INDEX.md) · [**💼 ANSIO**](https://ansio.ai)

</div>
