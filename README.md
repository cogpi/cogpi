# Kenbound

[English](#english) | [中文](#中文)

## English

Kenbound checks that your AI assistant only shows each person what they are allowed to see.

When documents are loaded into a knowledge base or an AI agent, the permissions from the source system are often lost. Kenbound tests this from the outside: it asks questions as different test users, places synthetic decoy documents with unique markers, and reports who can see what they should not, with reproducible evidence.

> Status: early development. The first open-source release of the command-line client is planned for Q4 2026.

### Planned features

- A leak matrix by identity, document and entry point
- Synthetic decoy documents only, no real company data needed
- Runs inside your own network; your data stays with you
- Revocation checks: does access really end when someone leaves or changes team?
- Local reports in HTML, Markdown and JSON

### Contact

- Website: https://kenbound.com
- Support: support@kenbound.com

## 中文

Kenbound 帮企业检查并管住公司的 AI 助手，只让每个人看到自己该看的资料。

文档接入知识库或智能体之后，源系统里的权限常常没有跟过去。Kenbound 从外部检测这个问题：用不同身份的测试账号提问，在知识库里放入带唯一标记的合成诱饵文档，找出“谁看到了不该看的内容”，并给出可以复现的证据。

> 当前状态：早期开发中。命令行客户端的首个开源版本计划于 2026 年第四季度发布。

### 计划提供的能力

- 按“身份 × 文档 × 入口”输出越权矩阵
- 只用合成的诱饵文档，不需要真实的公司数据
- 在企业自己的网络里运行，数据不出企业
- 撤权检测：员工离职或调岗后，权限是否真的收回
- 本地报告：HTML、Markdown 和 JSON

### 联系方式

- 官网：https://kenbound.com
- 支持：support@kenbound.com

## License / 许可证

Apache License 2.0
