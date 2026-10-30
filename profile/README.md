# qingluo

我们做两个产品：

- **[DrawOffer 职绘](https://www.drawoffer.com)**：AI 简历制作、按岗位 JD 改简历、AI 模拟面试与求职进度管理。导入 PDF / Word 简历，每处修改由你确认后再写入。
- **[LinkRag](https://linkrag.cn)**：面向企业的 RAG 系统，把复杂文档变成可以对话、可以溯源的知识。

We build **[DrawOffer](https://www.drawoffer.com)**, an AI resume builder with job-description tailoring, mock interviews and an application tracker, and **[LinkRag](https://linkrag.cn)**, an enterprise RAG system.

## 开源项目 · Open source

### DrawOffer 职绘

| 仓库 | 说明 |
|---|---|
| [drawoffer-skills](https://github.com/ql-link/drawoffer-skills) | 简历与求职 Agent Skills，可直接装进 Claude Code：简历诊断、STAR 改写、从资料写简历、简历翻译、面试准备 |
| [drawoffer-prompts](https://github.com/ql-link/drawoffer-prompts) | 求职提示词库，复制到任意 AI 助手即用：简历诊断、JD 匹配、面试准备与复盘 |
| [chinese-resume-templates](https://github.com/ql-link/chinese-resume-templates) | 57 套免费中文简历模板：校招、实习、社招，附预览图与示例数据 |
| [drawoffer-mcp](https://github.com/ql-link/drawoffer-mcp) | MCP Server：让 Claude、Cursor 等 AI 工具读取你在 DrawOffer 的简历、岗位和投递记录（即将上线） |

### LinkRag 与工具

| 仓库 | 说明 |
|---|---|
| [LinkRag](https://github.com/ql-link/LinkRag) | Python RAG 服务：文档解析、分片、向量化、索引与召回 |
| [LinkRag-Service](https://github.com/ql-link/LinkRag-Service) | LinkRag 的 Java 管理端 |
| [LinkRag-Web](https://github.com/ql-link/LinkRag-Web) | LinkRag 的 Web 前端 |
| [LinkRag-Eval](https://github.com/ql-link/LinkRag-Eval) | LinkRag 的检索评测项目 |
| [LinkParse](https://github.com/ql-link/LinkParse) | 纯 CPU 文档解析服务（PDF / DOC / DOCX / 图片） |
| [LinkCli](https://github.com/ql-link/LinkCli) | 企业内部 MCP 聚合网关 |
| [LinkSpec](https://github.com/ql-link/LinkSpec) | Spec 驱动 + 文档治理的 AI 开发工具包 |
