# OpenLM Awesomes

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![](https://img.shields.io/badge/Last%20Update-Apr%2018,%202023-blue.svg)


An up-to-date awesome list of open-source large language models, instruction & RLHF datasets and high-performance codebases.

 - [Open Large Language Models](#Open-Large-Language-Models)
 - [Open Instruction-following Large Language Models](#Open-Instruction-following-Large-Language-Models)
 - [Open Instruction Tuning and RLHF Datasets](#Open-Instruction-Tuning-and-RLHF-Datasets)
 - [High-performance Open Instruction Tuning Codebase](#High-performance-Open-Instruction-Tuning-Codebase)


## Open Large Language Models

| Model | Stars | Organization | Language[^1] | Checkpoints |
| --- | --- | --- | --- | --- |
| [LLaMa](https://github.com/facebookresearch/llama)[^2] | ![](https://img.shields.io/github/stars/facebookresearch/llama.svg) | Meta AI | Multi-Lang | [7B](https://huggingface.co/decapoda-research/llama-7b-hf) & [13B](https://huggingface.co/decapoda-research/llama-13b-hf) & [30B](https://huggingface.co/decapoda-research/llama-30b-hf) & [65B](https://huggingface.co/decapoda-research/llama-65b-hf) |
| [OPT](https://github.com/facebookresearch/metaseq) | ![](https://img.shields.io/github/stars/facebookresearch/metaseq.svg) | Meta AI | Eng. |  [125M](https://huggingface.co/facebook/opt-125m) & [350M](https://huggingface.co/facebook/opt-350m) & [1.3B](https://huggingface.co/facebook/opt-1.3b) & [2.7B](https://huggingface.co/facebook/opt-2.7b) & [6.7B](https://huggingface.co/facebook/opt-6.7b) & [13B](https://huggingface.co/facebook/opt-13b) & [30B](https://huggingface.co/facebook/opt-30b) & [66B](https://huggingface.co/facebook/opt-66b) & 175B[^3] |
| [BLOOM](https://huggingface.co/bigscience/bloom) | -- | BigScience | Multi-Lang | [560m](https://huggingface.co/bigscience/bloom-560m) & [1.1B](https://huggingface.co/bigscience/bloom-1b1) & [1.7B](https://huggingface.co/bigscience/bloom-1b7) & [3B](https://huggingface.co/bigscience/bloom-3b) & [7.1B](https://huggingface.co/bigscience/bloom-7b1) & [176B](https://huggingface.co/bigscience/bloom) |
| [GLM](https://github.com/THUDM/GLM-130B)[^4] | ![](https://img.shields.io/github/stars/THUDM/GLM-130B.svg) | Tsinghua | CHI. & Eng. | [2B](https://huggingface.co/THUDM/glm-2b) & [10B](https://huggingface.co/THUDM/glm-10b) & 130B[^5] |


[^1]: Languages used in pretraining texts. CHI is short for Chinese. Eng is short for English.

[^2]: Direct access to the LLaMa models is currently not possible due to Meta AI's policies. However, interested individuals can apply to access the models by filling out a form, which can be found at [here](https://github.com/facebookresearch/llama). Alternatively, the checkpoints for the LLaMa models can be accessed via the following link on the [Decapoda Research](https://huggingface.co/decapoda-research) page of Huggingface.

[^3]: Direct access to the OPT models with 176B params is currently not possible due to Meta AI's policies. However, interested individuals can apply to access the models by filling out a form, which can be found at [here](https://github.com/facebookresearch/metaseq/tree/main/projects/OPT).

[^4]: There are other GLM models (with different pretraining corpus) that are available at the [THUDM](https://huggingface.co/models?other=glm,thudm) page of Huggingface. GLM models include different size: 10B/2B/515M/410M/335M/110M (English), 10B/335M (Chinese). In above Table, GLM models with Engilish are provided.

[^5]: Direct access to the GLM model with 130B params is currently not possible due to THUDM's policies. However, interested individuals can apply to access the models by filling out a form, which can be found at [here](https://github.com/THUDM/GLM-130B).

## Open Instruction-following Large Language Models

| Model | Stars | Organization | Based Model | Checkpoints |
| --- | --- | --- | --- | --- |
| [BLOOMZ](https://huggingface.co/bigscience/bloomz) | -- | BigScience | BLOOM | [560m](https://huggingface.co/bigscience/bloomz-560m) &  [1.1B](https://huggingface.co/bigscience/bloomz-1b1) & [1.7B](https://huggingface.co/bigscience/bloomz-1b7) & [3B](https://huggingface.co/bigscience/bloomz-3b) & [7.1B](https://huggingface.co/bigscience/bloomz-7b1) & [176B](https://huggingface.co/bigscience/bloomz) |
| [Alpaca](https://github.com/tatsu-lab/stanford_alpaca) | ![](https://img.shields.io/github/stars/tatsu-lab/stanford_alpaca.svg) | Stanford | LLaMa | [7B](https://huggingface.co/tatsu-lab/alpaca-7b-wdiff) |
| [Vicuna](https://vicuna.lmsys.org/) | ![](https://img.shields.io/github/stars/lm-sys/FastChat.svg) | lm-sys | LLaMa | [7B](https://huggingface.co/lmsys) & [13B](https://huggingface.co/lmsys) |
| [Chinese-Vicuna](https://github.com/Facico/Chinese-Vicuna) | ![](https://img.shields.io/github/stars/Facico/Chinese-Vicuna.svg) | Facico | LLaMa | [7B](https://huggingface.co/Facico/Chinese-Vicuna-lora-7b-3epoch-belle-and-guanaco) |


## Open Instruction Tuning and RLHF Datasets

| Dataset | Language | #Samples |Annotation Type | Online Link |
| -- | --- | --- | --- | --- |
| alpaca_chinese_dataset | Chinese | 52K | GPT-generated & Human-annotated | [hikariming/alpaca_chinese_dataset](https://github.com/hikariming/alpaca_chinese_dataset) |
| BELLE/data | Chinese | 1.5M | GPT-generated | [BELLE/data/1.5M](https://github.com/LianjiaTech/BELLE/tree/main/data/1.5M) |
| pCLUE | Chinese | 1.2M | Formated from Existing Datasets | [CLUEbenchmark/pCLUE](https://github.com/CLUEbenchmark/pCLUE) |
| Med-ChatGLM/data | Chinese | 7K | GPT-generated | [SCIR-HI/Med-ChatGLM](https://github.com/SCIR-HI/Med-ChatGLM) |
| COIG | Chinese | 181K | Follow this [paper](https://arxiv.org/abs/2304.07987) | [BAAI/COIG](https://huggingface.co/datasets/BAAI/COIG) |


## High-performance Open Instruction Tuning Codebase

 - [**DeepSpeed Chat**](https://github.com/microsoft/DeepSpeed/tree/master/blogs/deepspeed-chat): Easy, Fast and Affordable RLHF Training of ChatGPT-like Models at All Scales
 - [**ColossalChat**](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat) is a project to implement LLM with RLHF, powered by the Colossal-AI project.
 - [**LMFlow**](https://github.com/OptimalScale/LMFlow): An extensible, convenient, and efficient toolbox for finetuning large machine learning models, designed to be user-friendly, speedy and reliable, and accessible to the entire community.