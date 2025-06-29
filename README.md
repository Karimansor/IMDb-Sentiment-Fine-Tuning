# IMDb Sentiment Analysis - Fine-tuned BERT Model

This project fine-tunes a pre-trained BERT model from Hugging Face on the IMDb movie reviews dataset for binary sentiment classification (positive/negative).

## Project Overview

- Task: Sentiment Analysis (Binary Classification)
- Dataset: IMDb
- Model: bert-base-uncased fine-tuned using Transformers and PyTorch
- Accuracy: About 92.8% on validation data



## Sample Usage

### Load the model and tokenizer

```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification

tokenizer = AutoTokenizer.from_pretrained("saved_model")
model = AutoModelForSequenceClassification.from_pretrained("saved_model")
