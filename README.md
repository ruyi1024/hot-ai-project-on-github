# Hot AI Projects on GitHub

Curating the hottest and most trending AI repositories on GitHub, organized by category for quick discovery.

English | [简体中文](./README.zh-CN.md)

> This list focuses on **active**, **useful**, and **high-signal** open-source AI projects.
>
> Last updated: **2026-04-30** (UTC+8)

## Table of Contents

- [Selection Criteria](#selection-criteria)
- [How to Use This List](#how-to-use-this-list)
- [Categories](#categories)
  - [Large Language Models (LLM)](#large-language-models-llm)
  - [AI Agents](#ai-agents)
  - [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation)
  - [AI Coding](#ai-coding)
  - [Image Generation](#image-generation)
  - [Video Generation](#video-generation)
  - [Speech (ASR / TTS)](#speech-asr--tts)
  - [Multimodal](#multimodal)
  - [MLOps & Deployment](#mlops--deployment)
  - [Evaluation & Observability](#evaluation--observability)
  - [Prompt Engineering & System Prompts](#prompt-engineering--system-prompts)
  - [Learning Resources & Skills](#learning-resources--skills)
  - [AI Applications & Productivity Tools](#ai-applications--productivity-tools)
- [Recently Added](#recently-added)
- [Contribution Guide](#contribution-guide)
- [License](#license)

## Selection Criteria

Projects in this list should satisfy most of the following:

- Recently active maintenance (commits/issues/PRs in recent months)
- Clear README and usable documentation
- Practical value (can be used in real workflows)
- Meaningful community traction (stars, forks, discussion, adoption)
- Open-source license with clear usage terms

## How to Use This List

- Start from categories that match your use case.
- Check each project's last update date and release status.
- Prefer projects with active issue responses and community support.
- Combine projects from different categories to build complete AI workflows.

## Categories

> Tip: Keep each item short and structured. You can expand details in a separate wiki later.

### Large Language Models (LLM)

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [vllm](https://github.com/vllm-project/vllm) | High-throughput and memory-efficient LLM inference/serving engine. | 78,658 | Apache-2.0 | Python/CUDA |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | Efficient local LLM inference in C/C++ across CPU/GPU platforms. | 107,527 | MIT | C/C++ |
| [litellm](https://github.com/BerriAI/litellm) | Unified OpenAI-compatible API for many LLM providers. | 45,290 | MIT | Python |

### AI Agents

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [LangChain](https://github.com/langchain-ai/langchain) | Framework for building LLM applications and agent workflows. | 135,458 | MIT | Python/TypeScript |
| [AutoGen](https://github.com/microsoft/autogen) | Multi-agent conversation framework from Microsoft. | 57,596 | MIT | Python |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Role-based multi-agent orchestration framework. | 50,331 | MIT | Python |

### RAG (Retrieval-Augmented Generation)

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Data framework for LLM apps and RAG pipelines. | 49,051 | MIT | Python ecosystem |
| [Haystack](https://github.com/deepset-ai/haystack) | End-to-end RAG and search orchestration framework. | 25,030 | Apache-2.0 | Python + vector databases |
| [RAGFlow](https://github.com/infiniflow/ragflow) | Open-source RAG engine with practical pipeline UX. | 79,297 | Apache-2.0 | Python |

### AI Coding

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [Continue](https://github.com/continuedev/continue) | Open-source AI code assistant extension for IDEs. | 32,896 | Apache-2.0 | Coding copilot |
| [Tabby](https://github.com/TabbyML/tabby) | Self-hosted AI coding assistant. | 33,483 | Apache-2.0 | Private code completion |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Autonomous software engineering agent platform. | 72,394 | MIT | Coding agent |

### Image Generation

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Popular local UI for Stable Diffusion workflows. | 162,668 | AGPL-3.0 | Diffusion model tooling |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | Node-based visual workflow UI for diffusion models. | 110,737 | GPL-3.0 | Composable image pipelines |

### Video Generation

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [AnimateDiff](https://github.com/guoyww/AnimateDiff) | Animates diffusion images into short videos. | 12,106 | Apache-2.0 | Image-to-video |
| [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) | Practical video utilities for ComfyUI pipelines. | 1,605 | GPL-3.0 | Video workflow tooling |

### Speech (ASR / TTS)

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [whisper](https://github.com/openai/whisper) | Robust multilingual speech recognition model. | 98,669 | MIT | ASR |
| [coqui-ai/TTS](https://github.com/coqui-ai/TTS) | Open-source deep-learning text-to-speech toolkit. | 45,195 | MPL-2.0 | TTS |

### Multimodal

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [LLaVA](https://github.com/haotian-liu/LLaVA) | Open-source visual instruction tuning for multimodal chat. | 24,739 | Apache-2.0 | Text + image |
| [Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL) | Multimodal understanding/generation model family by Qwen team. | 19,098 | Varied | Text + image/video |

### MLOps & Deployment

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [BentoML](https://github.com/bentoml/BentoML) | Packaging and serving framework for ML/LLM inference APIs. | 8,614 | Apache-2.0 | Inference serving |
| [KServe](https://github.com/kserve/kserve) | Kubernetes-native model serving platform. | 5,400 | Apache-2.0 | Production deployment |

### Evaluation & Observability

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [Ragas](https://github.com/explodinggradients/ragas) | Evaluation framework for RAG and LLM applications. | 13,724 | Apache-2.0 | LLM/RAG evaluation |
| [Langfuse](https://github.com/langfuse/langfuse) | Open-source LLM engineering platform for traces and observability. | 26,366 | MIT | Prompt/trace monitoring |

### Prompt Engineering & System Prompts

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) | Collection of leaked/public system prompts from AI products. | - | - | Prompt analysis/reference |
| [LangGPT](https://github.com/langgptai/LangGPT) | Structured prompt engineering framework and prompt templates. | - | - | Prompt methodology |

### Learning Resources & Skills

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [dive-into-llms](https://github.com/Lordog/dive-into-llms) | Learning materials for understanding and building with LLMs. | - | - | Tutorial/resource |
| [andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) | Skill-style resources inspired by Andrej Karpathy workflows. | - | - | Learning/skills |
| [last30days-skill](https://github.com/mvanhorn/last30days-skill) | Skill repository for productivity and AI-assisted workflows. | - | - | Skill pack |

### AI Applications & Productivity Tools

| Project | Description | Stars | License | Notes |
| --- | --- | ---: | --- | --- |
| [NarratoAI](https://github.com/linyqh/NarratoAI) | AI-powered content creation and narration workflow project. | - | - | Content generation |
| [Pixelle-Video](https://github.com/AIDC-AI/Pixelle-Video) | AI video generation project and related tooling. | - | - | Video creation |
| [worldmonitor](https://github.com/koala73/worldmonitor) | Monitoring/insight project for global trends and signals. | - | - | Trend monitoring |
| [Archon](https://github.com/coleam00/Archon) | AI-centric project focused on orchestration/automation workflows. | - | - | Agent/workflow |
| [markitdown](https://github.com/microsoft/markitdown) | Convert files/content into Markdown for LLM processing pipelines. | - | MIT | Data preprocessing |
| [omi](https://github.com/BasedHardware/omi) | Open AI-native wearable ecosystem and companion stack. | - | - | Hardware + AI |
| [GenericAgent](https://github.com/lsdefine/GenericAgent) | Generic AI agent implementation for reusable task automation. | - | - | Agent framework |
| [TrendRadar](https://github.com/sansan0/TrendRadar) | AI trend discovery and signal tracking project. | - | - | Trend analysis |
| [RAG-Anything](https://github.com/HKUDS/RAG-Anything) | RAG framework targeting broad document/data understanding. | - | - | RAG extension |
| [PandaWiki](https://github.com/chaitin/PandaWiki) | AI-assisted wiki/knowledge base construction project. | - | - | Knowledge management |
| [Clawith](https://github.com/dataelement/Clawith) | AI application project (tooling/productivity-oriented). | - | - | General AI app |
| [next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) | Next.js + AI diagram generation/editing workflow inspired by draw.io. | - | - | AI diagrams |

## Recently Added

Track your latest additions here (suggestion: keep only last 10-20 entries):

- `2026-04-30` - Added **system_prompts_leaks** in `Prompt Engineering & System Prompts`.
- `2026-04-30` - Added **LangGPT** in `Prompt Engineering & System Prompts`.
- `2026-04-30` - Added **NarratoAI** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **Pixelle-Video** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **worldmonitor** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **Archon** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **markitdown** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **RAG-Anything** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **PandaWiki** in `AI Applications & Productivity Tools`.
- `2026-04-30` - Added **next-ai-draw-io** in `AI Applications & Productivity Tools`.

## Contribution Guide

Contributions are welcome.

When submitting a new project, please include:

- Project link
- Category
- One-line description
- Stars (approximate is fine)
- Primary language
- License
- Why it should be included (1-2 lines)

Suggested PR title format:

`add: <project-name> to <category>`

## License

This repository is licensed under the [MIT License](./LICENSE).

