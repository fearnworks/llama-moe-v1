MoE 4-bit Llama-v2 w/ QLora ELM Forest (BTM)

We are creating an MoE model by stitching together a bunch of QLora domain-specific adaptations on the base Llama v2 models. Each example during the inference would be routed through a set of QLora modules or their combination. This routing the main things that need to be learned in some way or the other. The goal is to solve an existing task better by using specialized domain experts. This is kind of an opensource and efficient attempt to mimic GPT4 with opensource Llama2 model.

Working document: https://docs.google.com/document/d/1YKDRCu7M9mflWrxKc1HeFs2HBWk4HXVrrOsLrIn6EXM/edit?usp=sharing


**Quantized Llama models:**
- 7B: Huggingface model tags for 7B models:
        TheBloke/Llama-2-7B-GGML
        Link: https://huggingface.co/TheBloke/Llama-2-7B-GGML
        TheBloke/Llama-2-7B-GPTQ
        Link: https://huggingface.co/TheBloke/Llama-2-7B-GPTQ



**Setup**
pip install -r requirements.txt

