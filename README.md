# SlimNets

A comparison of popular methods to create more efficient (smaller and faster) Nueral Networks.

Framework:
Pytorch

Dataset:
CIFAR10

Model:
VGGnet11,16,19

Methods:
1. Gradual Pruning (sparse)
2. Low-Rank Factorization
3. Knowledge Distillation

Absolute Metrics:

1. Model size (weights)
2. Test Accuracy
3. Training Time (h)
4. Inference Time (s)
5. Runtime model size

Relative Metrics:
1. Model compression rate
2. Training/inference accelerations
3. Relative accuracy between small and large models.

References:
1. https://github.com/chengyangfu/pytorch-vgg-cifar10
2. https://github.com/pytorch/vision/blob/master/torchvision/models/vgg.py
3. https://github.com/jacobgil/pytorch-pruning/blob/master/finetune.py
4. https://github.com/bearpaw/pytorch-classification/blob/master/models/cifar/alexnet.py
5. https://github.com/jiecaoyu/pytorch-nin-cifar10/blob/master/original.py
6. https://github.com/wanglouis49/pytorch-weights_pruning

### Gradual Pruning Progression Curves based on:

M. Zhu and S. Gupta, “To prune, or not to prune: exploring the efficacy
of pruning for model compression,” ArXiv e-prints, Oct. 2017.

![Alt text](sparse.png?raw=true "Gradual Pruning Progression Curves ")

### VGG 19 Loss Progression with Gradual Pruning
![Alt text](loss.png?raw=true "VGG 19 Loss Progression with Gradual Pruning")
