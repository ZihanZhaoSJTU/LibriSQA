# LibriSQA
<div align="center">
    <img src="https://github.com/ZihanZhaoSJTU/LibriSQA/blob/main/overview.png" width="600">
</div>

The official codes for [**LibriSQA: Advancing Free-form and Open-ended Spoken Question Answering with a Novel Dataset and Framework**](https://arxiv.org/pdf/2308.10390.pdf) 

While Large Language Models (LLMs) have demonstrated commendable performance across a myriad of domains and tasks, existing LLMs still exhibit a palpable deficit in handling multimodal functionalities, especially for the Spoken Question Answering (SQA) task which necessitates precise alignment and deep interaction between speech and text features. To address the SQA challenge on LLMs, we initially curated the free-form and open-ended LibriSQA dataset from Librispeech, comprising Part I with natural conversational formats and Part II encompassing multiple-choice questions followed by answers and analytical segments. Both parts collectively include 107k SQA pairs that cover various topics. Given the evident paucity of existing speech-text LLMs, we propose a lightweight, end-to-end framework to execute the SQA task on the LibriSQA, witnessing significant results. By reforming ASR into the SQA format, we further substantiate our framework's capability in handling ASR tasks. Our empirical findings bolster the LLMs' aptitude for aligning and comprehending multimodal information, paving the way for the development of universal multimodal LLMs.

We have released the dataset. The code will be released soon.

## Usage
### 1. Download the speech from LibriSpeech
Training: https://www.openslr.org/resources/12/train-clean-360.tar.gz

testing: https://www.openslr.org/resources/12/test-clean.tar.gz
### 2. Download LibriSQA
The dataset is available at [Huggingface](https://huggingface.co/datasets/ZihanZhao/LibriSQA)

## Model
<div align="center">
    <img src="https://github.com/ZihanZhaoSJTU/LibriSQA/blob/main/model.png" width="600">
</div>


## Acknowledgement
LibriSpeech: An ASR corpus based on public domain audio books: -- https://ieeexplore.ieee.org/abstract/document/7178964

LLaMA: Open and Efficient Foundation Language Models -- https://arxiv.org/abs/2302.13971

LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention -- https://arxiv.org/abs/2303.16199

PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering -- https://arxiv.org/abs/2305.10415

We thank the authors for their great idea and open-sourced code which helped us with this paper.

## Contribution

Please raise an issue if you need help, any contributions are welcomed.
