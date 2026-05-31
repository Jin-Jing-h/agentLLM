# LLM 多智能体社会仿真平台调研

> 筛选条件：2024 年之后、正式发表、CCF-B 及以上、引用量较高，且没有明显形成系列化后续工作的论文。

|  排名 |  年份  | 论文 / 平台                                                                                                                             | 发表出处                                 | CCF / 影响力                            |       引用量 | 平台实现的任务                                              | 模拟到的现象                        | 传播路径                                                                       |
| :-: | :--: | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------ | --------: | ---------------------------------------------------- | ----------------------------- | -------------------------------------------------------------------------- |
|  1  | 2024 | [**EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities**][1]                                   | **ACL 2024**                         | **CCF-A**                            | 约 **236** | 用 LLM 智能体模拟宏观经济活动，让智能体根据自身属性、市场环境和历史记忆做工作、消费等决策。     | 个体异质性、消费变化、劳动供给变化、宏观经济波动。     | 宏观环境先给出工资、价格、市场趋势等信息；智能体根据自身情况和记忆做决策；大量个体决策汇总成宏观经济变化，再影响下一轮智能体行为。          |
|  2  | 2024 | [**MAgIC: Investigation of Large Language Model Powered Multi-Agent in Cognition, Adaptability, Rationality and Collaboration**][2] | **EMNLP 2024**                       | **CCF-B**                            | 约 **127** | 构建多智能体竞争与博弈环境，用狼人杀、博弈论场景评估 LLM 智能体的判断、推理、欺骗、合作和协调能力。 | 多智能体协作、竞争、欺骗、理性决策、群体博弈。       | 系统设置社会推理游戏或博弈任务；多个智能体分别获得不同身份和信息；智能体通过发言、推理和投票互动；最终根据胜负和行为指标评估多智能体能力。      |
|  3  | 2024 | [**Unveiling the Truth and Facilitating Change: Towards Agent-based Large-scale Social Movement Simulation**][3]                    | **Findings of ACL 2024**             | **ACL 关联正式论文，是否按 CCF-A 认定需看学校/单位规则** | 约 **114** | 构建大规模社会运动仿真框架 HiSim，用 LLM 核心用户和规则普通用户模拟社交媒体上的社会运动传播。 | 社会运动扩散、公众响应、观点变化、线上集体行动。      | 现实事件先触发社交媒体讨论；核心用户由 LLM 驱动生成发帖、转发、评论等行为；大量普通用户用规则模型扩散反应；最终形成整体社会运动传播趋势。    |
|  4  | 2024 | [**Is this the real life? Is this just fantasy? The Misleading Success of Simulating Social Interactions With LLMs**][4]            | **EMNLP 2024**                       | **CCF-B**                            |  约 **74** | 构建社会互动仿真评估框架，比较“全知视角”和“非全知视角”下 LLM 模拟社会互动的差异。        | 信息不对称、社会互动失真、过度乐观的仿真结果。       | 系统设置不同信息条件下的社交互动任务；LLM 在全知或非全知环境中生成互动；研究发现全知设定下表现更好，但真实社会互动中的信息不对称会显著降低效果。 |
|  5  | 2025 | [**GenSim: A General Social Simulation Platform with Large Language Model based Agents**][5]                                        | **NAACL 2025 System Demonstrations** | **CCF-B 相关，Demo 论文**                 |  约 **57** | 构建通用社会仿真平台，支持自定义社会场景、大规模智能体和错误修正机制，最多支持十万级智能体仿真。     | 大规模社会行为、长期仿真稳定性、错误累积与修正、群体互动。 | 研究者先定义场景、智能体角色和交互规则；平台批量生成智能体并推进多轮交互；如果行为不合理，系统通过纠错机制修正，再继续运行仿真。           |

## References

[1]: https://aclanthology.org/2024.acl-long.829/
[2]: https://aclanthology.org/2024.emnlp-main.416/
[3]: https://aclanthology.org/2024.findings-acl.285/
[4]: https://aclanthology.org/2024.emnlp-main.1208/
[5]: https://aclanthology.org/2025.naacl-demo.15/
