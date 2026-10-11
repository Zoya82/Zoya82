# Zoya82｜AI 应用、Agent 与模型评测

我做从任务定义、模型与工具接入到评测和迭代的 AI 项目，关注检索策略、生成结果核验和可追溯的实验记录。使用 AI coding 工具协作开发，并用代码、保存结果和版本记录核对交付。

## 精选项目

| 项目 | 做了什么 | 当前可查看的成果 |
|---|---|---|
| [auto0998：检索策略与 Agent 评测](https://github.com/Zoya82/auto0998-agent-eval) | 检索策略接口、AI coding agent 迭代、隔离评分、完整快照与恢复 | 真实最佳策略、离线演示、同版归档结果；GPT方法554／1000，平台提交未完成 |
| [法律问答：SFT、DPO、RAG](https://github.com/Zoya82/llm_sft_dpo_legalqa) | LoRA微调、偏好对齐、法条检索与引用核验 | 6步Notebook、实验报告、148条留出评测及版本口径 |
| [mini Search-R1](https://github.com/Zoya82/mini_search_r1) | HotpotQA子集、向量检索、标签协议与单轮rollout | 已跑单轮检索基线；冷启动SFT及RL训练待完成 |
| [GRPO＋GSM8K](https://github.com/Zoya82/grpo_r1_gsm8k) | 小模型LoRA、格式及正确性规则奖励 | 40步训练日志、曲线、奖励重算脚本；尚无独立测试集结论 |
| [中文问题生成：Mengzi-T5](https://github.com/Zoya82/t5-chinese-qg-finetune) | DuReaderQG微调、三档对比、检索baseline | 训练与评测Notebook、BLEU结果、可视化 |

## 快速查看

先看 [auto0998的两个本地演示](https://github.com/Zoya82/auto0998-agent-eval#两个本地演示)，再看 [法律问答完整实验报告](https://github.com/Zoya82/llm_sft_dpo_legalqa/blob/main/PROJECT_REPORT.md) 与 [最新重算结果](https://github.com/Zoya82/llm_sft_dpo_legalqa/blob/main/outputs/report_tables/T_ablation148.md)。每个仓库首页说明已完成范围、证据来源和运行方法。

主要使用 Python、PyTorch、Transformers、PEFT、TRL、向量检索和 Harbor。项目覆盖 MPS 本地训练与 GPU 容器评测；公开仓库保留代码和可检查结果，数据、模型权重及私有评测资产按项目说明准备。

最近更新：2026-10-11。
