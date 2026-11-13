# Reddit AI and Programming Trends Digest / Reddit AI与编程趋势摘要

Date / 日期: Friday, November 13, 2026

Search status / 搜索状态: The search results are predominantly historical snippets. Most items are older than 24 hours. Items within the last 24 hours are marked "recent" in the item text, based on the age shown in the search results (for example "23 hours ago", "1 day ago", "10 hours ago"). Several of those recent items come from news outlets, YouTube, Instagram, or LinkedIn rather than Reddit. Reddit pages returned HTTP 403 in earlier runs, so Reddit content comes from search snippets only.
搜索状态：搜索结果以历史摘要为主。绝大多数条目早于24小时。过去24小时内的条目，已根据搜索结果中显示的时间（如"23 hours ago"、"1 day ago"、"10 hours ago"）在条目文字中标注为"近期"。其中部分近期条目来自新闻媒体、YouTube、Instagram或LinkedIn，而非Reddit。Reddit页面在之前的运行中返回HTTP 403，因此Reddit内容仅来自搜索摘要。

Not found / 未找到: The following named items had no matching result and are not included as items: the r/LocalLLaMA post on AI tools developers stop using after hype (10 hours ago), the r/ArtificialInteligence post on enterprise cloud fragility, the r/GrokBot post itself (the Grok Bot items below come from GitHub, xAI, and other sources), the r/grok post on agent reliability and retry fatigue, the Devsplainers post as a Reddit thread (a related Devsplainers-attributed Reddit result was found; see below), and the r/Rlanguage and r/Python post on migrating from specialized statistics environments. The r/learnprogramming Python-over-JavaScript item was not re-found in this run; an older r/learnprogramming thread is cited below instead. The Matt Maher 40% figure comes from the video snippet and was not verified in the video itself.
未找到：以下指定条目没有匹配结果，因此不作为条目收录：r/LocalLLaMA关于开发者在热潮过后停用的AI工具（10小时前）的帖子、r/ArtificialInteligence关于企业云脆弱性的帖子、r/GrokBot帖子本身（下列Grok Bot条目来自GitHub、xAI及其他来源）、r/grok关于智能体可靠性与重试疲劳的帖子，以及作为Reddit帖子的Devsplainers条目（找到了一条与Devsplainers相关的Reddit结果，见下文），以及r/Rlanguage与r/Python关于从专业统计环境迁移的帖子。r/learnprogramming关于Python超过JavaScript（由ML与数据工作负载驱动）的条目，本次运行未能重新找到，下文改引用一条较早的r/learnprogramming帖子。Matt Maher的40%数据来自视频摘要，未在视频正文中核实。

## 1) AI Applications / AI落地方向

### United Airlines restricts personal AI agents / 美联航限制个人AI智能体
- Recent (23 hours ago, YouTube short, Broke in Prod): United Airlines published a help-center page titled "Unauthorized third-party AI agents or assistants." Link: https://www.youtube.com/shorts/SINapsQM23A
  近期（23小时前，YouTube短视频，Broke in Prod）：美联航发布了标题为"Unauthorized third-party AI agents or assistants"（未经授权的第三方AI智能体或助手）的帮助中心页面。链接：https://www.youtube.com/shorts/SINapsQM23A
- Recent (1 day ago, Investing.com and Reuters-syndicated StreetInsider; SRN News and Thrifty Traveler carry the same story): United said on Wednesday it would restrict AI bots' access to its digital platforms, citing data security. Thrifty Traveler says United is the first U.S. airline to publicly block AI agents from booking flights, citing privacy, security, and FAA and DOT rules. Links: https://www.investing.com/news/stock-market-news/united-airlines-moves-to-block-ai-agents-from-its-platform-over-security-concerns-5019752 ; https://srnnews.com/united-airlines-moves-to-block-ai-agents-from-its-platform-over-security-concerns/ ; https://thriftytraveler.com/news/airlines/united-blocks-ai-agents-booking-flights/
  近期（1天前，Investing.com，并由StreetInsider转载路透社报道；SRN News与Thrifty Traveler也报道了同一事件）：美联航周三表示，将限制AI机器人访问其数字平台，理由是数据安全。Thrifty Traveler称，美联航是首家公开禁止AI智能体订票的美国航空公司，理由包括隐私、安全以及FAA和DOT规则。链接：https://www.investing.com/news/stock-market-news/united-airlines-moves-to-block-ai-agents-from-its-platform-over-security-concerns-5019752 ；https://srnnews.com/united-airlines-moves-to-block-ai-agents-from-its-platform-over-security-concerns/ ；https://thriftytraveler.com/news/airlines/united-blocks-ai-agents-booking-flights/
