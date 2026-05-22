# 国际科技集锦 - 2026-05-22

**今日要点**：Google I/O 发布 Gemini 3.5 Flash 并打响订阅降价战；Anthropic Mythos 挖出万级零日漏洞震动网安圈；NVIDIA Rubin 六芯片平台全面量产；欧盟 AI 法案 8 月大限压境；Q1 全球创投刷新历史；开源 Agent 框架持续爆火。

---

### 1. Google I/O 2026：Gemini 3.5 Flash 发布，订阅价格降 20%，AI 价格战正式开打

**来源**：9to5Google / Google Blog  ・  **时间**：2026-05-19  
**原文链接**：https://9to5google.com/2026/05/19/google-io-2026-news/

5 月 19 日 Google I/O 2026 大会上，Google 密集发布新品。模型层面推出 **Gemini 3.5 Flash**——在旗舰智能与 Flash 系列速度之间取得新平衡，编码与 Agentic 基准超越 Gemini 3.1 Pro；同步亮相的 **Gemini Omni** 系列支持图像、音频、视频、文本多模态输入并可输出视频。订阅价格方面，顶级 AI Ultra 套餐从每月 250 美元降至 200 美元，并新增 100 美元入门档，降价幅度达 20%。开发者工具方面，Google 升级 Agent 开发平台 Antigravity，支持多子 Agent 编排与跨平台终端沙箱，并提出开放标准 **WebMCP**，允许浏览器端 AI Agent 直接调用结构化工具。此次 I/O 是对 OpenAI 和 Anthropic 的正面价格宣战，三方角力进入新阶段。

---

### 2. Anthropic Claude Mythos + Project Glasswing：AI 自主挖出万个零日漏洞，以"白名单"模式限量发布

**来源**：Anthropic Official / The Ringer / Simon Willison  ・  **时间**：2026-05-06  
**原文链接**：https://www.anthropic.com/glasswing

Anthropic 发布迄今能力最强的模型 **Claude Mythos Preview**，并同步推出 **Project Glasswing** 网络安全倡议，承诺 1 亿美元算力资源，联合 AWS、Apple、Cisco、CrowdStrike、Google、微软、NVIDIA、Linux Foundation 等机构共同护航关键基础设施。Mythos 的惊人之处在于：在受控环境下，它自主扫描主要操作系统与浏览器后，识别出**数千个零日漏洞**，包括一个潜伏 17 年、可在运行 NFS 的 FreeBSD 上远程取得 root 权限的 RCE 漏洞。由于能力过强、潜在滥用风险极高，Anthropic 决定**不对外公开发布** Mythos，仅向白名单合作伙伴开放，为行业树立了"能力自我限制"的新先例，同时也引发"攻防边界究竟在哪里"的持续讨论。

---

### 3. NVIDIA Rubin 平台六芯片全面量产，Token 成本有望降至 Blackwell 十分之一

**来源**：NVIDIA Newsroom / Data Center Knowledge  ・  **时间**：2026-01-05（持续更新至 5 月）  
**原文链接**：https://nvidianews.nvidia.com/news/rubin-platform-ai-supercomputer

年初发布、如今已全面量产的 **NVIDIA Rubin 平台**由六块协同设计芯片组成：Vera CPU、Rubin GPU、NVLink 6 Switch、ConnectX-9 SuperNIC、BlueField-4 DPU 及 Spectrum-6 以太网交换机。与上一代 Blackwell 相比，Rubin 可实现 **5× 推理、3.5× 训练**性能提升，且 Token 生成成本目标降至约十分之一。AWS、Google Cloud、微软 Azure、OCI 均已确认将于 2026 年下半年率先部署 Vera Rubin 实例。作为主要代工方，台积电（TSMC）受益于先进封装需求激增，2026 年全年营收预计增长近 30%。NVIDIA 年营收同比增长 65% 至 2159 亿美元，数据中心业务增幅达 68%，Rubin 是其迈向 2027 年万亿美元营收目标的核心引擎。

---

### 4. 欧盟 AI 法案 8 月大限压境，全球企业迎来最大合规考验

