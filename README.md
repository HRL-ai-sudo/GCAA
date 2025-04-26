# MTLF
This is a project about Multi-task Two-stage Learning Framework (MTLF)

# Introduction
We revisit the multi-task collaborative learning in MSA. Specifically, we incorporate a teacher-student learning paradigm (knowledge distillation) to address the challenge of scarce unimodal labels, and propose the TLS as an alternative to traditional self-supervised label generation techniques. This involves leveraging the multimodal representation (teacher) to guide the learning process of the unimodal representation (student).

# Usage
Here is how to run the code.

## Requirement
* Python 3.8.0
* Pytorch 1.2.0
* CUDA 11.6
* tqdm 4.65.0
* transformers 4.28.1

## Train
Begin training.
* Dataset: get in the *DATA* file.
* Epoch: 50.
* Learning rate: 1e-5.
* Dropout : 0.

