# Neural Language Modeling
This repository is basically a collection of my work related to language modeling using neural networks.
It contains discussions and Python3/TensorFlow implementations of several standard research papers related to the field, along with a list and brief description of references.

## Research papers
1. **Recurrent Neural Network based Language Model**, Mikolov et al, 2010 \[ [pdf](References/mikolov.pdf) | [discussion](mikolov.ipynb) ]
2. **Recurrent Neural Network Regularization**, Zaremba et al, 2014 \[ [pdf](References/zaremba.pdf) | [discussion](zaremba.ipynb) ]
3. **On the state-of-the-art evaluation in Neural Language Models**, Melis et al, 2017 \[ [pdf](References/melis.pdf) | [discussion](melis.ipynb) ]
4. **Regularizing and Optimizing LSTM Language Models**, Merity et al, 2017 \[ [pdf](References/merity.pdf) | [discussion](merity.ipynb) ]
5. **Distilling the Knowledge in a Neural Network**, G. Hinton et al, 2015 \[ [pdf](References/hinton.pdf) ]
## References
* [**Vector Representations of Words** - TensorFlow](https://www.tensorflow.org/tutorials/word2vec) : This tutorial is about the `word2vec` model described by Mikolov et al \[[pdf](References/word_embeddings_mikolov.pdf)] and its implementation using TensorFlow
* [**Efficient Estimation of Word Representations in Vector Space** - Mikolov et al., 2013](References/mikolov_word_vectors.pdf) : This paper talks about the novel architectures proposed by Mikolov et al. to learn highly effective word vectors from a large dataset in significantly less time.
* [**A Primer on Neural Network Models for Natural Language Processing** - Yoav Goldberg, 2015](References/primer_nlp.pdf) : This tutorial surveys neural network models from the perspective of NLP research and covers input encoding for natural language tasks, feed-forward networks, convolutional networks, recurrent networks and recursive networks, as well as the computation graph abstraction for automatic gradient computation.
* [**Deep Learning for NLP** - CS224D, Stanford University](https://cs224d.stanford.edu/lecture_notes/) : These notes talk in sufficient details about the various methods for learning word embeddings (CBOW, Skip-gram, Negative sampling) as well as neural network models suitable for NLP. 
* [**Long Short-Term Memory** - Sepp Hochreiter & Jürgen Schmidhuber, 1997](References/lstm.pdf) : This paper summarizes previous approaches towards improving RNNs and then introduces LSTMs in great detail.
