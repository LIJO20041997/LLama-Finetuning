### 1 Fine tunning using unsloth/Llama-3.2-1B-Instruct quantized model
    - A simple fine tunning task using unsloth with the "yahma/alpaca-cleaned" dataset from hugging face 
        - Used peft for parameter efficient training
        - Formatted the prompt
        - Used SFTTrainer to fine-tune the model with formatted data.
        - finetunned and saved the model locally 
    
