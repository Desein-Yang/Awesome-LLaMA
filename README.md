# Awesome-LLaMA

<a href="https://github.com/sindresorhus/123"><img src="https://camo.githubusercontent.com/abb97269de2982c379cbc128bba93ba724d8822bfbe082737772bd4feb59cb54/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667"></a>

Awesome-LLaMA is a curated list of open-source projects related to LLaMA. LLaMA is a series of generative language models released by MetaAI, which has gained significant influence and gradually improved its ecosystem in the field of GenAI. We aim to help learning, growth, and communication by discovering and promoting influential projects centered around LLaMA. Welcome to Contribute !


Awesome-LLaMA 是一个关于 LLaMA 的精选开源项目列表。LLaMA 是一系列由 MetaAI 开源发布的生成式大语言模型，在 GenAI 领域拥有很高的影响力和逐步完善的生态。我们希望通过发现和推广围绕 LLaMA 的有影响力项目帮助学习、成长、交流。

本仓库既包括在 LLaMA 上进行二次开发和迁移的**模型**项目，如二次训练，语言迁移、垂直领域迁移和其他模态任务，也包括围绕 LLaMA 的完善**方案**，如私有化部署、推理加速、交互界面、外接检索等。持续完善中，欢迎 contribute。



## Contents

- 模型
    - 中文迁移
    - 领域迁移
    - 多模态迁移
- 方案
    - 推理加速
    - 部署交互
    - AI Agents

### 中文迁移