- Recent (1 day ago, Newsmax): United said allowing AI agents to conduct transactions could expose customers' sensitive personal information or result in unintended purchases. No link was returned in the snippet for this specific item beyond the Google news redirect, which is not reproduced here.
  近期（1天前，Newsmax）：美联航表示，允许AI智能体进行交易可能导致客户敏感个人信息泄露，或产生非预期的购买。
- Recent (10 hours ago, LinkedIn, John Walter): The post says that on November 11, United rewrote its contract of carriage, and that using an AI agent to "make, modify or service a Ticket" is now prohibited. The post says a violation allows United to take action. Link: https://www.linkedin.com/posts/jowalter_united-airlines-just-banned-personal-agents-activity-7526658915359686656-yptm
  近期（10小时前，LinkedIn，John Walter）：该帖称，美联航于11月11日修改了运输合同，现在禁止使用AI智能体"制作、修改或服务机票"，违规者将面临美联航采取的行动。链接：https://www.linkedin.com/posts/jowalter_united-airlines-just-banned-personal-agents-activity-7526658915359686656-yptm
- Takeaway: airlines are setting rules for personal agents acting on a customer's behalf. Check any airline or vendor terms before letting an agent book, change, or buy anything.
  收获：航空公司正在为代表客户行事的个人智能体设定规则。在允许智能体预订、修改或购买任何内容之前，应先查看相关航空公司或供应商的条款。

### Cloud outages and AI reliability / 云服务中断与AI可靠性
- Historical (Jan 23, 2026, 2WTech): A Microsoft 365 outage temporarily knocked out access to Outlook, Teams, and other core cloud services. Link: https://2wtech.com/microsoft-365-outage-disrupts-outlook-teams-and-core-cloud-services/ (older than 24 hours).
  历史（2026年1月23日，2WTech）：一次Microsoft 365中断使Outlook、Teams及其他核心云服务暂时无法访问。链接：https://2wtech.com/microsoft-365-outage-disrupts-outlook-teams-and-core-cloud-services/（早于24小时）。
- Historical (Dec 9, 2025, GBHackers and Yahoo! Finance Canada): Copilot had an outage affecting users in the UK, with degraded access reported; Yahoo says Copilot is integrated into the company's other products. Links: https://gbhackers.com/microsoft-copilot-outage-disrupts-uk-and-europe/ ; https://ca.finance.yahoo.com/news/microsoft-copilot-down-ai-assistant-112709054.html (older than 24 hours).
  历史（2025年12月9日，GBHackers与Yahoo! Finance Canada）：Copilot出现中断，影响英国用户，报告称访问降级；Yahoo称Copilot已集成到该公司的其他产品中。链接：https://gbhackers.com/microsoft-copilot-outage-disrupts-uk-and-europe/ ；https://ca.finance.yahoo.com/news/microsoft-copilot-down-ai-assistant-112709054.html（早于24小时）。
- Historical (Feb-era Computing UK snippet, undated in the result): Microsoft attributed a complete Copilot outage across platforms to a DDoS attack. Link: https://www.google.com/goto?url=CAESlwEBxCJF1yV7GAKY0GzQPKY5ojtiuXsd-3AgxPOI34MCiRDzf77Xq-hUPAGecWqcfQaJ2fXHBPMAWIgwC6AuI13ff40XrLOHfDu9qeGciPHItEHLmknpCL1F_OzNoJg2KuDn0jGvjlYbwlhDsl9BkPQftE8EE2G07bOdt7sGnAklq_jX_yTfnIqx779EVxyKk_ayrBRyD6k4 (date not shown; treat as older than 24 hours until confirmed).
  历史（Computing UK，结果中未注明日期）：微软将Copilot在所有平台上的完全中断归因于DDoS攻击。链接同上（日期未显示，在确认之前应视为早于24小时）。
- Takeaway: an AI feature is only as available as the cloud it runs on. Plan a fallback for when the host service goes down, and do not treat AI availability as separate from the platform.
  收获：AI功能的可用性不会超过其所依赖的云服务。应为宿主服务中断制定备用方案，不要把AI的可用性与平台本身割裂看待。

## 2) Prompts, Grok Bot and Personal Agent Applications / 提示词、Grok Bot与个人智能体应用

