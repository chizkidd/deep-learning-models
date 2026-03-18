[![Notebooks Deployment Status](https://github.com/chizkidd/deep-learning-models/actions/workflows/deploy-notebooks.yml/badge.svg)](https://github.com/chizkidd/deep-learning-models/actions/workflows/deploy-notebooks.yml)
[![View Notebooks](https://img.shields.io/badge/View-Live%20Notebooks-blue?logo=github)](https://chizkidd.github.io/deep-learning-models/)

# Deep Learning Models
A collection of various deep learning architectures, models, &amp; their implementations (PyTorch or TensorFlow) in Jupyter Notebooks.

## Convolutional Neural Networks (CNN)

#### [LeNet](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| LeNet-5 | [MNIST](https://huggingface.co/datasets/ylecun/mnist) | [![Tensorflow](https://img.shields.io/badge/Tensor-Flow1.0-orange)](tensorflow/lenet5-mnist.ipynb)  |
| LeNet-5 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![Tensorflow](https://img.shields.io/badge/Tensor-Flow1.0-orange)](tensorflow/lenet5-cifar.ipynb)  |

#### [AlexNet](https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| AlexNet | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |   [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-alexnet-cifar10.ipynb)  |

#### [VGG-16](https://arxiv.org/pdf/1409.1556)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| VGG-16 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-vgg16-cifar10.ipynb)  |

#### [Network-in-Network (NiN)](https://arxiv.org/pdf/1312.4400)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| NiN | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-nin-cifar10.ipynb)  |

#### [GoogLeNet](https://arxiv.org/pdf/1409.4842)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| GoogLeNet | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-googlenet-cifar10.ipynb)  |

#### [ResNet](https://arxiv.org/pdf/1409.4842)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| ResNet-18 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-resnet18-cifar10.ipynb)  |
| ResNet-34 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-resnet34-cifar10.ipynb)  |
| ResNet-50 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-resnet50-cifar10.ipynb)  |
| ResNet-101 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-resnet101-cifar10.ipynb)  |
| ResNet-152 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-resnet152-cifar10.ipynb)  |

#### [DenseNet](https://arxiv.org/pdf/1608.06993)
|Title | Dataset  | Notebooks |
| --- | --- | --- |
| DenseNet-121 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |   [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-densenet121-cifar10.ipynb)  |

#### [MobileNet](https://arxiv.org/pdf/1704.04861)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| MobileNet | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-mobilenet-cifar10.ipynb)  |
| [MobileNet-V2](https://arxiv.org/pdf/1801.04381) | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-mobilenet-v2-cifar10.ipynb)  |
| [MobileNet-V3-Small](https://arxiv.org/pdf/1905.02244) | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-mobilenet-v3-small-cifar10.ipynb)  |
| [MobileNet-V3-Large](https://arxiv.org/pdf/1905.02244) | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-mobilenet-v3-large-cifar10.ipynb)  |

#### [ShuffleNet](https://arxiv.org/pdf/1707.01083)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| ShuffleNet | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-shufflenet-v1-cifar10.ipynb)  |
| [ShuffleNet-V2](https://arxiv.org/abs/1807.11164) | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-shufflenet-v2-cifar10.ipynb)  |


#### [EfficientNet](https://arxiv.org/pdf/1905.11946)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| EfficientNet-B0 | [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/cnn/cnn-efficientnet-B0-cifar10.ipynb)  

## Recurrent Neural Networks (RNN)

#### Many-to-one: Sentiment Analysis / Classification

|Title | Dataset | Notebooks |
| --- | --- | --- | 
| Simple single-layer RNN ([Elman](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1402_1)) | [IMDB](https://huggingface.co/datasets/stanfordnlp/imdb) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-simple-imdb.ipynb)  |
| Simple single-layer RNN ([Elman](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1402_1)) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-simple-agnews.ipynb)  |
| Simple single-layer [LSTM](https://www.bioinf.jku.at/publications/older/2604.pdf) | [IMDB](https://huggingface.co/datasets/stanfordnlp/imdb) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-lstm-imdb.ipynb)  |
| Simple single-layer [LSTM](https://www.bioinf.jku.at/publications/older/2604.pdf) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-lstm-agnews.ipynb)  |
| Simple single-layer [GRU](https://arxiv.org/pdf/1406.1078) | [IMDB](https://huggingface.co/datasets/stanfordnlp/imdb) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-gru-imdb.ipynb)  |
| Simple single-layer [GRU](https://arxiv.org/pdf/1406.1078) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-gru-agnews.ipynb)  |
| [Bidirectional GRU](https://arxiv.org/pdf/1409.0473) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-gru-bi-agnews.ipynb)  |
| [Stacked GRU](https://arxiv.org/pdf/1409.0473) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-gru-stacked-agnews.ipynb)  |
| Stacked Bidirectional GRU | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-gru-bi-stack-agnews.ipynb)  |

#### Many-to-Many / Sequence-to-Sequence: Text Generation

|Title | Dataset | Description | Notebooks |
| --- | --- | --- | --- |
| Character-level RNN (GRU) | [Tiny Shakespeare](https://github.com/karpathy/char-rnn/blob/master/data/tinyshakespeare/input.txt) | - | [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-char-gru-tinyshakespeare.ipynb) |
| Character-level RNN (GRU) | [Wikitext](https://huggingface.co/datasets/Salesforce/wikitext) | - | [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/rnn-char-gru-wikitext.ipynb) |
| RNN Encoder-Decoder ([Seq2Seq](https://arxiv.org/pdf/1409.3215)) | [Multi30k (en-de)](https://huggingface.co/datasets/bentrevett/multi30k) | Implementation of [Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078) (2014) | [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/seq2seq.ipynb) |
| Encoder-Decoder with [Bahdanau Attention](https://arxiv.org/pdf/1409.0473) | [Multi30k (en-de)](https://huggingface.co/datasets/bentrevett/multi30k) | Implementation of [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473) (2016) | [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn/seq2seq-attn.ipynb) |

<br><br>

_Currently ongoing ..._

---
