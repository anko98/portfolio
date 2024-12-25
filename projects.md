---
layout: default
title: Projects
---

# My Projects

[Home](https://anko98.github.io/portfolio/) | [Projects](https://anko98.github.io/portfolio/projects)

### Comparative Analysis of Sentiment and Emotion Prediction Models in Context of Covid-19 Conspiracy Theories

This project was grounded in the cultural evolutionary theory - a theory based on Darwinian evolutionary theory, which claims that cultural information is spread according to the features, which increase their probablity of spreading. I wanted to find out whether negative Tweets will spread better, and also, compare classic and more modern sentiment and emotion analysis methods.

For sentiment analysis, I used VADER, Twitter-roBERTa-base for Sentiment Analysis from Hugging Face, and a fine-tuned RoBERTa. For emotion analysis - NRCLex, Emotion English DistilroBERTa-base from HuggingFace and a fine-tuned RoBERTa

<p align="center">
  <img src="https://github.com/anko98/portfolio/blob/main/images/distribution%20of%20sentiment%20scores%20by%20tweet%20type.png?raw=true" alt="Sentiment distribution">
</p>
There were slightly fewer conspiracy tweets and they were more negative.

<p align="center">
  <img src="https://github.com/anko98/portfolio/blob/main/images/Emotions%20by%20Tweet%20Type.png?raw=true" alt="Emotion distribution">
</p>

In short, I didn't find a correlation between sentiment, emotions and tweet popularity. RoBERTa-based models from Hugging Face performed the best, but in some cases not well enough to apply it in real-life (e.g., only 25% of joyful tweets correctly classified :( ) Poor performance of fine-tuned RoBERTas can be due to a small dataset (a big limitation for personal projects). However, emotion and sentiment distribution suggests true and conspiratory messages substantially differ between each other.


