# FinetunedBertforJobDescriptions
This repository contains code and resources for a natural language processing (NLP) task involving masked language modeling and downstream classification of job descriptions as remote or in-person. The project utilizes the Transformers library, TensorFlow, and the DistilBERT model to accomplish this task.

### Task Overview
The objective of this project is to fine-tune a pre-trained DistilBERT model using masked language modeling on a dataset of job descriptions. The masked language modeling technique helps the model gain a better understanding of the text present in job descriptions. This finetuning process aims to decrease the perplexity measure from 25 to 11, improving the model's familiarity with the job description data.

The finetuned model is then used for downstream classification of job descriptions, specifically categorizing them as remote or in-person.

### Model and Libraries Used
In this project, we utilized the DistilBERT model, a pre-trained transformer-based architecture designed for efficient NLP tasks. The DistilBERT model is known for its smaller size and faster inference time while still retaining high performance.

To implement the masked language modeling and downstream classification, we used the Transformers library, which provides a user-friendly interface for working with transformer models. TensorFlow, a popular deep learning framework, was employed as the backend for training and deploying the model.

### Data and Fine-tuning Process
The masked language modeling was performed based on a sample of 150 million job descriptions. The DistilBERT model was fine-tuned using a Jupyter Notebook, which is included in this repository. The notebook outlines the fine-tuning process, including data preprocessing, model configuration, training, and evaluation.

### Results
The finetuned DistilBERT model achieved a decrease in perplexity measure from 25 to 11, indicating improved understanding of the job description text. This enhanced model was then utilized for the downstream classification task of categorizing job descriptions as remote or in-person.