### Grok Bot's dedicated cloud computer per agent / Grok Bot为每个智能体配置专属云端电脑
- Historical (Aug 11, 2026, GitHub grok-bot-app/grok-bot): The repository describes Grok Bot's own cloud computer, saying the bot works not on your device but in a dedicated cloud VM with browser, filesystem, and terminal. Link: https://github.com/grok-bot-app/grok-bot (older than 24 hours).
  历史（2026年8月11日，GitHub grok-bot-app/grok-bot）：该仓库描述Grok Bot拥有自己的云端电脑，称Bot不在用户设备上运行，而是在专属云虚拟机中运行，并配有浏览器、文件系统和终端。链接：https://github.com/grok-bot-app/grok-bot（早于24小时）。
- Historical (Aug 11, 2026, xAI): Grok Bot is described as a team of always-on agents that have their own computer, work inside tools and apps, and keep working 24/7. Link: https://x.ai/news/introducing-grok-bot (older than 24 hours).
  历史（2026年8月11日，xAI）：Grok Bot被描述为一支常驻智能体团队，拥有自己的电脑，在工具和应用中工作，并全天候持续运行。链接：https://x.ai/news/introducing-grok-bot（早于24小时）。
- Historical (Sep 14, 2026, aik8s.run): Grok Bot is described as a hosted computer-use agent rather than a downloadable model. Its persistence is its most obvious difference from ordinary agents. Link: https://www.google.com/goto?url=CAESdQHEIkXXnO7HFhgBsZDMPXFMS6aBe3Ht01svkl7KSre2JzYgVDQVaGQSemVCs4KfqorpZL2XL3FCoOzUGwY6IKhEHT_ftvTw6Lx-8ceLJZlQEnQHZj__j6JrA_AW3y5qF8_8P6nuFQYNCIry7WwB2nOeznlajw (older than 24 hours).
  历史（2026年9月14日，aik8s.run）：Grok Bot被描述为托管的计算机使用智能体，而非可下载部署的模型；其持久性是与普通智能体最明显的区别。链接同上（早于24小时）。
- Historical (Aug 20, 2026 and Aug 15, 2026): Reddit r/AISEOInsider snippet says Grok Bot turns AI agents into cloud workers that can log into apps, draft replies, and keep running. Link: https://www.google.com/goto?url=CAESmgEBxCJF17yc9ETKAwvDNdCU3-dwE1u143DHmdrtLkWD6-83RfW9RftHySnT_HKVeXPUF9MyhyYGs6Vv8uPgd7oTCb6xZYmggNP0I4XK33MaEiVlntkvpJuCy2kgymdQKvIPO7Uz0y_dbeVs5yIhmLGLR7yhEoAIcEdjXwIetpRG3mf0inUoKXC4L-r9ULl8eXPuKxZ08VwO-oPw (older than 24 hours). Separately, joaoqueiros.com (Aug 15, 2026) describes a managed cloud computer and durable bot identities. Link: https://www.ai.joaoqueiros.com/blog/grok-bot-always-on-ai-agent-teams-routines-skills-security (older than 24 hours).
  历史：Reddit r/AISEOInsider的摘要称，Grok Bot把AI智能体变成可以登录应用、起草回复并持续运行的云端工作者。链接同上（早于24小时）。另外，joaoqueiros.com（2026年8月15日）描述了托管的云端电脑和持久的Bot身份。链接：https://www.ai.joaoqueiros.com/blog/grok-bot-always-on-ai-agent-teams-routines-skills-security（早于24小时）。
- Recent (4 days ago, GitHub wolfqing/OpenSuperBot): An open-source, self-hosted alternative describes AI teammates that each get a cloud computer with a browser, filesystem, and terminal, plus persistent memory and bot-to-bot communication. Link: https://github.com/wolfqing/OpenGrokBot (4 days ago, so older than 24 hours).
  近期但仍早于24小时（4天前，GitHub wolfqing/OpenSuperBot）：一个开源的自托管替代方案，描述了各自拥有云端电脑（含浏览器、文件系统、终端）、具备持久记忆并可在Bot之间通信的AI队友。链接：https://github.com/wolfqing/OpenGrokBot（4天前，早于24小时）。
- Not confirmed in the results: dedicated instance per agent for tool logins and 2FA handling. The GitHub and xAI sources describe a per-bot cloud computer, but the search results did not confirm 2FA navigation or 24/7 background execution beyond the xAI wording "keep working 24/7." Treat those specifics as unverified.
  未经结果证实：为每个智能体提供专属实例以处理工具登录和双重验证（2FA）。GitHub与xAI来源描述了每个Bot拥有云端电脑，但搜索结果未证实2FA导航，除xAI的"全天候运行"表述外，也未证实后台持续执行的细节。这些具体内容应视为未经验证。
