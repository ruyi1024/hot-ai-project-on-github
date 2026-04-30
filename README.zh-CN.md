# GitHub 热门 AI 项目清单

按类别整理 GitHub 上最热门、最值得关注的 AI 开源项目，帮助你快速发现高质量项目。

[English](./README.md) | 简体中文

> 本清单重点关注：**活跃维护**、**实用价值高**、**社区信号强** 的开源 AI 项目。
>
> 最后更新：**2026-04-30** (UTC+8)

## 目录

- [收录标准](#收录标准)
- [使用方式](#使用方式)
- [分类清单](#分类清单)
  - [大语言模型（LLM）](#大语言模型llm)
  - [AI Agent](#ai-agent)
  - [RAG（检索增强生成）](#rag检索增强生成)
  - [AI 编程](#ai-编程)
  - [图像生成](#图像生成)
  - [视频生成](#视频生成)
  - [语音（ASR / TTS）](#语音asr--tts)
  - [多模态](#多模态)
  - [MLOps 与部署](#mlops-与部署)
  - [评测与可观测性](#评测与可观测性)
- [最近新增](#最近新增)
- [贡献指南](#贡献指南)
- [许可证](#许可证)

## 收录标准

项目通常满足以下大部分条件：

- 最近仍有活跃维护（提交 / Issue / PR）
- README 和文档清晰可用
- 能落地到实际场景
- 具备社区热度（Star、Fork、讨论、采用度）
- 开源许可证明确

## 使用方式

- 先从与你需求最接近的分类开始看。
- 重点关注项目最近更新时间与发布节奏。
- 优先选择社区反馈积极、Issue 响应快的项目。
- 不同分类项目可以组合成完整 AI 技术栈。

## 分类清单

> 建议每条信息保持简洁，详细内容可放到后续 Wiki 或 docs。

### 大语言模型（LLM）

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [vllm](https://github.com/vllm-project/vllm) | 高吞吐、内存友好的 LLM 推理与服务引擎。 | 78,658 | Apache-2.0 | Python/CUDA |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | 面向 CPU/GPU 的高效本地 LLM 推理实现。 | 107,527 | MIT | C/C++ |
| [litellm](https://github.com/BerriAI/litellm) | 多模型供应商统一 OpenAI 兼容 API。 | 45,290 | MIT | Python |

### AI Agent

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [LangChain](https://github.com/langchain-ai/langchain) | 构建 LLM 应用与 Agent 工作流的框架。 | 135,458 | MIT | Python/TypeScript |
| [AutoGen](https://github.com/microsoft/autogen) | 微软开源的多 Agent 对话协作框架。 | 57,596 | MIT | Python |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 基于角色分工的多 Agent 编排框架。 | 50,331 | MIT | Python |

### RAG（检索增强生成）

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [LlamaIndex](https://github.com/run-llama/llama_index) | 面向 LLM 应用与 RAG 的数据框架。 | 49,051 | MIT | Python 生态 |
| [Haystack](https://github.com/deepset-ai/haystack) | 端到端 RAG 与检索编排框架。 | 25,030 | Apache-2.0 | Python + 向量数据库 |
| [RAGFlow](https://github.com/infiniflow/ragflow) | 偏工程落地的开源 RAG 引擎。 | 79,297 | Apache-2.0 | Python |

### AI 编程

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [Continue](https://github.com/continuedev/continue) | 开源 IDE AI 编程助手扩展。 | 32,896 | Apache-2.0 | Coding copilot |
| [Tabby](https://github.com/TabbyML/tabby) | 可自托管的 AI 编程助手。 | 33,483 | Apache-2.0 | 私有化代码补全 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 自动化软件工程 Agent 平台。 | 72,394 | MIT | Coding agent |

### 图像生成

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | 最流行的 Stable Diffusion 本地工作台之一。 | 162,668 | AGPL-3.0 | Diffusion 工具链 |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | 面向扩展工作流的节点式图像生成 UI。 | 110,737 | GPL-3.0 | 可组合图像流水线 |

### 视频生成

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [AnimateDiff](https://github.com/guoyww/AnimateDiff) | 将扩散图像流程扩展到短视频生成。 | 12,106 | Apache-2.0 | Image-to-video |
| [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) | ComfyUI 视频处理常用增强组件。 | 1,605 | GPL-3.0 | 视频工作流工具 |

### 语音（ASR / TTS）

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [whisper](https://github.com/openai/whisper) | 鲁棒性很强的多语种语音识别模型。 | 98,669 | MIT | ASR |
| [coqui-ai/TTS](https://github.com/coqui-ai/TTS) | 开源深度学习文本转语音工具库。 | 45,195 | MPL-2.0 | TTS |

### 多模态

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [LLaVA](https://github.com/haotian-liu/LLaVA) | 开源视觉指令微调与多模态对话方案。 | 24,739 | Apache-2.0 | 文本 + 图像 |
| [Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL) | Qwen 团队开源的多模态模型系列。 | 19,098 | Varied | 文本 + 图像/视频 |

### MLOps 与部署

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [BentoML](https://github.com/bentoml/BentoML) | ML/LLM 推理服务打包与部署框架。 | 8,614 | Apache-2.0 | Inference serving |
| [KServe](https://github.com/kserve/kserve) | Kubernetes 原生模型服务平台。 | 5,400 | Apache-2.0 | 生产部署 |

### 评测与可观测性

| 项目 | 项目描述 | Stars | License | 备注 |
| --- | --- | ---: | --- | --- |
| [Ragas](https://github.com/explodinggradients/ragas) | 面向 RAG 与 LLM 应用的评测框架。 | 13,724 | Apache-2.0 | LLM/RAG 评测 |
| [Langfuse](https://github.com/langfuse/langfuse) | 开源 LLM 观测平台，支持调用链追踪。 | 26,366 | MIT | Prompt/Trace 监控 |

## 最近新增

记录最近新增项目（建议保留 10-20 条）：

- `YYYY-MM-DD` - 在 `分类` 中新增 **项目名称**。
- `YYYY-MM-DD` - 在 `分类` 中新增 **项目名称**。

## 贡献指南

欢迎贡献。

提交新项目时请尽量提供：

- 项目链接
- 项目分类
- 一句话描述
- Star 数（可近似）
- 主要语言
- License
- 收录理由（1-2 句）

建议 PR 标题格式：

`add: <project-name> to <category>`

## 许可证

本仓库基于 [MIT License](./LICENSE) 开源。
