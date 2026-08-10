# Awesome-Private-LLM-Platform 🔒

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Private LLM Platform Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Private-LLM-Platform/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Private-LLM-Platform?style=social" alt="GitHub stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Private-LLM-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Private-LLM-Platform?style=social" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Private-LLM-Platform/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🚀 Top Private LLM Platforms

A curated list of leading enterprise platforms and tools for private, secure, and self-hosted large language model (LLM) development, fine-tuning, inference, RAG, and agentic AI.

**Primary focus: open-source software 🔓.**

Commercial / hosted platforms are listed separately with detailed pricing, free trial limits, and company valuation data for completeness. Open-source alternatives and community tools are emphasized throughout.

---

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Key Focus | Company Size (Valuation / Revenue) | Starting Price | Free Tier / Free Trial Limits |
|----------|-------------|-----------|-----------------------------------|----------------|-------------------------------|
| **[NVIDIA AI Enterprise](https://www.nvidia.com/en-us/data-center/products/ai-enterprise/)** | Full-stack software platform with NIM microservices, NeMo tools, optimized inference (vLLM, TensorRT-LLM, Triton), and cloud/edge support. | High-performance inference, microservices, GPU AI | **$5.51 Trillion** (Market Cap) / **$215.9B** Revenue | **$4,500 / GPU / year** ($1/hour/GPU on cloud marketplaces) | **90-day free trial** license (or hands-on access via NVIDIA LaunchPad) |
| **[IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai)** | Integrated studio for building, testing, and scaling enterprise AI. Supports Granite models, agent tooling, RAG, and hybrid deployment. | Enterprise foundation models, RAG, agents, governance | **$250 Billion** (Market Cap) / **$68.3B** Revenue | **$1,110/month** (Standard Plan base) / Pay-as-you-go | **Lite Plan**: 20 Capacity Unit Hours (CUH)/month & 300,000 tokens/month |
| **[Cohere North](https://cohere.com/north)** | Secure AI agent platform for private deployment (VPC, on-prem, air-gapped). Combines LLMs, search, and automation with strict compliance. | Private agentic AI workspace with data sovereignty | **$20.0 Billion** (Valuation) | **$0.0375 per 1M input tokens** (Command R7B starting tier) | **1,000 API calls / month** (Free Trial API key limit) |
| **[SambaNova Suite](https://sambanova.ai/)** | Full-stack LLM platform powered by custom RDUs (SN40L/SN50). Serves massive open-source models with high performance and model ownership. | Hardware-accelerated private inference at scale | **$11.0 Billion** (Valuation) | **$0.10 per 1M tokens** (Base model Developer tier rate) | **$5 free trial credits** valid for 3 months |
| **[Together Enterprise](https://www.together.ai/enterprise)** | Enterprise platform for inference and fine-tuning of open models. Offers serverless/dedicated endpoints, VPC options, and high throughput. | High-performance open-model inference & fine-tuning | **$8.3 Billion** (Valuation) | **$1.49 / GPU hour** (L40) / **$8.00 per 1M training tokens** | **$5 free trial credits** on account creation ($50,000 via Startup Program) |
| **[DataRobot AI Cloud](https://www.datarobot.com/)** | End-to-end AI platform with GenAI playground, LLM gateway (70+ models), RAG, agentic frameworks, observability, and governance. | GenAI experimentation, production governance, multi-model orchestration | **$6.3 Billion** (Valuation) | **$25,000 / year** (Starting enterprise setup/services threshold) | **30-day free trial**: Capped at 15 vector DBs & 1,000 LLM calls |
| **[Writer Enterprise](https://writer.com/)** | Full-stack enterprise generative AI platform with proprietary Palmyra LLMs, Knowledge Graph for company data, and AI Studio for agents. | Brand-aligned content, agents, and knowledge workflows | **$1.9 Billion** (Valuation) | **$29 / user / month** (Starter plan, billed annually) | **14-day free trial** (no credit card required) |
| **[H2O AI Cloud](https://h2o.ai/platform/ai-cloud/)** | End-to-end platform including Driverless AI, H2O-3, LLM Studio, Enterprise h2oGPTe, MLOps, and document AI on Kubernetes. | AutoML + generative AI, private cloud, explainability | **$1.7 Billion** (Valuation) | **$50,000 / year** (Enterprise unit base license) | **90-day free trial** with full platform capabilities |
| **[Anyscale](https://www.anyscale.com/)** | Unified AI compute platform built by creators of Ray. Enables scalable LLM serving (Ray Serve + vLLM), fine-tuning, batch inference, and RAG. | Distributed Ray workloads, production LLM serving & post-training | **$1.65 Billion** (Valuation) | **$0.80 / node hour** (On-demand compute management rate) | **$100 free credits** upon new account registration |
| **[Predibase](https://predibase.com/)** | Platform for fine-tuning and serving open LLMs with private serverless deployments, LoRAX multi-adapter serving, and OpenAI APIs. | Cost-efficient fine-tuning & multi-adapter inference | **$250 Million** (Estimated Valuation) | **$0.0001 / 1K tokens** (Serverless fine-tuned inference) / Pay-as-you-go | **14-day free trial** with **$25 initial free credits** |

---

## 🔓 Open-Source Softwares & Tools

These tools form the core ecosystem for private, self-hosted, and fully controlled LLM development, fine-tuning, inference, RAG, and agentic systems. All software can run entirely on your own infrastructure with zero data leaving your environment.

Sorted by GitHub star count in descending order ⭐.

| Project | Description | Stars | Category / Focus | License |
|---------|-------------|-------|------------------|---------|
| **[Ollama](https://github.com/ollama/ollama)** | Simple, Docker-like tool for running open-source LLMs locally or on servers with an OpenAI-compatible API. | <a href="https://github.com/ollama/ollama/stargazers"><img src="https://img.shields.io/github/stars/ollama/ollama?style=social&color=white" alt="Ollama Stars"/></a> | Local Runtime & Serving | MIT |
| **[llama.cpp](https://github.com/ggerganov/llama.cpp)** | Highly optimized C/C++ inference engine (GGUF format) for CPU, GPU, and edge devices. | <a href="https://github.com/ggerganov/llama.cpp/stargazers"><img src="https://img.shields.io/github/stars/ggerganov/llama.cpp?style=social&color=white" alt="llama.cpp Stars"/></a> | C/C++ Inference Engine | MIT |
| **[Dify](https://github.com/langgenius/dify)** | Open-source LLM application development platform with visual workflow builder, RAG, agents, and observability. | <a href="https://github.com/langgenius/dify/stargazers"><img src="https://img.shields.io/github/stars/langgenius/dify?style=social&color=white" alt="Dify Stars"/></a> | LLM App Platform & Workflow Builder | AGPL-3.0 |
| **[vLLM](https://github.com/vllm-project/vllm)** | High-throughput, memory-efficient LLM serving engine with PagedAttention, continuous batching, and OpenAI API. | <a href="https://github.com/vllm-project/vllm/stargazers"><img src="https://img.shields.io/github/stars/vllm-project/vllm?style=social&color=white" alt="vLLM Stars"/></a> | High-Throughput Serving Engine | Apache 2.0 |
| **[Unsloth](https://github.com/unslothai/unsloth)** | Fast and memory-efficient fine-tuning library (2× faster fine-tuning, 80% less VRAM usage). | <a href="https://github.com/unslothai/unsloth/stargazers"><img src="https://img.shields.io/github/stars/unslothai/unsloth?style=social&color=white" alt="Unsloth Stars"/></a> | Efficient Fine-Tuning | Apache 2.0 |
| **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** | All-in-one desktop and self-hosted AI document chat & private RAG application. | <a href="https://github.com/Mintplex-Labs/anything-llm/stargazers"><img src="https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social&color=white" alt="AnythingLLM Stars"/></a> | Private RAG & Document Chat UI | MIT |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | Feature-rich, self-hosted web interface designed for Ollama, vLLM, and OpenAI-compatible APIs. | <a href="https://github.com/open-webui/open-webui/stargazers"><img src="https://img.shields.io/github/stars/open-webui/open-webui?style=social&color=white" alt="Open WebUI Stars"/></a> | Self-Hosted Web Interface | MIT |
| **[CrewAI](https://github.com/crewai-inc/crewai)** | Framework for orchestrating role-playing, autonomous AI agents for complex collaborative tasks. | <a href="https://github.com/crewai-inc/crewai/stargazers"><img src="https://img.shields.io/github/stars/crewai-inc/crewai?style=social&color=white" alt="CrewAI Stars"/></a> | Multi-Agent Orchestration | MIT |
| **[Flowise](https://github.com/FlowiseAI/Flowise)** | Drag-and-drop UI node-based builder for constructing custom LLM flows, chains, and agents. | <a href="https://github.com/FlowiseAI/Flowise/stargazers"><img src="https://img.shields.io/github/stars/FlowiseAI/Flowise?style=social&color=white" alt="Flowise Stars"/></a> | Low-Code / No-Code Agent Builder | MIT |
| **[LlamaIndex](https://github.com/run-llama/llama_index)** | Data framework for building context-augmented LLM applications, RAG pipelines, and data agents. | <a href="https://github.com/run-llama/llama_index/stargazers"><img src="https://img.shields.io/github/stars/run-llama/llama_index?style=social&color=white" alt="LlamaIndex Stars"/></a> | RAG & Data Framework | MIT |
| **[Text Generation WebUI](https://github.com/oobabooga/text-generation-webui)** | Gradio-based desktop web interface for running local LLMs (supports Transformers, llama.cpp, ExLlama). | <a href="https://github.com/oobabooga/text-generation-webui/stargazers"><img src="https://img.shields.io/github/stars/oobabooga/text-generation-webui?style=social&color=white" alt="Text Generation WebUI Stars"/></a> | Local Desktop Web UI | AGPL-3.0 |
| **[Jan](https://github.com/janhq/jan)** | Open-source alternative to ChatGPT & LM Studio that runs 100% offline on local computers. | <a href="https://github.com/janhq/jan/stargazers"><img src="https://img.shields.io/github/stars/janhq/jan?style=social&color=white" alt="Jan Stars"/></a> | Local Desktop Assistant | AGPL-3.0 |
| **[DeepSpeed](https://github.com/microsoft/DeepSpeed)** | Deep learning optimization library for extreme scale distributed model training and offloading. | <a href="https://github.com/microsoft/DeepSpeed/stargazers"><img src="https://img.shields.io/github/stars/microsoft/DeepSpeed?style=social&color=white" alt="DeepSpeed Stars"/></a> | Distributed Training & Scaling | Apache 2.0 |
| **[LangGraph](https://github.com/langchain-ai/langgraph)** | Stateful, multi-actor agent orchestration framework with checkpointing, cycle support, and human-in-the-loop. | <a href="https://github.com/langchain-ai/langgraph/stargazers"><img src="https://img.shields.io/github/stars/langchain-ai/langgraph?style=social&color=white" alt="LangGraph Stars"/></a> | Production Stateful Agents | MIT |
| **[Ray](https://github.com/ray-project/ray)** | Unified distributed computing framework for scaling AI workloads, Ray Serve model inference, and fine-tuning. | <a href="https://github.com/ray-project/ray/stargazers"><img src="https://img.shields.io/github/stars/ray-project/ray?style=social&color=white" alt="Ray Stars"/></a> | Distributed Compute & Serving | Apache 2.0 |
| **[LocalAI](https://github.com/mudler/LocalAI)** | Drop-in OpenAI-compatible REST API for local, private inferencing without GPU requirements. | <a href="https://github.com/mudler/LocalAI/stargazers"><img src="https://img.shields.io/github/stars/mudler/LocalAI?style=social&color=white" alt="LocalAI Stars"/></a> | OpenAI-Compatible API | MIT |
| **[SGLang](https://github.com/sgl-project/sglang)** | High-performance serving framework with RadixAttention for fast structured generation and agentic workloads. | <a href="https://github.com/sgl-project/sglang/stargazers"><img src="https://img.shields.io/github/stars/sgl-project/sglang?style=social&color=white" alt="SGLang Stars"/></a> | Fast Structured Inference | Apache 2.0 |
| **[TRL (Transformer RL)](https://github.com/huggingface/trl)** | Hugging Face library for post-training alignment, RLHF, DPO, GRPO, and preference optimization. | <a href="https://github.com/huggingface/trl/stargazers"><img src="https://img.shields.io/github/stars/huggingface/trl?style=social&color=white" alt="TRL Stars"/></a> | Alignment & Post-Training | Apache 2.0 |
| **[Megatron-LM](https://github.com/NVIDIA/Megatron-LM)** | NVIDIA framework for large-scale GPU training using tensor, pipeline, and sequence parallelism. | <a href="https://github.com/NVIDIA/Megatron-LM/stargazers"><img src="https://img.shields.io/github/stars/NVIDIA/Megatron-LM?style=social&color=white" alt="Megatron-LM Stars"/></a> | Frontier-Scale Training | Shell License |
| **[BentoML](https://github.com/bentoml/BentoML)** | Unified model packaging, serving, and deployment framework for building scalable AI microservices. | <a href="https://github.com/bentoml/BentoML/stargazers"><img src="https://img.shields.io/github/stars/bentoml/BentoML?style=social&color=white" alt="BentoML Stars"/></a> | Model Serving & Microservices | Apache 2.0 |
| **[TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)** | NVIDIA library for optimizing LLM inference performance, throughput, and memory footprint on NVIDIA GPUs. | <a href="https://github.com/NVIDIA/TensorRT-LLM/stargazers"><img src="https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM?style=social&color=white" alt="TensorRT-LLM Stars"/></a> | GPU-Accelerated Inference | Apache 2.0 |
| **[Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl)** | Config-driven fine-tuning toolkit supporting full fine-tuning, LoRA, QLoRA, and FlashAttention. | <a href="https://github.com/OpenAccess-AI-Collective/axolotl/stargazers"><img src="https://img.shields.io/github/stars/OpenAccess-AI-Collective/axolotl?style=social&color=white" alt="Axolotl Stars"/></a> | YAML Config Fine-Tuning | Apache 2.0 |
| **[Phoenix](https://github.com/Arize-ai/phoenix)** | Open-source LLM observability, tracing, evaluation, and prompt engineering workspace by Arize AI. | <a href="https://github.com/Arize-ai/phoenix/stargazers"><img src="https://img.shields.io/github/stars/Arize-ai/phoenix?style=social&color=white" alt="Phoenix Stars"/></a> | Observability & Evaluation | ELv2 |
| **[SkyPilot](https://github.com/skypilot-org/skypilot)** | Open-source multi-cloud job orchestrator for running AI & LLM workloads across AWS, GCP, Azure, and OCI. | <a href="https://github.com/skypilot-org/skypilot/stargazers"><img src="https://img.shields.io/github/stars/skypilot-org/skypilot?style=social&color=white" alt="SkyPilot Stars"/></a> | Multi-Cloud GPU Orchestrator | Apache 2.0 |
| **[KServe](https://github.com/kserve/kserve)** | Standardized, Kubernetes-native model serving platform supporting scale-to-zero and MLOps workflows. | <a href="https://github.com/kserve/kserve/stargazers"><img src="https://img.shields.io/github/stars/kserve/kserve?style=social&color=white" alt="KServe Stars"/></a> | Kubernetes Model Serving | Apache 2.0 |

---

## ⚡ Quick Start Recommendations

| Goal | Recommended Starting Point |
|------|---------------------------|
| 💻 **Simple local / private LLM runtime** | **Ollama** + **Open WebUI** or **Jan** / **LM Studio** |
| ⚡ **Production high-throughput inference** | **vLLM** (or **SGLang** for structured output & agents) |
| 🌐 **Distributed training & serving at scale** | **Ray** + **Anyscale** (or pure open-source Ray) |
| 🎯 **Fast & efficient fine-tuning** | **Unsloth** or **Axolotl** |
| 🤖 **Enterprise private agents & RAG** | **LangGraph** + **LlamaIndex** + **vLLM** / **Dify** |
| ☸️ **Kubernetes-native serving** | **KServe** + **vLLM** |
| 🏎️ **Maximum NVIDIA GPU performance** | **TensorRT-LLM** + **NVIDIA NIM** (or open stack) |
| ☁️ **Full private cloud alternative** | Self-host **vLLM** + **Ray** + **Open WebUI** / **AnythingLLM** |
| 📑 **Private document chat & search** | **AnythingLLM** or **Dify** |

---

## ⭐ Star History

<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Private-LLM-Platform&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Private-LLM-Platform&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Private-LLM-Platform&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Private-LLM-Platform&type=date&legend=bottom-right" />
</picture>
</a>
</div>

---

## 🤝 Contributing

Contributions, corrections, and new open-source projects are welcome!  
Please open an issue or pull request to suggest additions.

---

**Last updated:** August 2026 📅  
Emphasizing open-source tools while documenting major commercial platforms for context.
