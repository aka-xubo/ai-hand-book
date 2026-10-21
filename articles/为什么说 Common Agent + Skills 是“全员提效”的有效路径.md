# 为什么说 Common Agent + Skills 是“全员提效”的有效路径

> 本文根据原文整理为 Markdown。涉及内部人员、组织、系统和资料的信息已作匿名化处理；部分含内部信息的配图已模糊化，演示视频未收录。

为什么说 Common Agent + Skills 是“全员提效”的有效路径

# **SaaS又死了 -- Claude一个插件吓哭华尔街，软件公司集体暴跌，2万亿元一日蒸发**

- https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills

![内部示意图（已脱敏）](assets/common-agent-skills/01-legal-plugin-repository.png)

![图片是一条推文，发布者为相关用户，用户名为相关用户，带有蓝色验证标识。推文内容提到“saasapocalypse”（SaaS末日）终于到来，因汤森路透社一个GitHub代码库一天内股价暴跌18%，简直是一场戏剧。下方有31条评论。该推文与文档中提到的SaaS公司集体暴跌、2万亿元一日蒸发的背景相关，反映了SaaS行业当前的市场波动情况。](assets/common-agent-skills/02-market-reaction.png)

![图片是一条推文，发布者为相关用户，内容为“由于Anthropic为Claude添加了企业插件，纳斯达克指数今天下跌了2.3%。市场终于意识到了这一点。SaaS已死。”该推文配有英文和中文翻译，发布于2026年2月4日4:48 AM，获得了658.6K次浏览。图片与上下文紧密相关，上下文提到Claude一个插件引发市场反应，此推文正是对这一市场反应的直接表述。](assets/common-agent-skills/03-market-reaction.png)

![图片是一条推文，发布者为相关用户，用户名为@相关用户，发布日期为2月4日。推文内容为：企业使用SaaS是因为其可靠性。否则，90%的系统都包含一些逻辑、图形用户界面和数据库。不服来辩。Linux和MySQL都存在了60多年，但微软、苹果和Oracle仍然占据主导地位。该推文下方有2条评论、1次转发、85个点赞、21K次阅读。图片与上下文紧密相关，是对上下文提到的“SaaS又死了”的观点进行反驳，认为SaaS并非企业唯一选择，还有其他系统存在。](assets/common-agent-skills/04-saas-market-view.png)

![图片是一条Twitter推文，发布者为@相关用户。推文内容提到，如果插件会扼杀SaaS，那么O365/ServiceNow/Datadog早就倒闭了。正在发生变化的是谁可以成为“前门”：应用程序UI与模型UI。SaaS成为基础设施+合规性+记录系统；代理成为新的用户体验。该推文与文档中探讨的“全员提效”路径相关，强调了Common Agent+Skills在软件公司转型中的重要性。](assets/common-agent-skills/05-agent-interface-debate.png)

![华尔街
](assets/common-agent-skills/06-market-context.png)

![老黄：我不信
](assets/common-agent-skills/07-market-context.png)

# 2025年最具代表性的 3 个Common Agents

## Manus -- Common Agent 由我来“定义”

- https://manus.im/app

![图片展示了Manus的标志及宣传语。左侧背景为蓝色，有手的图案和“manu”字样，下方是“the general AI agent”；右侧手机屏幕上显示相同标志及宣传语。画面中一只手指向手机屏幕。该图片与文档中介绍Manus的内容相关，Manus被视为较早跑通PMF的代表，其目标是海外市场，产品愿景是“心手合一”，此图直观呈现了Manus的品牌形象。](assets/common-agent-skills/08-manus-product.png)

![图片是Manus发展时间线，从2024年12月项目启动到2025年12月ARR破亿。关键节点包括：2025年2 - 3月产品研发，3月6日正式发布，3月28日商业化启动，5月13日全面开放注册，7月起组织重构，8月20日首次披露营收，12月17日ARR破亿。该图与上下文介绍Manus作为Common Agent的商业表现及发展进程相呼应，直观呈现其发展脉络。](assets/common-agent-skills/09-manus-growth-timeline.png)

- 商业上：Manus 被视为较早跑通 PMF（Product-Market Fit） 的代表。

- 目标：海外市场

