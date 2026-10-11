# 主题分类与检索

[返回首页](../README.md) · [月度归档](../archives/README.md)

每个条目使用一个或两个方向标签，以及少量具体主题标签。标签保留固定英文拼写，正文使用中文解释并保留关键英文术语。一个成果有多个关联主题时链接同一主记录，不复制全文。

## AI4Sec

用 AI 改进网络安全研究与工程实践。

| 标签 | 关注范围 |
| --- | --- |
| `vulnerability-discovery` | 漏洞发现、模糊测试、程序分析 |
| `code-security` | 代码审计、漏洞修复与补丁验证 |
| `detection-response` | 威胁检测、SOC 告警分析、事件响应 |
| `malware-analysis` | 恶意软件分类、逆向与行为分析 |
| `threat-intelligence` | 威胁情报抽取、关联与溯源证据 |
| `security-agents` | 安全任务 Agent 与合法授权测试评测 |
| `cyber-model-training` | Cyber 模型领域继续预训练、后训练（SFT / RL）与训练方法 |
| `cyber-training-data` | 网络安全训练数据、合成数据、质量、配比与许可 |
| `cyber-training-environments` | 合成任务环境、课程学习、可验证奖励与奖励设计 |
| `cyber-training-systems` | 与 Cyber 模型相关的分布式训练效率、检查点、故障恢复与成本 |
| `cyber-model-evaluation` | 数据泄漏 / 基准污染、受控基线、消融、迁移及真实场景验证 |

## Sec4AI

保护 AI 模型、数据、应用、Agent 与依赖链。

| 标签 | 关注范围 |
| --- | --- |
| `prompt-injection` | 直接或间接提示注入、上下文与指令边界 |
| `jailbreak-misuse` | 越狱评测、滥用风险与防护有效性 |
| `agent-tool-security` | Agent 工具调用、权限、隔离与 MCP 安全 |
| `data-exfiltration` | 上下文、检索数据与工具输出泄漏 |
| `poisoning-backdoors` | 训练 / 检索数据投毒、后门与触发机制 |
| `model-privacy` | 成员推断、模型反演与训练数据隐私 |
| `adversarial-robustness` | 对抗样本、分布变化与鲁棒性边界 |
| `ai-supply-chain` | 模型权重、依赖、数据与插件供应链 |
| `ai-security-evaluation` | 威胁模型、攻击成功率、基准与防御评测 |
| `safety-post-training` | 安全对齐后训练、正常任务效用、选择与外部验证；不等同Cyber任务能力训练 |

Cyber 模型训练通常归入 AI4Sec；训练过程的投毒、隐私、供应链或安全对齐问题也可归入 Sec4AI。解析时记录基础模型、数据 / 权重 / 环境可获得性及许可、训练与推理成本，以及评测隔离、受控基线和迁移证据；基准分数不单独作为真实场景能力的证明。

标签可随真实内容扩展，但应避免含义重复。跨方向的评测或系统同时标注 AI4Sec 与 Sec4AI，并解释各自关联。

## 已收录主题入口

下列入口指向实际发布条目；日期为日报日期。原始来源日期及新发布 / 背景补充状态见正文。完整逐项列表见[月度归档](../archives/README.md)。

