# 🔧 Finetuning Large Language Models (LLMs)

This project is based on the **Finetuning Large Language Models** short course by [DeepLearning.AI](https://www.deeplearning.ai/short-courses/fine-tuning-large-language-models/), taught by Sharon Zhou, CEO of Lamini. It demonstrates my hands-on experience with customizing LLMs using supervised finetuning techniques.

## 📌 Project Purpose

In this portfolio project, I explore how to fine-tune a pre-trained language model on custom data to improve model performance and adapt it to specific tasks or writing styles. Finetuning goes beyond prompt engineering by updating the model's weights, enabling it to learn domain-specific patterns and knowledge.

## 🚀 What I Accomplished

- 📊 **Prepared** and preprocessed domain-specific datasets for LLM finetuning.
- 🧠 **Trained** a large language model using Hugging Face tools with low-rank adaptation (LoRA) for efficient tuning.
- 🧪 **Evaluated** model performance using accuracy, loss metrics, and qualitative comparisons.
- 🔁 **Compared** finetuning to prompt engineering and RAG (Retrieval-Augmented Generation) methods.

## 🧠 Key Learning Outcomes

- Understand when and why to apply finetuning on LLMs.
- Set up a finetuning pipeline using `transformers`, `datasets`, and `accelerate`.
- Adapt LLMs to domain-specific tasks with limited data.
- Balance performance and efficiency using PEFT (Parameter-Efficient Fine-Tuning) techniques.

## 🛠 Tools and Libraries

- **Transformers**, **Datasets**, **Accelerate**, **PEFT** (Hugging Face)
- **PyTorch**
- **Pandas**, **NumPy**, **Scikit-learn**
- Jupyter Notebook

## 📌 Sample Use Case

In this project, I finetuned an LLM to adapt it to a domain-specific writing style (e.g., customer support emails or legal texts). The model showed improved coherence and contextual accuracy compared to zero-shot prompting.

## 🧪 Evaluation Metrics

- Training and validation loss
- Qualitative output comparisons
- Token-level accuracy
- Inference quality against baseline model