- 产品愿景：心手合一 -- 让智能真正触及现实世界，不做“理论物理学家”

> 模型解决的是智力问题，但是再强的智能，也没有办法把环境给内化掉，所以这就需要一双手，来去触及到现实世界。

- 产品思路：

- 来自 Cursor（一款AI编程产品）的启发：内部非工程师使用Cursor -- 运营同事写博客、数据分析同事数据分析与可视化

- 被动接受 AI 操作，对于不懂技术的人，存在天然的恐惧感 -- Cursor的形态对用户不是最优的

- 做观察者：用户应该可以按他的想象力去使用这个产品，通过观察用户在使用过程中整体的一个行为模式，去捕获到通用的场景，去做最后一公里的优化

- 产品形态：在云端可以异步执行，通过连接各种扩展，帮助所有知识工作者完成复杂工作的Common AI Agent

> **Manus 为什么不选一个领域进行深耕？**
> - 技术上
> - 专有模型被通用模型吃掉是很正常的事情
> - 通用模型+图灵机 理论上可以做任何东西
> - 通用的技术架构的优势 -- 用户可以按他的想象力去使用这个产品，不去引导用户做什么，而是看用户喜欢做什么
> - 产品上：
> - 很多能力最后会收敛，大家都会有，比如说之前很火的deepresearch
> - 通用产品有更大概率来服务用户的方方面面
> - 让 “长尾”用户满意，能够让用户出现 “aha moment” ，让用户获得极大的满足感

## Claude Code（以下简称CC）-- 一个被用户搞的“*不纯粹*”的“Code Agent”

- 工程上 -- 它是我心目中的 SOTA：https://www.anthropic.com/engineering

![图片展示了Anthropic官网的部分文章列表。左侧有三个图标，分别是三角形、指纹和圆圈。右侧文章标题及发布日期依次为：使用一组并行Claudes构建C编译器（2026年2月5日）、设计AI抗性技术评估（2026年1月21日）、为AI代理去神秘化（2026年1月9日）、有效利用长期运行代理（2025年11月26日）、在Claude开发者平台上引入高级工具使用（2025年11月24日）、使用MCP执行代码：构建更高效的代理（2025年11月4日）。这些文章与文档中介绍的Anthropic公司及其产品相关。](assets/common-agent-skills/10-agent-engineering-trends.png)

- 产品形态：相比于manus ，它一般运行在本地，代码能力T0级别，一样是Common Agent，支持各种插件

- 目标客户：开发者 -- 能力自然延展，覆盖到 “几乎所有的脑力工作者”  为什么会这样？-- 因为用户已经在这样用了。

- SDK 更名 -- Claude Code SDK ===> Claude Agent SDK

- 推出CoWork （GUI CC）-- “*not just developers*”

![图片展示了Agent SDK概述内容，强调使用Claude Code作为库构建生产级AI智能体。关键信息是“Claude Code SDK已更名为Claude Agent SDK”，并提示如需从旧版SDK迁移，请参阅迁移指南。该图片与文档中“SDK更名--Claude Code SDK===>Claude Agent SDK”内容对应，直观呈现了SDK名称变更这一重要信息。](assets/common-agent-skills/11-agent-sdk.png)

![图片为文档中介绍Claude Code部分内容的截图。文档提到发布Claude Code时预期开发者会用它编写代码，但很快开始用于几乎所有其他用途，促使开发了Cowork，一种更简单方式让所有人（不仅是开发者）以同样方式使用Claude。Cowork目前在macOS应用中面向Claude Max订阅用户推出，文档还标注了相关更新时间。图片中“Cowork”被红色框突出显示，与上下文紧密相关，直观呈现了Cowork这一概念。](assets/common-agent-skills/12-cowork-product.png)

## Open Claw -- 现象级开源，7天10万星，mac mini你买了吗？

![图片展示了GitHub排名Top 100中最高星项目列表，其中Open Claw项目以171654星位列第31位，仅次于n8n和gitignore。Open Claw是开源Windows和Office激活器，支持多种激活方法及高级故障排除，其创建时间为2026年2月7日。该图片与文档中介绍Open Claw为现象级开源项目，7天获10万星的内容相关，直观呈现了其在GitHub上的受欢迎程度。](assets/common-agent-skills/13-open-source-agent-ranking.png)

