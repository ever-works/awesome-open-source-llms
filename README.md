# Open Source LLMs

A comprehensive directory of open source large language models, comparing architectures, benchmark performance, licensing, and deployment options


## 📑 Table of Contents

- [Foundation Models (30)](#foundation-models)
- [Code Generation Models (4)](#code-generation-models)
- [Multimodal Models (3)](#multimodal-models)
- [Small Language Models (3)](#small-language-models)
- [Instruction-Tuned Models (7)](#instruction-tuned-models)
- [Reasoning Models (1)](#reasoning-models)
- [Deployment Platforms (1)](#deployment-platforms)
- [Novel Architectures (1)](#novel-architectures)
- [Research Models (1)](#research-models)
- [Specialized Models (1)](#specialized-models)


## Foundation Models

- [DeepSeek V3](https://www.deepseek.com/) - A cutting-edge open-source LLM with 685 billion parameters released in December 2025 by Hangzhou-based DeepSeek AI. Features mixture-of-experts architecture with up to 128K token context window, excelling at reasoning, coding, and complex problem-solving tasks. ([Read more](/details/deepseek-v3.md)) `Mixture Of Experts` `Reasoning` `Coding`
- [GLM-4 (Zhipu AI)](https://www.zhipuai.cn/) - Zhipu AI's fourth-generation bilingual (Chinese-English) open-source language model, with GLM-4.7 achieving top rankings in early 2026 with exceptional coding (94.2 HumanEval) and mathematical reasoning (95.7 AIME 2025). Features 200K context window. ([Read more](/details/glm-4-zhipu-ai.md)) `Reasoning` `Coding` `Bilingual`
- [GPT-OSS-120B (OpenAI)](https://openai.com/) - OpenAI's first fully open-weight LLM since GPT-2, with 120 billion parameters matching or surpassing o4-mini on core benchmarks including AIME, MMLU, TauBench, and HealthBench. Marks OpenAI's return to open-source model development. ([Read more](/details/gpt-oss-120b-openai.md)) `Open Weights` `Reasoning` `Latest`
- [Kimi K2.5](https://www.moonshot.cn/) - Moonshot AI's latest open-source model released January 2026, achieving the highest open-source score on SWE-bench Verified (76.8%) and 96% on AIME 2025 mathematics, outperforming most proprietary alternatives in software engineering and mathematical reasoning. ([Read more](/details/kimi-k25.md)) `Software Engineering` `Reasoning` `Latest`
- [LLaMA 2 (Meta)](https://llama.meta.com/llama2/) - Meta's second-generation open-source foundation model family with 7B, 13B, and 70B variants, featuring improved training, safety alignment, and commercial licensing. Includes both base and Chat variants optimized for dialogue applications. ([Read more](/details/llama-2-meta.md)) `Foundation` `Commercial` `Safety Aligned`
- [LLaMA 3 (Meta)](https://llama.meta.com/) - Meta's third-generation open source large language model family, featuring improved efficiency, better reasoning abilities, and enhanced multi-turn dialogue understanding. Widely adopted by startups, enterprises, and research teams for its transparency, customization options, and strong performance across diverse tasks. ([Read more](/details/llama-3-meta.md)) `Transformer` `Open Weights` `Multilingual`
- [LLaMA 4 (Meta)](https://llama.meta.com/) - Meta's latest fourth-generation open source language model family released in April 2025, featuring Llama 4 Scout and Llama 4 Maverick variants. First iteration to use mixture-of-experts architecture, representing cutting-edge advancement in open source AI capabilities. ([Read more](/details/llama-4-meta.md)) `Mixture Of Experts` `Open Weights` `Latest`
- [MiMo-V2-Flash](https://www.minimax.com/) - Efficient open-source model that outperforms larger models like DeepSeek-V3.2 on software engineering benchmarks with roughly 1/2 to 1/3 the parameters. Features 262K context window and achieves 94.1 on AIME 2025 with superior parameter efficiency. ([Read more](/details/mimo-v2-flash.md)) `Efficient` `Software Engineering` `Long Context`
- [Mistral 7B](https://mistral.ai/news/announcing-mistral-7b/) - Mistral AI's flagship 7-billion-parameter model with exceptional performance-to-size ratio, outperforming LLaMA 2 13B on most benchmarks. Features sliding window attention for efficient long-context handling and Apache 2.0 license. ([Read more](/details/mistral-7b.md)) `Efficient` `High Performance` `apache-2.0`
- [Mistral Small 3](https://mistral.ai/) - A 24-billion-parameter open-source LLM from French startup Mistral AI, achieving performance comparable to 70B models while being 3x faster. Released under Apache 2.0 license, excelling in efficiency and multilingual tasks. ([Read more](/details/mistral-small-3.md)) `apache-2.0` `Efficient` `Multilingual`
- [Mixtral 8x22B](https://mistral.ai/news/mixtral-8x22b) - Mistral AI's larger sparse mixture-of-experts model with 141B total parameters, using only 39B active parameters. Achieves 77.8% on MMLU and 78.6% on GSM8K, excelling in coding and mathematics with cost-efficient performance. ([Read more](/details/mixtral-8x22b.md)) `Mixture Of Experts` `Coding` `Mathematics`
- [Mixtral 8x7B](https://mistral.ai/news/mixtral-of-experts/) - Mistral AI's sparse mixture-of-experts model using 8 expert networks with 7B parameters each, activating only 12.9B parameters per token. Outperforms LLaMA 2 70B on most benchmarks with 6x faster inference, featuring 32K context window. ([Read more](/details/mixtral-8x7b.md)) `Mixture Of Experts` `Efficient` `apache-2.0`
- [OLMo 3 (AI2)](https://allenai.org/olmo) - Allen Institute for AI's latest fully open language model family with 7B and 32B variants, featuring OLMo 3-Think (32B) as the best fully open 32B-scale thinking model. Represents America's truly open reasoning models with complete transparency in training data and process. ([Read more](/details/olmo-3-ai2.md)) `Fully Open` `Reasoning` `Transparent`
- [Qwen 3 (Alibaba Cloud)](https://qwenlm.github.io/) - Alibaba Cloud's next-generation open-source LLM family with models up to 110B parameters, excelling in multilingual tasks (supporting 119 languages), coding, and extended context understanding. Built for flexibility and scale with strong performance across diverse applications. ([Read more](/details/qwen-3-alibaba-cloud.md)) `Multilingual` `apache-2.0` `Coding`
- [Snowflake Arctic](https://www.snowflake.com/en/product/features/arctic/) - Enterprise-focused open-source LLM with 480B total parameters using Dense-MoE architecture, activating only 17B parameters. Excels at SQL generation, coding, and instruction following. Trained for under $2M in three months under Apache 2.0 license. ([Read more](/details/snowflake-arctic.md)) `Enterprise` `Mixture Of Experts` `Sql`
- [Baichuan 2](https://www.baichuan-ai.com/) - Baichuan Intelligence's 13-billion-parameter open-source language model based on Transformer architecture, trained on approximately 1.2 trillion tokens. Supports both Chinese and English with 4096 context window, commercially usable for bilingual applications. ([Read more](/details/baichuan-2.md)) `Bilingual` `Chinese` `apache-2.0`
- [BLOOM](https://bigscience.huggingface.co/) - BigScience's multilingual open-source language model with 176 billion parameters, supporting 46 natural languages and 13 programming languages. Created through international collaboration of over 1,000 researchers, representing one of the largest open multilingual LLMs. ([Read more](/details/bloom.md)) `Multilingual` `Collaborative` `Large Scale`
- [ChatGLM3](https://chatglm.cn/) - Zhipu AI's third-generation bilingual (Chinese-English) conversational model with enhanced capabilities, longer context support, and improved reasoning. Part of the GLM series with strong performance in Chinese language tasks and general dialogue. ([Read more](/details/chatglm3.md)) `Bilingual` `Chinese` `Conversational`
- [Command R (Cohere)](https://cohere.com/command) - Cohere's retrieval-augmented generation model optimized for enterprise RAG applications, conversational interaction, and long-context tasks. Designed for production deployments with strong instruction following and tool use capabilities. ([Read more](/details/command-r-cohere.md)) `Rag` `Enterprise` `Conversational`
- [DBRX (Databricks)](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm) - Databricks' open-source mixture-of-experts language model with 132 billion total parameters, setting new standards for open LLMs when released in 2024. Outperformed existing open models including LLaMA 2 and Mixtral on key benchmarks. ([Read more](/details/dbrx-databricks.md)) `Mixture Of Experts` `Commercial` `High Performance`
- [Falcon 2](https://falconllm.tii.ae/) - Technology Innovation Institute's transformer-based open-source model with 11 billion parameters, providing multimodal capabilities for both text and vision. Known for multilingual support and being fully open without heavy-handed safety filters. ([Read more](/details/falcon-2.md)) `Multimodal` `Multilingual` `apache-2.0`
- [GPT-J-6B (EleutherAI)](https://www.eleuther.ai/artifacts/gpt-j) - EleutherAI's 6-billion-parameter open-source autoregressive language model trained on The Pile dataset. At release, it was the largest publicly available GPT-3-style language model, pioneering accessible open-source alternatives to proprietary models. ([Read more](/details/gpt-j-6b-eleutherai.md)) `Open Source` `Community` `Historic`
- [GPT-NeoX-20B (EleutherAI)](https://github.com/EleutherAI/gpt-neox) - EleutherAI's 20-billion-parameter autoregressive language model trained using the GPT-NeoX library. Open-source model with Apache 2.0 license, supporting research and production use with strong general-purpose capabilities across diverse tasks. ([Read more](/details/gpt-neox-20b-eleutherai.md)) `Open Source` `Research` `apache-2.0`
- [InternLM 2](https://github.com/InternLM/InternLM) - Multilingual foundational language model developed by SenseTime and Shanghai AI Lab with 7B and 20B variants. Pre-trained on 1.6T tokens across 104B parameters, offering strong Chinese and multilingual capabilities for research and commercial applications. ([Read more](/details/internlm-2.md)) `Multilingual` `Chinese` `Research`
- [MiniMax (ABAB)](https://www.minimax.com/) - Chinese AI company's multimodal foundation models with strong commercial presence. Part of the 'AI tigers' group, offering text, voice, and vision capabilities for enterprise and consumer applications across the Chinese market. ([Read more](/details/minimax-abab.md)) `Multimodal` `Chinese` `Commercial`
- [Moonshot AI (Kimi)](https://www.moonshot.cn/) - Chinese AI startup's long-context language model with exceptional memory capabilities, supporting extremely long conversations and document processing. Part of China's 'AI tigers' group with strong commercial presence and advanced reasoning abilities. ([Read more](/details/moonshot-ai-kimi.md)) `Long Context` `Chinese` `Commercial`
- [MPT-7B (MosaicML)](https://www.mosaicml.com/mpt) - MosaicML's 7-billion-parameter transformer trained from scratch on 1T tokens of text and code. Open-source with commercial use license, matching LLaMA-7B quality. Includes variants like MPT-7B-Chat, MPT-7B-Instruct, and MPT-7B-StoryWriter with 65K context. ([Read more](/details/mpt-7b-mosaicml.md)) `Commercial` `Long Context` `Code`
- [OPT-175B (Meta)](https://opt.alpa.ai/) - Meta's 175-billion-parameter open-source model released for research, matching GPT-3 scale. Trained with fully documented process and released with training logs, providing transparency into large-scale language model development. ([Read more](/details/opt-175b-meta.md)) `Large Scale` `Research` `Transparent`
- [RedPajama-INCITE](https://www.together.ai/blog/redpajama) - Open-source model family from Together AI trained on the 1.2 trillion token RedPajama dataset. Includes 3B and 7B variants (base, chat, instruct) with Apache 2.0 license. RedPajama-3B outperforms GPT-Neo and Pythia-2.8B on benchmarks. ([Read more](/details/redpajama-incite.md)) `Open Data` `apache-2.0` `Commercial`
- [Yi 1.5 (01.AI)](https://www.01.ai/) - 01.AI's open-source language model excelling at handling long sequences and maintaining contextual coherence. Known as a dark horse model with strong coding capabilities and performance in long-context understanding tasks. ([Read more](/details/yi-15-01ai.md)) `Long Context` `Coding` `apache-2.0`

## Code Generation Models

- [Code Llama (Meta)](https://ai.meta.com/blog/code-llama-large-language-model-coding/) - Meta's specialized code generation model built on LLaMA 2, available in 7B, 13B, 34B, and 70B sizes. Features up to 100K token context window, trained on 500B tokens of code, with variants for Python specialization and instruction following. ([Read more](/details/code-llama-meta.md)) `Coding` `Specialized` `Long Context`
- [StarCoder (BigCode)](https://huggingface.co/bigcode/starcoder) - BigCode's 15.5-billion-parameter open-source code generation model trained on 1 trillion tokens from The Stack dataset. Supports 80+ programming languages with 8K context window, developed through collaboration of Hugging Face and ServiceNow. ([Read more](/details/starcoder-bigcode.md)) `Coding` `Open Source` `Multilingual`
- [StarCoder2](https://huggingface.co/bigcode/starcoder2) - Next-generation code model from BigCode with improved architecture and enhanced performance over StarCoder. Continues support for 80+ programming languages with better code generation, understanding, and multilingual capabilities. ([Read more](/details/starcoder2.md)) `Coding` `Next Gen` `Multilingual`
- [WizardCoder](https://wizardlm.github.io/WizardCoder/) - Code-specialized LLM using Evol-Instruct methodology for code generation. WizardCoder-33B-V1.1 achieves 79.9 pass@1 on HumanEval, surpassing Anthropic's Claude and Google's Bard. Built from deepseek-coder with exceptional programming capabilities. ([Read more](/details/wizardcoder.md)) `Coding` `Evol Instruct` `High Performance`

## Multimodal Models

- [LLaVA (Large Language-and-Vision Assistant)](https://llava-vl.github.io/) - Open-source multimodal model connecting vision encoder and LLM for general-purpose visual and language understanding. LLaVA-OneVision-1.5 achieves state-of-the-art performance on native-resolution images with lower training costs, leading multiple multimodal benchmarks. ([Read more](/details/llava-large-language-and-vision-assistant.md)) `Vision Language` `Multimodal` `Open Source`
- [Pixtral 12B](https://mistral.ai/news/pixtral-12b/) - Mistral AI's first multimodal model with 12B parameters, combining vision and language understanding. Significantly outperforms other open-source multimodal models like Qwen2-VL 7B and LLaVA-OneVision 7B in instruction following and visual understanding tasks. ([Read more](/details/pixtral-12b.md)) `Vision Language` `Multimodal` `Mistral`
- [StepFun (Step-1)](https://www.stepfun.com/) - Chinese AI startup specializing in multimodal models with strong vision-language capabilities. Part of the 'AI tigers' group, focusing on advanced visual understanding and reasoning for enterprise and consumer applications in the Chinese market. ([Read more](/details/stepfun-step-1.md)) `Multimodal` `Chinese` `Vision Language`

## Small Language Models

- [Gemma 3 (Google)](https://ai.google.dev/gemma) - Google's third-generation family of lightweight open models built from Gemini technology, available in 2B, 7B, 9B, 12B, and 27B sizes. Gemma-3-27B beats the original Gemini 1.5-Pro across benchmarks, offering state-of-the-art performance for small language models. ([Read more](/details/gemma-3-google.md)) `Efficient` `Google` `Multilingual`
- [Phi-4 (Microsoft)](https://azure.microsoft.com/en-us/products/phi-3) - Microsoft's 14-billion-parameter small language model released January 2025 under MIT license. Phi-4-reasoning-plus approaches full DeepSeek R1 performance on AIME 2025, with a 14B model rivaling a 671B model, making it the poster child for the small language model revolution. ([Read more](/details/phi-4-microsoft.md)) `Efficient` `Reasoning` `Mit License`
- [StableLM 3B](https://stability.ai/) - Stability AI's open-source language model with 3 billion parameters, trained on 1.5 trillion text tokens using an updated version of The Pile dataset. Released under CC BY-SA-4.0 for commercial use, achieving state-of-the-art performance at the 3B scale. ([Read more](/details/stablelm-3b.md)) `Efficient` `Open Source` `Lightweight`

## Instruction-Tuned Models

- [Hermes 3 (Nous Research)](https://nousresearch.com/hermes3/) - Nous Research's latest general-use model with advanced long-term context retention, multi-turn conversation capability, complex roleplaying abilities, and enhanced agentic function-calling. Available in multiple sizes based on LLaMA architecture. ([Read more](/details/hermes-3-nous-research.md)) `Conversational` `Function Calling` `Roleplaying`
- [Dolly 2.0 (Databricks)](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm) - Databricks' fully open-source instruction-following LLM built on EleutherAI's 12B model, fine-tuned with 15,000 human-generated instruction-response pairs. First truly open instruction-tuned model with commercially viable licensing and open training data. ([Read more](/details/dolly-20-databricks.md)) `Commercial` `Human Annotated` `Fully Open`
- [OpenAssistant](https://github.com/LAION-AI/Open-Assistant) - Community-driven open-source chat-based assistant from LAION-AI with 161,443 messages in 35 languages, created by 13,500+ volunteers. Provides conversation trees with quality ratings, enabling research on assistant-style dialogue and model alignment. ([Read more](/details/openassistant.md)) `Community Driven` `Multilingual` `Conversational`
- [Stanford Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html) - Stanford's instruction-tuned model built on LLaMA-7B, fine-tuned on 52,000 instruction-following examples generated using Self-Instruct with GPT-3.5. Demonstrated that high-quality instruction-tuned models could be created cost-effectively using synthetic data. ([Read more](/details/stanford-alpaca.md)) `Instruction Tuned` `Synthetic Data` `Fine Tuned`
- [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/) - Open-source chatbot built on LLaMA (7B and 13B) fine-tuned on 70,000 user-shared ChatGPT conversations from ShareGPT. Achieves 90%+ ChatGPT quality according to GPT-4 evaluations, representing early success in instruction-tuned open models. ([Read more](/details/vicuna.md)) `Chatbot` `Instruction Tuned` `Fine Tuned`
- [WizardLM](https://github.com/nlpxucan/WizardLM) - Microsoft and Peking University's open-source LLM trained using the Evol-Instruct methodology to automatically generate complex instructions. WizardLM-2 variants based on Mixtral 8x22B, available in 8x22B, 70B, and 7B sizes with advanced instruction-following capabilities. ([Read more](/details/wizardlm.md)) `Instruction Tuned` `Evol Instruct` `Microsoft`
- [Zephyr 7B](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta) - HuggingFace H4's instruction-tuned chatbot model based on Mistral-7B, trained using Direct Preference Optimization (DPO) on public synthetic datasets. Available in Alpha and Beta versions, demonstrating effective alignment through DPO methodology. ([Read more](/details/zephyr-7b.md)) `Chatbot` `Dpo` `Mistral Based`

## Reasoning Models

- [Orca 2 (Microsoft)](https://www.microsoft.com/en-us/research/project/orca/) - Microsoft Research's reasoning-focused LLM fine-tuned from LLaMA 2, available in 7B and 13B sizes. Teaches various reasoning strategies and achieves performance levels similar to models 5-10x larger on complex reasoning tasks through innovative training methodology. ([Read more](/details/orca-2-microsoft.md)) `Reasoning` `Microsoft` `Efficient`

## Deployment Platforms

- [GPT4All](https://gpt4all.io/) - Nomic AI's ecosystem for running LLMs locally on consumer hardware, featuring optimized inference engine and collection of open-source models. Enables private, offline AI with CPU-friendly execution and easy-to-use desktop application. ([Read more](/details/gpt4all.md)) `Local Inference` `Privacy` `Cpu Friendly`

## Novel Architectures

- [RWKV](https://github.com/BlinkDL/RWKV-LM) - Receptance Weighted Key Value model with RNN-like architecture enabling infinite sequence length while maintaining transformer-level performance. Available in sizes from 169M to 14B parameters, trained on The Pile with linear computational complexity. ([Read more](/details/rwkv.md)) `Rnn Transformer Hybrid` `Efficient` `Long Context`

## Research Models

- [Pythia (EleutherAI)](https://github.com/EleutherAI/pythia) - EleutherAI's first LLM suite designed specifically for scientific research on learning dynamics. Features 154 checkpoints saved throughout training across multiple model sizes, enabling detailed study of how knowledge develops during training. ([Read more](/details/pythia-eleutherai.md)) `Research` `Interpretability` `Open Science`

## Specialized Models

- [WizardMath](https://github.com/nlpxucan/WizardLM) - Mathematics-specialized LLM using Evol-Instruct methodology adapted for mathematical problems. Achieves exceptional performance on math benchmarks through progressive problem complexity evolution and high-quality mathematical reasoning training. ([Read more](/details/wizardmath.md)) `Mathematics` `Reasoning` `Specialized`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This directory may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this directory, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg