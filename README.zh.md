<div align="center">

# 📍 Reading Compass · 创业读书罗盘

### *基于行者百万博主创业书单 · 把每一个 founder 决策放进 61 本书的多角度审视*

> 整理自 [**行者老师**](#-鸣谢) 的 100 本创业系统读书书单  
> *([@行者](#-鸣谢) · 小红书 · 抖音 · 百万级粉丝)*  
> Skylar 蒸馏 · 工程化为一个 Claude 技能 · 30 秒给你 5 个独立角度

**61 / 100 本完成 · 9 大集群 · 5 个决策协议 · 1 个 Claude 技能**

[![License: MIT](https://img.shields.io/badge/license-MIT-yellow)]()
[![Books](https://img.shields.io/badge/books-61%20%2F%20100-blue)](library/INDEX.md)
[![Source](https://img.shields.io/badge/source-行者书单-red)]()
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-black)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills)
[![English](https://img.shields.io/badge/English-README-green)](README.md)

[**安装**](#-一行安装) · [**书单**](library/INDEX.md) · [**案例**](examples/) · [**English**](README.md)

</div>

---

## 🎬 30 秒 demo

**创业者 · 晚 11 点 · 盯着 term sheet：**
> "Tier-1 VC 给的 $2M @ $12M post，我要不要接？"

**Reading Compass 回复：**

```
📚 决策栈分析 · "$2M @ $12M term sheet"

▸ 十亿教训 (#33)  · 创始人股权落到 70% — 距下一轮安全线偏紧
▸ Horowitz (#29)  · 这家 firm 18 个月赶走 2 个创始人 — 必须 reference 那 2 人
▸ Thiel (#21)     · 估值低一点 + runway 长一点 > 估值高 + runway 一样
▸ 大败局 II (#32)  · 5 个月 runway = 谈判中你是负杠杆
▸ Doerr (#97)     · 1 VC + 2 founder + 0 独立董事 = 治理结构不稳

🚦 接 — 但必须三个条件：
   1. Reference-call 那 2 位被赶走的创始人（不要 VC 给的引荐）
   2. 推动改为 $2.5M @ $11M
   3. Series A 阶段加一个独立董事席位 trigger

⚠️  红线（任一触发就 walk）：
   · fired-founder 反馈 partner 敌对
   · pro-rata 超过 100%
   · participating preference

⏱  48 小时行动：起草谈判 email + 联系 2 个备选 reference
```

**5 本书。30 秒。决策级分析 + 红线 + 行动。**

不是摘要工具。是 **disagreement engine**（让书之间互相吵架的引擎）。

---

## 🎯 一行安装

```bash
git clone https://github.com/SkylarWJY/skylar-reading-compass.git ~/.claude/skills/reading-compass
```

然后向 Claude 提问：

```
"用 reading compass 帮我分析：要不要 ship 这个 feature？"
"用读书库看一下：我要不要从大厂裸辞？"
"compass me on 我们 B2B AI 工具的定价"
"founder lens on 联合创始人股权拆分"
```

---

## 💡 为什么需要这个

> 「读 100 本书」是创业者最常听到的建议——也是最没用的建议之一。  
> 读到第 50 本时，第 1 本的框架早就在脑子里消解了。

**Reading Compass 解决的是 "well-read 之后的提取问题"。**

行者老师整理的这份 100 本书单，是中文创业圈最被认可的"founder-grade" 阅读路径。  
我（Skylar）作为 ANSIO 创始人，把这份书单的每本书 distill 进 Claude 技能 ——  
让它在 30 秒内，从 5 个独立角度，给你的具体决策做 stress test。

> Cagan 会说先做 smoke test。张小龙会说「能不能不加这个功能？」  
> 这是两个不同的问题。一个假设你会 ship。另一个 pressure-test 你该不该 ship。  
>  
> 摘要工具会把两者压成一个答案。**罗盘把它们的张力暴露出来。**

---

## 📊 进度 · 61 / 100

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
番外 Bonus     ████████████████████  2/2     ✅
```

剩 39 本。每周更新。⭐ this repo 跟进。

---

## 📖 书库 · 9 大集群

| # | 集群 | 锚定作者 | 何时调用 |
|---|---|---|---|
| 🏛 | **宏观地基** | 黄奇帆 · Studwell · 格林斯潘 | 市场进入 · 领域级力量分析 |
| 🇨🇳 | **中国语境** | 雷军 · 段永平 · 柳井正 · 吴晓波 | 中国市场 · 东亚资本 |
| 💥 | **失败案例库** | 大败局 I+II · 十亿教训 | **永远调用** — 每个决策做 pre-mortem |
| 🛠 | **产品方法论** | Cagan · 张小龙 · 梁宁 · 俞军 | Feature / Discovery / PM 决策 |
| 🎨 | **品牌叙事** | Trout · 华杉 · Berger · Mark · Holt | 定位 · 个人 IP · 信息设计 |
| 🧠 | **增长说服** | Eyal · Cialdini · Ferrier · 杨飞 · 徐志斌 | 漏斗 · 转化 · 病毒传播设计 |
| 👥 | **管理文化** | Grove · Doerr · Hastings · Schmidt · Covey | 招聘 · OKR · 团队冲突 |
| 🚀 | **创业经典** | Thiel · Horowitz · Ries · Christensen · 柳井正 | 0→1 · wartime · pivot 决策 |
| 💭 | **心智 OS** | Covey · Knapp · Minto · 谢胜子 · 张亚勤 | Founder 心法 · 时间 · 沟通 |

➕ **2 本番外** (时效语料)：谢胜子（公众号合集 · 51 篇江湖心法）· 张亚勤（post-DeepSeek 时代 AI 战略）

[**查看完整 100 本书索引 →**](library/INDEX.md)

---

## 📋 5 个决策协议

罗盘对不同决策类型走不同协议。每个协议预设了一套 5 本书的 stack：

| 协议 | 锚定问题 | 调用书目 |
|----------|----------------|-------|
| 💰 [**定价**](protocols/PRICING.md) | 我处在哪个价值层？ | 梁宁 · 俞军 · Cialdini · 张小龙 · 大败局 II |
| 👥 [**招聘**](protocols/HIRING.md) | Keeper Test + leverage 测算 | Hastings · Schmidt · Horowitz · Grove · 十亿教训 |
| 💵 [**融资**](protocols/FUNDRAISING.md) | Cap table 健康度 | 十亿教训 · Horowitz · Thiel · 大败局 II · Doerr |
| 🛠 [**Feature go/no-go**](protocols/FEATURE-GO-NOGO.md) | 能不能不加？ | 张小龙 · Cagan · 俞军 · 任天堂 · 张亚勤 |
| 🎤 [**个人 IP**](protocols/PERSONAL-IP.md) | 支点优势 + 原型选择 | Trout · Mark · 谢胜子 · Berger |

---

## 🧠 罗盘 vs 通用 AI

|  | 通用 ChatGPT 建议 | Reading Compass |
|---|------------------|-----------------|
| **来源** | 互联网平均 | 61 本 distilled 书（行者+ Skylar 双重 curated）|
| **态度** | "It depends" / "看情况" | 必须 commit 一个 verdict |
| **输出** | 一个角度 | 3-5 个角度 · 互相 productively disagree |
| **失败检查** | 跳过 | 必做 — 大败局家族 pre-mortem |
| **行动** | 模糊 | 一个具体 48 小时动作 |
| **语气** | 通用 | 中英双语 · founder-direct · **拒绝鸡汤** |

---

## 🚀 个性化

罗盘默认是 founder-agnostic。加一个文件就能 personalize：

```bash
echo "我在做 [X]，处在 [阶段]。ICP: [Y]。当前 bet: [Z]。" \
  > ~/.claude/skills/reading-compass/MY_CONTEXT.md
```

罗盘会把书的 frame 权重调整到你的具体语境。

---

## 🗺 路线图

- [x] **v1.0** · 61 本 · 9 集群 · 5 协议
- [ ] **v1.1** · 补齐剩余 39 本（完整 100）
- [ ] **v1.2** · 反模式库（50 个失败模式深度版）
- [ ] **v1.3** · 中英双语完整 parity 输出
- [ ] **v2.0** · 对话式决策访谈员（Claude 先问对的澄清问题，再 stack）

欢迎 PR — 带上你的书，填补一个 coverage gap，署你的名。

---

## 👥 鸣谢

### 🌟 行者老师 — 这份书单的整理者

这个技能是站在 **行者老师** 整理的 100 本创业系统读书书单之上的。这份书单是中文创业圈最系统、最被引用的一份阅读路径。

- 📕 小红书：[@行者](#) *(本人请补充准确链接)*
- 🎵 抖音：[@行者](#) *(本人请补充准确链接)*
- 👥 百万级粉丝 · 创业系统读书法 + 创业学习法

> 没有行者老师的 curation，这个技能不会存在。这份书单不是我（Skylar）的功劳——我只是作为读者 + builder，把行者老师的内容做了一层 distillation + tooling 的工作。如果你喜欢这个技能，请去关注行者老师本人。

### 🛠 Skylar — 蒸馏 + 工程化

**Skylar Wang** · [ANSIO](https://ansio.ai) 创始人 — 给 AI 创业者的 Bloomberg Terminal。

> 前 Morgan Stanley AVP · Columbia 应用分析硕士 · 在 LA。  
> ANSIO 每个产品决策背后的阅读功底，都在这里。

[𝕏 @SkylarWJY](https://x.com/SkylarWJY) · [LinkedIn](https://linkedin.com/in/SkylarWJY) · [ansio.ai](https://ansio.ai)

### 📚 原作者们

Cagan · Grove · Covey · Cialdini · Christensen · Thiel · Horowitz · Ries · Hastings · Doerr · Minto · Knapp · Gladwell · Berger · Mark · Holt · Trout · Studwell · Greenspan ·

吴晓波 · 黄奇帆 · 温铁军 · 吴敬琏 · 俞军 · 梁宁 · 张小龙 · 雷军 · 段永平 · 柳井正 · 松下幸之助 · 张亚勤 · 谢胜子 · 华杉 · 杨飞 · 徐志斌 · 关明生 · 张新民 ·

...还有许多。完整署名在 [`library/INDEX.md`](library/INDEX.md)。

---

## 📜 许可证

**MIT** — fork · remix · ship。署名感激但不强制。

书本身的版权归原作者所有。如果这个技能里的某个 frame 改变了你的思考方式 —— **请去买那本书。他们应得**。

---

<div align="center">

### **如果这帮你省下 100 小时阅读时间，⭐ this repo。**
### **如果它帮你避免了 1 个错误决策，告诉一个朋友。**

*Built with discipline. Maintained out of obsession.*  
*基于行者书单 · 蒸馏者 Skylar Wang*

[**🇺🇸 English README**](README.md) · [**📚 完整书库索引**](library/INDEX.md) · [**💼 ANSIO**](https://ansio.ai)

</div>