![图片展示的是一个名为“README”的界面，上方有“READM”字样。下方文字为“2026.01.31 本月最佳开源项目 TOP:opencode”，并配有“opencode”标识。该图片位于文档中介绍Open Claw开源项目部分，与上下文紧密相关，上下文提到Open Claw是现象级开源项目，7天内获10万星，mac mini已购买，此图可能是在展示与Open Claw相关的开源项目信息或排名情况。](assets/common-agent-skills/14-open-source-project.png)

- 特点1：真正能在 Personal 的基础上做到 Long Horizon Tasks。

![内部示意图（已脱敏）](assets/common-agent-skills/15-agent-daily-brief.png)

- 特点2：扩散效果好 -- 通过 IM Gateway 直接嵌入了用户的日常沟通流 （飞书、企微、whats app、slack）。

![图片展示了飞书Navi在手机端的使用界面。左侧显示“Remaining for today: 28P pending”，有多个待办事项，如回复相关用户等。中间界面有“Cancel”和“Upload”按钮，下方是飞书键盘。右侧界面显示“Navi - Podcast Notes.mp3”，有播放控制条，下方也有飞书键盘。该图片与文档中介绍飞书Navi在手机端使用场景的内容相关，直观呈现了其在手机端的界面样式及操作情况。](assets/common-agent-skills/16-mobile-agent-interface.png)

- 特点3：预装技能 -- 像于早期智能手机预装应用超市和 Use Case 来教育用户如何使用智能机一样，来降低用户的使用门槛。

![图片展示的是一个名为“skill - creator”的界面。界面上方有“Disable”按钮，下方文字说明在设计、结构化或打包技能时，可使用此功能，与脚本、参考文献和资产一起创建或更新AgentSkills。界面中有两个标签，“moltbot - bundled”和“eligible”，其中“eligible”标签以绿色突出显示。该图片与文档中介绍Claude Code（CC）预装技能的内容相关，直观呈现了CC预装技能的界面样式。](assets/common-agent-skills/17-skill-creator-interface.png)

![图片展示了Claude Code的技能界面。左侧有“coding-agent”标识，下方说明可通过后台进程运行Codex CLI、Claude Code、OpenCode或PI Coding Agent，实现程序化控制。右侧有“Disable”按钮，下方有“openclaw-bundled”和“eligible”标签。该图片与文档中介绍Claude Code技能的内容相关，直观呈现了其技能运行方式及状态标识，帮助用户了解其功能和当前状态。](assets/common-agent-skills/18-coding-agent-skill.png)

- 特点4：SOUL -- 真的是在设计一个“有血有肉的人类”，同时还在“建模用户”

![图片展示了三句与工作沟通相关的建议。上方是“这个文件夹就是家。把它当作家一样对待”，强调对文件夹的重视。中间是“写下来 - 不要‘记在脑子里’！”，提倡记录信息。下方是“群聊中的人类不会回复每条消息。你也不应该。质量 > 数量。如果你在真实的与朋友群聊中不会发它，那就不要发”，强调群聊中应注重质量，避免无意义信息。这些建议与文档中关于工作沟通的讨论相呼应，为高效沟通提供参考。](assets/common-agent-skills/19-agent-communication-principles.png)

![图片展示了Claude Code（CC）预装技能中SOUL的部分对话内容。上方是“你刚刚醒来。是时候弄清楚你是谁了。”，中间是“你现在是你自己了。”，下方是“这不只是元数据。这是弄清楚你是谁的开端。”。这些对话体现了CC在设计上注重“有血有肉的人类”，在“建模用户”方面的努力，与文档中介绍CC预装技能、降低用户使用门槛的内容相呼应。](assets/common-agent-skills/20-agent-personalization.png)

## 总结

|  | 产品形态 | 界面 | 是否支持Skills | 部署形态（一般） | 适用人群 | 市场 |
| --- | --- | --- | --- | --- | --- | --- |
| Manus | Common Agent | GUI | 是 | 云端 | 所有知识工作者 | 海外 |
| Claude Code | Common Agent | TUI + Cowork GUI | 是 | 本地 | 硬核开发、所有知识工作者 | 海外 |
| Open Claw | Common Agent | TUI + GUI | 是 | 本地 | 所有知识工作者 | 开源 |

