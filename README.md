# CN-COMM: Fine-Tuning for Cultural Competency in Chinese Communication

## Introduction
In a multicultural world, cultural competence
is a central skill to achieving effective communication across cultures. With large language models (LLMs) exhibiting biases towards Western values, there is a need to en-
hance these models to recognize and appropriately respond to cultural nuances. In this
paper, I focus on sensitivity to Chinese cultural customs in LLMs. I first explore the
tendency of the Llama2 model to generate responses aligning with Western tendencies in
communication. I then introduce CNCOMM-300,
a labeled dataset containing scenarios that
prompt for responses that align with Chinese
values. Its effectiveness is evaluated through
fine-tuning Llama2 with Low-Rank Adaptation (LoRA), producing llama-2-7b-cncomm.
Though the new model still exhibits some
shortcomings, it mitigates some initial concerns, showing that fine-tuning with new data is
promising for improving cultural competence
in biased LLMs. 

## Relevant Links
* dataset on huggingface: [CNNCOMM-300](https://huggingface.co/datasets/cheungra/CNCOMM-300/tree/main)
* fine-tuned model on huggingface: [llama-2-7b-cncomm](https://huggingface.co/cheungra/llama-2-7b-cncomm/tree/main)
* conference-style paper: [paper](https://drive.google.com/file/d/1j3-kXuPv9JkzUHyHs2s41N1G6DZCTcXo/view?usp=sharing)
* presentation slides: [slides](https://docs.google.com/presentation/d/1PbHaUbGgV78-kXos-dP1uRHgN6UDg-dgKI7aoHtcvRQ/edit?usp=sharing)

### Resources used:
- https://deci.ai/blog/fine-tune-llama-2-with-lora-for-question-answering/
- https://huggingface.co/meta-llama/Llama-2-7b-chat-hf
- https://huggingface.co/blog/llama2
- https://huggingface.co/docs/diffusers/en/training/lora
