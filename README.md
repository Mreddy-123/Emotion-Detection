# Emotion Detection with Multi-Label Classification: A Comparative Study Using Transformer Models

Introduction

This repository focuses on multi-label emotion detection using transformer models, where the task is to classify text data (such as tweets) into multiple emotion categories like anger, joy, sadness, and more. The project compares and analyzes the performance of several popular transformer-based models, including DistilBERT, Gemma-1.1-2b-it, and Mistral-7B. These models were fine-tuned and evaluated for their effectiveness in emotion classification tasks.


Models Used:

DistilBERT: A distilled version of the BERT model, known for its efficiency and faster inference while maintaining much of BERT's performance. It is a lightweight model, ideal for resource-constrained environments.

Gemma-1.1-2b-it: A robust pre-trained model for text classification tasks. This model has been fine-tuned with LoRA (Low-Rank Adaptation), an optimization technique that reduces the number of trainable parameters while maintaining performance.

Mistral-7B: A large-scale transformer model, known for its powerful performance on various natural language processing tasks. This model has been enhanced with PEFT (Parameter-Efficient Fine-Tuning) and quantization techniques for memory efficiency and fast inference.


Analysis Done:

Performance Comparison: We compare these models based on micro and macro F1-scores, accuracy, and evaluation loss to evaluate their effectiveness for multi-label emotion detection.

Optimization Techniques: The analysis also includes optimization methods like LoRA, PEFT, and quantization to improve model performance and computational efficiency.

This project offers insights into the trade-offs between model efficiency and performance, helping in selecting the right model for real-time applications or large-scale deployments in emotion detection tasks.


To View the final analysis visualizations, please navigate to the following links

WandB Links:

DistilBERT - https://wandb.ai/mani_utd/run_name/runs/x4mkspm1?nw=nwusermaniverthummala

Gemma- https://wandb.ai/mani_utd/emotions_kaggle_S2024/runs/u89t1ml9

Mistral 7B- https://wandb.ai/mani_utd/emotions_kaggle_S2024/runs/znruusv0

Mistral 7B with Quantization - https://wandb.ai/mani_utd/emotions_kaggle_S2024/runs/eehautoa


Please see the attached PDF for detailed analysis of the transformers models used and the Emotion Detection done using these models.