- Takeaway: a per-bot cloud computer with its own browser and files is the common pattern. Check which logins each bot holds and how it handles second-factor prompts before granting access.
  收获：拥有自己浏览器和文件的每Bot云端电脑是常见模式。在授予访问权限之前，应检查每个Bot持有哪些登录凭据，以及它如何处理二次验证提示。

## 3) AI Practical Dev Tips / AI开发实用技巧

### Review is the new bottleneck / 审查成为新的瓶颈
- Recent-to-historical (Aug 29, 2026, YouTube short, 2분코딩): AI coding agents generate code quickly, but they do not eliminate the cost of review, which involves understanding context, risks, and tests. Link: https://www.youtube.com/shorts/8HPAThYIZxo (older than 24 hours).
  近期至历史（2026年8月29日，YouTube短视频，2분코딩）：AI编程智能体能快速生成代码，但并不能消除审查的成本，审查需要理解上下文、风险和测试。链接：https://www.youtube.com/shorts/8HPAThYIZxo（早于24小时）。
- Historical (Jun 17, 2026, Reddit r/ClaudeAI, "AI coding is no longer the bottleneck. Review readiness is."): This is listed via an attribution to the Devsplainers account in the search index. Link: https://www.reddit.com/r/ClaudeAI/comments/1u82o60/ai_coding_is_no_longer_the_bottleneck_review/ (older than 24 hours; the snippet shows 12 answers, but the body was not opened).
  历史（2026年6月17日，Reddit r/ClaudeAI，"AI coding is no longer the bottleneck. Review readiness is."）：搜索索引中该条目与Devsplainers账号相关联。链接：https://www.reddit.com/r/ClaudeAI/comments/1u82o60/ai_coding_is_no_longer_the_bottleneck_review/（早于24小时；摘要显示有12条回复，但正文未打开）。
- Historical (May 6, 2026, daily.dev, "The bottleneck was never the code"): Jevons Paradox means cheaper code leads to more features, not fewer, making focus and prioritization harder. Link: https://daily.dev/posts/the-bottleneck-was-never-the-code-7dackdzws (older than 24 hours).
  历史（2026年5月6日，daily.dev，"The bottleneck was never the code"）：杰文斯悖论意味着代码变便宜会带来更多功能而非更少，使专注和优先级排序更困难。链接：https://daily.dev/posts/the-bottleneck-was-never-the-code-7dackdzws（早于24小时）。
- Historical (Jevons paradox, r/cscareers, Oct 1, 2026): Thread on Jevons paradox in the context of careers. Link: https://www.reddit.com/r/cscareers/comments/1wv1k77/jevons_paradox/ (older than 24 hours; body not opened).
  历史（杰文斯悖论，r/cscareers，2026年10月1日）：关于职业背景下杰文斯悖论的讨论。链接：https://www.reddit.com/r/cscareers/comments/1wv1k77/jevons_paradox/（早于24小时；正文未打开）。
- Recent (8 days ago, Instagram): A new study finds that bottlenecks downstream, including review and testing, keep AI-generated code from lifting overall productivity. Link: https://www.instagram.com/reel/DfWZUYPSp9P/ (8 days ago, so older than 24 hours).
  近期但仍早于24小时（8天前，Instagram）：一项新研究发现，包括审查和测试在内的下游瓶颈使AI生成的代码无法提升整体生产力。链接：https://www.instagram.com/reel/DfWZUYPSp9P/（8天前，早于24小时）。
- Historical (Sep 2025 and Feb 2026): METR found experienced developers were 19% slower with AI tools while believing they had sped up. Sources: https://www.reddit.com/r/softwarecrafters/comments/1sdgjv7/the_productivity_paradox_of_ai_coding_assistants/ (7 months old) and https://www.giga.engineer/blog/ai-productivity-paradox-2026 (Feb 4, 2026). Both older than 24 hours.
  历史（2025年9月及2026年2月）：METR发现，经验丰富的开发者使用AI工具时慢了19%，而他们自以为快了。来源：https://www.reddit.com/r/softwarecrafters/comments/1sdgjv7/the_productivity_paradox_of_ai_coding_assistants/（约7个月前）与https://www.giga.engineer/blog/ai-productivity-paradox-2026（2026年2月4日）。两者均早于24小时。
