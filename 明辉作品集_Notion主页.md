# 李明辉 | 作品集

> AI Agent 搭建者，一级市场投研训练中，经历过三次从零到一的商业落地。对一切未知保持好奇。

---

## 关于我

融合经济学理论功底与数据分析技术能力（Python/SQL/Tableau），具备"商业逻辑 + 数据验证"的双重视角。主导 3 个跨行业商业项目（金融二级市场、医疗环保、AI 节能），同时搭建了多套 AI Agent 系统（情报采集、投研自动化、产品拆解），覆盖从 0 到 1 落地全流程。全英文教育背景（高中至硕士），持有基金从业资格证。

---

## 作品项目

### 🔮 天纪AI — 紫微斗数AI解读
> 从0到1的AI产品，含排盘引擎、RAG检索、付费策略

- iztro排盘 (Node.js) + DeepSeek V4 + 87万字倪海夏天纪RAG + Streamlit
- 40+格局自动检测，产品策略文档完整（裂变设计+商业模式定价+数据资产战略）
- MVP已上线Streamlit Cloud，待商业化闭环

→ [Live Demo](https://tianji-ai-bhakafevsrjhbaqvusnvzu.streamlit.app) | [GitHub](https://github.com/liminghui2014-lgtm/tianji-ai)

---

### 🤖 嘟嘟 Agent 2.0 — L1/L2 分层调度一级市场情报系统

> Coze 多 Agent 协同。L1 总控调度 + L2 三路采集工作流 + VOL1 搜索策略引擎 + APE 独立审计。

**架构设计**：
- **VOL1 搜索策略引擎**：6 维度 × 50+机构 × 30+赛道的搜索词矩阵，配额动态分配。3层去重（精确→相似度→LLM语义），置信度自动计算
- **L2 工作流**：WF_VCinfogather，三路并行采集（36氪 / 通用搜索 / IT桔子），"代码→LLM→代码"夹逼管道架构，确保 JSON 输出 100% 结构化
- **L1 总控调度**：静默分级(S/A/B) → 强制 5 模块渲染深度研报（数据仪表盘 → 趋势洞察 → S级穿透 with Why Now 博弈分析 → A/B级列表 → 风险矩阵 + 关键监控清单）
- **APE 独立审计**：Gemini 3.1 Pro 驱动的 Agent Performance Evaluator，定期审计覆盖率/重复率/语义准确率（v3.0 评分从 82%→90%）

**效果**：覆盖率 40%→88%，重复率 <2%，日产 S 级情报 8-12 条

→ [GitHub](https://github.com/liminghui2014-lgtm/coze-vc-workflow)

---

### 🔬 SOP Agent Swarm — 三阶段产品拆解系统

> 本地 Agent Swarm 架构。3 Agent 协同 + 反幻觉协议 + 信源锚定 + LaTeX/Mermaid 强制输出。

**流程**：阶段 0：联网搜索锚定事实边界 → 阶段 1：Generator 生成 7 模块初稿 → 阶段 2：Red Teamer 事实核查与逻辑证伪 → 阶段 3：Architect 吸收审计意见重构终稿

**已产出**：DeepSeek V4（93分）、宇树科技（92分）两篇深度拆解

→ [GitHub](https://github.com/liminghui2014-lgtm/deep-vc-research)

---

### 📡 Deep VC Research — Claude Code 投研插件

8 步标准化 VC 尽调流程（MIT 协议）。反幻觉协议 + 4 级分层信源 + 跨平台中文适配 + 自动导出 Word。含完整样板研报（自然意志科技）。

→ [GitHub](https://github.com/liminghui2014-lgtm/deep-vc-research)

---

### 📡 Coze VC Pipeline — 一级市场情报自动化工作流

三路并行采集 + 夹逼管道架构，Coze 可导入。代码(确定性)→LLM(非确定性)→代码(确定性)，幻觉出不了管道。

→ [GitHub](https://github.com/liminghui2014-lgtm/coze-vc-workflow)

---

### 📊 IT桔子 VIP 日报 — 一级市场每日全景

Python + Playwright CDP 绕过反爬机制，VIP数据全自动抓取（市场全景→VC追踪→公司深度）+ Jarvis风格HUD可视化面板。

---

### ✍️ 明辉来了 — 投资视角拆解科技

17 篇深度文案，覆盖 AI / Web3 / 投资哲学 / 科技商业。不讲新闻，讲底层逻辑。

→ [抖音主页](https://www.douyin.com/user/MS4wLjABAAAACPfIQA4zgNJFkS2l5dEBqL7uDPUnpKeZxMGto-SBuXcFmC6OuBGg-caGQGzm4muf?from_tab_name=main)

---

### 🖥️ Claude Code GUI — 本地桌面客户端

React + TypeScript + Vite 前端 + FastAPI + SQLite 后端 + SSE 流式输出。

---

## 深度研报

### SOP 产品拆解案例

| 产品 | 核心判断 | 评分 |
|------|---------|:--:|
| DeepSeek V4 | 全球性价比断层领先的 MoE 大模型，GPU 硬件不归它管 | 93 |
| 宇树科技 | 全球最优秀的人形机器人硬件公司，AI 侧为零 | 92 |

### Gemini 穿透式赛道研报（9篇）

覆盖 AI 芯片（曦望芯科）、LLM 应用层（月之暗面）、空间智能（群核科技）、AI 基础设施（智谱AI）、人形机器人（宇树科技）、3D AIGC（Meshy.AI）、AI Agent（自然意志）、世界模型（极佳视界）、端侧AI（面壁智能）。

每篇含：业务全景 → 产品拆解 → 市场定位 → 护城河 → 风险判断 → 投资结论。

---

## 商业经历

### AI 节能项目 | 联合负责人 | 2024.03–至今

EMC 模式代理施耐德 SpaceLogic AI BOX，帮污水厂/食品厂 AI 节能。设计分段式基准线能耗模型（固定 60-70% + 可变 30-40%），解决 EMC 行业"省了多少电谁说了算"的核心争议。昆明第十三水质净化厂（200万邀标）、沈阳双汇、豫光金铅（合同双签）。预计实现 5%-21% 节电率，5 年累计创造 450 万元节能收益。

### 医疗耗材销售公司 | 创始人 | 2024–2025

3 个月实现月营收突破 50 万元，验证区域市场需求。因合作方合规风险上升，果断关停。

### 医疗废弃物就地化处置 | 项目经理 | 2023–2025

推广"非焚烧摩擦热"技术，在杭州、昆明等 200 余家医疗机构实现技术应用。较传统焚烧减少能耗 30% 以上。入选"一带一路"输出项目。因行业准入标准提高 + 合伙人分歧，有序退出。

### 二级市场量化策略 | 策略负责人 | 2021–2023

管理资金规模超 700 万元。搭建"量化信号 + 基本面分析"双驱动交易策略体系，运用 Python 进行数据回测与策略优化。极端波动中有效管控杠杆风险，依约完成全部亏损补足。

---

## 教育背景

**美国东北大学（Northeastern University）** | 数据分析学 | 硕士（MPS）| 2019–2021
- 课程：机器学习、时间序列分析、数据可视化、数据库管理、风险管理分析
- 技术栈：Python (pandas/scikit-learn)、R、SQL、Tableau、Azure
- Capstone：Spotify 歌曲流行度预测（EDA + 回归建模）

**加拿大里贾纳大学（University of Regina）** | 经济学 | 学士（B.Sc.）| 2014–2018
- 高中起在加拿大完成全部学业，全英文工作能力

### 硕士作品精选

| 项目 | 方法 | 工具 |
|------|------|------|
| Airbnb NYC 房价预测 | 线性回归 + 假设检验 + 正则化 + 数据挖掘 | R / Excel / Python |
| XN Project 广告数据分析 | EDA + 决策树 + 可视化 | Python / Tableau |
| 新产品上市风险分析 | SWOT + KRI + Bass 扩散模型 | Excel / R |
| edX 数据库设计 | ER图 → 3NF规范化 → SQL查询 | MySQL |

---

## 实习经历

- **腾讯** | 商业分析实习 | 2020 — Python/Tableau构建游戏直播热度预测模型
- **摩根士丹利（中国）** | 投资部实习 | 2018 — 金融衍生品定价模型 + 组合风险分析
- **戴德梁行** | 战略发展部实习 | 2019 — 昆明长水机场T2招商策略研究

---

## 技能

| 类别 | 内容 |
|------|------|
| **AI Agent** | Coze 多 Agent 协同、L1/L2 分层调度、SOP Swarm 架构、Claude Code Skill 开发 |
| **技术栈** | Python、JavaScript、Streamlit、FastAPI、React、SQLite、SQL、R |
| **投资分析** | 量化策略回测、VC Method、DCF、P/S 锚定、Term Sheet、尽调框架、赛道 Mapping |
| **商业落地** | 政企沟通、投标策略、团队搭建、股权架构、合作伙伴谈判、风险管理与止损决策 |
| **语言** | 全英文工作能力（12年海外教育，本硕全英文授课） |
| **证书** | 中国基金从业资格证、Azure Administration |

---

## 联系方式

- GitHub: [github.com/liminghui2014-lgtm](https://github.com/liminghui2014-lgtm)
- 邮箱: yeezus2049@163.com
- 抖音: [明辉来了](https://www.douyin.com/user/MS4wLjABAAAACPfIQA4zgNJFkS2l5dEBqL7uDPUnpKeZxMGto-SBuXcFmC6OuBGg-caGQGzm4muf?from_tab_name=main)
