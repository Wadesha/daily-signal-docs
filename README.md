GitHub Pages: `https://<你的 GitHub 用户名>.github.io/daily-signal-docs`

# The Daily Signal — 技术文档

基于 Treadstone Collective 的 [The Daily Signal](https://www.treadstonecollective.com/daily-signal) 项目，从情报分析方法论角度进行的技术文档重建。

## 内容

| 页面 | 说明 |
|---|---|
| [概览](index.html) | Pipeline 架构总览、核心框架介绍 |
| [数据流](data-flow.html) | 从采集到分发的六阶段完整数据流 |
| [评分逻辑](scoring.html) | 严重度、置信度、信源可靠性的评分标准 |
| [案例](case-study.html) | 霍尔木兹海峡军事活动的完整案例推演 |
| [输出](output.html) | Daily Signal 最终输出格式展示 |

## 技术架构

- 纯静态 HTML + CSS，无外部依赖
- 深色主题，响应式设计
- 可直接部署到 GitHub Pages 或任何静态托管服务

## 部署

1. 将此仓库 fork 到你的 GitHub 账号
2. 进入 Settings → Pages
3. 选择 `main` 分支，根目录 `/`
4. 访问 `https://<你的用户名>.github.io/daily-signal-docs/`

## 许可证

MIT