- Takeaway: budget time for review, tests, and verification, not just generation. Measure end-to-end delivery time, not only how fast code is written.
  收获：应为审查、测试和验证预留时间，而不仅是生成代码的时间。应衡量端到端的交付时间，而不只是代码编写速度。

### Silent instruction omission / 指令被静默遗漏
- Historical (9 months old, YouTube, Matt Maher, "AI Techniques Distilled From Thousands of Hours of Real Work"): The video snippet says that even with the best model and best prompts, AI will still silently drop 40% of what you asked for. This is a claim from a video snippet and was not verified in the video itself. Link: https://www.youtube.com/watch?v=kf6h6DOPjpI (older than 24 hours).
  历史（约9个月前，YouTube，Matt Maher，"AI Techniques Distilled From Thousands of Hours of Real Work"）：视频摘要称，即使使用最好的模型和最好的提示，AI仍会静默遗漏你要求的40%内容。这是视频摘要中的说法，未在视频正文中核实。链接：https://www.youtube.com/watch?v=kf6h6DOPjpI（早于24小时）。
- Related chapters in the same video: "Verify your plans," "Clear your context," and "Build your own tools." Link: https://www.youtube.com/watch?v=kf6h6DOPjpI&t=567 ; https://www.youtube.com/watch?v=kf6h6DOPjpI&t=837 ; https://www.youtube.com/watch?v=kf6h6DOPjpI&t=1410 (older than 24 hours).
  同一视频中的相关章节："Verify your plans"（验证计划）、"Clear your context"（清空上下文）和"Build your own tools"（构建自己的工具）。链接同上（早于24小时）。
- Takeaway: do not assume a long instruction list was fully followed. Check each requirement against the output with a checklist or a test.
  收获：不要假设长指令清单被完整执行。应用清单或测试逐项对照输出中的每条要求。

## 4) Popular Programming Technologies / 热议编程技术

### Python and GitHub language rankings / Python与GitHub语言排名
- Historical (about 1 year old, Reddit r/learnprogramming, "What makes Python popular?"): Thread on why Python is popular. Link: https://www.reddit.com/r/learnprogramming/comments/1hr28re/what_makes_python_popular/ (older than 24 hours; body not opened).
  历史（约1年前，Reddit r/learnprogramming，"What makes Python popular?"）：关于Python为何受欢迎的讨论。链接：https://www.reddit.com/r/learnprogramming/comments/1hr28re/what_makes_python_popular/（早于24小时；正文未打开）。
- Historical (Nov 1, 2024, InfoWorld): Python is the most popular language on GitHub and beat JavaScript, with AI as a driver. Link: https://www.infoworld.com/article/3596388/python-is-the-most-popular-language-on-github.html (older than 24 hours).
  历史（2024年11月1日，InfoWorld）：Python是GitHub上最受欢迎的语言，并超过了JavaScript，AI是其推动力。链接：https://www.infoworld.com/article/3596388/python-is-the-most-popular-language-on-github.html（早于24小时）。
- Historical (Oct 30, 2025, Slashdot): TypeScript overtook Python and JavaScript in August 2025 to become the most used language on GitHub. This conflicts with the Python-first claims above, so the current GitHub ranking is unresolved. Link: https://developers.slashdot.org/story/25/10/30/1753252/typescript-overtakes-python-and-javascript-to-claim-top-spot-on-github (older than 24 hours).
  历史（2025年10月30日，Slashdot）：TypeScript于2025年8月超过Python和JavaScript，成为GitHub上使用最多的语言。这与上文关于Python领先的说法相矛盾，因此当前GitHub排名尚无定论。链接：https://developers.slashdot.org/story/25/10/30/1753252/typescript-overtakes-python-and-javascript-to-claim-top-spot-on-github（早于24小时）。
- Takeaway: rankings depend on the year and the source, and Python's rise is linked to ML and data work. Check the current Octoverse report before quoting a leader.
  收获：排名取决于年份和来源，Python的上升与ML及数据工作相关。引用领先者之前应查看当前的Octoverse报告。

### Specialized statistics environments versus general-purpose languages / 专业统计环境与通用语言
- Historical (Apr 14, 2026, ITU Online IT Training): The article breaks down Python and R across learning curve, data handling, statistics, visualization, machine learning, and deployment. Link: https://www.ituonline.com/blogs/comparing-python-and-r-for-data-science-in-ai-driven-business-applications/ (older than 24 hours).
  历史（2026年4月14日，ITU Online IT Training）：文章从学习曲线、数据处理、统计、可视化、机器学习和部署等方面比较Python与R。链接：https://www.ituonline.com/blogs/comparing-python-and-r-for-data-science-in-ai-driven-business-applications/（早于24小时）。
