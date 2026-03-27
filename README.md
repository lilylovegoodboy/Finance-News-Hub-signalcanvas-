# SignalCanvas

<p align="center">
  <img src="./screenshots/logo.png" alt="SignalCanvas" width="220" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ui-signalcanvas-4c8bf5" />
  <img src="https://img.shields.io/badge/license-MIT-green" />
  <img src="https://img.shields.io/badge/status-active-success" />
  <img src="https://img.shields.io/badge/theme-dark-black" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/templates-6-blue" />
  <img src="https://img.shields.io/badge/pages-simulator%20%7C%20thesis%20engine%20%7C%20retail%20heat-6c63ff" />
  <img src="https://img.shields.io/badge/manual-included-orange" />
  <img src="https://img.shields.io/badge/open%20source-ui%20shell-brightgreen" />
  <img src="https://img.shields.io/github/stars/lilylovegoodboy/Finance-News-Hub-signalcanvas-" />
</p>

# Finance News Hub SignalCanvas UI ✨📊🧠

一个面向事件驱动投研场景的前端展示与产品壳开源项目 🚀
完整版将会在3月31日隆重登录！

这个仓库主要开放：

- 前端页面 🖥️
- 通用 UI 🎨
- 页面布局与交互 🧩
- 用户使用手册相关页面 📘
- 基础产品结构 🏗️

它展示了一个围绕以下模块组织起来的工作台：

- 快讯首页 📰
<img width="1262" height="616" alt="image" src="https://github.com/user-attachments/assets/8d9931c8-85e0-49e3-9865-b6891ba0e329" />
- 推演引擎 🔍
<img width="1256" height="608" alt="image" src="https://github.com/user-attachments/assets/83b159c8-5e62-4775-ab27-41bb452d4fa6" />
- 模拟人类投资 🤖
<img width="1262" height="610" alt="image" src="https://github.com/user-attachments/assets/89306a6c-9c9a-45fc-9907-ee16e52973b9" />
- 散户热度 🔥
  <img width="1253" height="608" alt="image" src="https://github.com/user-attachments/assets/d128e461-53f3-431c-9954-73a42b70b635" />
- 用户手册 📚
---

## 项目定位 🎯

这不是完整的生产版交易系统，也不是策略全开源仓库。

当前开源内容聚焦在：

- 产品页面设计
- 信息架构
- UI 组件与交互
- 使用手册与用户教育层
- 展示层的数据组织方式

未包含内容：

- 核心策略逻辑
- 关键打分与权重
- 主线推演核心规则
- 模拟人类投资执行引擎细节
- 生产环境密钥与私有数据源

---

## 当前包含的模块 🧱

- `快讯首页` 📰
  - 首页入口、导航、卡片式信息组织
- `推演引擎` 🧠
  - 推演结论、影响地图、因果链、风险判断的展示方式
- `模拟人类投资` 🤖
  - 执行路径、候选池、收益展示、模拟交易成绩区
- `散户热度` 🔥
  - 股吧热度、板块总热度、时间轴、散户指数等展示层结构
- `用户手册` 📘
  - 用户如何理解系统、如何使用页面、如何阅读模块

---

## 用户手册相关 📖

这个开源仓库特别保留了“用户手册”相关页面和结构，方便参考 ✍️：

- 如何为复杂系统写用户说明
- 如何把产品能力解释给普通用户
- 如何组织：
  - 首页怎么读
  - 推演引擎怎么看
  - 模拟投资怎么看
  - 散户热度怎么看

如果你也在做高信息密度产品，这部分会比较有参考价值 💡

---

## 项目结构 🗂️

```text
app/
  templates/
    base.html
    index.html
    thesis_engine.html
    simulator.html
    retail_heat.html
    user_manual.html
  static/
    style.css
mock/
screenshots/
```

---

## 设计原则 🧭

- 复杂信息先分层，再展示 🪜
- 用户先看结论，再看证据 👀
- AI 解释应嵌入模块，而不是只做独立聊天框 🤝
- 页面可以高信息密度，但不能高理解门槛 🧩
- 产品壳开放，策略芯保留 🔒

---

## 开源边界 🔐

本仓库开放的是“产品展示层”，不是“策略核心” ⚙️

适合查看和参考的部分：

- 页面模板 🧾
- 通用样式 🎨
- 导航与卡片系统 🧱
- 响应式布局 📱
- 用户手册与说明文案 📚

暂不开放的部分：

- 核心策略实现 🧠
- 候选排序与打分引擎 📈
- 主线竞争与执行逻辑 ⚔️
- 私有 prompt / 参数 / 权重 🗝️
- 生产数据链路与密钥 🔒

---

## 适合谁看 👥

这个仓库适合：

- 想做金融产品前端的人
- 想研究信息密度页面设计的人
- 想搭建事件驱动投研工作台的人
- 想参考“用户手册如何写”的人
- 对 AI + 投研产品交互感兴趣的人
部分开源，完全免费使用！😊
---

## 免责声明 ⚠️

本仓库仅用于产品设计、学习交流与界面展示参考 ✨

不构成任何投资建议。  
市场有风险，决策需谨慎 📉📈