### Common Agent 产品底层逻辑

- “Common中的垂类” -- 做一个不断优化的头部场景

- Claude code -- 软件研发

- Manus -- deep research

- 保持很强的“长尾能力” -- 当系统有足够多的可以被hack的点，观察用户怎么“滥用它”。当你看到用户用你的产品做一些你完全没想到的事情时，那就是潜在需求。

- 选择高频的潜在需求，通过插件/skills 的方式产品化这些场景

- 一个Common Agent 底座中，让不同场景之间有更好的协同性，并且互相增强相互的网络效应

# Common Agent 能力解读

## 强大的内核支撑

![图片展示了Common Agent工程化要素，即构建优秀通用智能体的核心能力。包含记忆系统、循环系统、工具调用、基础工具、编程能力、模型交互等要素。记忆系统支持长期与短期记忆，循环系统实现推理 - 行动 - 观察闭环，工具调用具备调用外部工具能力，基础工具内置Linux Bash等，编程能力通过代码实现业务逻辑，模型交互支持多种输入输出。该图与上文“Common Agent能力解读”中对Common Agent能力的介绍相呼应。](assets/common-agent-skills/21-common-agent-components.png)

## 能力边界在哪里？

![图片标题为“Common Agent能力边界的影响因素”，阐述决定智能体能力上限的四大要素。包含环境、工具、用户、模型四个部分。环境方面，部署形态决定资源与能力；工具方面，基础软件能力与可扩展技能丰富程度；用户方面，输入质量决定输出质量；模型方面，底层模型能力越强，Agent表现越好。该图与上文介绍Common Agent能力解读的内容相呼应，直观呈现其能力边界影响因素。](assets/common-agent-skills/22-agent-capability-boundaries.png)

## 一流厂商定标准，三流厂商做产品 -- Anthropic：“老子全都要”

### MCP 标准 -- 旨在为 AI 模型与外部资源之间提供统一的连接方式。

- 由 Anthropic 于 2024 年推出，25年12月被捐献给 Agentic AI Foundation，成为通用标准。

- MCP 希望能够像 USB-C 接口一样成为 AI 系统与各种数据源和工具之间的“通用接口”。

- 不同的 AI 应用可以轻松与多种数据源、工具进行“即插即用”的连接，无需再为每种不同的数据源开发独立的集成方法。

![图片展示了MCP架构，以笔记本电脑为背景，左侧有MCP server、Remote services、MCP clients等组件，右侧有MCP hosts、Claude、Local data sources等。MCP server与Remote services、MCP clients相连，MCP clients与MCP hosts相连，MCP hosts与Claude、Local data sources相连。该图与上下文紧密相关，直观呈现了MCP架构中各组件及其连接关系，帮助理解MCP在模型能力下降问题中的应用背景。](assets/common-agent-skills/23-mcp-architecture.png)

### 标准之殇

- 上下文过长容易导致模型能力下降： MCP要求把工具的完整定义给到模型，工具越多，占用的模型上下文越大，模型还没开始干活呢，就已经“撑死”了

### 从MCP 到 Skills，即是工程上优化，也是范式转移

- **工程巧解**： Anthropic 为了解决工具调用带来的胖上下文问题，提出了“渐进式披露/加载”的解法，从而推出了Skills

![信息分层设计哲学
](assets/common-agent-skills/24-progressive-disclosure.png)