**来源**：Holland & Knight / EU Digital Strategy  ・  **时间**：2026-04（持续）  
**原文链接**：https://www.hklaw.com/en/insights/publications/2026/04/us-companies-face-eu-ai-acts-possible-august-2026-compliance-deadline

**2026 年 8 月 2 日**，欧盟《人工智能法案》（EU AI Act）剩余核心条款正式生效，高风险 AI 系统（招聘、信贷评分、教育、执法等场景）须完成透明度披露、人工监督机制及合规文档备案。对于美国企业而言，只要 AI 系统输出"触达欧盟用户"，便可能触发管辖。欧盟于 2025 年 11 月提出"AI 综合修正案"，5 月 7 日已达成政治协议，部分条款小幅延期，但整体框架不变。与此同时，特朗普政府推行"轻监管"AI 战略并已放宽 NVIDIA H200 芯片对华出口限制，美欧 AI 治理路线分歧持续扩大，在两地同时运营的企业合规成本将成为不可回避的新竞争变量。

---

### 5. Q1 2026 全球创投历史性破 3000 亿美元，AI 独揽七成资金

**来源**：Crunchbase News  ・  **时间**：2026-04（Q1 季报）  
**原文链接**：https://news.crunchbase.com/venture/record-breaking-funding-ai-global-q1-2026/

2026 年第一季度，全球创业公司合计融资**逾 3000 亿美元**，为史上单季最高纪录。其中北美（美国+加拿大）独占 2526 亿美元，较上季度增长逾 3 倍；AI 相关投资约 2210 亿美元，约为上季 AI 投资总额的 **6 倍**。重要并购方面，ByteDance 旗下游戏平台沐瞳（Moonton）以 60 亿美元被 Savvy Games Group 收购；Capital One 以 51.5 亿美元计划收购金融科技独角兽 Brex。共享出行公司 Lime 于 5 月向 Nasdaq 提交 IPO 申请（代码拟用 "LIME"），成为年内科技 IPO 代表案例。这波融资浪潮的核心驱动力是 AI 基础设施与垂直 SaaS，资本对 AI 落地场景的押注已进入高速通道。

---

### 6. 开源 AI Agent 爆发：OpenClaw 破 21 万星，可视化编排框架引领新潮流

**来源**：ByteByteGo / NocoBase Blog / GitHub Trending  ・  **时间**：2026-05（持续）  
**原文链接**：https://blog.bytebytego.com/p/top-ai-github-repositories-in-2026

开源 AI 生态在 2026 年展现出强大生命力。**OpenClaw**（PSPDFKit 创始人 Peter Steinberger 的个人项目）年初病毒式传播后星标数从 9000 飙至 **21 万+**，成为当前 GitHub 最热门 AI 项目——它是一个完全本地运行的个人 AI 助手，支持 WhatsApp、Slack、iMessage、Telegram 等 50+ 应用接入，主打"数据不出设备"的隐私承诺。n8n、Dify、Langflow、Open WebUI 等**可视化 Agent 编排工具**持续走红，将 AI Agent 构建门槛从专业工程师降至领域专家。本地推理工具 **Ollama** 也维持高增长。开源项目在本地推理、工作流自动化和 Agent 框架领域已从追赶者蜕变为某些细分场景的引领者，对闭源商业产品构成实质性压力。

---

## 编辑观察

本周科技动态呈现出清晰的"能力跃升 × 生态卡位 × 监管滞后"三角张力。Google I/O 以 20% 降价向两大对手正面宣战，三方竞争已从参数比拼转向部署生态与价格策略；Anthropic Mythos 挖出万级零日漏洞却主动"封印"，揭示前沿模型能力已远超公众预期，"受控开放"将成为高风险 AI 领域的新范式。NVIDIA Rubin 量产与 Q1 创投刷新记录，共同勾勒出硬件算力与资金双轮驱动的 AI 基建热潮——这股热潮能否转化为真实商业回报，是 2026 下半年最值得持续观察的变量。欧盟 AI 法案 8 月大限则像一块倒计时石头：在美欧监管路线日益分歧的背景下，全球运营企业的合规策略将不得不向"双轨并行"演化。开源生态的持续爆发提醒所有从业者：护城河与否，要看能不能跑赢每半年一次的范式更迭。
