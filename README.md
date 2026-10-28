<!--
  个人主页 README · michaellu2007
-->

<p align="center">
  <img src="assets/banner.jpg" alt="banner" width="100%" />
</p>

# Hi there 👋

我是 **mini_doro**（[michaellu2007](https://github.com/michaellu2007)），某781大学大学牲。这里是我的杂物间，会上传一些我感兴趣的小玩意。

---

### 🚀 Projects

- **💘 [crush-monitor-agent](https://github.com/michaellu2007/crush-monitor-agent)** 🚧 working on - 基于微信聊天记录的"聊天顾问" Agent
  - 本地小模型判断消息的情绪和意图，云端大模型负责给出聊天建议，界面模仿微信三栏布局
  - 可以勾选聊天记录当上下文，让 AI 陪你分析"下一步怎么聊"
  - 深度改造自 [FerryCorleone/crush-monitor](https://github.com/FerryCorleone/crush-monitor)（MIT），感谢原项目

- **⏰ [fudan-elearning-reminder](https://github.com/michaellu2007/fudan-elearning-reminder)** - 复旦 eLearning 作业自动提醒（Python）
  - 自动检测没提交 / 没完成的作业，按时发邮件催你，交了就自动闭嘴；线下布置的作业也能提醒
  - 纯本地脚本运行，无需服务器、无需大模型，登录过期自动重登

- **📚 [fdu-note-summarized](https://github.com/michaellu2007/fdu-note-summarized)** - 大学课程笔记：AI 辅助整理老师讲义与学长笔记 + 人工校对，离线公式渲染，双击即开
  - 覆盖《数值算法与案例分析Ⅰ》《计算理论》《数据结构》《概率论》《LLM与NLP》等课程
  - NLP / LLM 课程的仓库另见 [llm-26-fall](https://github.com/michaellu2007/llm-26-fall)

- **🐱 [Wechat-Emoticon-Parser](https://github.com/michaellu2007/Wechat-Emoticon-Parser)** - 微信表情包导出与聊天图片解密工具（Windows，Python）
  - 从微信 4.1 本地加密数据中解出表情包和聊天图片，按原名整理导出，一条命令跑完

- **🔓 [wechat-decrypt](https://github.com/michaellu2007/wechat-decrypt)** - 微信 4.0 数据库解密工具（Windows，Python，MIT）
  - 从运行中的微信进程提取密钥，解密本地聊天数据库，支持实时消息监听，可作为 MCP 工具接入 AI 客户端

- **🏃 [campus-fit-tester](https://github.com/michaellu2007/campus-fit-tester)** - 自建校园体测系统的接口测试客户端（Node.js）
  - 完整模拟"登录 → 查询体测计划 → 上传记录 → 提交"全流程，用来检验自建服务端的防护是否严密
  - 仅限自己部署或获得授权的系统使用（详见仓库内免责声明）

- **🔋 [dorm-power-sentinel](https://github.com/michaellu2007/fdu-dorm-power-sentinel)** - 寝室电量哨兵（Python，MIT）
  - 监控宿舍剩余电量，撑不过半天自动发邮件催充值，深夜快断电前自动关机保护电脑
  - 开机自启、静默后台运行，充值后自动停止提醒，几乎零人工干预

- **🔋 石头扫地机器人app电池健康度检测** 🚧 计划中 · 敬请期待

- **📈 [my-quant-lab](https://github.com/michaellu2007/my-quant-lab)** - 免费简陋的量化实验平台（Python）
  - 均线交叉等常见策略的回测与选股面板，每日收盘自动跑批并保存结果，零成本运行

- **📊 daily_stock_analysis** - LLM 驱动的多市场股票分析系统（Python）
  - 汇总多来源行情与实时新闻，生成每日决策看板并自动推送，支持定时任务零成本运行

- **📊 [ridehailing-stoploss-study](https://github.com/michaellu2007/ridehailing-stoploss-study)** - 网约车停运损失司法案例实证分析：分析了 17,259 份判决书（2019–2026.7，Python）
  - 核心发现：全额支持停运损失的判决只占 18.6%，法院普遍"打折"；实际判赔大约只有索赔金额的七成
  - [GitHub Pages 交互图表在线浏览](https://michaellu2007.github.io/ridehailing-stoploss-study/)；代码 MIT，原始判决书不入库、仅存汇总结果

- **🐶 [mocklocation](https://github.com/michaellu2007/mocklocation)** - BeagleInCampus：无需 root 的 Android 模拟定位学习项目（Kotlin）
  - 地图选点、描点画路线、按配速自动回放，支持高德 / 百度地图
  - ⬇️ [Releases](https://github.com/michaellu2007/mocklocation/releases) 下载 APK（Android 8.0+）
  - ⚠️ 仅供定位技术学习与娱乐演示，请勿用于签到打卡或作弊

- **🛒 [edge-key](https://github.com/michaellu2007/edge-key)** - EdgeKey：一键部署到 Cloudflare Workers 的开源卡密商城系统
  - 前端页面、后端接口一体，同一套代码直接跑在 Cloudflare 上，零服务器成本

- **📝 小教程 / 资源整理**
  - [chatgpt-plus-tutorial](https://github.com/michaellu2007/chatgpt-plus-tutorial) - ChatGPT Plus / Pro 国内自助充值教程（支付宝 / 微信，免账号密码）
  - [relayAPI](https://github.com/michaellu2007/relayAPI) - AI API 中转站推荐与评测

### 🧪 Experiments

- **🛡️ [injection-defense-vs-utility](https://github.com/michaellu2007/injection-defense-vs-utility)** 🚧 working on - AI 助手能否一边拒绝恶意指令、一边把正常任务做完？
  - 对比了几种防御手段，看哪种既能防住提示注入攻击，又最少误伤正常请求

- **⚖️ [small-classifier-vs-prompted-llm](https://github.com/michaellu2007/small-classifier-vs-prompted-llm)** 🚧 working on - 标注数据很少时，传统小分类器和大语言模型谁更划算？
  - 实验发现：每个类别只要 8 条标注，小分类器就能在准确率、速度、成本上全面胜过被提示词驱动的大模型

- **📏 [dpo-shortcuts](https://github.com/michaellu2007/dpo-shortcuts)** 🚧 working on - 偏好微调（DPO）到底在学"答案正确"还是"答案更长"？
  - 把"正确性"和"长度"两个因素拆开测试，发现模型容易学成"越长越好"的捷径：输出越写越长、正确率反而下降。复旦 NLP/LLM 课程 project

### 🔧 Patched Builds（自编译 / 优化版）

- **📱 [DanXi](https://github.com/michaellu2007/DanXi)** - DanXi（校园一站式 App）个人自编译版，fork 自 [DanXi-Dev/DanXi](https://github.com/DanXi-Dev/DanXi)，仅 Android
  - 修复部分安全芯片受损的手机"每次重启都掉登录"的问题；同时移除更新提示
  - ⬇️ 自编译 Release 下载：**[v1.5.3-selfbuild.1 APK](https://github.com/michaellu2007/DanXi/releases/download/v1.5.3-selfbuild.1/DanXi-1.5.3-selfbuild.1-android.apk)**（38.9 MB）· [Releases 页面](https://github.com/michaellu2007/DanXi/releases)
  - ⚠️ 仅适合重启反复掉登录的设备；从官方版切换需卸载重装（本地数据会清空），普通用户请使用官方版本

- **📍 [Location-Spoofer](https://github.com/michaellu2007/Location-Spoofer)** - Android 虚拟定位框架（需要 Root + LSPosed），上游源码的自维护副本，个人编译版仅 Android
  - 多地图引擎选点 / 路线模拟、模拟真实的 GPS 漂移、Wi-Fi 与基站环境伪装、修复微信运动步数暴涨的 bug
  - ⬇️ 个人编译 Release：[v2.6.13-fix](https://github.com/michaellu2007/Location-Spoofer/releases/tag/v2.6.13-fix) · **[arm64-v8a APK](https://github.com/michaellu2007/Location-Spoofer/releases/download/v2.6.13-fix/LocationSpoofer_v2.6.13-fixed-arm64-v8a.apk)**（65.8 MB，64 位新机型）· **[armeabi-v7a APK](https://github.com/michaellu2007/Location-Spoofer/releases/download/v2.6.13-fix/LocationSpoofer_v2.6.13-fixed-armeabi-v7a.apk)**（54.0 MB，32 位旧机型）
  - ⚠️ 个人编译版签名与官方不同，安装前需卸载旧版（数据清空）；涉及 Root 与系统 Hook，仅限自有设备或已授权测试环境

- **🚴 Mentech 骑行 App 自编译版** 🚧 计划中 · 敬请期待

### 🏰 Interests

- **cyberpunk2077**
- **🚴 cycling**
- **aiming**
- **fps**

### 🔧 Tech & Tools

<img src="assets/typescript.svg" alt="TypeScript"> <img src="assets/nodejs.svg" alt="Node.js"> <img src="assets/javascript.svg" alt="JavaScript"> <img src="assets/html5.svg" alt="HTML5"> <img src="assets/python-badge.svg" alt="Python"> <img src="assets/ollama.svg" alt="Ollama"> <img src="assets/glm.svg" alt="GLM">

### 📫 Connect

[![GitHub](assets/github.svg)](https://github.com/michaellu2007)
[![Email](assets/email.svg)](mailto:michaellu2007+github@163.com)
[![Zotero](assets/zotero.svg)](https://www.zotero.org/jingyao-lu2007)

---

## 📊 GitHub Stats

![Stats](./profile/stats.svg)
![Top Langs](./profile/top-langs.svg)

## 📈 Contribution Graph

<img alt="3d profile" src="https://raw.githubusercontent.com/michaellu2007/michaellu2007/main/profile-3d-contrib/profile-night-view.svg" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/michaellu2007/michaellu2007/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/michaellu2007/michaellu2007/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/michaellu2007/michaellu2007/output/github-contribution-grid-snake.svg" />
</picture>
