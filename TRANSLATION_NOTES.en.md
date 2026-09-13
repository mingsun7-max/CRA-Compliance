# Translation and Review Notes

[简体中文](TRANSLATION_NOTES.md) | **English** | [Home](README.en.md)

## Version, source, and attribution

- Original work: *OpenChain CRA Compliance Requirements & Checklist* and associated registers, OpenChain CRA project. Lead author: Devashri Datta; see the [original contributor register](CONTRIBUTORS.en.md).
- Upstream: [OpenChain-Project/CRA-Compliance](https://github.com/OpenChain-Project/CRA-Compliance); [project website](https://cra-compliance.openchainproject.org).
- Scope: root contribution guide and two registers; version 1.0 checklist and supporting files; the PA_5.1 draft retained in `versions/`. Root navigation and full-text latest-version files are maintained bilingually. `LICENSE` is retained in its original form without a Chinese counterpart; `Pre-Release-Versions/` has been deleted.
- Fixed source commit: `cd497f7a5a8daca97e50d049bfd9d4a6c60376e9`. The English checklist identifies version 1.0 and the release date 2026-09-11.
- Translation date: 2026-09-13. Prepared with Codex assistance; not endorsed by OpenChain or signed off by qualified counsel. Attribution of original contributors does not imply their participation in, review of, or endorsement of these translations.
- License: the translations and guides use **CC-BY-4.0** ([full license](LICENSE)). Changes comprise Chinese translations, bilingual navigation, terminology notes, and expressly identified translator review notes. Retained English source content is available through the corresponding language pages. Preserve attribution, source and license links, and notices of changes when redistributing; do not imply endorsement by the original authors.

## Translation rules and legal status

These are translations of specified source versions, not official Chinese legislation, product compliance conclusions, conformity assessments, certifications, or legal opinions. Consult the corresponding English source for translation ambiguities. Determine legal obligations, conditions, and legal effect from the applicable official EU texts; neither the checklist nor its translations replace the law.

Numbering, classification labels, checkboxes, evidence fields, and cross-references are preserved. Personal and organizational names, product names, legal and standards identifiers, email addresses, technical fields, and status codes generally remain unchanged. Bracketed instructions are translated but their fields remain unfilled. Unconfirmed and TBD entries are translated without inventing missing information.

| Source term | Chinese rendering / treatment |
| :---- | :---- |
| must / must not | 必须 / 不得; preserves source strength without asserting that every item is a direct statutory duty |
| should | 宜; a recommendation, distinguished from must |
| may | 可以 for permission or choice; 可能 for possibility |
| CRA REQUIREMENT / DIRECT CRA OBLIGATION | CRA 要求 / CRA 直接义务; the author's classification, not a renewed legal certification |
| GOOD PRACTICE | 良好实践 |
| CONFORMITY EVIDENCE / IMPLEMENTATION CONTROL | 符合性证据 / 实施控制 |
| ORGANIZATION SBOM PROFILE / IMPLEMENTATION CONTROL | 组织 SBOM 配置要求 / 实施控制 |
| LEGAL REVIEW / IMPLEMENTATION CONTROL | 法律审查 / 实施控制 |
| placing on the market / making available on the market | 投放市场 / 在市场提供; kept distinct |
| product with digital elements (PDE) | 含数字要素的产品 |
| free and open-source software (FOSS) / freeware | 自由和开源软件 / 免费软件; free of charge is not equated with open source |
| open-source software steward / maintainer | 开源软件管理者 / 维护者; distinguishes the statutory organizational role from maintenance |
| conformity assessment / EU Declaration of Conformity | 符合性评定 / 欧盟符合性声明 |
| self-certification | 自我认证; follows the source without implying third-party certification |
| notified body / authorised representative | 公告机构 / 授权代表 |
| harmonised standards / presumption of conformity | 协调标准 / 符合性推定 |
| essential cybersecurity requirements | 基本网络安全要求 |
| without undue delay / without delay | 无不当延迟地 / 不延迟地 |
| actively exploited vulnerability | 正被主动利用的漏洞; distinct from every known or theoretically exploitable vulnerability |
| Technical File / technical documentation | 技术文档（成套资料） / 技术文件 |
| provenance / integrity / completeness | 来源（含来源证明） / 完整性（防篡改） / 完整程度（覆盖是否齐全） |
| declared license / concluded license | 声明许可证 / 判定许可证 |
| RACI | 执行责任 (Responsible), 最终责任 (Accountable), 征询 (Consulted), 知会 (Informed) |
| statutory Annex / checklist Annex | 附件 / 附录 |

<a id="source-review"></a>
## Translator review notes: source statements and limits of use

These additions are **not part of the English source and are not a complete legal review**. Jurisdiction: European Union. Selected legal sources were checked as of **2026-09-13**. Qualified counsel should assess the particular product, organizational role, and relevant Member State rules. The [CRA reference website](https://www.cyberresilienceact.eu/) provides a [full-text regulation page](https://www.cyberresilienceact.eu/regulation.html) and the article links below. It is an independent reference site, not an official EU legal publication platform; the authentic Official Journal acts and corrigenda govern. The homepage, full-text page, and cited article anchors were verified as accessible on 2026-09-13.

| Source location | Review note |
| :---- | :---- |
| §4.4.10: SME fine exemption | “SME” is too broad. Article 64(10)(a) addresses manufacturers qualifying as microenterprises or small enterprises and the early-warning deadlines in Article 14(2)(a) or (4)(a). It does not cover all medium-sized enterprises or waive reporting duties. The translation preserves the source wording. [Legal provisions: Article 64](https://www.cyberresilienceact.eu/regulation.html#art-64). |
| Section 1, Appendix A steward definition, and §3.5 | The definition is summarized. Article 3(14) includes systematic and sustained support for developing specific FOSS products intended for commercial activities, among other conditions. Steward status alone does not establish importer/distributor duties; actual roles and Articles 19–24 must be assessed. [Legal provisions: Article 3](https://www.cyberresilienceact.eu/regulation.html#art-3); [Articles 19–24](https://www.cyberresilienceact.eu/regulation.html#art-19). |
| §2.5 and §2.7.2 conformity routes | “Harmonised standards or a notified body” is incomplete. Article 32(2) also addresses common specifications and qualifying European cybersecurity certification schemes; Article 32(5) contains an Annex III FOSS route. Do not exclude statutory alternatives based on the summary. [Legal provisions: Article 32](https://www.cyberresilienceact.eu/regulation.html#art-32). |
| Section 1 deadline table, roadmap, and Appendix A AR entry | These summaries do not replace the product-specific analysis in §2.5.2 / §7.4. Article 18 permits appointment by written mandate; it does not impose a universal AR appointment duty on every non-EU manufacturer. [Legal provisions: Article 18](https://www.cyberresilienceact.eu/regulation.html#art-18). |
| Section 1 deadline table and §4.1.5–4.1.6 | The overview calls EUVD/KEV feeds “required,” while the detailed items classify them as good practice or implementation controls. This source discrepancy is preserved. Article 14 is triggered by awareness of a qualifying vulnerability or incident, not solely database inclusion or internal approval. [Legal provisions: Article 14](https://www.cyberresilienceact.eu/regulation.html#art-14). |
| §8.2.1–8.2.2 | Article 12 includes conditions and procedural exceptions. Article 12(1)(c) specifically requires the EU Declaration of Conformity to demonstrate the cybersecurity protection level required by AI Act Article 15. The summary does not establish automatic compliance with all AI rules. [Legal provisions: Article 12](https://www.cyberresilienceact.eu/regulation.html#art-12). |
| §2.7, §4.5.4, Appendix A, and references | Historical dates and “pending” labels are retained, not reconfirmed as current platform or standards status. The official publication of non-binding Commission guidance C(2026) 5252 (2026-07-27) and Delegated Regulation 2026/881 were checked. Not every third-party resource or unpublished draft was independently verified. [Guidance publication](https://digital-strategy.ec.europa.eu/en/library/commission-publishes-new-guidance-support-timely-cyber-resilience-act-implementation); [delegated regulation](https://eur-lex.europa.eu/eli/reg_del/2026/881/oj/eng). |
| Revision history, contribution guide, and release dates | The contribution guide dates RC1 to 2026-08-23, while the revision history gives 2026-08-19. The checklist gives 2026-09-11 for version 1.0, while the history retains TBD and a blank author field. These discrepancies and historical item counts are preserved. |
| §3.1.6 BSI link | The source mixes a URL with nested Markdown. The translation repairs the link syntax while retaining the existing destination. |

Other labels and summaries may also require interpretation. Internal risk acceptance does not itself waive legal duties. SaaS scope, standards mappings, secure-development controls, and technical documentation must be checked against the applicable scope, assessment, and original authorities.

<a id="archive-review"></a>
## Additional review notes for the PA_5.1 historical draft

The historical translation preserves all **159 actual checklist items**, labels, numbering, and historical statements. The source summaries state “157”; that discrepancy is retained and identified here. It is not current compliance guidance. The filename says PA_5.1, while its internal version says PA5. The following notes identify source issues without endorsing them. Legal provisions are available in the [full CRA text](https://www.cyberresilienceact.eu/regulation.html).

| Historical location | Review note |
| :---- | :---- |
| Section 1, §2.5.8, Appendix B | Importer, distributor, and substantial modification are defined in Article 3(16), (17), and (30), respectively. The source cites (17), (18), and (32) incorrectly. |
| §2.5.2 and §7.5 | Authorised representatives are addressed in Article 18, not Articles 22/25. The source's three-option formulation is not a universal duty for all foreign manufacturers; check the product and other applicable legislation. |
| §2.5.9 | Article 32(5) permits qualifying Annex III FOSS products to use Article 32(1) procedures subject to conditions including public technical documentation; it does not generally replace Module A or notified-body routes. |
| §3.1–3.4 and §4.1 | Some SBOM fields, dependency depths, tools, testing frequencies, and database choices are labelled “CRA REQUIREMENT.” Distinguish statutory requirements from implementation controls and consult the revised version 1.0 classifications. |
| §4.4.2–4.4.5 and §4.4.7 | Article 14 requires notification to the coordinating CSIRT and ENISA. The severe-incident final report is generally due one month after the Article 14(4)(b) notification, not generically after the earliest warning. Vulnerability final-report content is specified in Article 14(2)(c). Without an EU main establishment, the receiving Member State is determined in the order specified in Article 14(7). |
| §5.1.5 and §5.2.2 | Commercial-activity indicators do not establish manufacturer status independently of scope and role facts. Article 24(1) requires a steward's security policy to be documented in a verifiable manner, rather than generally requiring publication of the entire policy. Its specific cooperation and reporting duties also apply. |
| §2.4.4, §3.4.8, §6, §7.1, and §7.3 | Technical-documentation and declaration retention is principally addressed in Article 13(13); support periods in Article 13(8); continued availability of issued security updates in Article 13(9). Consider the free-update rule and exceptions in Annex I, Part II(8), rather than the draft's incorrect citations or shortened periods. |
| Appendix A traceability matrix | The draft's numbering and summaries are not a verbatim statutory mapping. Verify them against Annex I. The translation preserves the historical structure without independently certifying the mapping. |

## Bilingual maintenance record

| Date | Change |
| :---- | :---- |
| 2026-09-13 | Added complete Chinese translations of the version 1.0 checklist and three supporting files, terminology, and review notes. |
| 2026-09-13 | Split root documents by language; translated the contribution guide and PA_5.1 archive; added language navigation; changed Chinese latest to a link to the 1.0 Chinese text; deleted `Pre-Release-Versions/`; retained the license unchanged. |
| 2026-09-13 | Replaced both root latest entries with the complete current texts; removed item-level translator-review links from the Chinese 1.0 checklist; deleted both root revision-history files while retaining the 1.0 archive; updated and verified legal-provision links on the CRA reference website. |

Translations do not automatically track English updates. Record source commits and change scope in subsequent revisions. Propose substantive source changes through the [contribution process](CONTRIBUTING.en.md), clearly identifying them rather than silently rewriting the translation.
