---
title: "An evaluation of fisher approximations beyond kronecker factorization"
collection: publications
permalink: /publication/2018-05-01-an-evaluation-of-fisher
excerpt: 'Add except...'
month: may
year: 2018
date: 2018-05-01
venue: Workshop at International Conference on Learning Representations
authors: César Laurent, Thomas George, Xavier Bouthillier, Nicolas Ballas and Pascal Vincent
paperurl: https://openreview.net/pdf?id=ryVC6tkwG
type: workshop
citation: ''
---

We study two coarser approximations on top of a Kronecker factorization (K-FAC) of the
Fisher information matrix, to scale up Natural Gradient to deep and wide Convolutional
Neural Networks (CNNs). The first considers the activations (feature maps) as spatially
uncorrelated while the second considers only correlations among groups of channels. Both
variants yield a further block-diagonal approximation tailored for CNNs, which is much
more efficient to compute and invert. Experiments on the VGG11 and ResNet50
architectures show the technique can substantially speed up both K-FAC and a baseline
with Batch Normalization in wall-clock time, yielding faster convergence to similar or
better generalization error.

BibTeX:

    @inproceedings{laurent2018evaluation,
        author = {Laurent, C{\'e}sar and George, Thomas and Bouthillier, Xavier and Ballas, Nicolas and Vincent, Pascal},
        booktitle = {Workshop at International Conference on Learning Representations},
        month = {may},
        title = {An evaluation of fisher approximations beyond kronecker factorization},
        url = {https://openreview.net/pdf?id=ryVC6tkwG},
        year = {2018}
    }
    
    
