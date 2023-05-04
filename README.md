# Hate-Speech-Detection-in-Amharic-Language
 This repository contains the code and resources for a machine learning project that uses fine-tuned mBERT to detect hate speech in Amharic language. The model was fine-tuned using the Hugging Face Trainer API.

# Dataset 
The finetuning was done on an Amharic Dataset that was made available by Mendeley Data (https://data.mendeley.com/datasets/ymtmxx385m). The dataset contains 30,000 rows of Amharic text labeled as hate speech or not hate speech.

# Fine-Tuning
This model was created by finetuning the mBERT model for the downstream task of Hate speech detection for the Amharic language. The initial mBERT model used for finetuning is Davlan/bert-base-multilingual-cased-finetuned-amharic which was provided by Davlan on Huggingface. The model was fine-tuned using HuggingFace's Trainer API.
