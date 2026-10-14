# Hi, I'm Arborsen 👋

**AI Agent · Reinforcement Learning · Embodied AI**

我是哈尔滨工业大学（深圳）**2026 级研究生，研究方向为 AI Agent**。本科就读于电子科技大学，专业为电磁场与无线技术。

我关注智能体如何学习、推理并与环境交互，也喜欢把模型原理落实到数据、训练、推理和评测的完整流程中。

## 研究与实践

- **AI Agent 与大模型推理**：关注任务理解、环境反馈、自生成任务与可验证奖励，持续阅读和分析相关论文。
- **强化学习**：围绕策略梯度、VPG / PPO、价值函数与 GAE，结合源码和 CartPole 实验理解算法机制。
- **具身智能**：开展视觉语言动作模型（VLA）的工程复现，实践机器人数据适配、多卡后训练与仿真闭环评测。

## 具身模型工程实践

### LingBot-VLA 2.0 × RoboTwin

围绕 **6B 视觉语言动作模型**与 RoboTwin 双臂操作场景，打通数据准备、模型后训练、权重导出和仿真评测链路。

- **数据与动作对齐**：处理 LeRobot 数据兼容、三路 RGB 与 14 维状态 / 动作映射，验证归一化和动作还原的一致性。
- **分布式训练与恢复**：完成四卡 FSDP2 后训练，跑通 5,000 步训练与 HF 权重导出；处理显存、磁盘和 checkpoint 保存恢复问题。
- **闭环评测与系统排障**：通过 WebSocket 衔接模型推理与仿真环境，开展 zero-shot 和后训练评测，定位数据、训练、推理与仿真各环节的问题。

## 精选公开项目

| 项目 | 解决的问题与技术实践 |
| --- | --- |
| [招投标评审 RAG 系统](https://github.com/Arborsen/26.7.7) | 面向招标文档的问答与专家参考手册原型，整合向量检索、BM25、RRF 融合、引用溯源和 SSE 流式回答。 |
| [FlipFocus · 翻面番茄钟](https://github.com/Arborsen/FlipFocus) | 用手机翻面动作启动或暂停专注计时，结合 Android 加速度传感器、防抖与前台服务实现轻量交互。 |
| [强化学习：源码与实验](https://github.com/Arborsen/spinningup-master) | 基于 OpenAI Spinning Up 的学习与实验仓库，包含中文学习材料和适配现代 Gym API 的 CartPole VPG 训练例程。 |

## 开源贡献

从具体缺陷出发，结合问题复现、实现修改和回归测试参与上游项目。

| 项目 | 贡献 | 状态 |
| --- | --- | --- |
| [idb #352](https://github.com/jakearchibald/idb/pull/352) | 修复读取 `NaN` 时的包装与缓存异常，补充边界值回归测试。 | **已合并** |
| [DeepDiff #641](https://github.com/qlustered/deepdiff/pull/641) | 改进固定偏移时区对象的比较与哈希处理，补充相关测试。 | PR 已提交 |
| [Lark #1665](https://github.com/lark-parser/lark/pull/1665) | 修复树重建中的条件内联与参数拼接问题，补充语法重建回归测试。 | PR 已提交 |
| [xiaohongshu-skills #100](https://github.com/autoclaw-cc/xiaohongshu-skills/pull/100) | 修复多标签话题选择，增加话题完整性校验与测试。 | PR 已提交 |
| [cc-switch #5158](https://github.com/farion1231/cc-switch/pull/5158) | 为 API 转换链路补充可配置的默认输出预算及兼容性测试。 | PR 已提交 |

贡献状态更新于 **2026-10-14**，最新进展见对应 PR。

## 技术与工作方式

**Python / PyTorch · FSDP2 · VLA · RAG / FastAPI · Kotlin / Android · Git / GitHub**

我习惯把理论、代码和实验结果对应起来，重视边界条件、回归测试与可复现记录，也使用 AI 编程工具辅助学习和开发。

技术之外，我喜欢摄影与视频表达。欢迎通过相关项目的 Issue 交流。
