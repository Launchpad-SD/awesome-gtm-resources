# Awesome GTM Resources

> 面向创业者和 GTM 团队的优质开源资源清单，每周更新。
>
> **这是盛大 Launchpad 团队发起的项目** — 在 [Launchpad-SD](https://github.com/Launchpad-SD) 下维护。

格式参考 [awesome list](https://github.com/sindresorhus/awesome)。

## 为什么做这个

Launchpad 的工作是帮创业者把产品推向市场。GTM 和 marketing 方向好用的开源工具、agent skills 和打法，大多散落在 X 和 GitHub 上，看到了容易错过，想找的时候又找不到。所以我们把它们集中收集起来，筛一遍，放在这里。

## 对你有什么用

- 省掉自己满世界搜的时间。
- 每一条都经过筛选，不是把搜索结果原样堆上来。
- 每周更新。
- 按类别整理，按需取用。
- 偏向可以直接配合 Claude Code / Codex / 各类 agent 使用的工具和 skills。

## 怎么用

- 按下面的类别浏览，找到对应场景的资源。
- Star 或 Watch 本仓库，跟进每周更新。
- 有好资源欢迎提 PR，或者直接开一个 issue 丢链接，详见[参与贡献](#contributing)。

## 我们如何筛选

- 每周在 X 上找被提及的 GTM / marketing 相关 GitHub 仓库。
- 优先看互动量高、作者粉丝多的帖子，以及本身有热度的仓库（star 数、近期是否还在更新）。
- 每一条在收录前都会人工或用脚本核实。
- 绝不编造条目。
- 已停更或已归档的仓库不收录。

## 目录

- [Agent Skills 与打法（Agent Skills & Playbooks）](#agent-skills)
- [内容与 SEO / GEO（Content, SEO & GEO）](#content-seo-geo)
- [社媒分发与视频（Social Distribution & Video）](#social-video)
- [主动触达与销售（Outbound & Sales）](#outbound-sales)
- [热点与竞品监控（Trend & Competitor Monitoring）](#monitoring)
- [Agent 基础设施与 MCP（Agent Infra & MCP）](#agents-mcp)
- [相关清单（Related Lists）](#related-lists)
- [参与贡献（Contributing）](#contributing)

<a id="agent-skills"></a>
## Agent Skills 与打法（Agent Skills & Playbooks）

- [marketingskills](https://github.com/coreyhaines31/marketingskills) - 面向 Claude Code / agent 的营销技能集，涵盖转化率优化、文案、SEO、数据分析和增长。
- [seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills) - SEO/GEO 方向的 Claude skills 合集（正式版本在 aaron-marketing-skills 中维护）。
- [agency-agents](https://github.com/msitarzewski/agency-agents) - 数百个预设专家角色的 agent 合集，其中 marketing、paid-media、sales 部门覆盖增长、SEO/AEO、小红书 / 抖音 / Reddit 运营、投放和销售。
- [ai-marketing-skills](https://github.com/ericosiu/ai-marketing-skills) - Single Brain 团队开源的营销与销售 Claude Code skills，覆盖增长实验、outbound、SEO、内容运营和 CRO，是完整工作流而不只是 prompt。
- [LMTY Competitive Skills](https://github.com/LMTYdotcom/skills) - 面向竞争型 GTM 的 agent skills，用来做竞品简报、定位与 messaging 检查、定价与发布评审、battlecard 和 win-loss 分析。

<a id="content-seo-geo"></a>
## 内容与 SEO / GEO（Content, SEO & GEO）

- [open-seo](https://github.com/every-app/open-seo) - 开源版 Semrush / Ahrefs 替代方案。
- [GEOFlow](https://github.com/yaojingang/GEOFlow) - 开源的 GEO 内容工程与多站点分发工具。
- [claude-seo](https://github.com/AgriciDaniel/claude-seo) - 面向 Claude Code 的全套 SEO 审计 skill，含 26 个子 skill 和 19 个子 agent，覆盖技术 SEO、E-E-A-T、schema 和 GEO。
- [geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude) - GEO 优先的 SEO skill，给网站做 AI 搜索可引用度评分、AI 爬虫访问和品牌提及检查，并能输出给客户看的报告。
- [wewrite](https://github.com/imraywang/wewrite) - 公众号内容全流程 skill，从热点抓取、写稿、SEO、配图到排版，一句话推到微信草稿箱。

<a id="social-video"></a>
## 社媒分发与视频（Social Distribution & Video）

- [AiToEarn](https://github.com/yikart/AiToEarn) - AI 辅助的多平台内容发布与变现工具。
- [hypit](https://github.com/hypit-ai/hypit) - 用 AI agent 端到端复刻爆款视频，一条命令批量产出多个版本。
- [Postiz](https://github.com/gitroomhq/postiz-app) - 可自部署的开源社媒排期发布工具，支持 agent 调用，一处管理多个平台的定时发布。
- [HyperFrames](https://github.com/heygen-com/hyperframes) - HeyGen 开源的“写 HTML 出视频”框架，为 agent 设计，适合批量制作产品演示和社媒短视频。
- [brag](https://github.com/latent-spaces/brag) - 一条命令把做好的项目变成带音乐、动效和分享文案的发布短视频（基于 HyperFrames）。
- [social-media-skills](https://github.com/charlie947/social-media-skills) - 17 个面向 Codex / Claude 的社媒 skills，覆盖学习个人语气、LinkedIn 写作、调研、数据分析和 Reels 脚本。
- [native-subtitle-quote-image](https://github.com/chengyi-ai/native-subtitle-quote-image) - 从视频精确取帧并保留原字幕，生成适合小红书 / 抖音的 3:4 字幕长图的 agent skill。
- [OpenMontage](https://github.com/calesthio/OpenMontage) - 开源的 agent 视频制作系统，把 Claude Code 变成视频工作室，内置 12 条制作流水线和数百个 skill 文件。
- [Easel](https://github.com/ZJU-REAL/Easel) - ZJU-REAL（浙江大学）团队开源的社媒运营 agent，覆盖找热点、策划、创作、多平台发布和复盘，并把有效经验沉淀回账号画像。
- [baoyu-skills](https://github.com/JimLiu/baoyu-skills) - 宝玉开源的内容创作 skills 合集，包括封面图、文章配图、Markdown 排版和发布到公众号等。

<a id="outbound-sales"></a>
## 主动触达与销售（Outbound & Sales）

- [OpenOutreach](https://github.com/eracle/OpenOutreach) - 可自部署的 AI agent，用于 B2B 获客和邮件触达。
- [newsjack](https://github.com/elvisun/newsjack) - 开源 agent skills，把 agent 变成一支公关 / 热点借势团队。
- [Chuwu-PR-OS](https://github.com/chuwu57/Chuwu-PR-OS) - 初五整理的中文公关方法体系：从传播理论、原则、框架到工作流，附 8 个 PR agent 技能（舆情、危机预案、新闻稿等）。
- [coldoutboundskills](https://github.com/growthenginenowoslawski/coldoutboundskills) - 30 多个冷邮件 / outbound 的 Claude Code skills，覆盖 ICP、线索获取、文案、发信基础设施和 Clay 工作流。
- [Harvey](https://github.com/ethanplusai/harvey) - 跑在 Claude Code / Codex 订阅上的自主销售 agent，找潜在客户、按每家公司的具体信号写冷邮件，发信前逐封人工批准。

<a id="monitoring"></a>
## 热点与竞品监控（Trend & Competitor Monitoring）

- [TrendRadar](https://github.com/sansan0/TrendRadar) - AI 热点 / 舆情监控，支持多平台聚合和 MCP。
- [Horizon](https://github.com/Thysrael/Horizon) - AI 个人新闻雷达，生成中英双语每日简报。
- [last30days-skill](https://github.com/mvanhorn/last30days-skill) - 调研任意话题最近 30 天在 Reddit、X、YouTube、HN 等平台的讨论，并汇总成一份报告的 agent skill。
- [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) - 社媒调研 agent skills，用来找爆款帖子、挖评论、拆解竞品和查广告库（需要 ScrapeCreators API key）。

<a id="agents-mcp"></a>
## Agent 基础设施与 MCP（Agent Infra & MCP）

- [Agent-Reach](https://github.com/Panniantong/Agent-Reach) - 让 agent 读取和搜索 Twitter、Reddit、YouTube、GitHub 等平台的命令行工具，无需 API 费用。

<a id="related-lists"></a>
## 相关清单（Related Lists）

- [awesome-grok-bot](https://github.com/RongleCat/awesome-grok-bot) - Grok Bot 相关资源的中英双语精选清单。

<a id="contributing"></a>
## 参与贡献（Contributing）

条目格式：

```
- [名称](链接) - 一句话说明。
```

规则：

1. 只添加你已经核实过的资源，绝不编造条目。
2. 把条目加到最贴近的类别下，向 `main` 分支提 PR；现有类别都不合适时，可以在 PR 里新开一个类别。
3. 一次提交的条目较多时，建议一个 PR 只涉及一个类别。
4. 不想提 PR 也可以直接开一个 issue，把链接丢给 Launchpad 团队。

每周节奏：收集候选链接 → 提 PR → 合并到 `main`。
