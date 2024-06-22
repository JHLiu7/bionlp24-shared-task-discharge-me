# BioNLP 2024 Shared Task: "Discharge Me!"

This repo contains model checkpoints and inference scripts used for submissions by e-Health CSIRO to the Shared Task on generating discharge summary sections ([Discharge Me!](https://stanford-aimi.github.io/discharge-me/)), including brief hospital course (BHC) and discharge instruction (DI).



|                                      | Link                                                      |
| ------------------------------------ | --------------------------------------------------------- |
| PRIMERA: fully fine-tuned for BHC    | https://huggingface.co/jhliu/DischargeGen-PRIMERA-BHC     |
| PRIMERA: fully fine-tuned for DI     | https://huggingface.co/jhliu/DischargeGen-PRIMERA-DI      |
| Llama3: fine-tuned with LoRA for BHC | https://huggingface.co/jhliu/DischargeGen-Llama3-lora-BHC |
| Llama3: fine-tuned with LoRA for DI  | https://huggingface.co/jhliu/DischargeGen-Llama3-lora-DI  |



Examples on how to use these trained checkpoints for inference can be found at [`example.ipynb`](https://github.com/JHLiu7/bionlp24-shared-task-discharge-me/blob/main/example.ipynb), which shows how we prepare the text and use the prior content of the discharge summary as input to generate `BHC` and `DI`. 

 
