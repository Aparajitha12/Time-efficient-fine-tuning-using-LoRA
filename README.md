# Time-Efficient Fine-Tuning Using LoRA vs Full Model

This project presents a comparative analysis between full fine-tuning and parameter-efficient fine-tuning (LoRA) on the DistilBERT model using the SST-2 sentiment classification dataset.

It demonstrates how LoRA can significantly reduce the number of trainable parameters and training time, while achieving near-baseline accuracy. All results are reproducible, visualized, and summarized.

---

## Features

- Fine-tuning DistilBERT with and without LoRA (PEFT)
- Parameter-efficient training using Hugging Face PEFT
- Runtime and parameter efficiency visualizations
- Clean project structure with exportable model files and logs
- Reproducible results using controlled seeds

---

## Setup and Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Aparajitha12/lora-vs-baseline-finetuning.git
   cd lora-vs-baseline-finetuning
