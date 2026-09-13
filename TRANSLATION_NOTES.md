# 翻译说明与核对提示

**简体中文** | [English](TRANSLATION_NOTES.en.md) | [首页](README.md)

## 版本、来源与署名

- 原作：《OpenChain CRA Compliance Requirements & Checklist》及配套登记册，OpenChain CRA 项目；主要作者 Devashri Datta，其他贡献者及审阅者见[贡献者与审阅者](CONTRIBUTORS.md)（英文原表：[CONTRIBUTORS.en.md](CONTRIBUTORS.en.md)）。
- 上游项目：[OpenChain-Project/CRA-Compliance](https://github.com/OpenChain-Project/CRA-Compliance)；[项目网站](https://cra-compliance.openchainproject.org)。
- 翻译范围：根目录贡献指南及两份登记册、1.0 主清单及配套文件、`versions/` 保留的 PA_5.1 历史稿；维护根目录双语导航及最新版全文。`LICENSE` 仅保留原文，不另附中文版本；`Pre-Release-Versions/` 已删除。
- 固定原文提交：`cd497f7a5a8daca97e50d049bfd9d4a6c60376e9`。英文主清单标示版本 1.0，发布日期 2026-09-11。
- 中文翻译日期：2026-09-13。翻译通过 Codex 辅助完成；未经 OpenChain 官方认可，亦未经合格律师签署确认。所列原文贡献者的署名不表示其参与、审阅或认可本中文译本。
- 许可：译文及本导读沿用仓库的 **CC-BY-4.0**（[许可证全文](LICENSE)）。本次改编包括中文翻译、双语导航、术语说明及明确标示的译者核对提示；保留内容的英文原文按语言页面归档。再传播时请保留原作署名、来源、许可链接及改编说明，不得暗示原作者为译文或使用者背书。

## 翻译规则与法律地位

本仓库各译文是对指定原文版本的翻译，不是法规的官方中文文本、产品合规结论、符合性评定、认证或法律意见。译文有歧义时应核对对应英文原文；法律义务、适用条件及法律效力应依据适用的欧盟官方法律文本确定，不能以本清单或其英文原文替代法律。

译文保留原文编号、分类标签、复选框、证据栏及交叉引用。人名、机构及产品专名、法规与标准编号、邮箱、技术字段和状态代码原则上保留。方括号填写提示已译为中文，待填写内容仍为空白；原文的 `[confirm]`、`TBD` 等分别译为“待确认”“待定”，不推定补全。

| 原文措辞或术语 | 本译本处理 |
| :---- | :---- |
| must / must not | 必须／不得；表达原文要求强度，不表示该项必然为法定直接义务 |
| should | 宜；表示建议性要求或良好实践，区别于 must |
| may | 可以；表示许可或选择；表示可能性时译为“可能” |
| CRA REQUIREMENT / DIRECT CRA OBLIGATION | CRA 要求／CRA 直接义务；保留原作者的分类，未将其重新认证为法律结论 |
| GOOD PRACTICE | 良好实践 |
| CONFORMITY EVIDENCE / IMPLEMENTATION CONTROL | 符合性证据／实施控制 |
| ORGANIZATION SBOM PROFILE / IMPLEMENTATION CONTROL | 组织 SBOM 规范／实施控制 |
| profile（CSAF VEX profile、SPDX hardware profile） | 保留英文 profile；指标准中的文档类型或数据模型分层，不是“配置文件”。“organization SBOM profile”按其含义译为“组织 SBOM 规范”并括注英文 |
| LEGAL REVIEW / IMPLEMENTATION CONTROL | 法律审查／实施控制 |
| placing on the market / making available on the market | 投放市场／在市场上提供；保留两个概念的区分 |
| product with digital elements (PDE) | 含数字要素的产品 |
| free and open-source software (FOSS) / freeware | 自由和开源软件／免费软件；不将免费等同于开源 |
| open-source software steward / maintainer | 开源软件管理者／维护者；保留法定组织角色与维护角色的区别 |
| conformity assessment / EU Declaration of Conformity | 符合性评定／欧盟符合性声明 |
| self-certification | 自我认证；按原文用语翻译，不意味着取得第三方认证 |
| notified body / authorised representative | 公告机构／授权代表 |
| harmonised standards / presumption of conformity | 协调标准／符合性推定 |
| conformity claim / conformance claim | 符合性主张；指组织对外主张符合，区别于作为法定文件的“欧盟符合性声明” |
| important products Class I / Class II; critical products | 第 I 类／第 II 类重要产品；关键产品 |
| essential cybersecurity requirements | 基本网络安全要求 |
| without undue delay / without delay | 无不当延迟地／无延迟地 |
| actively exploited vulnerability | 正被主动利用的漏洞；不等同于所有已知或理论可利用漏洞 |
| Technical File / technical documentation | 统一译为“技术文档”；二者在原文中均指 CRA 第 31 条及附件 VII 所指的同一套文件 |
| provenance / integrity / completeness | 来源（含来源证明）／完整性（防篡改）／完整程度（覆盖是否齐全） |
| documented（形容词） | 形成文件的 |
| essential / important entities（NIS2） | 基本实体／重要实体 |
| declared license / concluded license | 声明许可证／判定许可证 |
| RACI | 执行责任（Responsible）、最终责任（Accountable）、征询（Consulted）、知会（Informed）职责矩阵 |
| Annex / 本清单 Annex | 法规的“附件”／本清单的“附录” |

上述术语统一适用于 1.0 清单及配套文件；`versions/` 下的 PA_5.1 历史稿按其翻译时的用语保留，未随本次统一改动。

<a id="source-review"></a>
## 译者核对提示：原文表述与使用边界

以下为译者补充，**不是英文原文的一部分，也不是完整法律审查**。司法辖区为欧盟；所选法律依据已核对至 **2026-09-13**。使用时仍需由熟悉具体产品、组织角色及相关成员国规则的合格法律顾问复核。法律条文通过 [CRA 参考网站](https://www.cyberresilienceact.eu/)的[法规全文页](https://www.cyberresilienceact.eu/regulation.html)及下列条款定位链接查阅。该站为独立参考网站，非欧盟官方法律发布平台；具有法律效力的文本及勘误以《欧盟官方公报》为准。上述网站首页、全文页及所引条款锚点已于 2026-09-13 核验可访问。

| 原文位置 | 核对提示 |
| :---- | :---- |
| §4.4.10：SME 罚款豁免 | **原文“中小企业”概括过宽。** CRA 第 64 条第 10 款 (a) 项针对符合微型或小型企业条件的制造商，涉及未遵守第 14 条第 2 款 (a) 项或第 4 款 (a) 项的早期预警期限；不能推及全部中型企业，亦不免除报告义务。正文忠实保留原文措辞。[法律条文：第 64 条](https://www.cyberresilienceact.eu/regulation.html#art-64) |
| 第 1 节、附录 A 的管理者定义及 §3.5 相关说明 | 原文为定义摘要。第 3 条第 (14) 项还涉及系统性、持续支持特定 FOSS 产品开发及该产品拟用于商业活动等要件。管理者身份本身不当然产生进口商／分销商义务；须另行判断实际角色，并结合第 19–24 条适用。[法律条文：第 3 条](https://www.cyberresilienceact.eu/regulation.html#art-3)、[第 19–24 条](https://www.cyberresilienceact.eu/regulation.html#art-19) |
| §2.5、§2.7.2 的符合性评定路径 | 原文将部分路径简化为“协调标准或公告机构”。第 32 条第 2 款还涉及共同规范及符合条件的欧洲网络安全认证方案；第 32 条第 5 款另有附件 III FOSS 路径。不能仅凭该概括排除其他法定路径。[法律条文：第 32 条](https://www.cyberresilienceact.eu/regulation.html#art-32) |
| 第 1 节期限表、实施路线图、附录 A 的授权代表（AR）条目 | 这些概览不能替代 §2.5.2／§7.4 的具体产品法律分析。CRA 第 18 条允许通过书面授权委任授权代表，并不普遍强制所有非欧盟制造商委任授权代表。[法律条文：第 18 条](https://www.cyberresilienceact.eu/regulation.html#art-18) |
| 第 1 节期限表与 §4.1.5–4.1.6 | 概览表将 EUVD／KEV 信息源写为“要求”，正文则将其归为良好实践或实施控制；保留该原文差异。第 14 条触发点是获知符合条件的漏洞或事件，不能把数据库收录或内部审批当作唯一触发点。[法律条文：第 14 条](https://www.cyberresilienceact.eu/regulation.html#art-14) |
| §8.2.1–8.2.2 | 第 12 条涉及具体条件及程序例外；尤其第 1 款 (c) 项要求在欧盟符合性声明中证明达到《人工智能法案》第 15 条要求的网络安全保护水平。不得仅据简表推定自动满足全部人工智能法规义务。[法律条文：第 12 条](https://www.cyberresilienceact.eu/regulation.html#art-12) |
| §2.7、§4.5.4、附录 A 及参考资料 | 保留原文“截至 2026 年 8 月／年中”等历史时点及“待发布”标记，不能视为译文发布日所有标准和平台注册状态的重新确认。已核对委员会 C(2026) 5252 的官方发布页（2026-07-27 发布；该指引不具约束力），以及第 2026/881 号授权条例的官方文本；未逐一独立核验全部第三方资源或未公开草案。[官方指引发布页](https://digital-strategy.ec.europa.eu/en/library/commission-publishes-new-guidance-support-timely-cyber-resilience-act-implementation)；[授权条例官方文本](https://eur-lex.europa.eu/eli/reg_del/2026/881/oj/eng) |
| 修订历史、贡献指南与主清单版本日期 | 贡献指南记载 RC1 发布日为 2026-08-23，修订历史记载为 2026-08-19；分别保留。主清单注明 2026-09-11 发布，但原修订历史的 1.0 日期仍为 TBD、作者栏空白；译文分别保留。历史版本检查项数量也按原文保留。 |
| §4.2.1、参考资料 | 原文所称“CISA VEX minimum viable guidelines”对应 CISA 发布的 VEX 最低要求文件；译为“最低要求指南”并括注原文英文，未改变链接目标。 |
| §3.1.6 的 BSI 链接 | 原文存在网址与 Markdown 嵌套混排；译文整理为原有目标网址的正常 Markdown 链接，未改变目标页面。 |

其他原文标签或摘要也可能需要解释。例如，组织内部风险接受不能当然免除法定义务；有关 SaaS、标准映射、安全开发控制及技术文档的概括，均应结合适用范围、评估结果与原始依据复核。本次翻译不替代上述判断。

<a id="archive-review"></a>
## PA_5.1 历史稿的补充核对提示

历史稿正文逐项翻译，保留实际 **159 个检查项**、义务标签、编号及历史表述；原稿汇总所称“157 项”原样保留并在此注明差异；不作为现行合规建议。其文件名为 PA_5.1，内部版本仍为 PA5。以下提示针对原稿，不能解读为对相关错误表述的认可；法律条文见 [CRA 法规全文](https://www.cyberresilienceact.eu/regulation.html)。

| 历史稿位置 | 核对提示 |
| :---- | :---- |
| 第 1 节、§2.5.8、附录 B | 进口商、分销商、实质性修改的定义分别见第 3 条第 (16)、(17)、(30) 项，原稿引用的 (17)、(18)、(32) 项有误。 |
| §2.5.2、§7.5 | 授权代表见第 18 条，不是第 22／25 条；原稿“三选一”的概括不能作为所有境外制造商的普遍义务。须核对具体产品及其他适用法规。 |
| §2.5.9 | 第 32 条第 5 款允许符合条件的附件 III FOSS 产品在技术文档公开等条件下采用第 32 条第 1 款程序，并非一概替代模式 A 或公告机构路径。 |
| §3.1–3.4、§4.1 | 原稿将部分 SBOM 字段、依赖深度、工具、测试频率和数据库选择标为“CRA 要求”；法定要求与组织实施控制必须区分，不能仅据标签推定法条逐项强制要求。对照 1.0 的修订分类使用。 |
| §4.4.2–4.4.5、§4.4.7 | 第 14 条要求向协调 CSIRT 和 ENISA 通知；严重事件最终报告通常自第 14 条第 4 款 (b) 项通知提交起一个月内提交，不能笼统从最初预警起算。漏洞最终报告内容见第 14 条第 2 款 (c) 项；无欧盟主要营业机构时的接收成员国按第 14 条第 7 款规定顺序确定。 |
| §5.1.5、§5.2.2 | 商业活动指标不应脱离产品范围及角色事实直接等同于制造商身份。第 24 条第 1 款要求管理者以可核验方式制定并记录网络安全政策，并非概括地要求公开整份政策；还须适用其具体合作和报告义务。 |
| §2.4.4、§3.4.8、§6、§7.1、§7.3 | 技术文档及欧盟符合性声明的保存主要见第 13 条第 13 款；支持期主要见第 13 条第 8 款；已发布安全更新的持续可获取性见第 13 条第 9 款。须结合附件 I 第 II 部分第 (8) 项的免费更新规则及其例外，不宜沿用原稿误引或简化期限。 |
| 附录 A 可追溯性矩阵 | 原稿编号和概括并非逐字法规映射；使用时必须逐项核对附件 I。中文版保留其历史编排，不对映射作独立认证。 |

## 双语维护记录

| 日期 | 变更 |
| :---- | :---- |
| 2026-09-13 | 新增 1.0 主清单及三份配套文件中文全文、术语对照及核对提示。 |
| 2026-09-13 | 完成根目录双语拆分、贡献指南翻译及 PA_5.1 中文归档；补齐语言切换；将中文 latest 改为 1.0 中文链接页；删除 `Pre-Release-Versions/`；许可证原样保留。 |
| 2026-09-13 | 根目录中英文 latest 改为最新版本全文；移除 1.0 中文清单的逐项“译者核对提示”链接；删除根目录中英文修订历史文件，保留 1.0 归档；将“法律条文”链接更新至 CRA 参考网站并核验可用性。 |
| 2026-09-13 | 对 1.0 主清单、附录 D 及本说明进行逐句中英对照审校：统一术语（技术文档、在市场上提供、第 I 类／第 II 类重要产品、含数字要素的产品、符合性推定、符合性主张、形成文件的、profile、选择退出机制、可追溯性矩阵）；修正定义与法律表述（制造商定义中的 markets、PDE 定义中的 separately marketed、书面委任书、NIS2 基本实体、第 14 条第 7 款主要营业机构的主语等）；消除若干歧义句与翻译腔；补齐表格注释的 Markdown 转义。根目录 latest 与 `1.0/zh-CN/` 同步更新。 |

译文不会自动跟随英文更新。后续修订应说明原文提交及变化范围；原文内容的实质修订宜通过[贡献流程](CONTRIBUTING.md)另行提出，并明确标示，不在译文中无提示改写。
