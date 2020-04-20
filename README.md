# U-net reproduction

This repository hosts the work done by Django Brunink and Thaine H. Assumpção for the reproducibility project part of the deep learning course (CS4240) at Delft University of Technology. We reproduced the [u-net](https://arxiv.org/abs/1505.04597), a deep learning network used for biomedical image segmentation [1]. It includes:

* **Ipython jupyter notebook**: code with an overview of the U-net as described in the original article and the steps taken to reproduce some of the article's results.
* **Reproducibility folder**: data needed for the notebook to be run
   * U-Net/Data Set: datasets used in the article's experiments (obtained by registering to the [EM segmentation challenge](http://brainiac2.mit.edu/isbi_challenge/) and downloaded from the [ISBI cell tracking challenge](http://celltrackingchallenge.net/) website)
   * U-Net/Trained models: location to be stored trained models

[1] Ronneberger, O., Fischer, P., & Brox, T. (2015, October). U-net: Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Springer, Cham.

## Dependencies

The code was developed using Python 3 and we've included pip installations for smooth running through Google Colaboratory. If run locally, four libraries are needed to execute the code:

* `torch`
* `torchsummary`
* [`elasticdeform`](https://github.com/gvtulder/elasticdeform)
* [`tifffile`](https://pypi.org/project/tifffile/)

## Pre-trained models

The pre-trained models are too heavy to be uploaded in GitHub and therefore can be downloaded from:
https://drive.google.com/drive/folders/1a_0PXjVT5s2ituMdzehn2UAMPdFQsPOF?usp=sharing
