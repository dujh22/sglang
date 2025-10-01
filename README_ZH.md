<div align="center" id="sglangtop">
<img src="https://raw.githubusercontent.com/sgl-project/sglang/main/assets/logo.png" alt="logo" width="400" margin="10px"></img>

[![PyPI](https://img.shields.io/pypi/v/sglang)](https://pypi.org/project/sglang)
![PyPI - Downloads](https://static.pepy.tech/badge/sglang?period=month)
[![license](https://img.shields.io/github/license/sgl-project/sglang.svg)](https://github.com/sgl-project/sglang/tree/main/LICENSE)
[![issue resolution](https://img.shields.io/github/issues-closed-raw/sgl-project/sglang)](https://github.com/sgl-project/sglang/issues)
[![open issues](https://img.shields.io/github/issues-raw/sgl-project/sglang)](https://github.com/sgl-project/sglang/issues)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/sgl-project/sglang)

</div>

---

| [**博客**](https://lmsys.org/blog/2025-05-05-large-scale-ep/)
| [**文档**](https://docs.sglang.ai/)
| [**加入 Slack**](https://slack.sglang.ai/)
| [**加入双周开发会议**](https://meeting.sglang.ai/)
| [**路线图**](https://github.com/sgl-project/sglang/issues/7736)
| [**幻灯片**](https://github.com/sgl-project/sgl-learning-materials?tab=readme-ov-file#slides) |

## 新闻

- [2025/08] 🔔 SGLang x AMD 旧金山见面会 8/22：GPU 实践研讨会、AMD/xAI/SGLang 技术分享及社交活动（[路线图](https://github.com/sgl-project/sgl-learning-materials/blob/main/slides/amd_meetup_sglang_roadmap.pdf)、[大规模 EP](https://github.com/sgl-project/sgl-learning-materials/blob/main/slides/amd_meetup_sglang_ep.pdf)、[亮点](https://github.com/sgl-project/sgl-learning-materials/blob/main/slides/amd_meetup_highlights.pdf)、[AITER/MoRI](https://github.com/sgl-project/sgl-learning-materials/blob/main/slides/amd_meetup_aiter_mori.pdf)、[Wave](https://github.com/sgl-project/sgl-learning-materials/blob/main/slides/amd_meetup_wave.pdf)）。
- [2025/08] 🔥 SGLang 提供对 OpenAI gpt-oss 模型的首日支持（[说明](https://github.com/sgl-project/sglang/issues/8833)）
- [2025/06] 🔥 SGLang，这个每天为数万亿 token 提供服务的高性能推理基础设施，已获得 a16z 第三批开源 AI 资助（[a16z 博客](https://a16z.com/advancing-open-source-ai-through-benchmarks-and-bold-experimentation/)）。
- [2025/06] 🔥 在 GB200 NVL72 上使用 PD 和大规模 EP 部署 DeepSeek（第一部分）：解码吞吐量提高 2.7 倍（[博客](https://lmsys.org/blog/2025-06-16-gb200-part-1/)）。
- [2025/05] 🔥 在 96 个 H100 GPU 上使用 PD 解耦和大规模专家并行部署 DeepSeek（[博客](https://lmsys.org/blog/2025-05-05-large-scale-ep/)）。
- [2025/03] 在 AMD Instinct MI300X 上加速 DeepSeek-R1 推理（[AMD 博客](https://rocm.blogs.amd.com/artificial-intelligence/DeepSeekR1-Part2/README.html)）
- [2025/03] SGLang 加入 PyTorch 生态系统：高效的 LLM 服务引擎（[PyTorch 博客](https://pytorch.org/blog/sglang-joins-pytorch/)）
- [2024/12] v0.4 版本发布：零开销批处理调度器、缓存感知负载均衡器、更快的结构化输出（[博客](https://lmsys.org/blog/2024-12-04-sglang-v0-4/)）。

<details>
<summary>更多</summary>

- [2025/02] 释放 AMD Instinct™ MI300X GPU 上的 DeepSeek-R1 推理性能（[AMD 博客](https://rocm.blogs.amd.com/artificial-intelligence/DeepSeekR1_Perf/README.html)）
- [2025/01] SGLang 在 NVIDIA 和 AMD GPU 上首日支持 DeepSeek V3/R1 模型，并进行了 DeepSeek 特定优化。（[说明](https://github.com/sgl-project/sglang/tree/main/benchmark/deepseek_v3)、[AMD 博客](https://www.amd.com/en/developer/resources/technical-articles/amd-instinct-gpus-power-deepseek-v3-revolutionizing-ai-development-with-sglang.html)、[10 多家其他公司](https://x.com/lmsysorg/status/1887262321636221412)）
- [2024/10] 首次 SGLang 线上见面会（[幻灯片](https://github.com/sgl-project/sgl-learning-materials?tab=readme-ov-file#the-first-sglang-online-meetup)）。
- [2024/09] v0.3 版本发布：DeepSeek MLA 快 7 倍、torch.compile 快 1.5 倍、支持多图像/视频的 LLaVA-OneVision（[博客](https://lmsys.org/blog/2024-09-04-sglang-v0-3/)）。
- [2024/07] v0.2 版本发布：使用 SGLang Runtime 更快地服务 Llama3（相比 TensorRT-LLM、vLLM）（[博客](https://lmsys.org/blog/2024-07-25-sglang-llama3/)）。
- [2024/02] SGLang 通过压缩有限状态机实现 **JSON 解码速度提升 3 倍**（[博客](https://lmsys.org/blog/2024-02-05-compressed-fsm/)）。
- [2024/01] SGLang 通过 RadixAttention 提供高达 **5 倍的推理速度**（[博客](https://lmsys.org/blog/2024-01-17-sglang/)）。
- [2024/01] SGLang 为官方 **LLaVA v1.6** 发布演示提供服务支持（[使用说明](https://github.com/haotian-liu/LLaVA?tab=readme-ov-file#demo)）。

</details>

## 关于

SGLang 是一个用于大语言模型和视觉语言模型的快速服务框架。
通过协同设计后端运行时和前端语言，它使您与模型的交互更快、更可控。
核心特性包括：

- **快速后端运行时**：提供高效服务，具备用于前缀缓存的 RadixAttention、零开销 CPU 调度器、预填充-解码解耦、推测解码、连续批处理、分页注意力、张量/流水线/专家/数据并行、结构化输出、分块预填充、量化（FP4/FP8/INT4/AWQ/GPTQ）以及多 LoRA 批处理。
- **灵活前端语言**：为编程 LLM 应用提供直观接口，包括链式生成调用、高级提示、控制流、多模态输入、并行处理和外部交互。
- **广泛模型支持**：支持多种生成模型（Llama、Qwen、DeepSeek、Kimi、GPT、Gemma、Mistral 等）、嵌入模型（e5-mistral、gte、mcdse）和奖励模型（Skywork），可轻松扩展以集成新模型。
- **活跃社区**：SGLang 是开源的，拥有活跃的社区支持和广泛的行业采用。

## 快速开始

- [安装 SGLang](https://docs.sglang.ai/get_started/install.html)
- [快速入门](https://docs.sglang.ai/basic_usage/send_request.html)
- [后端教程](https://docs.sglang.ai/basic_usage/openai_api_completions.html)
- [前端教程](https://docs.sglang.ai/references/frontend/frontend_tutorial.html)
- [贡献指南](https://docs.sglang.ai/developer_guide/contribution_guide.html)

## 基准测试与性能

在发布博客中了解更多：[v0.2 博客](https://lmsys.org/blog/2024-07-25-sglang-llama3/)、[v0.3 博客](https://lmsys.org/blog/2024-09-04-sglang-v0-3/)、[v0.4 博客](https://lmsys.org/blog/2024-12-04-sglang-v0-4/)、[大规模专家并行](https://lmsys.org/blog/2025-05-05-large-scale-ep/)。

## 路线图

[开发路线图（2025 下半年）](https://github.com/sgl-project/sglang/issues/7736)

## 采用与赞助

SGLang 已实现大规模部署，每天在生产环境中生成数万亿 token。它受到众多领先企业和机构的信赖和采用，包括 xAI、AMD、NVIDIA、Intel、LinkedIn、Cursor、Oracle Cloud、Google Cloud、Microsoft Azure、AWS、Atlas Cloud、Voltage Park、Nebius、DataCrunch、Novita、InnoMatrix、MIT、UCLA、华盛顿大学、斯坦福大学、加州大学伯克利分校、清华大学、Jam & Tea Studios、Baseten 以及北美和亚洲的其他主要科技组织。作为开源 LLM 推理引擎，SGLang 已成为事实上的行业标准，在全球超过 1,000,000 个 GPU 上运行。

<img src="https://raw.githubusercontent.com/sgl-project/sgl-learning-materials/refs/heads/main/slides/adoption.png" alt="logo" width="800" margin="10px"></img>

## 联系我们

如果您是有兴趣大规模采用或部署 SGLang 的企业，包括技术咨询、赞助机会或合作咨询，请通过 contact@sglang.ai 联系我们。

## 致谢

我们从以下项目中学习了设计并复用了代码：[Guidance](https://github.com/guidance-ai/guidance)、[vLLM](https://github.com/vllm-project/vllm)、[LightLLM](https://github.com/ModelTC/lightllm)、[FlashInfer](https://github.com/flashinfer-ai/flashinfer)、[Outlines](https://github.com/outlines-dev/outlines) 和 [LMQL](https://github.com/eth-sri/lmql)。
