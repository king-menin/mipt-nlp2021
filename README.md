# mipt-nlp2021
NLP course, MIPT

### Course instructors
Anton Emelianov (login-const@mail.ru, @king_menin), Alena Fenogenova (alenush93@gmail.com)

Telegram chat [mipt-nlp2021](https://t.me/joinchat/HlYsCUgkZ9sTL0mJ)

Videos [here](https://drive.google.com/drive/folders/1YbyT2wA4LEcaMitwuTr7fuYcpWeAWzIW?usp=sharing)

## Mark
```math
final_mark=sum_i (max_score(HW_i)) / count(HWs) * 10, i==1..4
```

## Lecture schedule

#### Week 1

* Lecture: [Intro to NLP](lectures/L1.Intro2NLP.pdf)
* Practical: [Text preprocessing](seminars/sem1/sem1_basic_text_processing.ipynb), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem1/sem1_basic_text_processing.ipynb)
* [Video](https://drive.google.com/file/d/1DoD4Yaw-oFBSjK4awL0F_pXbdOMlfkwI/view?usp=sharing)

#### Week 2

* Lecture: [Word embeddings](lectures/L2.WordEmbeddings.pdf)

Distributional semantics. Count-based (pre-neural) methods. Word2Vec: learn vectors. GloVe: count, then learn. N-gram (collocations)
RusVectores. t-SNE.
* Practical: [word2vec, fasttext](seminars/sem2/2_embeddings.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem2/2_embeddings.ipynb)
* [HW1](HWs/hw1.ipynb) If you have problems with datasets you also can obtain this [here](https://drive.google.com/drive/folders/1hlcNE2X10SRucppU0-hRfrGwjYFMCWdL?usp=sharing)
* [Video](https://drive.google.com/file/d/1lD5k1b8LAJ8wSM45Z1TDYstXqqwYjb9L/view?usp=sharing)

#### Week 3

* Lecture: [RNN + CNN, Text classification](lectures/L3.TextClassification_BasicNNs_at_NLP.pdf)

Neural Language Models: Recurrent Models, Convolutional Models. Text classification (architectures)
* Practical: [Classification with LSTM, CNN](seminars/sem3/sem3_classification.ipynb), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem3/sem3_classification.ipynb)
* [Video](https://drive.google.com/file/d/1i6X3Hv7bzC8-ZHKeVvuu_gabaYrfMygM/view?usp=sharing)

#### Week 4

* Lecture: [Language modelling and NER](lectures/L4.LMs_Intro_and_NER.pdf)

Task description, methods (Markov Model, RNNs), evaluation (perplexity), Sequence Labelling (NER, pos-tagging, chunking etc.) N-gram language models, HMM, MEMM, CRF
* Practical: [NER](seminars/sem4/sem4_ner.ipynb), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem4/sem4_ner.ipynb)
* [HW2](HWs/hw2.ipynb), [https://www.kaggle.com/c/mipt-nlp-hw2-2021/](https://www.kaggle.com/c/mipt-nlp-hw2-2021/)
* [Video](https://drive.google.com/file/d/1XjpVthq-U35YhDu94qxKN4JcxbID1kqy/view?usp=sharing)

#### Week 5

* Lecture: [Machine translation, Seq2seq, Attention, Transformers](lectures/L5.MT_Attention_Transformers.pdf)

Basics: Encoder-Decoder framework, Inference (e.g., beam search),  Eval (bleu).
Attention: general, score functions, models. Bahdanau and Luong models. 
Transformer: self-attention, masked self-attention, multi-head attention.

* [Video](https://drive.google.com/file/d/1A3rpB4YuBoSF3vZ6BagZXyLP5jIhlkct/view?usp=sharing)

#### Week 6

* Lecture: [Transfer learning in NLP](lectures/L6.TransferLearning.pdf)

Bertology (BERT, GPT-s, t5, etc.), Subword Segmentation (BPE), Evaluation of big LMs.
* Practical: [transformers models for classification task](seminars/sem6/TransferLearningSeminar.ipynb), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem6/TransferLearningSeminar.ipynb)
* Practical: [Transfer learning](seminars/sem6)
* Video: [Part1](https://drive.google.com/file/d/1QjoIIl87lnhHBWmDc5sJUmYmaVEpLOjy/view?usp=sharing), [Part2](https://drive.google.com/file/d/1Nzej1VWkx4JqJeNN1PX7i9mvUh_P7Dpk/view?usp=sharing)

#### Week 7

Lecture & Practical: How to train big models? [Part1. Distributed training](lectures/L7.DistributedTraining.pdf), [Part2. RuGPT3 Training](lectures/train_large_scale_gpt3.pdf)

Training Multi-Billion Parameter Language Models. Model Parallelism. Data Parallelism.

* Practical: [DDP example](seminars/sem7)
* [Video](https://drive.google.com/file/d/1h23zg69zNARtcnb7sexq0E7_shIfF4yn/view?usp=sharing)
* [HW3](HWs/hw3.ipynb), [https://www.kaggle.com/c/mipt-nlp-hw3-2021/](https://www.kaggle.com/c/mipt-nlp-hw3-2021/)

#### Week 8

* Lecture: [Syntax parsing](lectures/L8.syntax_mipt.pdf)
* Practical: [Syntax](seminars/sem8/seminar_syntax_mipt.ipynb)
* [Video](https://drive.google.com/file/d/1a_79qtfLNaUTTJJl7SkiGzlxo7hGXTMH/view?usp=sharing)

#### Week 9

* Lecture: [Question answering](lectures/L9.QA.pdf)
* Practical: [seminar QA](seminars/sem9/seminar9chatbots.ipynb), [seminar chatbots](seminars/sem9/seminar9qa.ipynb)
* [Video](https://drive.google.com/file/d/1Ilkjp3sjz3jow2V3M8j_eL4pW6wz-R0D/view?usp=sharing)

Squads (one-hop, multi-hop), architectures, retrieval and search, chat-bots


#### Week 10

* Lecture: [Summarization, simplification, paraphrasing](lectures/L10.Summarization.pdf)
* Practical: [summarization seminar](seminars/sem10/Summarization.ipynb)
* [Video](https://drive.google.com/file/d/1StmAJ85xnNz7OKcQuj4tyzpaIUJ5xROR/view?usp=sharing)

#### Week 11

* Lecture: [Knowledge Distillation in NLP](lectures/L11.Knowledge_Distillation_in_NLP.pdf)
* [Video](https://drive.google.com/file/d/1rPyzjUSTtpjO8PyO7mR4QnjoA1cAaePP/view?usp=sharing)



## Recommended Resources
### En

* [ruder.io](https://ruder.io/)
* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

* [Курс nlp в яндексе](https://github.com/yandexdataschool/nlp_course)
* [НКРЯ](http://ruscorpora.ru)
* [Открытый корпус](http://opencorpora.org)
* [Дистрибутивные семантические модели для русского языка](http://rusvectores.org/ru/)
* [Морфология](https://tech.yandex.ru/mystem/)
* [Синтаксис](https://habrahabr.ru/post/317564/)
* [Томита-парсер](https://tech.yandex.ru/tomita/)
* [mathlingvo](http://mathlingvo.ru)
* [nlpub](https://nlpub.ru)
* [Text Visualisation browser](http://textvis.lnu.se)


## Literature

* Manning, Christopher D., and Hinrich Schütze. Foundations of statistical natural language processing. Vol. 999. Cambridge: MIT press, 1999.
* Martin, James H., and Daniel Jurafsky. "Speech and language processing." International Edition 710 (2000): 25.
* Cohen, Shay. "Bayesian analysis in natural language processing." Synthesis Lectures on Human Language Technologies 9, no. 2 (2016): 1-274.
* Goldberg, Yoav. "Neural Network Methods for Natural Language Processing." Synthesis Lectures on Human Language Technologies 10, no. 1 (2017): 1-309.

