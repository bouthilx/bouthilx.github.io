---
title: "Fast approximate natural gradient descent in a kronecker factored eigenbasis"
collection: publications
permalink: /publication/2018-12-01-fast-approximate-natural
excerpt: 'Add except...'
month: dec
year: 2018
date: 2018-12-01
venue: Advances in Neural Information Processing Systems
authors: Thomas George, César Laurent, Xavier Bouthillier, Nicolas Ballas and Pascal Vincent
paperurl: https://papers.nips.cc/paper/8164-fast-approximate-natural-gradient-descent-in-a-kronecker-factored-eigenbasis.pdf
type: conference
citation: ''
---

Optimization algorithms that leverage gradient covariance information, such as variants
of natural gradient descent (Amari, 1998), offer the prospect of yielding more effective
descent directions.  For models with many parameters, the covari- ance matrix they are
based on becomes gigantic, making them inapplicable in their original form. This has
motivated research into both simple diagonal approxima- tions and more sophisticated
factored approximations such as KFAC (Heskes, 2000; Martens & Grosse, 2015; Grosse &
Martens, 2016). In the present work we draw inspiration from both to propose a novel
approximation that is provably better than KFAC and amendable to cheap partial updates.
It consists in tracking a diagonal variance, not in parameter coordinates, but in a
Kronecker-factored eigenbasis, in which the diagonal approximation is likely to be more
effective.  Experiments show improvements over KFAC in optimization speed for several
deep network architectures.

BibTeX:

    @inproceedings{george2018fast,
        author = {George, Thomas and Laurent, C{\'e}sar and Bouthillier, Xavier and Ballas, Nicolas and Vincent, Pascal},
        booktitle = {Advances in Neural Information Processing Systems},
        month = {dec},
        pages = {9550--9560},
        title = {Fast approximate natural gradient descent in a kronecker factored eigenbasis},
        url = {https://papers.nips.cc/paper/8164-fast-approximate-natural-gradient-descent-in-a-kronecker-factored-eigenbasis.pdf},
        year = {2018}
    }
    
    
