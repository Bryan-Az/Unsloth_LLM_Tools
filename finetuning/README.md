# Finetuning & Continued Finetuning with Unsloth

In this repo, I finetune four models using Unsloth across a variety of machine learning use-cases. Unsloth allows access to finetune popular LLMs such as LlaMA 3.1, Phi-3.5, Gemma 2, Mistral... and more. They provide a method to apply LoRa finetuning and then convert Unsloth's LoRa Adapted models (useful for speeding up model training by freezing previously trained parameters and adding new trainable parameters) to GGML format (a C library for machine learning models that speeds up distribution and inference).

I also showcase how to implement continued finetuning from a custom checkpoint using the previously finetuned models that I've uploaded to the HuggingFace model repository.

## Models and Use-cases

All of the models will be finetuned using their 7B parameter AND 4-bit quantized version. Unsloth provides condensed and pre-trained models for specific tasks. I will further pretrain these models to leverage their pre-existing knowledge.


1. Qwen 2.5 | Multi-Lingual 'Ethical' Chat

2. Qwen 2.5 Math | Math Problem Solving 

3. Qwen 2.5 Coder | Code Generation in C#

4. CodeLLaMA  | Code Generation in Python 

