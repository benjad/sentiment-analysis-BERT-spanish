

## Sentiment analysis with BERT in Spanish 
This repository contains the code and resources for my personal blog article: ["Sentiment analysis with BERT in Spanish"](http://benjad.github.io/2020/08/04/clasificador-sentimiento-BERT/)
## Installation
First we need to install all the necessary libraries:

`pip install -r requirements.txt`


Then we download the PyTorch weights for the uncased model [BETO](https://github.com/dccuchile/beto):

`wget https://users.dcc.uchile.cl/~jperez/beto/uncased_2M/pytorch_weights.tar.gz`

`wget https://users.dcc.uchile.cl/~jperez/beto/uncased_2M/vocab.txt` 

`wget https://users.dcc.uchile.cl/~jperez/beto/uncased_2M/config.json` 

`tar -xzvf pytorch_weights.tar.gz`

`mv config.json pytorch/.`

`mv vocab.txt pytorch/.`



## Resources:

1. [reviews.csv](reviews.csv): Reviews from the *yapo.cl* app  saved into a *.csv* file.

2. [reviewsclean.csv](reviewsclean.csv): cleaned reviews and starts rating transformed into 3 categories: *negative*, *neutral* and *positive*.

3. [BERT.ipynb](BERT.ipynb): The jupyter notebook with all the code for the article.

