# OpenChain CRA 1.0 简体中文版

本目录提供《OpenChain CRA 合规要求与检查清单》1.0 版本及其三份配套文件的**非官方简体中文译本**。译文为供审阅的参考译稿，涵盖原主清单第 1–9 节、全部 **193 个检查项**、实施路线图、自我认证汇总、附录 A–D 及参考资源。

## 文件导航

| 内容 | 简体中文 | 对应英文原文 |
| :---- | :---- | :---- |
| 主清单 | [CRA 合规要求与检查清单 1.0](CRA_Checklist_Requirement_v1.0.md) | [English](../CRA_Checklist_Requirement_v1.0.md) |
| 外部引用与采用情况 | [附录 D——外部引用、使用、工具与采用情况](ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.md) | [English](../ANNEX_D_EXTERNAL_REFERENCES_AND_ADOPTION.md) |
| 贡献者与审阅者 | [贡献者与审阅者登记册](CONTRIBUTORS.md) | [English](../CONTRIBUTORS.md) |
| 修订历史 | [原项目修订历史](REVISION_HISTORY.md) | [English](../REVISION_HISTORY.md) |

[返回仓库首页](../../README.md) · [贡献流程](../../CONTRIBUTING.md) · [许可证全文](../../LICENSE)

## 版本、来源与署名

