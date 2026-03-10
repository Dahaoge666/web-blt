# 2026-03-10 变更记录

## 变更概览

- 新增 `AGENTS.md`，作为 AI 上下文入口，补充项目背景、技术栈、目录结构、编程规范与特别说明。
- 更新 `README.md` 页面章节，新增页面跳转逻辑说明与截图占位。
- 按新规范落实：本次变更已在 `changelog/` 中记录。

## 页面跳转逻辑（当前）

- 首页 `index.html`
  - 顶部导航可跳转：`services.html`、`process.html`、`contact.html`
  - 主按钮“查看业务详情”跳转 `services.html`
  - 次按钮“获取报价方案”跳转 `contact.html`
- 业务页 `services.html`
  - “提交需求”跳转 `contact.html`
- 流程页 `process.html`
  - “咨询流程匹配方案”跳转 `contact.html`
- 联系页 `contact.html`
  - “返回查看业务能力”跳转 `services.html`
