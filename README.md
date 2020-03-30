# BERT-tf2
Implement BERT on Tensorflow 2.* using the TF hub pre-trained BERT model and the official model repository of Tensorflow.

The main reason behind this project is that I couldn't find any straightforward implementation of BERT for Tensorflow 2 in eager mode. This was also part of my learning about the recent changes on NLP.

## Use case
As a use case, the notebook existing in this repository uses BERT for the classification of movie reviews.

We use the [IMDB dataset](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/imdb) that contains the text of 50,000 movie reviews split into 25,000 reviews for training and 25,000 reviews for testing.

## Installation
The notebook runs on Python 3.* and Tensorflow 2.1 or later.

To use it, you can:
- Clone this repository and [tensorflow/models](https://github.com/tensorflow/models) in the same folder.
- or simply clone with submodules: `git -recursive clone https://github.com/Alieladi/Bert-tf2.git`

The [tensorflow/models](https://github.com/tensorflow/models) requires to install some libraries. Use the command: `pip install --user -q -r models/official/requirements.txt`
