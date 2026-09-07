# Social-Media-Sentiment-Analysis
Sentiment analysis component for a nonprofit organization's social media sentiment dashboard using Hugging Face Transformers.

## Project Overview

This project is a sentiment analysis component developed for a
Social Media Sentiment Dashboard for a Nonprofit Organization.

The component analyzes social media comments and classifies them
as Positive, Negative, or Neutral.

## My Contribution

I was responsible for the Hugging Face Transformers component
as Member 5 of the team.

My work included:
- Selecting a suitable pretrained sentiment analysis model
- Implementing sentiment analysis using Hugging Face Transformers
- Creating sample social media test cases
- Testing the model on different types of comments
- Evaluating predictions and confidence scores
- Identifying challenging and context-dependent cases

## Technology Used

- Python
- Hugging Face Transformers
- PyTorch
- CardiffNLP Twitter RoBERTa Sentiment Model
- Google Colab / Jupyter Notebook

## Model

Model used:

`cardiffnlp/twitter-roberta-base-sentiment-latest`

The model was selected because it is designed for social-media text
and supports three sentiment labels:

- Positive
- Negative
- Neutral

## Testing

The model was initially tested on 3 basic examples and then
evaluated on 10 additional test cases containing positive, negative,
neutral, and challenging statements.

Most clear sentiment cases were classified correctly. However,
some implicit or context-dependent statements were more challenging
for the model.

## Results

The testing showed that the model performs well on clear sentiment
expressions but may have difficulty identifying indirect negativity,
sarcasm, or context-dependent sentiment.

## Conclusion

Hugging Face Transformers provided a practical way to implement
the sentiment analysis component using a pretrained model without
training a model from scratch.

The component can be used as part of the overall Social Media
Sentiment Dashboard.

## Project Files

