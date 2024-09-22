<h1 align="center">English to Yoruba Translation using RNN</h1>

<div align="center">

[![Language](https://img.shields.io/badge/Python-darkblue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![ML Tool](https://img.shields.io/badge/PyTorch-FF6F00.svg?style=flat&logo=pytorch&logoColor=white)](https://www.tensorflow.org/)
[![Framework](https://img.shields.io/badge/sklearn-darkorange.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/index.html)
![reposize](https://img.shields.io/github/repo-size/Oyebamiji-Micheal/English-to-Yoruba-Translation-using-RNN)
[![Topic](https://img.shields.io/badge/Deep%20Learning-lightblue.svg?style=flat)]()
[![Model](https://img.shields.io/badge/RNN-lightgreen.svg?style=flat)](https://arxiv.org/abs/1409.3215)

</div>

<h4 align="center">A beginner's approach to Sequence to Sequence modeling</h4>

<br/>

<img src="images/cover.jpg">

<h2>Table of Contents</h2>

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Result](#result)

<a id="overview"></a>
<h2>Overview</h2>
<p align="justify">
This project is a beginner’s approach to Sequence to Sequence (Seq2Seq) modeling with Recurrent Neural Networks (RNNs), specifically LSTMs. My aim here is to understand the foundation of Seq2Seq modeling and progressively build my understanding of NLP workflow.</p>
Some of my past projects on natural language processing include:

- <a href="https://github.com/Oyebamiji-Micheal/Sentiment-Analysis-of-Spotify-Songs" target="_blank">Sentiment Analysis of Spotify Songs</a>
- <a href="https://github.com/Oyebamiji-Micheal/Quora-Insincere-Questions-Classification-using-TF-IDF" target="_blank">Quora Insincere Questions Classification using TF-IDF</a>
- <a href="https://github.com/Oyebamiji-Micheal/Predicting-Disaster-Tweets-using-Bag-of-Words" target="_blank">Predicting Disaster Tweets using Bag of Words</a>

In this project, I implemented a Seq2Seq model using RNN (LSTM). The approach is straightforward, with a basic word-level tokenizer and no advanced tokenization techniques like BPE. The goal is to get familiar with the typical Seq2Seq modeling workflow, rather than focusing on achieving state-of-the-art results.

<a id="dataset"></a>
<h2>Dataset</h2>
<p align="justify">
The dataset used for this project was obtained from the <a href="https://zindi.africa/competitions/ai4d-yoruba-machine-translation-challenge" target="_blank">Zindi AI4D Yoruba Machine Translation Challenge</a>. It consists of 10,000 Yoruba to English parallel sentence pairs. </p>
</p>

<a id="model"></a>
<h2>Model</h2>
<p align="justify">
In the notebook, I followed a tutorial by <a href="https://github.com/bentrevett/pytorch-seq2seq" target="_blank">Bentrevett</a>, based on the paper <a href="https://arxiv.org/abs/1409.3215" target="_blank">Sequence to Sequence Learning with Neural Networks</a>.
While the original paper uses a 4-layer architecture, he used a simpler 2-layer setup for both the encoder and decoder, focusing on building a fundamental understanding of how Seq2Seq models work. Training was done for 10 epochs.
</p>

<a id="result"></a>
<h2>Result</h2>
<p align="justify">
Given the limited dataset size and the simple model architecture, I was not expecting so much. However, this project helped me learn how to work with Seq2Seq models: from preparing the data, building the encoder and decoder, to training the model and evaluating it. In the future, I aim to explore more interesting techniques like using pre-trained word embeddings and different tokenization methods. </p>

See you in the next one 🙂
