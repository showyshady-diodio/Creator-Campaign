# Campaign Workspace Demo

这是一个不依赖后端或模型 API 的高保真静态网页 Demo，用来展示海外营销服务商从 Brief、销售方案、交付 Gate 到执行复盘的项目工作台。

## 打开方式

直接双击 `index.html`，即可在浏览器中查看。

## 当前可演示交互

- 从项目总览进入 `Healthy Motion Malaysia` 项目；
- 查看项目概览、销售方案、交付 Gate、执行看板；
- 打开「新建 Campaign」输入 Brief，并模拟创建成功；
- 在手机宽度下查看响应式布局。

## 后续可以接入的能力

1. 用 Dify API 替换「新建 Campaign」后的模拟提示，发送 Brief 到总控工作流；
2. 将 Dify 的需求洞察、销售方案、交付评估、执行输出分别写入对应 Tab；
3. 用 Supabase / Airtable / 飞书多维表格保存客户和项目状态；
4. 接入真实广告、KOL 与 CRM 数据前，先保持所有案例为脱敏模拟数据。