- 原作：《OpenChain CRA Compliance Requirements & Checklist》及配套登记册，OpenChain CRA 项目；主要作者 Devashri Datta，其他贡献者及审阅者见[原文名单](../CONTRIBUTORS.md)。
- 上游项目：[OpenChain-Project/CRA-Compliance](https://github.com/OpenChain-Project/CRA-Compliance)；[项目网站](https://cra-compliance.openchainproject.org)。
- 本次翻译范围：用户指定仓库 [mingsun7-max/CRA-Compliance 的 1.0 目录](https://github.com/mingsun7-max/CRA-Compliance/tree/cd497f7a5a8daca97e50d049bfd9d4a6c60376e9/1.0)。不包含预发布归档或今后对 `latest` 的更新。
- 固定原文提交：`cd497f7a5a8daca97e50d049bfd9d4a6c60376e9`。英文主清单标示版本 1.0，发布日期 2026-09-11。
- 中文翻译日期：2026-09-13。翻译通过 Codex 辅助完成；未经 OpenChain 官方认可，亦未经合格律师签署确认。所列原文贡献者的署名不表示其参与、审阅或认可本中文译本。
- 许可：译文及本导读沿用仓库的 **CC-BY-4.0**（[许可证全文](../../LICENSE)）。本次改编包括中文翻译、中文导航、术语说明及明确标示的译者核对提示；原英文文件予以保留。再传播时请保留原作署名、来源、许可链接及改编说明，不得暗示原作者为译文或使用者背书。

## 翻译规则与法律地位

本文是对指定版本的翻译，不是法规的官方中文文本、产品合规结论、符合性评定、认证或法律意见。译义有歧义时应核对对应英文原文；法律义务、适用条件及法律效力应依据适用的欧盟官方法律文本确定，不能以本清单或其英文原文替代法律。

译文保留原文编号、分类标签、复选框、证据栏及交叉引用。人名、机构及产品专名、法规与标准编号、邮箱、技术字段和状态代码原则上保留。方括号填写提示已译为中文，待填写内容仍为空白；原文的 `[confirm]`、`TBD` 等分别译为“待确认”“待定”，不推定补全。

| 原文措辞或术语 | 本译本处理 |
| :---- | :---- |
| must / must not | 必须／不得；表达原文要求强度，不表示该项必然为法定直接义务 |
| should | 宜；表示建议性要求或良好实践，区别于 must |
| may | 可以；表示许可或选择；表示可能性时译为“可能” |
| CRA REQUIREMENT / DIRECT CRA OBLIGATION | CRA 要求／CRA 直接义务；保留原作者的分类，未将其重新认证为法律结论 |
| GOOD PRACTICE | 良好实践 |
| CONFORMITY EVIDENCE / IMPLEMENTATION CONTROL | 符合性证据／实施控制 |
| ORGANIZATION SBOM PROFILE / IMPLEMENTATION CONTROL | 组织 SBOM 配置要求／实施控制 |
| LEGAL REVIEW / IMPLEMENTATION CONTROL | 法律审查／实施控制 |
| placing on the market / making available on the market | 投放市场／在市场提供；保留两个概念的区分 |
| product with digital elements (PDE) | 含数字要素的产品 |
| free and open-source software (FOSS) / freeware | 自由和开源软件／免费软件；不将免费等同于开源 |
| open-source software steward / maintainer | 开源软件管理者／维护者；保留法定组织角色与维护角色的区别 |
| conformity assessment / EU Declaration of Conformity | 符合性评定／欧盟符合性声明 |
| self-certification | 自我认证；按原文用语翻译，不意味着取得第三方认证 |
| notified body / authorised representative | 公告机构／授权代表 |
| harmonised standards / presumption of conformity | 协调标准／符合性推定 |
| essential cybersecurity requirements | 基本网络安全要求 |
| without undue delay / without delay | 无不当延迟地／不延迟地 |
| actively exploited vulnerability | 正被主动利用的漏洞；不等同于所有已知或理论可利用漏洞 |
| Technical File / technical documentation | 技术文档（成套资料）／技术文件 |
| provenance / integrity / completeness | 来源（含来源证明）／完整性（防篡改）／完整程度（覆盖是否齐全） |
| declared license / concluded license | 声明许可证／判定许可证 |
| RACI | 执行责任（Responsible）、最终责任（Accountable）、征询（Consulted）、知会（Informed）职责矩阵 |
| Annex / 本清单 Annex | 法规的“附件”／本清单的“附录” |

<a id="source-review"></a>
## 译者核对提示：原文表述与使用边界

以下为译者补充，**不是英文原文的一部分，也不是完整法律审查**。司法辖区为欧盟；选定法律依据核对截至 **2026-09-13**。使用时仍需由熟悉具体产品、组织角色及相关成员国规则的合格法律顾问复核。法律来源采用 [CRA 官方合并文本](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120)辅助定位；具有法律效力的文本及勘误以《欧盟官方公报》为准。

| 原文位置 | 核对提示 |
| :---- | :---- |
| §4.4.10：SME 罚款豁免 | **原文“中小企业”概括过宽。** CRA 第 64 条第 10 款 (a) 项针对符合微型或小型企业条件的制造商，涉及未遵守第 14 条第 2 款 (a) 项或第 4 款 (a) 项的早期预警期限；不能推及全部中型企业，亦不免除报告义务。正文忠实保留原文措辞，适用时须按法条核对。[一手法律依据：第 64 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120) |
| 第 1 节、附录 A 的管理者定义及 §3.5 相关说明 | 原文为定义摘要。第 3 条第 (14) 项还涉及系统性、持续支持特定 FOSS 产品开发及该产品拟用于商业活动等要件。管理者身份本身不当然产生进口商／分销商义务；须另行判断实际角色，并结合第 19–24 条适用。[一手法律依据：第 3、19–24 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120) |
| §2.5、§2.7.2 的符合性评定路径 | 原文将部分路径简化为“协调标准或公告机构”。第 32 条第 2 款还涉及共同规范及符合条件的欧洲网络安全认证方案；第 32 条第 5 款另有附件 III FOSS 路径。不能仅凭该概括排除其他法定路径。[一手法律依据：第 32 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120) |
| 第 1 节期限表、实施路线图、附录 A 的 AR 说明 | 这些概览不能替代 §2.5.2／§7.4 的具体产品法律分析。CRA 第 18 条允许通过书面授权委任授权代表，并不普遍强制所有非欧盟制造商委任授权代表。[一手法律依据：第 18 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120) |
| 第 1 节期限表与 §4.1.5–4.1.6 | 概览表将 EUVD／KEV 信息源写为“要求”，正文则将其归为良好实践或实施控制；保留该原文差异。第 14 条触发点是获知符合条件的漏洞或事件，不能把数据库收录或内部审批当作唯一触发点。[一手法律依据：第 14 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120) |
| §8.2.1–8.2.2 | 第 12 条涉及具体条件及程序例外；尤其第 1 款 (c) 项要求在欧盟符合性声明中证明达到《人工智能法案》第 15 条要求的网络安全保护水平。不得仅据简表推定自动满足全部人工智能法规义务。[一手法律依据：第 12 条](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R2847-20241120) |
| §2.7、§4.5.4、附录 A 及参考资料 | 保留原文“截至 2026 年 8 月／年中”等历史时点及“待发布”标记，不能视为译文发布日所有标准和平台注册状态的重新确认。已核对委员会 C(2026) 5252 的官方发布页（2026-07-27、指引不具约束力），以及第 2026/881 号授权条例的官方文本；未逐一独立核验全部第三方资源或未公开草案。[官方指引发布页](https://digital-strategy.ec.europa.eu/en/library/commission-publishes-new-guidance-support-timely-cyber-resilience-act-implementation)；[授权条例官方文本](https://eur-lex.europa.eu/eli/reg_del/2026/881/oj/eng) |
| 修订历史与主清单版本日期 | 主清单注明 2026-09-11 发布，但原修订历史的 1.0 日期仍为 TBD、作者栏空白；译文分别保留。历史版本检查项数量也按原文保留。 |
| §3.1.6 的 BSI 链接 | 原文存在网址与 Markdown 嵌套混排；译文整理为原有目标网址的正常 Markdown 链接，未改变目标页面。 |

其他原文标签或摘要也可能需要解释。例如，组织内部风险接受不能当然免除法定义务；有关 SaaS、标准映射、安全开发控制及技术文件的概括，均应结合适用范围、评估结果与原始依据复核。本次翻译不替代上述判断。

## 中文版本维护记录

| 日期 | 中文版本变更 | 对应原文 |
| :---- | :---- | :---- |
| 2026-09-13 | 新增主清单及三份配套文件的完整简体中文翻译；新增本导读、术语对照及译者核对提示；更新仓库 README 中文入口。 | 1.0；提交 `cd497f7a5a8daca97e50d049bfd9d4a6c60376e9` |

中文版本不会自动跟随英文 `latest` 更新。后续翻译修订宜说明对应原文提交及变化范围；对原文内容的实质修订，应通过项目贡献流程另行提出，避免在译文中未经标示地改写原意。