- Historical (Aug 30, 2025, GMSTAT): R is described as a functional language, and OOP in R structures code around objects. Link: https://rfaqs.com/advanced-r/class-in-r/object-oriented-programming-in-r/ (older than 24 hours).
  历史（2025年8月30日，GMSTAT）：R被描述为函数式语言，R中的面向对象编程围绕对象组织代码。链接：https://rfaqs.com/advanced-r/class-in-r/object-oriented-programming-in-r/（早于24小时）。
- Historical (Oct 21, 2024, Chatomics short): Python is a general language with strengths in deep learning, while R has more pre-built bioinformatics packages. Link: https://www.youtube.com/shorts/B6A-NpCpgNc (older than 24 hours).
  历史（2024年10月21日，Chatomics短视频）：Python是通用语言，在深度学习方面有优势，而R拥有更多现成的生物信息学包。链接：https://www.youtube.com/shorts/B6A-NpCpgNc（早于24小时）。
- Takeaway: R remains strong in statistics and bioinformatics, and Python is strong in production and ML. These snippets do not show a migration trend, so do not present one as fact.
  收获：R在统计与生物信息学方面依然强势，Python在生产与机器学习方面强势。这些摘要并未显示迁移趋势，因此不应将其作为事实陈述。

## Sources / 来源

- https://www.youtube.com/shorts/SINapsQM23A
- https://www.investing.com/news/stock-market-news/united-airlines-moves-to-block-ai-agents-from-its-platform-over-security-concerns-5019752
- https://srnnews.com/united-airlines-moves-to-block-ai-agents-from-its-platform-over-security-concerns/
- https://thriftytraveler.com/news/airlines/united-blocks-ai-agents-booking-flights/
- https://www.linkedin.com/posts/jowalter_united-airlines-just-banned-personal-agents-activity-7526658915359686656-yptm
- https://2wtech.com/microsoft-365-outage-disrupts-outlook-teams-and-core-cloud-services/
- https://gbhackers.com/microsoft-copilot-outage-disrupts-uk-and-europe/
- https://ca.finance.yahoo.com/news/microsoft-copilot-down-ai-assistant-112709054.html
- https://github.com/grok-bot-app/grok-bot
- https://x.ai/news/introducing-grok-bot
- https://www.google.com/goto?url=CAESdQHEIkXXnO7HFhgBsZDMPXFMS6aBe3Ht01svkl7KSre2JzYgVDQVaGQSemVCs4KfqorpZL2XL3FCoOzUGwY6IKhEHT_ftvTw6Lx-8ceLJZlQEnQHZj__j6JrA_AW3y5qF8_8P6nuFQYNCIry7WwB2nOeznlajw
- https://www.ai.joaoqueiros.com/blog/grok-bot-always-on-ai-agent-teams-routines-skills-security
- https://github.com/wolfqing/OpenGrokBot
- https://www.youtube.com/shorts/8HPAThYIZxo
- https://www.reddit.com/r/ClaudeAI/comments/1u82o60/ai_coding_is_no_longer_the_bottleneck_review/
- https://daily.dev/posts/the-bottleneck-was-never-the-code-7dackdzws
- https://www.reddit.com/r/cscareers/comments/1wv1k77/jevons_paradox/
- https://www.instagram.com/reel/DfWZUYPSp9P/
- https://www.reddit.com/r/softwarecrafters/comments/1sdgjv7/the_productivity_paradox_of_ai_coding_assistants/
- https://www.giga.engineer/blog/ai-productivity-paradox-2026
- https://www.youtube.com/watch?v=kf6h6DOPjpI
- https://www.reddit.com/r/learnprogramming/comments/1hr28re/what_makes_python_popular/
- https://www.infoworld.com/article/3596388/python-is-the-most-popular-language-on-github.html
- https://developers.slashdot.org/story/25/10/30/1753252/typescript-overtakes-python-and-javascript-to-claim-top-spot-on-github
- https://www.ituonline.com/blogs/comparing-python-and-r-for-data-science-in-ai-driven-business-applications/
- https://rfaqs.com/advanced-r/class-in-r/object-oriented-programming-in-r/
- https://www.youtube.com/shorts/B6A-NpCpgNc
