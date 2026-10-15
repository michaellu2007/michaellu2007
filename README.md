<!--
  个人主页 README · michaellu2007
  配套 .github/workflows/ 已就位，部署步骤见 SETUP.md
-->

<p align="center">
  <img src="assets/banner.jpg" alt="banner" width="100%" />
</p>

# Hi there 👋

我是 **mini_doro**（[michaellu2007](https://github.com/michaellu2007)）

---

### 🚀 Projects

- **💘 [crush-monitor-agent](https://github.com/michaellu2007/crush-monitor-agent)** - 基于微信聊天记录的关系感知与陪伴决策 Agent
  - 双系统架构：本地小模型（Ollama + JevK5）逐条做情绪 / 意图判断——免费；云端模型（GLM）负责顾问对话与回复生成，评估与生成分开路由
  - 微信式三栏界面：会话列表 / 聊天记录 / 顾问对话；chatlog 解密导入，多会话管理，好感度与关系阶段概览，可勾选记录当上下文问"下一步怎么聊"
  - 深度改造自 [FerryCorleone/crush-monitor](https://github.com/FerryCorleone/crush-monitor)（MIT），感谢原项目

- **📚 [fdu-note-summarized](https://github.com/michaellu2007/fdu-note-summarized)** - 复旦大学课程笔记：AI 辅助整理老师讲义与学长笔记 + 人工校对，离线 KaTeX 渲染，双击即开
  - 覆盖四门课：《数值算法与案例分析Ⅰ》（邵美悦老师荣誉课程）、《计算理论》、《数据结构》、《LLM与NLP》
  - 每篇笔记标注来源（板书 / 讲义 / 教材补充），公式全部走离线 KaTeX，不依赖网络

- **🏃 [campus-fit-tester](https://github.com/michaellu2007/campus-fit-tester)** - 自建校园体测系统的接口测试客户端（Node.js）
  - 走微信 PC 版小程序调试通道（WMPF + CDP），完整复现「登录 → 查询体测计划 → 开记录 → 心跳 → 提交」全流程
  - 用来检验自建服务端的防线：请求签名（sn / X-Sn-Verify / HMAC）、心跳节奏、距离合理性、围栏判定
  - 仅限自己部署或获得授权的系统使用（详见仓库内免责声明）

- **📈 [my-quant-lab](https://github.com/michaellu2007/my-quant-lab)** - 免费简陋的量化实验平台（Python）
  - qbot 回测 / 选股面板 + 均线交叉等策略脚本，数据源 AKShare / Tushare，零成本运行
  - 每日收盘自动跑批：策略信号生成 + 结果落盘，bat 一键启动

### 🏰 Interests

- **米奇妙妙屋 & 上海迪士尼**

### 🔧 Tech & Tools

<img src="assets/typescript.svg" alt="TypeScript"> <img src="assets/nodejs.svg" alt="Node.js"> <img src="assets/javascript.svg" alt="JavaScript"> <img src="assets/html5.svg" alt="HTML5"> <img src="assets/python.svg" alt="Python" height="28"> <img src="assets/ollama.svg" alt="Ollama"> <img src="assets/glm.svg" alt="GLM">

### 📫 Connect

[![GitHub](assets/github.svg)](https://github.com/michaellu2007)
[![Email](assets/email.svg)](mailto:michaellu2007+github@163.com)

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