1. [Ziya-llama-13B-v1](https://huggingface.co/IDEA-CCNL/Ziya-LLaMA-13B-v1) ![Static Badge](https://img.shields.io/badge/stars-3.3k-blue) 基于 llama-1 的 13B 中文通用模型（CPT+SFT+RLHF）
2. [Chinese llama alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca) ![Static Badge](https://img.shields.io/badge/stars-14.2k-blue)  基于 llama-1,2 的 7B，13B，33B 中文通用模型（CPT+ SFT+RLHF）
3. [Chinese-Vicuna](https://github.com/Facico/Chinese-Vicuna) ![Static Badge](https://img.shields.io/badge/stars-4k-blue)基于 llama-1 少参数微调的 7，13B 中文通用（SFT+lora）模型，支持 4，8bit
4. [Linly: Chinese-LLaMA-1&2](https://github.com/CVI-SZU/Linly) ![Static Badge](https://img.shields.io/badge/stars-2.7k-blue)基于 llama-1,2 的 7，13B 中文通用模型，也训了openllama, falcon 等模型
5. [Luotuo-Chinese-LLM](https://github.com/LC1332/Luotuo-Chinese-LLM) ![Static Badge](https://img.shields.io/badge/stars-3.3k-blue) 基于 llama-1 的 13B 中文通用模型（SFT+lora）

### 领域迁移


1. [QiZhenGPT](https://github.com/CMKRG/QiZhenGPT) ![Static Badge](https://img.shields.io/badge/stars-424-blue)医学领域，基于Chinese-llama-alpaca 7，13B模型开发
2. [MedicalGPT](https://github.com/shibing624/MedicalGPT)  ![Static Badge](https://img.shields.io/badge/stars-1.4k-blue)医学领域，基于ziya-llama-13b 和 baichuan 13b 的模型 (CPT+SFT+RLHF)
3. [Chatlaw](https://github.com/PKU-YuanGroup/ChatLaw)  ![Static Badge](https://img.shields.io/badge/stars-4.8k-blue) 法律领域，基于ziya-llama-13b 和 anima-33b 微调的模型(lora)
4. [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT)  ![Static Badge](https://img.shields.io/badge/stars-8.1k-blue) 金融领域，基于 llama 和 GLM 在中美金融市场的数据微调的 13B 模型（SFT+lora+RLHF）
5. [EduGPT](https://github.com/hqanhh/EduGPT) ![Static Badge](https://img.shields.io/badge/stars-257-blue) 教育领域，基于 llama-1 的13B 模型（CPT+SFT+RLHF）

### 多模态迁移

- [Video-LLaMA](https://github.com/DAMO-NLP-SG/Video-LLaMA) ![Static Badge](https://img.shields.io/badge/stars-1.5k-blue)  🔥 视频指令理解模型，语言模型基于 llama 模型指令微调
- [LLaVA](https://github.com/haotian-liu/LLaVA) ![Static Badge](https://img.shields.io/badge/stars-4.8k-blue) 语言-视觉理解模型，语言模型基于 llama 

### 推理加速


1. [llama.cpp](https://github.com/ggerganov/llama.cpp) ![Static Badge](https://img.shields.io/badge/stars-39.6k-blue) 纯 c/c++ 实现 llama 模型推理加速
2. [lit-llama](https://github.com/Lightning-AI/lit-llama) ![Static Badge](https://img.shields.io/badge/stars-5.1k-blue) 实现 llama 支持 flash, 4bit, 8bit, GPTQ 4bit 量化的推理加速
3. [llama2.c](https://github.com/karpathy/llama2.c) ![Static Badge](https://img.shields.io/badge/stars-11.4k-blue) 纯c单文件极简实现llama2 推理加速
4. [llama2.rs](https://github.com/srush/llama2.rs) ![Static Badge](https://img.shields.io/badge/stars-655-blue) 🔥 纯rust 语言实现 llama2 推理加速
5. [llama2-cpu](https://github.com/kennethleungty/Llama-2-Open-Source-LLM-CPU-Inference)  ![Static Badge](https://img.shields.io/badge/stars-744-blue)支持 cpu 上推理量化 llama2

### 部署交互

1. [dalai](https://github.com/cocktailpeanut/dalai) ![Static Badge](https://img.shields.io/badge/stars-28k-blue) 一键本地部署 llama，支持跨平台部署，支持 llama.cpp
2. [text-generation-webui](https://github.com/oobabooga/text-generation-webui)  ![Static Badge](https://img.shields.io/badge/stars-22.4k-blue) 基于 Web UI 的文本生成界面一键部署方案，支持 llama, GPT-Q
3. [llama-gpt](https://github.com/getumbrel/llama-gpt) ![Static Badge](https://img.shields.io/badge/stars-7.8k-blue) 类 chatgpt 的私有化部署方案，支持 code llama，支持 Mac M1 
### AI Agents

- [llm-index](https://github.com/jerryjliu/llama_index) ![Static Badge](https://img.shields.io/badge/stars-20.7k-blue)  支持 llama 模型做工具/检索增强的方案，支持多种数据检索(APIs, PDFs, docs, SQL, etc.)
- [llama-lab](https://github.com/run-llama/llama-lab) ![Static Badge](https://img.shields.io/badge/stars-867-blue) 🔥对标 AutoGPT ，基于 llama 模型做的 langchain 方案，支持 llama-index 
- [llm-chain](https://github.com/sobelio/llm-chain) ![Static Badge](https://img.shields.io/badge/stars-807-blue) 基于 rust 语言的 llama  langchain 方案
- [llama-hub](https://github.com/emptycrown/llama-hub) ![Static Badge](https://img.shields.io/badge/stars-2.3k-blue) 一系列社区支持的系列 API 工具，支持 llama index








## Contributing
We welcome contributions from the community to help expand and enrich the Awesome-LLaMA repository. If you have come across an interesting project, tool, or resource that is relevant to LLaMA, please feel free to submit a pull request. Together, let's build a comprehensive resource for the LLaMA community!

我们欢迎社区的贡献，以帮助扩展和丰富Awesome-LLaMA 仓库。如果您发现了与 LLaMA 相关的有趣项目、工具或资源，请随时提交拉取请求。让我们共同建立一个为 LLaMA 社区服务的综合资源！

To contribute, please follow these guidelines:

- Fork and create your branch. 
- Ensure your contribution adheres to the established format and categories.
- Provide a brief description and include the necessary links to the project/repository.
- Submit a pull request, and we will review.


要进行贡献，请遵循以下准则：

- Fork 该仓库并从 main 分支创建您的分支。
- 确保您的贡献符合已建立的格式和分类。
- 提供简要描述，并包含指向项目/仓库的必要链接。
- 提交拉取请求，我们将会审查您的提交。


