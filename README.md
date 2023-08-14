# FinetuningFalcon7B_QLORA
Fine-tuning a model like Falcon-7B for a specific task involves adapting the pretrained model by providing task-specific labeled data. The goal of this process is to make the language model more specialized and accurate in generating text or responses related to space science topics. By exposing the model to domain-specific data and allowing it to learn from the nuances of the space science domain, the finetuned LLM becomes better equipped to produce coherent and contextually relevant content in the realm of space science. This can result in improved performance when generating text, answering questions, or providing insights within the space science field.

Here I have fine-tuned the recent Falcon-7b model on a single Google colab.
I have leveraged PEFT library from Hugging Face ecosystem, as well as QLoRA for more memory efficient finetuning.

Dataset used is : sakharamg/AviationQA

