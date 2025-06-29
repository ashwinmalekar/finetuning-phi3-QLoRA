# finetuning-phi3-QLoRA
Finetuning Phi-3 (SLM) using parameter efficient finetuning(PEFT) method - QLoRA on the SQuAD dataset


Finetuning a LLM/SLM can help you ehance your AI workflow with regards to inference quality. With finetuning, you tune the language model's weights to adapt to your domain and pick its nuances. 
Its like your own in-house developed language model, except you did not have to spend a fortune on it. 

Although full-finetuning of a language model is not very cost efficient, imagine updating 400 Billion weights on your local 8Gb RAM!

Hence, here I showcase a parameter-efficient finetuning method. With Quantization - QLoRA (Quantized Low-Rank Adapters)

read more about QLoRA here: https://medium.com/@dillipprasad60/qlora-explained-a-deep-dive-into-parametric-efficient-fine-tuning-in-large-language-models-llms-c1a4794b1766

I have picked up Phi-3-3.8B from Microsoft as it's a small language model and performs very well on reasoning & conversational instruction based tasks.

Refer to the notebook. 

Thank you - Ashwin 
