# OpenChain CRA Compliance Requirements & Checklist

The OpenChain CRA Compliance Requirements & Checklist is a community-maintained, OpenChain-aligned self-certification and readiness resource for organizations preparing for EU Cyber Resilience Act obligations.

It is mapped to Regulation (EU) 2024/2847 and aligned with ISO/IEC 18974, ISO/IEC 5230, and relevant SBOM guidance including BSI TR-03183.

## 简体中文版 / Simplified Chinese

**Version 1.0 now has an unofficial Simplified Chinese translation**, covering all 193 checklist items, the implementation roadmap, annexes, references, and the three supporting registers.

**现已提供 1.0 版本的非官方简体中文译本**，包括完整主清单及三份配套文件，保留英文原文，并另附术语对照、版本来源及译者核对提示。

- [中文导读与翻译说明 / Chinese guide and translation notes](1.0/zh-CN/README.md)
- [CRA 合规要求与检查清单 1.0 / Full checklist](1.0/zh-CN/CRA_Checklist_Requirement_v1.0.md)
- [外部引用与采用情况 / External references and adoption](1.0/zh-CN/ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.md)
- [贡献者与审阅者 / Contributors and reviewers](1.0/zh-CN/CONTRIBUTORS.md)
- [修订历史 / Revision history](1.0/zh-CN/REVISION_HISTORY.md)

Translation date: **2026-09-13**. Source: version 1.0 at commit `cd497f7a5a8daca97e50d049bfd9d4a6c60376e9`. The translation is a reference draft for review, has not been endorsed by OpenChain or signed off by qualified legal counsel, and does not constitute legal advice or certification. Check the English source for translation ambiguities and the applicable official EU legal texts for legal obligations. It does not automatically track future `latest` updates. The translation is provided under the repository's CC-BY-4.0 license.

译文为供审阅的参考译稿，未经 OpenChain 官方认可或合格律师签署确认；不构成法律意见或认证，也不自动跟随 `latest` 更新。翻译歧义应核对英文原文，法律义务以适用的欧盟官方法律文本为准。译文沿用仓库 CC-BY-4.0 许可。

## Overview

The CRA (Regulation (EU) 2024/2847) establishes mandatory cybersecurity requirements for products with digital elements placed on the EU market. Organizations that develop, maintain, or distribute software with digital elements must ensure their products meet essential cybersecurity requirements throughout the product lifecycle.

The checklist covers program governance, product assessment, SBOM quality, vulnerability handling, regulatory reporting, OSS stewardship, technical-file evidence, security updates, and supply-chain obligations.

## Repository Contents

| File | Description |
|---|---|
| `CRA_Checklist_Requirement_latest.md` | Release-target checklist on this branch, currently matching the version 1.0 |
| `CONTRIBUTING.md` | Review and contribution workflow |
| `CONTRIBUTORS.md` | Contributor and reviewer register |
| `REVISION_HISTORY.md` | Review cycle and major change register |
| `ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.md` | External references, use, tooling, and adoption register |
| `1.0` | Archive directory for checklist version 1.0 |
| [`1.0/zh-CN`](1.0/zh-CN/README.md) | Unofficial Simplified Chinese translations of version 1.0 and its supporting registers, with translation notes |
| `Pre-Release-Versions` | Archive directory for pre-release checklist versions |

## Checklist Structure

Version 1.0 covers 9 sections and 193 checklist items:

| Section | Topic | Items |
|---|---|---|
| 2 | Program Architecture and Governance | 46 |
| 3 | Component Management, SBOM Quality, Provenance, and Secure Development | 57 |
| 4 | Vulnerability Handling, VEX, and Art. 14 Reporting | 35 |
| 5 | OSS Stewardship | 15 |
| 6 | Security Updates and Support Period | 7 |
| 7 | Technical File, DoC, and Supply Chain Sharing | 20 |
| 8 | Cross-Framework Integration (NIS2, AI Act, DORA, Data Act) | 8 |
| 9 | Procurement and Buyer-Side Obligations | 5 |

## Key Features

- Art. 14 three-stage reporting cascade (24h Early Warning / 72h Notification / 14-day Final Report) with RACI and tabletop exercise requirements
- SBOM quality controls including dependency depth, file/snippet reference handling, provenance, signing, and HBOM for hardware products
- Secure development, secure build infrastructure, secrets management, and release-gate controls
- Third-party software supply chain qualification for COTS, SDKs, ODM/OEM components, outsourced development, and freeware
- Self-maintained open source software controls for legacy, forked, or internally maintained components
- EU Declaration of Conformity workflow with Annex V template structure
- Authorized Representative operational procedures for non-EU manufacturers
- Supporting registers for external references, contributors, and revision history

## Status

Current main release : **Version 1.0**

## Contribution Workflow

Feedback and proposed changes are tracked through GitHub issues and pull requests. Community comments may also be submitted through the public Google Doc during review windows.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full review and contribution workflow.

## License

CC-BY-4.0 - See [LICENSE](LICENSE) for details.

## Contributors and Reviewers

Contributor and reviewer details are maintained in [CONTRIBUTORS.md](CONTRIBUTORS.md).
