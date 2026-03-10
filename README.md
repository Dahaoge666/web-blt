# 博利通精密工艺官网（轻量版）

基于 **Vite + 原生 HTML/CSS** 的企业展示站，聚焦机械加工表面处理场景。

## 页面结构

- `/index.html`：首页（品牌介绍、核心优势、业务入口）
- `/services.html`：主营业务详情（电泳、喷漆/喷粉、配套服务）
- `/process.html`：标准化工艺流程与质量控制
- `/contact.html`：合作咨询与需求对接指引

## 页面跳转逻辑

- 首页导航可跳转至：主营业务、工艺流程、合作咨询
- 首页按钮：
  - `查看业务详情` → `/services.html`
  - `获取报价方案` → `/contact.html`
- 业务页按钮：
  - `提交需求` → `/contact.html`
- 流程页按钮：
  - `咨询流程匹配方案` → `/contact.html`
- 联系页按钮：
  - `返回查看业务能力` → `/services.html`

## 页面截图（初始化/更新时维护）

> 说明：仅在页面初始化或页面更新时，补充对应页面最新截图，无需每次全量更新。

### 首页（index.html）

![首页截图](browser:/tmp/codex_browser_invocations/0a25f059883e27e5/artifacts/artifacts/index.png)

### 主营业务页（services.html）

![主营业务页截图](browser:/tmp/codex_browser_invocations/3d39d04664a39705/artifacts/artifacts/services.png)

### 工艺流程页（process.html）

![工艺流程页截图](browser:/tmp/codex_browser_invocations/3d39d04664a39705/artifacts/artifacts/process.png)

### 合作咨询页（contact.html）

![合作咨询页截图](browser:/tmp/codex_browser_invocations/3d39d04664a39705/artifacts/artifacts/contact.png)

## 快速启动

```bash
npm install
npm run dev
```

默认地址：`http://localhost:5173`

## 常用命令

- `npm run dev`：启动开发环境
- `npm run build`：构建生产版本
- `npm run preview`：预览构建结果
