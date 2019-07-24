# NTM
Testing of Neural Topic Modeling for Japanese articles

This repository intended to test performance of Neural Topic Model and Gensim LDA.
A Pytorch implementation of Neural Topic Model and Gensim LDA test code are contained in this repository.

## Dataset
livedoor ニュースコーパス / livedoor News Corpus  
https://www.rondhuit.com/download.html#ldcc  
CC BY-ND 2.1 JP  
https://creativecommons.org/licenses/by-nd/2.1/jp/


## Neural Topic Model
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m3yrin/NTM/blob/master/NTM_jp.ipynb)

### Reference 
* yuewang-cuhk/TAKG
https://github.com/yuewang-cuhk/TAKG
* ysmiao/nvdm
https://github.com/ysmiao/nvdm/
* http://tdual.hatenablog.com/entry/2018/04/09/133000

### memo
* yuewang-cuhk' s NTM implementation is partially used.
* tdual' s script is massively cited.
* janome tokenizer is used instead of Mecab.
  
***GPU instance is recommended.*** If training is too slow, please check instance type of Google Colaboratory.

## LDA
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m3yrin/NTM/blob/master/LDA_jp.ipynb)

### Reference
http://tdual.hatenablog.com/entry/2018/04/09/133000

### Memo
* tdual' s LDA script is massively cited.
* janome tokenizer is used instead of Mecab.


