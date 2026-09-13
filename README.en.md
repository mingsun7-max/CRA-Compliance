# OpenChain CRA Compliance Requirements & Checklist

[简体中文](README.md) | **English**

This repository provides the OpenChain CRA Compliance Requirements & Checklist and unofficial Chinese translations. It covers open-source governance, software bills of materials (SBOMs), vulnerability handling, and supply-chain management to support readiness and evidence management for the EU Cyber Resilience Act (CRA).

**Current version: 1.0 (11 September 2026)** · [English checklist](1.0/CRA_Checklist_Requirement_v1.0.md) · [Chinese translation](1.0/zh-CN/CRA_Checklist_Requirement_v1.0.md)

## Contents and scope

The community-maintained checklist maps to Regulation (EU) 2024/2847 and aligns with ISO/IEC 18974, ISO/IEC 5230, and relevant guidance including BSI TR-03183. CRA applicability depends on product scope, market-supply activities, and organizational roles; it is not determined solely by the use of open-source software.

The checklist comprises an introduction and eight assessment sections with **193 checklist items**, followed by an implementation roadmap, self-certification summary, glossary, requirement mappings, and references.

| Section | Topic | Items |
| :---- | :---- | ----: |
| 2 | Program architecture and governance | 46 |
| 3 | Component management, SBOMs, provenance, and secure development | 57 |
| 4 | Vulnerability handling, VEX, and Article 14 reporting | 35 |
| 5 | OSS stewardship | 15 |
| 6 | Security updates and support period | 7 |
| 7 | Technical file, declaration of conformity, and supply-chain sharing | 20 |
| 8 | Cross-framework integration | 8 |
| 9 | Procurement and buyer-side obligations | 5 |

## Key features

- Article 14 reporting, RACI ownership, and tabletop exercises: 24-hour early warning and 72-hour notification; the vulnerability final report is generally due within 14 days after a corrective or mitigating measure becomes available, and the severe-incident final report within one month after the 72-hour notification is submitted.
- SBOM dependency depth, file/snippet references, provenance, signing, and HBOMs for hardware products.
- Secure development, build infrastructure, secrets management, and release gates.
- Supply-chain qualification for COTS software, SDKs, ODM/OEM components, outsourced development, and freeware.
- Controls for legacy, forked, and internally maintained open-source components.
- EU Declaration of Conformity workflow and Annex V template structure; authorised-representative operating procedures where applicable.
- Integration with NIS2, the AI Act, DORA, the Data Act, and eIDAS, with external-reference, contributor, and revision registers.

Apply reporting deadlines with the relevant triggers, report types, and statutory exceptions; see the [review notes](TRANSLATION_NOTES.en.md#source-review).

## Bilingual documents

| Document | 简体中文 | English |
| :---- | :---- | :---- |
| Current checklist entry | [latest](CRA_Checklist_Requirement_latest.md) | [latest](CRA_Checklist_Requirement_latest.en.md) |
| Version 1.0 checklist | [Chinese text](1.0/zh-CN/CRA_Checklist_Requirement_v1.0.md) | [English text](1.0/CRA_Checklist_Requirement_v1.0.md) |
| Contribution guide | [中文](CONTRIBUTING.md) | [English](CONTRIBUTING.en.md) |
| Contributors and reviewers | [中文](CONTRIBUTORS.md) | [English](CONTRIBUTORS.en.md) |
| Revision history | [中文](REVISION_HISTORY.md) | [English](REVISION_HISTORY.en.md) |
| External references and adoption | [中文](ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.md) | [English](ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.en.md) |
| Translation and review notes | [中文](TRANSLATION_NOTES.md) | [English](TRANSLATION_NOTES.en.md) |
| License (original only) | [LICENSE](LICENSE) | [LICENSE](LICENSE) |
| Version directory | [1.0](1.0/README.md) | [1.0](1.0/README.en.md) |
| Historical archive | [versions](versions/README.md) | [versions](versions/README.en.md) |

Root documents default to Chinese; English documents use the `.en.md` suffix. Version 1.0 English originals remain in `1.0/`, with complete Chinese translations in `1.0/zh-CN/`. The root `CRA_Checklist_Requirement_latest.md` links to the version 1.0 Chinese text rather than maintaining a separate checklist copy. `Pre-Release-Versions/` has been removed; the remaining historical draft is retained for traceability only.

## Use

The Chinese translations preserve source numbering, requirement strength, applicability conditions, and evidence fields. Legal summaries, historical status statements, and unconfirmed source information are accompanied by relevant [translation and review notes](TRANSLATION_NOTES.en.md).

The checklist and translations are readiness and evidence-management tools. Completing or signing a checklist does not itself constitute a CRA conformity assessment, an EU Declaration of Conformity, or evidence of lawful CE marking. The Chinese translations are not endorsed by OpenChain and do not constitute legal advice. Consult the English source for translation ambiguities and the applicable official EU legal texts for legal obligations.

CRA Article 14 applies from **11 September 2026**; the Regulation generally applies from **11 December 2027**, subject to the relevant provisions, roles, and transitional arrangements. [Official CRA text, Articles 69 and 71](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120)

## Contributions and license

Submit translation issues and improvements through this repository's issues or pull requests. Substantive changes to the source checklist follow the upstream process described in the [contribution guide](CONTRIBUTING.en.md).

This repository uses **CC-BY-4.0**. Retain attribution, source and license information, and notices of changes when sharing or adapting the material. The lead author is Devashri Datta; see the full [contributor and reviewer register](CONTRIBUTORS.en.md).

[Upstream project](https://github.com/OpenChain-Project/CRA-Compliance) · [OpenChain CRA project website](https://cra-compliance.openchainproject.org)
