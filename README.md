# AASD-4015---Chinese-Sentiment-Analysis

<b>Members:</b> 
1. Saksham Prakash (101410709) 
2. Sik Yin Sun (101409665)

## Background and Motivation
<b> Why Chinese? </b>

With both the team members belonging to different ethnicities, we wanted to explore the usage of NLP models on our native languages. With Saksham's native language Hindi and Sik's native language Chinese, we decided on Chinese as we found larger community support and resources.

<b> Why Text Classification?</b>

Initially, we explored Text Generation ideas for fine-tuning a transformer-based model on Chinese Texts. For this we explored Andrej's NanoGPT repository but couldn't get a chinese tokenizer/encoder running without errors. We further explored Text Generation models on Hugging Face as well as a few Question-Answering datasets and models on Hugging Face. However, we resorted to a simpler task of text classification in chinese for now, given the available time and resources.

<b> Why HuggingFace? </b>

Learning HuggingFace libraries for transformers felt essential because it seems to be the emerging AI exploratory space with a large community for working professionals looking to try different AI solutions quickly for the problem at hand.

## Problem Statement

The Applied AI Solutions Development Program has exclusively trained models in English. Still, now the team is interested in exploring the effectiveness of machine learning and deep learning in other languages. For this project, we have selected Chinese for sentiment analysis, using a dataset from hugging face that includes various comments on different topics such as hotels, seafood, and restaurants. We intend to utilize existing models, namely bert-base-chinese from hugging face (https://huggingface.co/bert-base-chinese) and Roberta-based models from hugging face ("https://huggingface.co/liam168/c2-roberta-base-finetuned-dianping-chinese", "https://huggingface.co/Jiabo/Roberta_Chinese_sentiment"). Both models will undergo fine-tuning, and we will compare their performance to assess the efficacy of transformers in Chinese. In addition, the "accuracy" metric will be used to evaluate the performance of the models.

| SNo. | Contents |
| -------- | -------- |
| 1 | Installing and Importing libraries |
| 2 | Data - Chinese Sentiment |
| 3.1 | Trying bert-base-chinese |
| 3.2 | Trying liam168/c2-roberta-base-finetuned-dianping-chinese |
| 3.3 | Trying Jiabo/Roberta_Chinese_sentiment |
| 4 | Results |

Deploy website: https://sikyinsun.github.io/Chinese-Sentiment-Analysis/
