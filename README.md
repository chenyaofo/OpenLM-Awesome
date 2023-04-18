# OpenLM-Awesome

## Open Large Language Models

| Model | Stars | Organization | Language[^1] | Style | Checkpoints |
| --- | --- | --- | --- | --- | --- |
| [LLaMa](https://github.com/facebookresearch/llama)[^2] | ![](https://img.shields.io/github/stars/facebookresearch/llama.svg) | Meta AI | Multi-Language | Decoder-style | [7B](https://huggingface.co/decapoda-research/llama-7b-hf) & [13B](https://huggingface.co/decapoda-research/llama-13b-hf) & [30B](https://huggingface.co/decapoda-research/llama-30b-hf) & [65B](https://huggingface.co/decapoda-research/llama-65b-hf) |
| [OPT](https://github.com/facebookresearch/metaseq) | ![](https://img.shields.io/github/stars/facebookresearch/metaseq.svg) | Meta AI | English | Decoder-style | [125M](https://huggingface.co/facebook/opt-125m) & [350M](https://huggingface.co/facebook/opt-350m) & [1.3B](https://huggingface.co/facebook/opt-1.3b) & [2.7B](https://huggingface.co/facebook/opt-2.7b) & [6.7B](https://huggingface.co/facebook/opt-6.7b) & [13B](https://huggingface.co/facebook/opt-13b) & [30B](https://huggingface.co/facebook/opt-30b) & [66B](https://huggingface.co/facebook/opt-66b) & 175B[^3] |
| [BLOOM](https://huggingface.co/bigscience/bloom) | -- | BigScience | Multi-Language | Decoder-style | [560m](https://huggingface.co/bigscience/bloom-560m) & [1.1B](https://huggingface.co/bigscience/bloom-1b1) & [1.7B](https://huggingface.co/bigscience/bloom-1b7) & [3B](https://huggingface.co/bigscience/bloom-3b) & [7.1B](https://huggingface.co/bigscience/bloom-7b1) & [176B](https://huggingface.co/bigscience/bloom) |
| [GLM](https://github.com/THUDM/GLM-130B)[^4] | ![](https://img.shields.io/github/stars/THUDM/GLM-130B.svg) | Tsinghua | Chinses & English | GLM-style | [2B](https://huggingface.co/THUDM/glm-2b) & [10B](https://huggingface.co/THUDM/glm-10b) & 130B[^5] |


[^1]: Languages used in pretraining texts.

[^2]: Direct access to the LLaMa models is currently not possible due to Meta AI's policies. However, interested individuals can apply to access the models by filling out a form, which can be found at [here](https://github.com/facebookresearch/llama). Alternatively, the checkpoints for the LLaMa models can be accessed via the following link on the [Decapoda Research](https://huggingface.co/decapoda-research) page of Huggingface.

[^3]: Direct access to the OPT models with 176B params is currently not possible due to Meta AI's policies. However, interested individuals can apply to access the models by filling out a form, which can be found at [here](https://github.com/facebookresearch/metaseq/tree/main/projects/OPT).

[^4]: There are other GLM models (with different pretraining corpus) that are available at the [THUDM](https://huggingface.co/models?other=glm,thudm) page of Huggingface. GLM models include different size: 10B/2B/515M/410M/335M/110M (English), 10B/335M (Chinese). In above Table, GLM models with Engilish are provided.

[^5]: Direct access to the GLM model with 130B params is currently not possible due to THUDM's policies. However, interested individuals can apply to access the models by filling out a form, which can be found at [here](https://github.com/THUDM/GLM-130B).