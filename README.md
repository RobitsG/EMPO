# Mitigating Hallucinations in Large Vision-Language Models via Entity-Centric Multimodal Preference Optimization

This repository provides the code and data for EMPO, which achieves enhanced modality alignment than existing human preference alignment methods(e.g., DPO).

## Introduction

**Illustration of EMPO.** (1) At the data level, we construct a fine-grained preference alignment dataset across three aspects: image, instruction condition, and model response. (2) At the method level, we propose entity-centric multimodal preference optimization for aligning image contents with semantic concepts.
![Illustration of EMPO](./asserts/framework.png)

**Attention weight heatmaps** of outputs to image and instruction tokens from LLaVA-1.5 and EMPO. The hallucinated tokens are highlighted in red. The image is tokenized into 4×4 patches (above the red dash line).
![Attention weight heatmaps](./asserts/case2.png)

#### The code and dataset will be released after the paper is accepted.
