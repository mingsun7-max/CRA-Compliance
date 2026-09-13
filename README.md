# OpenChain CRA 合规要求与检查清单

**简体中文** | [English](README.en.md)

本仓库提供 OpenChain CRA 合规要求与检查清单及非官方中文译本，涵盖开源软件治理、软件物料清单（SBOM）、漏洞处理与供应链管理，帮助组织开展欧盟《网络韧性法案》（CRA）合规准备与证据管理。

**当前版本：1.0（2026 年 9 月 11 日）** · [阅读中文清单](1.0/zh-CN/CRA_Checklist_Requirement_v1.0.md) · [英文原文](1.0/CRA_Checklist_Requirement_v1.0.md)

## 内容与适用范围

本清单由 OpenChain 社区维护，映射至欧盟第 2024/2847 号条例，并与 ISO/IEC 18974、ISO/IEC 5230 及 BSI TR-03183 等相关指引衔接。CRA 适用性取决于产品范围、市场提供行为及组织角色，不能仅凭是否使用开源软件判断。

主清单包含引言及八个检查章节，共 **193 个检查项**，另附实施路线图、自我认证汇总、术语表、要求映射及参考资料。

| 章节 | 主题 | 检查项数 |
| :---- | :---- | ----: |
| 2 | 合规体系架构与治理 | 46 |
| 3 | 组件管理、SBOM、来源与安全开发 | 57 |
| 4 | 漏洞处理、VEX 与第 14 条报告 | 35 |
| 5 | 开源软件管理 | 15 |
| 6 | 安全更新与支持期 | 7 |
| 7 | 技术文档、符合性声明与供应链共享 | 20 |
| 8 | 跨框架衔接 | 8 |
| 9 | 采购与买方义务 | 5 |

## 主要内容

- 第 14 条三阶段报告、RACI 职责与桌面演练：24 小时早期预警、72 小时通知；漏洞最终报告通常在纠正或缓解措施可用后 14 日内提交，严重事件最终报告通常在 72 小时通知提交后一个月内提交。
- SBOM 依赖深度、文件／代码片段引用、来源证明与签名，以及硬件产品的 HBOM。
- 安全开发、构建基础设施、秘密信息管理及发布门禁。
- 商业现成软件（COTS）、SDK、ODM／OEM 组件、外包开发及免费软件的供应链资格审查。
- 遗留、派生及内部维护开源组件的管理控制。
- 欧盟符合性声明流程及附件 V 模板结构；按适用情形实施授权代表操作程序。
- NIS2、《人工智能法案》、DORA、《数据法案》及 eIDAS 等框架衔接，另附外部引用、贡献者与修订记录。

上述报告期限须结合触发条件、具体报告类型及法定例外适用，见[翻译核对提示](TRANSLATION_NOTES.md#source-review)。

## 双语文档

| 文档 | 简体中文 | English |
| :---- | :---- | :---- |
| 最新清单全文 | [latest](CRA_Checklist_Requirement_latest.md) | [latest](CRA_Checklist_Requirement_latest.en.md) |
| 1.0 版本清单 | [中文全文](1.0/zh-CN/CRA_Checklist_Requirement_v1.0.md) | [英文全文](1.0/CRA_Checklist_Requirement_v1.0.md) |
| 贡献指南 | [中文](CONTRIBUTING.md) | [English](CONTRIBUTING.en.md) |
| 贡献者与审阅者 | [中文](CONTRIBUTORS.md) | [English](CONTRIBUTORS.en.md) |
| 1.0 修订历史 | [中文](1.0/zh-CN/REVISION_HISTORY.md) | [English](1.0/REVISION_HISTORY.md) |
| 外部引用与采用情况 | [中文](ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.md) | [English](ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.en.md) |
| 翻译说明与核对提示 | [中文](TRANSLATION_NOTES.md) | [English](TRANSLATION_NOTES.en.md) |
| 许可证（仅保留原文） | [LICENSE](LICENSE) | [LICENSE](LICENSE) |
| 版本目录 | [1.0](1.0/README.md) | [1.0](1.0/README.en.md) |
| 历史归档 | [versions](versions/README.md) | [versions](versions/README.en.md) |

根目录默认使用中文，英文文档采用 `.en.md` 后缀。1.0 英文原文保留在 `1.0/`，完整中文译文位于 `1.0/zh-CN/`。根目录 `CRA_Checklist_Requirement_latest.md` 和 `CRA_Checklist_Requirement_latest.en.md` 分别展示当前最新版本的中文和英文全文，现与 1.0 对应版本同步；版本目录保留归档。`Pre-Release-Versions/` 已移除；仍保留的历史稿仅供追溯。

## 使用说明

中文译文保留原文编号、要求强度、适用条件及证据栏。原文中的法律概括、历史状态或待确认事项，已在[翻译说明](TRANSLATION_NOTES.md)中标示必要核对提示。

本清单及其译文是合规准备与证据管理工具。填写或签署清单不等于完成 CRA 符合性评定、出具欧盟符合性声明或合法加贴 CE 标志。中文译文未经 OpenChain 官方认可，不构成法律意见。翻译歧义应核对英文原文；法律义务以适用的欧盟官方法律文本为准。

CRA 第 14 条自 **2026 年 9 月 11 日**起适用，法规通常自 **2027 年 12 月 11 日**起适用；仍须结合具体条款、角色及过渡安排判断。[CRA 官方文本，第 69、71 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120)

## 贡献与许可

翻译问题及改进建议请通过本仓库的议题或拉取请求提出；原清单的实质修订遵循[贡献指南](CONTRIBUTING.md)所述上游流程。

本仓库采用 **CC-BY-4.0**。转载或改编时，请保留原作署名、来源、许可信息及修改说明。主要作者为 Devashri Datta，完整署名见[贡献者与审阅者](CONTRIBUTORS.md)。

[上游项目](https://github.com/OpenChain-Project/CRA-Compliance) · [OpenChain CRA 项目网站](https://cra-compliance.openchainproject.org)
