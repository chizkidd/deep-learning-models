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
| AlexNet | CIFAR-10 |   [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/alexnet-cifar10.ipynb)  |

#### [VGG-16](https://arxiv.org/pdf/1409.1556)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| VGG-16 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/vgg16-cifar10.ipynb)  |

#### [Network-in-Network (NiN)](https://arxiv.org/pdf/1312.4400)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| NiN | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/nin-cifar10.ipynb)  |

#### [GoogLeNet](https://arxiv.org/pdf/1409.4842)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| GoogLeNet | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/googlenet-cifar10.ipynb)  |

#### [ResNet](https://arxiv.org/pdf/1409.4842)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| ResNet-18 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/resnet18-cifar10.ipynb)  |
| ResNet-34 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/resnet34-cifar10.ipynb)  |
| ResNet-50 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/resnet50-cifar10.ipynb)  |
| ResNet-101 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/resnet101-cifar10.ipynb)  |
| ResNet-152 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/resnet152-cifar10.ipynb)  |

#### [DenseNet](https://arxiv.org/pdf/1608.06993)
|Title | Dataset  | Notebooks |
| --- | --- | --- |
| DenseNet-121 | CIFAR-10 |   [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/densenet121-cifar10.ipynb)  |

#### [MobileNet](https://arxiv.org/pdf/1704.04861)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| MobileNet | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/mobilenet-cifar10.ipynb)  |
| [MobileNet-V2](https://arxiv.org/pdf/1801.04381) | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/mobilenet-v2-cifar10.ipynb)  |
| [MobileNet-V3-Small](https://arxiv.org/pdf/1905.02244) | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/mobilenet-v3-small-cifar10.ipynb)  |
| [MobileNet-V3-Large](https://arxiv.org/pdf/1905.02244) | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/mobilenet-v3-large-cifar10.ipynb)  |

#### [ShuffleNet](https://arxiv.org/pdf/1707.01083)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| ShuffleNet | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/shufflenet-v1-cifar10.ipynb)  |
| [ShuffleNet-V2](https://arxiv.org/abs/1807.11164) | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/shufflenet-v2-cifar10.ipynb)  |


#### [EfficientNet](https://arxiv.org/pdf/1905.11946)
|Title | Dataset | Notebooks |
| --- | --- | --- | 
| EfficientNet-B0 | CIFAR-10 |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/efficientnet-B0-cifar10.ipynb)  

## Recurrent Neural Networks (RNN)

#### Many-to-one: Sentiment Analysis / Classification

|Title | Dataset | Notebooks |
| --- | --- | --- | 
| Simple single-layer RNN ([Elman](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1402_1)) | [IMDB](https://huggingface.co/datasets/stanfordnlp/imdb) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn-simple-imdb.ipynb)  |
| Simple single-layer RNN ([Elman](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1402_1)) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn-simple-agnews.ipynb)  |
| Simple single-layer [LSTM](https://www.bioinf.jku.at/publications/older/2604.pdf) | [IMDB](https://huggingface.co/datasets/stanfordnlp/imdb) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn-lstm-imdb.ipynb)  |
| Simple single-layer [LSTM](https://www.bioinf.jku.at/publications/older/2604.pdf) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn-lstm-agnews.ipynb)  |
| Simple single-layer [GRU](https://arxiv.org/pdf/1406.1078) | [IMDB](https://huggingface.co/datasets/stanfordnlp/imdb) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn-gru-imdb.ipynb)  |
| Simple single-layer [GRU](https://arxiv.org/pdf/1406.1078) | [AG News](https://huggingface.co/datasets/fancyzhx/ag_news) |  [![PyTorch](https://img.shields.io/badge/Py-Torch-red)](pytorch/rnn-gru-agnews.ipynb)  |


<br><br>

_Currently ongoing ..._

---
