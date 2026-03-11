# OpenClaw Skills 中文说明文档

## 简介

**Awesome OpenClaw Skills** 是一个精选的 OpenClaw 技能集合，包含 **5,494 个社区开发的技能**，从 ClawHub 官方注册表（13,729 个技能）中筛选而来。这些技能可以扩展 OpenClaw 的能力，让它能够与外部服务交互、自动化工作流程并执行专业任务。

本仓库的技能已经过质量筛选，排除了垃圾、重复、低质量和恶意的技能。

## 目录

- [安装方法](#安装方法)
- [分类说明](#分类说明)
- [安全注意事项](#安全注意事项)
- [贡献指南](#贡献指南)

---

## 安装方法

### 方法一：使用 ClawHub CLI（推荐）

```bash
clawhub install <skill-slug>
```

示例：
```bash
clawhub install agent-memory
clawhub install github-automation
```

### 方法二：手动安装

将技能文件夹复制到以下位置之一：

| 位置 | 路径 | 优先级 |
|------|------|--------|
| 工作区 | `<project>/skills/` | 最高 |
| 全局 | `~/.openclaw/skills/` | 中等 |
| 内置 | 随 OpenClaw 安装 | 最低 |

### 方法三：直接粘贴链接

将技能的 GitHub 仓库链接直接粘贴到助手的聊天中，让助手自动设置。

---

## 分类说明

本仓库包含 **30 个主要类别**，总计 5,494 个技能。以下是每个类别的说明和代表性技能。

### 1. Coding Agents & IDEs（编码代理与集成开发环境）
**技能数量：1,223**

用于增强 AI 编码助手的能力，包括代码生成、项目管理、开发工具集成等。

**代表性技能：**
- **0g-compute** - 使用 0G 计算网络的低成本 TEE 验证 AI 模型
- **agent-access-control** - AI 代理的分层访问控制
- **agent-audit** - 审计 AI 代理的性能、成本和 ROI
- **active-maintenance** - OpenClaw 的自动化系统健康和内存代谢
- **agent-memory** - AI 代理的持久化内存系统

**使用场景：**
- 代码生成和重构
- 项目管理和任务追踪
- 开发环境配置
- 代码质量审计

---

### 2. Web & Frontend Development（Web 与前端开发）
**技能数量：938**

专注于 Web 开发、前端框架、UI/UX 设计等。

**代表性技能：**
- **frontend-design** - 创建高质量的前端界面
- **react-components** - React 组件库和最佳实践
- **web-artifacts-builder** - 构建复杂的 Web 工件
- **webapp-testing** - 使用 Playwright 测试 Web 应用

**使用场景：**
- 前端页面开发
- UI 组件创建
- 响应式设计
- Web 应用测试

---

### 3. Git & GitHub（版本控制）
**技能数量：170**

与 Git 和 GitHub 相关的自动化、仓库管理、代码审查等。

**代表性技能：**
- **agent-commons** - 咨询、提交、扩展和挑战推理链
- **agentdo** - 为其他 AI 代理发布任务或从 AgentDo 任务队列中领取工作
- **azure-devops** - 管理 Azure DevOps 项目、仓库和分支
- **auto-pr-merger** - 自动化 GitHub PR 合并工作流
- **conventional-commits** - 使用约定式提交格式化提交消息

**使用场景：**
- 自动化提交和推送
- PR 创建和管理
- 代码审查流程
- 分支管理

---

### 4. DevOps & Cloud（开发运维与云服务）
**技能数量：409**

云服务集成、CI/CD、容器化、基础设施管理等。

**代表性技能：**
- **deploy-agent** - 全栈应用的多步部署代理
- **docker-automation** - Docker 容器自动化管理
- **kubernetes-tools** - Kubernetes 集成工具
- **cloud-monitoring** - 云服务监控和告警

**使用场景：**
- 自动化部署
- 容器管理
- 云资源监控
- CI/CD 流程

---

### 5. Browser & Automation（浏览器与自动化）
**技能数量：335**

浏览器自动化、网页抓取、表单填写等。

**代表性技能：**
- **2captcha** - 使用 2Captcha 服务解决验证码
- **web-scraping** - 网页数据抓取
- **browser-automation** - 浏览器自动化操作
- **form-filling** - 自动填写表单

**使用场景：**
- 自动化测试
- 数据抓取
- 表单提交
- 验证码处理

---

### 6. Search & Research（搜索与研究）
**技能数量：350**

学术搜索、文献管理、研究工具等。

**代表性技能：**
- **academic-research** - 使用 OpenAlex API 搜索学术论文
- **arxiv-search-collector** - arXiv 论文检索工作流
- **paper-summary** - 学术论文总结
- **research-tools** - 研究工具集

**使用场景：**
- 学术文献搜索
- 论文摘要生成
- 引用管理
- 研究数据收集

---

### 7. AI & LLMs（人工智能与大语言模型）
**技能数量：197**

AI 模型集成、提示工程、模型路由等。

**代表性技能：**
- **4claw** - AI 代理专用的图像板
- **agent-memory** - AI 代理的持久化内存系统
- **agentic-calling** - 使 AI 代理能够拨打和接听电话
- **agent-orchestration** - 多代理系统协调和优化
- **ai-humanizer** - 人性化 AI 生成的文本

**使用场景：**
- AI 模型集成
- 提示优化
- 多模型协作
- AI 输出人性化

---

### 8. Productivity & Tasks（生产力与任务管理）
**技能数量：206**

任务管理、日程安排、生产力工具等。

**代表性技能：**
- **4to1-planner** - 使用 4To1 方法的 AI 规划教练
- **adhd-daily-planner** - 友好的 ADHD 日常规划器
- **asana** - 通过 REST API 集成 Asana
- **task-automation** - 任务自动化工具

**使用场景：**
- 日程管理
- 任务追踪
- 项目规划
- 时间管理

---

### 9. PDF & Documents（PDF 与文档处理）
**技能数量：111**

PDF 处理、文档转换、文档生成等。

**代表性技能：**
- **pdf** - PDF 文件读取、合并、拆分、旋转等操作
- **docx** - Word 文档创建和编辑
- **pptx** - PowerPoint 演示文稿创建
- **document-converter** - 文档格式转换

**使用场景：**
- PDF 处理
- 文档生成
- 格式转换
- 文档提取

---

### 10. CLI Utilities（命令行工具）
**技能数量：186**

命令行实用工具、脚本自动化等。

**代表性技能：**
- **bat-cat** - 带语法高亮的 cat 克隆
- **gh** - GitHub CLI 集成
- **terminal-automation** - 终端自动化工具
- **script-runner** - 脚本执行器

**使用场景：**
- 终端操作
- 脚本自动化
- 系统管理
- 文件处理

---

### 11. Image & Video Generation（图像与视频生成）
**技能数量：170**

AI 图像生成、视频制作、媒体编辑等。

**代表性技能：**
- **3d-model-generation** - 使用 AI 生成 3D 模型
- **ai-music-video** - 端到端生成 AI 音乐视频
- **image-generation** - AI 图像生成
- **video-editing** - 视频编辑工具

**使用场景：**
- AI 图像生成
- 视频制作
- 3D 建模
- 媒体编辑

---

### 12. Communication（通信）
**技能数量：149**

邮件、聊天、通知等通信工具集成。

**代表性技能：**
- **email-automation** - 邮件自动化
- **slack-integration** - Slack 集成
- **discord-bot** - Discord 机器人
- **notification-tools** - 通知工具

**使用场景：**
- 邮件管理
- 团队协作
- 消息通知
- 聊天机器人

---

### 13. Transportation（交通运输）
**技能数量：109**

地图、导航、交通信息等。

**代表性技能：**
- **maps-integration** - 地图服务集成
- **route-planning** - 路线规划
- **traffic-info** - 实时交通信息
- **location-services** - 位置服务

**使用场景：**
- 路线规划
- 交通查询
- 地理编码
- 位置追踪

---

### 14. Marketing & Sales（营销与销售）
**技能数量：104**

营销自动化、销售工具、广告管理等。

**代表性技能：**
- **adwhiz** - 管理 Google Ads 营销活动
- **content-repurpose-pro** - 内容重用和转换
- **seo-tools** - SEO 优化工具
- **email-marketing** - 邮件营销

**使用场景：**
- 广告管理
- SEO 优化
- 内容营销
- 销售自动化

---

### 15. Health & Fitness（健康与健身）
**技能数量：88**

健康追踪、健身计划、营养管理等。

**代表性技能：**
- **fitness-tracker** - 健身追踪
- **nutrition-planner** - 营养计划
- **health-monitoring** - 健康监测
- **workout-generator** - 锻炼计划生成

**使用场景：**
- 健康追踪
- 健身规划
- 营养管理
- 运动记录

---

### 16. Media & Streaming（媒体与流媒体）
**技能数量：85**

音视频流、媒体播放、内容分发等。

**代表性技能：**
- **streaming-tools** - 流媒体工具
- **media-player** - 媒体播放器
- **content-delivery** - 内容分发
- **audio-processing** - 音频处理

**使用场景：**
- 直播管理
- 媒体播放
- 音频处理
- 视频流

---

### 17. Notes & PKM（笔记与个人知识管理）
**技能数量：71**

笔记应用、知识库、文档管理等。

**代表性技能：**
- **2nd-brain** - 个人知识库
- **note-taking** - 笔记记录
- **knowledge-base** - 知识库管理
- **document-organizer** - 文档整理

**使用场景：**
- 笔记管理
- 知识整理
- 文档归档
- 信息检索

---

### 18. Calendar & Scheduling（日历与日程安排）
**技能数量：65**

日历管理、会议安排、时间规划等。

**代表性技能：**
- **calendar-sync** - 日历同步
- **meeting-scheduler** - 会议安排
- **time-blocking** - 时间块规划
- **reminder-system** - 提醒系统

**使用场景：**
- 日程管理
- 会议安排
- 时间规划
- 提醒设置

---

### 19. Shopping & E-commerce（购物与电子商务）
**技能数量：55**

电商集成、购物自动化、价格追踪等。

**代表性技能：**
- **price-tracker** - 价格追踪
- **product-search** - 商品搜索
- **order-management** - 订单管理
- **payment-processing** - 支付处理

**使用场景：**
- 价格监控
- 商品搜索
- 订单处理
- 支付集成

---

### 20. Security & Passwords（安全与密码管理）
**技能数量：53**

安全审计、密码管理、加密工具等。

**代表性技能：**
- **password-manager** - 密码管理器
- **security-audit** - 安全审计
- **encryption-tools** - 加密工具
- **vulnerability-scanner** - 漏洞扫描

**使用场景：**
- 密码管理
- 安全审计
- 数据加密
- 漏洞检测

---

### 21. Personal Development（个人发展）
**技能数量：51**

学习工具、技能培养、个人成长等。

**代表性技能：**
- **learning-tracker** - 学习追踪
- **skill-development** - 技能发展
- **habit-tracker** - 习惯追踪
- **goal-setting** - 目标设定

**使用场景：**
- 学习管理
- 习惯养成
- 目标追踪
- 技能提升

---

### 22. Speech & Transcription（语音与转录）
**技能数量：45**

语音识别、文本转语音、字幕生成等。

**代表性技能：**
- **speech-to-text** - 语音转文本
- **text-to-speech** - 文本转语音
- **transcription** - 音频转录
- **subtitle-generator** - 字幕生成

**使用场景：**
- 语音识别
- 音频转录
- 语音合成
- 字幕制作

---

### 23. Apple Apps & Services（Apple 应用与服务）
**技能数量：44**

Apple 生态系统集成、iOS/macOS 工具等。

**代表性技能：**
- **apple-shortcuts** - Apple 快捷指令
- **icloud-sync** - iCloud 同步
- **ios-automation** - iOS 自动化
- **macos-tools** - macOS 工具

**使用场景：**
- Apple 设备集成
- iCloud 管理
- iOS 自动化
- macOS 工具

---

### 24. Smart Home & IoT（智能家居与物联网）
**技能数量：43**

智能家居控制、IoT 设备管理等。

**代表性技能：**
- **home-automation** - 家居自动化
- **iot-control** - IoT 设备控制
- **smart-devices** - 智能设备管理
- **sensor-monitoring** - 传感器监控

**使用场景：**
- 智能家居控制
- IoT 设备管理
- 传感器数据
- 自动化场景

---

### 25. Data & Analytics（数据与分析）
**技能数量：42**

数据分析、可视化、报表生成等。

**代表性技能：**
- **data-analysis** - 数据分析
- **visualization** - 数据可视化
- **report-generator** - 报表生成
- **analytics-tools** - 分析工具

**使用场景：**
- 数据分析
- 图表生成
- 报表制作
- 数据洞察

---

### 26. Clawdbot Tools（Clawdbot 工具）
**技能数量：37**

Clawdbot 专用工具和增强功能。

**代表性技能：**
- **clawdbot-backup** - Clawdbot 配置备份
- **clawdgigs** - AI 代理档案管理
- **clawver-onboarding** - Clawver 商店设置
- **agent-wellness** - AI 代理健康管理

**使用场景：**
- Clawdbot 配置
- 代理管理
- 工具增强
- 系统维护

---

### 27. Gaming（游戏）
**技能数量：36**

游戏集成、游戏自动化、电竞工具等。

**代表性技能：**
- **game-automation** - 游戏自动化
- **gaming-stats** - 游戏统计
- **esports-tools** - 电竞工具
- **game-integration** - 游戏集成

**使用场景：**
- 游戏自动化
- 数据统计
- 电竞分析
- 游戏集成

---

### 28. Self-Hosted & Automation（自托管与自动化）
**技能数量：32**

自托管服务、自动化工具、服务器管理等。

**代表性技能：**
- **self-hosting** - 自托管服务
- **automation-tools** - 自动化工具
- **server-management** - 服务器管理
- **backup-automation** - 备份自动化

**使用场景：**
- 自托管部署
- 服务器管理
- 自动化脚本
- 备份恢复

---

### 29. iOS & macOS Development（iOS 与 macOS 开发）
**技能数量：29**

iOS/macOS 应用开发工具和框架。

**代表性技能：**
- **swift-tools** - Swift 开发工具
- **ios-sdk** - iOS SDK 集成
- **macos-development** - macOS 开发
- **app-testing** - 应用测试

**使用场景：**
- iOS 应用开发
- macOS 应用开发
- Swift 编程
- 应用测试

---

### 30. Moltbook（Moltbook 相关）
**技能数量：46**

Moltbook 平台相关的技能。

**代表性技能：**
- **moltbook-integration** - Moltbook 集成
- **moltbook-tools** - Moltbook 工具
- **moltbook-automation** - Moltbook 自动化

**使用场景：**
- Moltbook 集成
- 平台工具
- 自动化操作

---

### 31. Agent-to-Agent Protocols（代理间协议）
**技能数量：17**

AI 代理之间的通信和协作协议。

**代表性技能：**
- **a0x-agents** - AI 代理的集体大脑和 Base
- **claw-to-claw** - 代表人类与其他 AI 代理协调
- **towns-protocol** - Towns Protocol 机器人构建
- **udau** - AI 代理的联合协议

**使用场景：**
- 代理间通信
- 多代理协作
- 协议实现
- 分布式系统

---

### 32. Finance（金融）
**技能数量：21**

金融数据、交易、投资分析等。

**代表性技能：**
- **financial-data** - 金融数据查询
- **trading-tools** - 交易工具
- **investment-analysis** - 投资分析
- **market-monitoring** - 市场监控

**使用场景：**
- 金融数据查询
- 投资分析
- 交易执行
- 市场监控

---

## 安全注意事项

### 重要提醒

本列表中的技能已经过**精选但未经全面审计**。它们可能在被添加后被原作者更新、修改或替换。

### 安全风险

在安装或使用任何技能之前，请注意以下风险：

- **提示注入**：恶意的提示可能改变 AI 行为
- **工具污染**：不安全的工具调用可能危害系统
- **隐藏恶意负载**：可能包含隐藏的恶意代码
- **不安全的数据处理**：可能泄露敏感信息

### 安全检查

OpenClaw 与 **VirusTotal** 合作提供安全扫描：

1. 访问技能在 ClawHub 上的页面
2. 查看 VirusTotal 报告
3. 确认技能未被标记为危险

### 推荐的安全工具

- [Snyk Skill Security Scanner](https://github.com/snyk/agent-scan) - 技能安全扫描器
- [Agent Trust Hub](https://ai.gendigital.com/agent-trust-hub) - 代理信任中心

### 最佳实践

1. **审查源代码**：安装前查看技能的源代码
2. **检查更新**：定期检查技能是否有可疑更新
3. **最小权限原则**：只授予技能必需的权限
4. **隔离测试**：在隔离环境中测试新技能
5. **监控行为**：监控技能的运行行为和资源使用

---

## 贡献指南

### 添加新技能

如果你想添加新技能到这个列表，请遵循以下步骤：

1. **先发布到官方仓库**：技能必须已发布在 `github.com/openclaw/skills` 仓库
2. **准备 PR**：在 PR 描述中包含：
   - ClawHub 链接（如 `https://clawhub.ai/author/skill-name`）
   - GitHub 链接（如 `https://github.com/openclaw/skills/tree/main/skills/author/skill-name`）
3. **遵循格式**：使用标准格式和简洁描述（不超过 10 个字）
4. **质量要求**：
   - 技能必须有真实的社区使用
   - 必须是成熟的、经实战验证的技能
   - 不接受刚创建不久的新技能

### PR 格式

提交 PR 时，标题格式应为：

```
Add skill: author/skill-name
```

### 更多信息

详见 [CONTRIBUTING.md](CONTRIBUTING.md) 文件。

---

## 统计信息

- **总技能数**：5,494
- **类别数**：30
- **数据源**：ClawHub（13,729 个技能）
- **筛选排除**：6,940 个低质量/恶意技能
- **最大类别**：Coding Agents & IDEs（1,223 个）
- **最小类别**：Agent-to-Agent Protocols（17 个）

---

## 相关链接

- [ClawHub 官方注册表](https://clawhub.ai)
- [OpenClaw 官方仓库](https://github.com/openclaw/skills)
- [问题反馈](https://github.com/VoltAgent/awesome-clawdbot-skills/issues)
- [VoltAgent Discord](https://s.voltagent.dev/discord)

---

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

---

**更新日期**：2026 年 3 月 11 日
**维护者**：VoltAgent
**联系方式**：necati@voltagent.dev
