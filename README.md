# Arabic Medical QA with Fine-Tuned LLaMA 3.2-3B
## Overview
This project focuses on adapting a Large Language Model (LLM), LLaMA 3.2-3B, for Arabic medical question-answering (QA). Leveraging a subset of the Arabic Healthcare Dataset (AHD), the study demonstrates how fine-tuning LLMs can address the challenges of low-resource languages and specialized domains like healthcare.

## Key Features
Fine-tuned LLaMA 3.2-3B on 3,000 samples of Arabic medical QA data using parameter-efficient techniques.
Evaluation through three approaches:
Zero-Shot Learning: Quick, concise answers with limited contextual depth.
Few-Shot Learning: Enhanced detail and informativeness, but occasionally diverging from the core question.
Fine-Tuning: Delivered the most accurate and contextually relevant answers.
Innovative evaluation metrics using GPT-4 for assessing accuracy, contextual understanding, and clarity, overcoming the limitations of traditional NLP metrics like BLEU and ROUGE.
Dataset
The Arabic Healthcare Dataset (AHD) comprises over 800,000 expert-annotated QA pairs spanning 90 categories. For this project, 3,000 rows were selected via stratified random sampling to ensure balanced representation across categories.

## Goals
Adapt a state-of-the-art LLM for Arabic medical QA, a low-resource language domain.
Compare the performance of zero-shot, few-shot, and fine-tuned models.
Demonstrate the potential of fine-tuning to enhance LLM performance in domain-specific applications.
## Results
Fine-Tuning consistently provided the most accurate and relevant answers.
Few-Shot Learning added useful context but sometimes lacked focus.
Zero-Shot Learning was concise but occasionally switched to English and struggled with complex or culturally specific questions.
## Future Directions
This project sets a foundation for:

Extending fine-tuning to larger datasets for improved generalization.
Expanding evaluation to multilingual capabilities.
Applying the model to other critical domains requiring domain-specific NLP solutions.