> 如果你希望了解“渐进式加载”，我强烈建议你去阅读这篇文章：[从《塞尔达传说》到AI Agent：Claude Skills背后的信息分层设计哲学](https://mp.weixin.qq.com/s/F9BtGpZNQxLkalg62ayBXw)

- **宽松的架构设计：**仅仅是信息分层不足以引起“能力涌现”，更巧妙的是它让一个没有编程能力的人，仅仅**依靠语言组织能力**，就可以低成本创造出AI可执行的技能，这让它具备了“**广泛的群众基础**”

![技能短时间内爆发式增长
](assets/common-agent-skills/25-skills-growth.png)

# Skills -- 范式转变，从面向人类交接到面向Agent交接

> 想象你要把一项工作交给新同事。要是不能口头传达，只能通过文档交接（并且你想一次就交接好，之后别再被打扰），你会准备什么？
> - 任务的执行 SOP 与必要背景知识（这件事大致怎么做）
> - 工具的使用说明（用什么软件、怎么操作）
> - 要用到的模板、素材（历史案例、格式规范）
> - 可能遇到的问题、规范、解决方案（细节指引补充）

## 拆解“交接大礼包”

Skill 的设计架构，几乎是人类交接大礼包的数字版本：

- 在 Skill 中，指令文档用于灵活指导，代码用于可靠性调用，资源用于事实查找与参考。

![相对标准的 Skill 结构示例，其中只有 SKILL.md 是必需的，其他结构为可选项
](assets/common-agent-skills/26-skill-package-structure.png)

## 那个干掉几千亿美金市值的插件长啥样？

![内部示意图（已脱敏）](assets/common-agent-skills/27-internal-skill-example.png)

## Skills vs 传统AI工作流

> 原文包含内部流程画板，本版本已隐藏画板内容。

![图片对比了传统AI工作流与Agent Skills。传统AI工作流存在刚性路径、维护困难、学习成本高、平台锁定等问题；而Agent Skills则可移植，借助LLM智能灵活应对各类问题，组合拔高，N个Skill可应对远超N的应用场景。图片位于介绍Skills与传统AI工作流差异的上下文之间，直观呈现了两种工作流的优劣对比，强调了Agent Skills在灵活性和可移植性上的优势。](assets/common-agent-skills/29-workflow-vs-skills.png)

> - **Skills 与Workflow是可以融合的**：在特定的业务场景下，刚性代表确定性，灵活意味着不可靠，通过Workflow 封装确定性，由 Agent 承担类似 hook 的角色，直接触发

# 回答 - 为什么说 Common Agent + Skills 是“全员提效”的有效路径

![图片以“Common Agent + Skills：知识沉淀新范式”为标题，阐述人人可贡献、AI擅长执行、知识永续传承的理念。分为受众广、门槛低、可持续、AI擅长执行、Wiki转Skill、传帮带转AI复制六个方面，分别说明任何人都能贡献专业知识、无需掌握复杂AI技术、封装一次可多次使用、AI能执行结构化知识、从Wiki封装Skill直接用、从传帮带变成AI学习后规模化复制。该图与上下文紧密相关，直观呈现了Common Agent + Skills的优势。](assets/common-agent-skills/30-skills-knowledge-model.png)

# 真AI Native 产品未来的发展趋势

### 知识型SaaS：**重构护城河，价值锚点迁移**

- 知识型SaaS（专家经验数字化）依赖信息获取和整理，受冲击影响大，市场在重新定价

**Thomson Reuters 股价被击穿的背后逻辑**

![图片展示了知识型SaaS价值重构前后的对比。标题为“价值重构前后”，左侧是旧价值公式，包含数据、界面、解读三层收费，且为高毛利模式；右侧是新价值公式，仅剩数据，变为一层收费，利润出现压缩。图片与上下文紧密相关，上下文提到知识型SaaS要重构护城河、价值锚点迁移，图片通过价值公式的前后变化直观呈现了这一趋势，突出了从复杂模式向简洁模式转变的特点。](assets/common-agent-skills/31-knowledge-saas-value.png)

- 重构护城河，价值锚点迁移

- 不堆叠功能

- 往数据独占方向走 ===> 这部分是通用模型无法训练到的

- 与客户建构信任链===> 基于墙内数据打造的可信任链：出事了，我可以负责，你行吗？

![图片展示了法律风险评估技能的内容。作为公司内部法务团队的法律风险评估助理，需运用结构化框架协助评估、分类和记录法律风险。重要提示指出，协助处理法律流程但不提供法律建议，风险评估应由合格法律专业人士审核，框架仅供参考，各组织应根据自身风险承受能力和行业背景定制。图片与上下文紧密相关，是对法律风险评估技能职责和注意事项的说明。](assets/common-agent-skills/32-legal-skill-example.png)

![图片为新闻标题及相关内容，标题为“数据公司受AI抛售潮冲击，对Claude威胁论予以反击”。内容提到在本周由人工智能引发的抛售潮中遭受重创的两家公司——汤森路透和洲际交易所周四主张，它们宝贵的专有数据资料库将使其免受AI的干扰。图片与上下文的关系是，上下文提到知识型SaaS依赖信息获取和整理，受冲击影响大，而图片内容则反映了数据公司对AI威胁的回应，强调其专有数据资料库的保护作用。](assets/common-agent-skills/33-news-context.png)

### 流程型SaaS： **新的交互范式 -- Workflow In Chat**

- 流程型SaaS因严密的业务逻辑，0容错，护城河很高

- **观点1：逐步失去入口控制权**

- Agent 交互友好性，AI 对话成为主要入口

- 继而失去前端界面交互的定价权，逐渐从前端的操作软件演变成后端的CRUD 接口/数据库

![图片展示了传统Web助手（嵌入式）与对话式AI工作台（独立式）的交互方式对比。左侧为传统Web助手，界面占比较小，集成方式为浮层/弹出，功能定位单一，对话，使用场景为辅助咨询、快速问答。右侧为对话式AI工作台，界面占比较大，集成方式为独立应用/浏览器插件，功能定位为对话+知识+流程管理，使用场景为使用终端、专业工作台、流程管理、深度交互。该图与上下文讨论的流程型SaaS交互方式变化相关，直观呈现了两种交互方式特性。](assets/common-agent-skills/34-ai-workbench-comparison.png)

- **观点2：定制化服务溢价被击穿**

- 交付被卷：Coding Agent 能力这么强，交付为什么这么慢？

- agent高扩展性：有没有原子API，做没做到Agent 平权，直接让agent 定制行不行？

- **观点3：新的交互范式 -- LUI（language user interface） + GUI in Chat + API Action**

- LUI：对话入口，通过对话+文件+语音进行意图识别

- GUI in Chat：动态更新、原生媒体预览、状态持久化，以及直接的可视化操作流程

- API Action：接口、MCP Server 以及Skills

> **3大要素加速这一范式落地**
> - 体验既效率：LUI 极简的操作方式，让用户通过对话调动复杂的业务系统
> - 个性化需求的即时满足：无需排期，agent 实时理解业务意图，动态渲染出符合标准的前端组件
> - 甲方数据主权：一旦新交互范式普及，那么甲方一定会将其写入招标要求

- **观点4：商业价值分化**

- Level1：infra - 提供API 基础调用，沦为驱动他人界面的“**哑**”后端。

- Level2：数字员工 - 切分客户的工资体系，而不是 IT 预算

### 构建AI Native 应用的5大原则

要构建 Agent-native 应用，我们需要遵循以下 5 大核心原则：

![图片展示了构建AI Native应用的5大原则，从基础能力到涌现智能的完整方法论。从上至下依次为：随时间进化，通过上下文积累和Prompt优化持续进化；涌现能力，Agent完成未显式设计任务形成飞轮效应；可组合性，通过编写新Prompt创造新功能；颗粒度，原子工具经Agent组合实现功能特性；平权，用户通过UI能做的事Agent通过工具完成。这些原则与文档中构建Agent - native应用需遵循的5大核心原则内容相呼应。](assets/common-agent-skills/35-ai-native-principles.png)

# 组织实践：Skills 的应用思考与实践

## 高频且碎片化的，容易打断工作主线的协作事项

- 用户自己去做，而且不需要知道在入口在哪里

> 原文包含演示视频，本版本未收录视频。

## 数据分析 -- 不只是提供图表，而且是从专业角度洞察

- 图表出现的意义是为了帮助人类更加方便的总结信息

- 大量图表反而会分散人的注意力

- 通过AI总结，直接给到人类想要的信息

> 原文包含演示视频，本版本未收录视频。

**之前**

![内部示意图（已脱敏）](assets/common-agent-skills/36-internal-skill-dashboard.png)

**现在**

![内部示意图（已脱敏）](assets/common-agent-skills/37-internal-usage-report.png)

## 专家经验沉淀 -- 让你的Agent 也成为专家

- 背景：公司万年Java8的服务要统一升级

- 以前的方式：一位 Java 技术专家 先趟坑 -- 实验+总结，给出文档 ，再交接给其他团队，其他团队参考文档升级

- 现在的方式：文档变成了技能，Agent直接学习使用，单个项目升级可以从2天缩短到2小时

## 用 Skills 串联研发工作流

> 原文包含内部流程画板，本版本已隐藏画板内容。

- 研发工作流的每个节点，都需要Skill的支撑

- Jira分析 -- 通过分析Jira与AI共创需求

> 原文包含演示视频，本版本未收录视频。

## 知识库 -- 不要再开通文档权限（待制作）

- Skill 架构天然适合做知识库

![内部示意图（已脱敏）](assets/common-agent-skills/39-document-permissions.png)

# 普通人如何开始

### 首先得安装1个可以工作的Common Agent

| Agents | 是否需要下载 | 是否需要付费 | 是否有图形界面 | 推荐指数 | 备注 |
| --- | --- | --- | --- | --- | --- |
| Claude Code CLI | 是 -- 找 | 公司统一支付费用 | 否 | 5 |  |
| Codex CLI | 是 -- 找 | 公司统一支付费用 | 否 | 4 |  |
| Codex Mac App | 是 -- 下载地址： https://openai.com/zh-Hans-CN/codex/get-started/ ，且找 | 公司统一支付费用 | 是 | 4 | - 非开发者，Mac OS 用户推荐 |
| Manus | 否 -- 登陆注册：https://manus.im/app | 非Pro版本每天有固定额度 | 是 | 3 | - 本地文件需要通过上传、下载操作 - 不能连接处理公司内部业务，适用个人 - 模型效果不保证 |
| Trae | 是 -- 下载地址：https://www.trae.ai/ | 非Pro版本每天有固定额度 | 是 | 3 | - 模型效果不保证 |

> 如果以上都不满足，你再等等 正在加紧制作 Claude Code 桌面版本

### 一切从学习如何使用Skills 开始

- Github 上有超过10万个技能，覆盖了日常办公领域的各个方面

- 组织内部的 Skills 平台

> - 你们肯定希望可以一键安装skills，请耐心等待【Skills 一键安装】 -- 一键安装已经支持
> - 你们肯定希望可以快速找到你想要的skills，请耐心等待【Skills 检索】

#### 示例1：还是那个超贵的法律咨询技能

- 此处演示省略1000字

#### 示例2：你的AI用的不好，大概率是因为你不会提问，没关系，让AI问你吧

- 此处演示省略1000字

#### 示例3：视频制作

- 此处演示省略1000字

### 技能组合 - 一套小连招

- 使用skill-creator 创建技能：用“Excel Analysis" 分析数据，通过 "Baoyu Infographic" 展示图表

### 后续

- 将你日常工作中高频的流程、工作方式、知识整理成档，然后使用skill-creator构建

- 积极分享，为组织贡献Skills 到

> 示例中所用技能均可从此处下载：
> - 技能创作：skills/skill-creator
> - 法律合规咨询：skills/anthropics/knowledge-work-plugins
> - 头脑风暴：skills/superpowers-brainstorm
> - 视频制作：skills/remotion
> - 数据分析：skills/excel-analysis
> - 图表展示：skills/antvis/Infographic

# 结尾

> - 这个世界充满不确定性，若将模型的每次迭代升级视为海平面上升，那么我们需思考：我们所构建的是什么，是沙堡还是船？若是前者，其必将被淹没；若是后者，我们又有什么好担心的？
> - 26年，每个人都应该要能使用Skills，我们不需要成为**superman**，要成为**hyberman**，不一定拥有能力，但要拥有能自主调用的能力，整个 github 都可能成为你的能力

![图片以蓝色文字呈现，强调AI开发中避免被AI“喂废”的重要性。核心内容包括：AI需懂业务逻辑，才能写出AI能懂的Spec；永远维护“意图”的单一来源；避免被AI“喂废”；SDD也可理解为“损耗左移”AI原生开发世界观；最危险的陷阱是把思考的痛苦完全外包给AI；小白需能看懂测试用例是否覆盖了业务场景，这是胜任工作的底线。图片与上下文紧密相关，是对AI开发中需注意的关键点的总结。](assets/common-agent-skills/40-ai-development-principles.png)