| 主题 | 已收录条目 |
| --- | --- |
| `malware-analysis` | [2026-10-11 · 源码恢复SoK：编译与行为验证](../daily/2026/10/2026-10-11.md#paper-source-recovery-validation)；[2026-10-11 · ORCAGen：离线验证与运行时防御](../daily/2026/10/2026-10-11.md#paper-orcagen-offline-defense) |
| `safety-post-training` | [2026-10-11 · ReSI：晋级与评测边界](../daily/2026/10/2026-10-11.md#paper-resi-selection-boundaries) |
| `jailbreak-misuse` | [2026-10-11 · ReSI：晋级与评测边界](../daily/2026/10/2026-10-11.md#paper-resi-selection-boundaries) |
| `vulnerability-discovery` | [2026-10-01 · GTIG AI 归因漏洞观察](../daily/2026/10/2026-10-01.md#news-gtig-ai-vulnerability)；[2026-10-03 · ABSENTIA：逐路由审计](../daily/2026/10/2026-10-03.md#paper-absentia-route-invariant-audit)；[2026-10-10 · AVRI：证据保留与成本归因](../daily/2026/10/2026-10-10.md#paper-avri-evidence-cost) |
| `agent-tool-security` | [2026-10-01 · MCP OAuth issuer](../daily/2026/10/2026-10-01.md#news-mcp-oauth-issuer)；[OpenShell v0.1.2](../daily/2026/10/2026-10-01.md#project-openshell-runtime-controls)；[2026-10-02 · Asymmetric：Agent 服务组合风险](../daily/2026/10/2026-10-02.md#news-asymmetric-agent-service-chains)；[2026-10-02 · PACE：执行前来源与权限检查](../daily/2026/10/2026-10-02.md#paper-pace-execution-boundary)；[2026-10-02 · LLMLeak：正常网页抓取外泄](../daily/2026/10/2026-10-02.md#paper-llmleak-web-fetching)；[2026-10-03 · SQL Copilot：执行身份](../daily/2026/10/2026-10-03.md#news-sql-copilot-permission-boundary)；[2026-10-03 · APEX：交接与副作用](../daily/2026/10/2026-10-03.md#paper-apex-cross-skill-authorization)；[2026-10-04 · GitLab AI Gateway：模板沙箱与网关权限](../daily/2026/10/2026-10-04.md#news-gitlab-ai-gateway-template-sandbox)；[2026-10-04 · ZoneClaw：持久记忆分区与权限晋升](../daily/2026/10/2026-10-04.md#paper-zoneclaw-memory-authority)；[2026-10-05 · Pincer：资源层授权](../daily/2026/10/2026-10-05.md#paper-pincer-resource-authorization)；[2026-10-05 · MIRROR：消息完整性](../daily/2026/10/2026-10-05.md#paper-mirror-quorum-integrity)；[2026-10-06 · TPRS：工具元数据与测量](../daily/2026/10/2026-10-06.md#paper-tprs-measurement)；[2026-10-07 · 两阶段审计：执行前筛选](../daily/2026/10/2026-10-07.md#paper-gated-trace-audit)；[2026-10-08 · Secure-CUA：单步事务与界面定位](../daily/2026/10/2026-10-08.md#paper-secure-cua-transactions)；[2026-10-08 · CredLeakBench：泄漏与安全恢复](../daily/2026/10/2026-10-08.md#paper-credleak-recovery)；[2026-10-09 · NOMOS：政策规则与误拦](../daily/2026/10/2026-10-09.md#paper-nomos-policy-gates)；[2026-10-10 · Anthropic：评测边界与恢复路径](../daily/2026/10/2026-10-10.md#news-anthropic-evaluation-boundaries)；[2026-10-10 · One Word：类型化守卫与误封成本](../daily/2026/10/2026-10-10.md#paper-option-channel-guardrails)；[2026-10-11 · PyCache Trap：运行产物溯源](../daily/2026/10/2026-10-11.md#paper-pycache-artifact-provenance) |
| `data-exfiltration` | [2026-10-01 · MCP OAuth 凭据边界](../daily/2026/10/2026-10-01.md#news-mcp-oauth-issuer)；[2026-10-02 · Asymmetric：Agent 服务组合风险](../daily/2026/10/2026-10-02.md#news-asymmetric-agent-service-chains)；[2026-10-02 · PACE：执行前来源与权限检查](../daily/2026/10/2026-10-02.md#paper-pace-execution-boundary)；[2026-10-02 · LLMLeak：正常网页抓取外泄](../daily/2026/10/2026-10-02.md#paper-llmleak-web-fetching)；[2026-10-03 · SQL Copilot：工具副作用](../daily/2026/10/2026-10-03.md#news-sql-copilot-permission-boundary)；[2026-10-04 · ZoneClaw：持久记忆分区与权限晋升](../daily/2026/10/2026-10-04.md#paper-zoneclaw-memory-authority)；[2026-10-08 · CredLeakBench：泄漏与安全恢复](../daily/2026/10/2026-10-08.md#paper-credleak-recovery) |
| `ai-security-evaluation` | [2026-10-01 · OpenShell 证明器覆盖范围](../daily/2026/10/2026-10-01.md#project-openshell-runtime-controls)；[2026-10-02 · Asymmetric：Agent 服务组合风险](../daily/2026/10/2026-10-02.md#news-asymmetric-agent-service-chains)；[2026-10-02 · PACE：执行前来源与权限检查](../daily/2026/10/2026-10-02.md#paper-pace-execution-boundary)；[2026-10-02 · LLMLeak：正常网页抓取外泄](../daily/2026/10/2026-10-02.md#paper-llmleak-web-fetching)；[2026-10-03 · APEX：效用与评分边界](../daily/2026/10/2026-10-03.md#paper-apex-cross-skill-authorization)；[2026-10-04 · ZoneClaw：持久记忆分区与权限晋升](../daily/2026/10/2026-10-04.md#paper-zoneclaw-memory-authority)；[2026-10-04 · NEEDLE：后门方向与拒答子空间](../daily/2026/10/2026-10-04.md#paper-needle-weight-orthogonalisation)；[2026-10-05 · Pincer：条件指标与成本](../daily/2026/10/2026-10-05.md#paper-pincer-resource-authorization)；[2026-10-05 · MIRROR：诚实路径假设](../daily/2026/10/2026-10-05.md#paper-mirror-quorum-integrity)；[2026-10-06 · TPRS：评测表示敏感性](../daily/2026/10/2026-10-06.md#paper-tprs-measurement)；[Whiteout：保护与事实完整性](../daily/2026/10/2026-10-06.md#paper-whiteout-privacy)；[2026-10-07 · 两阶段审计：成本与漏检](../daily/2026/10/2026-10-07.md#paper-gated-trace-audit)；[统一监测：报警时间窗](../daily/2026/10/2026-10-07.md#paper-misuse-harm-window)；[2026-10-08 · Secure-CUA：单步事务与界面定位](../daily/2026/10/2026-10-08.md#paper-secure-cua-transactions)；[2026-10-08 · CredLeakBench：泄漏与安全恢复](../daily/2026/10/2026-10-08.md#paper-credleak-recovery)；[2026-10-09 · NOMOS：效用与评测隔离](../daily/2026/10/2026-10-09.md#paper-nomos-policy-gates)；[2026-10-09 · DITTO：模型依赖与覆盖](../daily/2026/10/2026-10-09.md#paper-ditto-model-audit)；[2026-10-10 · Anthropic：评测边界与恢复路径](../daily/2026/10/2026-10-10.md#news-anthropic-evaluation-boundaries)；[2026-10-10 · One Word：类型化守卫与误封成本](../daily/2026/10/2026-10-10.md#paper-option-channel-guardrails)；[2026-10-10 · LTBD：可学习边界与复现缺口](../daily/2026/10/2026-10-10.md#paper-ltbd-learned-boundaries)；[2026-10-10 · RAISED：自蒸馏与任务效用](../daily/2026/10/2026-10-10.md#paper-raised-self-distillation)；[2026-10-11 · PyCache Trap：运行产物溯源](../daily/2026/10/2026-10-11.md#paper-pycache-artifact-provenance)；[2026-10-11 · ReSI：晋级与评测边界](../daily/2026/10/2026-10-11.md#paper-resi-selection-boundaries) |
| `cyber-model-training` | [2026-10-01 · MiST](../daily/2026/10/2026-10-01.md#paper-mist-mid-training)；[CyberWorld](../daily/2026/10/2026-10-01.md#paper-cyberworld-world-model)；[2026-10-02 · Crossing the Cyber Divide：策略迁移](../daily/2026/10/2026-10-02.md#paper-cyber-policy-transfer)；[2026-10-03 · AuraForge：安全筛选SFT](../daily/2026/10/2026-10-03.md#paper-auraforge-security-supervision)；[2026-10-04 · KaliBench：命令评分与runtime-free RLVR](../daily/2026/10/2026-10-04.md#paper-kalibench-runtime-free-rewards)；[2026-10-08 · Ask the Expert：训练期防御指导](../daily/2026/10/2026-10-08.md#paper-ask-expert-defense)；[2026-10-10 · LTBD：可学习边界与复现缺口](../daily/2026/10/2026-10-10.md#paper-ltbd-learned-boundaries)；[2026-10-10 · RAISED：自蒸馏与任务效用](../daily/2026/10/2026-10-10.md#paper-raised-self-distillation) |
| `cyber-training-data` | [2026-10-01 · MiST 合成数据与隔离](../daily/2026/10/2026-10-01.md#paper-mist-mid-training)；[2026-10-03 · AuraGym：测试与训练隔离](../daily/2026/10/2026-10-03.md#paper-auraforge-security-supervision)；[2026-10-04 · KaliBench：命令评分与runtime-free RLVR](../daily/2026/10/2026-10-04.md#paper-kalibench-runtime-free-rewards)；[2026-10-10 · RAISED：自蒸馏与任务效用](../daily/2026/10/2026-10-10.md#paper-raised-self-distillation) |
| `cyber-training-environments` | [2026-10-01 · CyberWorld 世界模型](../daily/2026/10/2026-10-01.md#paper-cyberworld-world-model)；[2026-10-02 · Crossing the Cyber Divide：策略迁移](../daily/2026/10/2026-10-02.md#paper-cyber-policy-transfer)；[2026-10-08 · Ask the Expert：训练期防御指导](../daily/2026/10/2026-10-08.md#paper-ask-expert-defense)；[2026-10-10 · Anthropic：评测边界与恢复路径](../daily/2026/10/2026-10-10.md#news-anthropic-evaluation-boundaries) |
| `cyber-model-evaluation` | [2026-10-01 · GTIG 归因边界](../daily/2026/10/2026-10-01.md#news-gtig-ai-vulnerability)；[MiST 消融](../daily/2026/10/2026-10-01.md#paper-mist-mid-training)；[CyberWorld 评测口径](../daily/2026/10/2026-10-01.md#paper-cyberworld-world-model)；[2026-10-02 · 分层 Cyber 防御：规划与执行](../daily/2026/10/2026-10-02.md#paper-hierarchical-cyber-defense)；[2026-10-02 · Crossing the Cyber Divide：策略迁移](../daily/2026/10/2026-10-02.md#paper-cyber-policy-transfer)；[2026-10-03 · AuraForge：oracle与预算归因](../daily/2026/10/2026-10-03.md#paper-auraforge-security-supervision)；[2026-10-03 · ABSENTIA：成对计分与人工复核](../daily/2026/10/2026-10-03.md#paper-absentia-route-invariant-audit)；[2026-10-04 · KaliBench：命令评分与runtime-free RLVR](../daily/2026/10/2026-10-04.md#paper-kalibench-runtime-free-rewards)；[2026-10-05 · AgentSecGraph：上下文保留与研究/产品差异](../daily/2026/10/2026-10-05.md#paper-agentsecgraph-evidence)；[2026-10-06 · ICS：分阶段覆盖与负结果](../daily/2026/10/2026-10-06.md#paper-ics-evidence-pipeline)；[2026-10-07 · SAGE：覆盖与正确性](../daily/2026/10/2026-10-07.md#paper-sage-repair-origin)；[2026-10-08 · Ask the Expert：训练期防御指导](../daily/2026/10/2026-10-08.md#paper-ask-expert-defense)；[2026-10-09 · AIDA：证据与推理预算](../daily/2026/10/2026-10-09.md#paper-aida-evidence)；[2026-10-10 · AVRI：证据保留与成本归因](../daily/2026/10/2026-10-10.md#paper-avri-evidence-cost)；[2026-10-11 · 源码恢复SoK：编译与行为验证](../daily/2026/10/2026-10-11.md#paper-source-recovery-validation) |
| `prompt-injection` | [2026-10-02 · PACE：执行前来源与权限检查](../daily/2026/10/2026-10-02.md#paper-pace-execution-boundary)；[2026-10-03 · SQL Copilot：数据库说明与权限](../daily/2026/10/2026-10-03.md#news-sql-copilot-permission-boundary)；[2026-10-03 · APEX：跨技能授权混淆](../daily/2026/10/2026-10-03.md#paper-apex-cross-skill-authorization)；[2026-10-04 · ZoneClaw：持久记忆分区与权限晋升](../daily/2026/10/2026-10-04.md#paper-zoneclaw-memory-authority)；[2026-10-05 · Pincer：隔离授权依据](../daily/2026/10/2026-10-05.md#paper-pincer-resource-authorization)；[2026-10-07 · 统一监测：报警时间窗](../daily/2026/10/2026-10-07.md#paper-misuse-harm-window)；[2026-10-08 · Secure-CUA：单步事务与界面定位](../daily/2026/10/2026-10-08.md#paper-secure-cua-transactions)；[2026-10-09 · NOMOS：确定性工具门控](../daily/2026/10/2026-10-09.md#paper-nomos-policy-gates)；[2026-10-10 · One Word：类型化守卫与误封成本](../daily/2026/10/2026-10-10.md#paper-option-channel-guardrails)；[2026-10-10 · LTBD：可学习边界与复现缺口](../daily/2026/10/2026-10-10.md#paper-ltbd-learned-boundaries)；[2026-10-10 · RAISED：自蒸馏与任务效用](../daily/2026/10/2026-10-10.md#paper-raised-self-distillation) |
| `ai-supply-chain` | [2026-10-02 · LLMLeak：正常网页抓取外泄](../daily/2026/10/2026-10-02.md#paper-llmleak-web-fetching)；[2026-10-03 · APEX：技能供应链](../daily/2026/10/2026-10-03.md#paper-apex-cross-skill-authorization)；[2026-10-04 · GitLab AI Gateway：模板沙箱与网关权限](../daily/2026/10/2026-10-04.md#news-gitlab-ai-gateway-template-sandbox)；[2026-10-09 · DITTO：模型加载审计](../daily/2026/10/2026-10-09.md#paper-ditto-model-audit)；[2026-10-11 · PyCache Trap：运行产物溯源](../daily/2026/10/2026-10-11.md#paper-pycache-artifact-provenance) |
| `detection-response` | [2026-10-02 · 分层 Cyber 防御：规划与执行](../daily/2026/10/2026-10-02.md#paper-hierarchical-cyber-defense)；[2026-10-06 · ICS：遥测证据链](../daily/2026/10/2026-10-06.md#paper-ics-evidence-pipeline)；[2026-10-08 · Ask the Expert：训练期防御指导](../daily/2026/10/2026-10-08.md#paper-ask-expert-defense)；[2026-10-09 · AIDA：关闭告警的证据要求](../daily/2026/10/2026-10-09.md#paper-aida-evidence)；[2026-10-11 · ORCAGen：离线验证与运行时防御](../daily/2026/10/2026-10-11.md#paper-orcagen-offline-defense) |
| `security-agents` | [2026-10-02 · 分层 Cyber 防御：规划与执行](../daily/2026/10/2026-10-02.md#paper-hierarchical-cyber-defense)；[2026-10-03 · ABSENTIA：覆盖与分解](../daily/2026/10/2026-10-03.md#paper-absentia-route-invariant-audit)；[2026-10-04 · KaliBench：命令评分与runtime-free RLVR](../daily/2026/10/2026-10-04.md#paper-kalibench-runtime-free-rewards)；[2026-10-05 · AgentSecGraph：候选与漏洞分开](../daily/2026/10/2026-10-05.md#paper-agentsecgraph-evidence)；[2026-10-09 · AIDA：独立裁决与成本消融](../daily/2026/10/2026-10-09.md#paper-aida-evidence)；[2026-10-10 · AVRI：证据保留与成本归因](../daily/2026/10/2026-10-10.md#paper-avri-evidence-cost)；[2026-10-11 · ORCAGen：离线验证与运行时防御](../daily/2026/10/2026-10-11.md#paper-orcagen-offline-defense) |
| `code-security` | [2026-10-03 · AuraForge：安全编程监督](../daily/2026/10/2026-10-03.md#paper-auraforge-security-supervision)；[2026-10-03 · ABSENTIA：授权不变量](../daily/2026/10/2026-10-03.md#paper-absentia-route-invariant-audit)；[2026-10-05 · AgentSecGraph：静态证据图](../daily/2026/10/2026-10-05.md#paper-agentsecgraph-evidence)；[2026-10-07 · SAGE：失败来源定位](../daily/2026/10/2026-10-07.md#paper-sage-repair-origin)；[2026-10-11 · 源码恢复SoK：编译与行为验证](../daily/2026/10/2026-10-11.md#paper-source-recovery-validation) |
| `model-privacy` | [2026-10-06 · Whiteout：定向隐私保护](../daily/2026/10/2026-10-06.md#paper-whiteout-privacy) |
| `poisoning-backdoors` | [2026-10-04 · NEEDLE：后门方向与拒答子空间](../daily/2026/10/2026-10-04.md#paper-needle-weight-orthogonalisation) |
| `adversarial-robustness` | [2026-10-04 · NEEDLE：后门方向与拒答子空间](../daily/2026/10/2026-10-04.md#paper-needle-weight-orthogonalisation) |

## 类型与证据字段

- 类型：`news`（新闻）、`project`（项目）、`paper`（论文）
- 时效：新发布 / 重要更新 / 背景补充；说明本期新在哪里
- 证据：原始资料已核对 / 作者自报 / 独立验证 / 分析推断
- 置信度：高 / 中 / 低，并给出具体理由；低置信度的重要信息可以保留风险提示，不能包装为确定事实
- 稳定标识：按来源记录项目全名、版本或提交、DOI、arXiv ID 与版本等；不存在时不编造

## 检索方法

在 GitHub 的仓库搜索中输入以下查询，再选择代码搜索。也可直接在仓库内按文件路径或日期查找。

- 方向：`repo:timwhitez/AIxSec AI4Sec`
- 主题：`repo:timwhitez/AIxSec "prompt-injection"`
- 模型训练：`repo:timwhitez/AIxSec "cyber-model-training"`
- 项目或论文：`repo:timwhitez/AIxSec "项目全名或论文标题"`
- 指定月份的日报：`repo:timwhitez/AIxSec path:daily/2026/10`
- 日期：先用 GitHub 文件查找搜索 `YYYY-MM-DD.md`，再在对应日报中定位条目

以上是查询示例，不表示仓库已经有对应日报。GitHub 搜索可能要求登录且存在索引延迟；找不到新内容时，从[月度归档](../archives/README.md)或仓库文件目录进入。

阅读历史结论时，同时检查条目的更正记录、版本日期和后续重要更新。
