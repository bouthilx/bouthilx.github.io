---
title: "Accounting for Variance in Machine Learning Benchmarks"
collection: publications
permalink: /publication/2021-04-07-accounting-for-variance
excerpt: 'Add excerpt...'
month: april
year: 2021
date: 2021-04-07
venue: 'Machine Learning and Systems (MLSys 2021)'
authors: Xavier Bouthillier, Pierre Delaunay, Mirko Bronzi, Assya Trofimov, Brennan Nichyporuk, Justin Szeto, Nazanin Mohammadi Sepahvand, Edward Raff, Kanika Madan, Vikram Voleti, Samira Ebrahimi Kahou, Vincent Michalski, Tal Arbel, Chris Pal, Gael Varoquaux, Pascal Vincent
paperurl: 'https://proceedings.mlsys.org/paper/2021/hash/cfecdb276f634854f3ef915e2e980c31-Abstract.html'
citation: ''
---

Strong empirical evidence that one machine-learning algorithm A outperforms another one B, ideally
calls for multiple trials optimizing the learning pipeline over sources of variation such as data
sampling, augmentation, parameter initialization, and hyperparameters choices. This is prohibitively
expensive, and corners are cut to reach conclusions. We model the whole benchmarking process and all
sources of variation, revealing that variance due to data sampling, parameter initialization and
hyperparameter choice impact markedly machine learning benchmark. We analyze the predominant
comparison methods used today in the light of this variance. We show a counter-intuitive result that
a biased estimator with more source of variation will give better results, closer to the ideal
estimator at a 51× reduction in compute cost. Using this we perform a detailed study on the error
rate of detecting improvements, on five different deep-learning tasks/architectures. This study
leads us to propose recommendations for future performance comparisons.  This paper is about the
number 1. The number 2 is left for future work.

Oral: https://youtu.be/-bukIBTkQiM
Poster video: https://youtu.be/ZE2WLeavnEY
Twitter: shorturl.at/hvxI2

BibTeX:

    @article{bouthillier2021accounting,
      title={Accounting for variance in machine learning benchmarks},
      author={Bouthillier, Xavier and Delaunay, Pierre and Bronzi, Mirko and Trofimov, Assya and Nichyporuk, Brennan and Szeto, Justin and Mohammadi Sepahvand, Nazanin and Raff, Edward and Madan, Kanika and Voleti, Vikram and Ebrahimi Kahou, Samira and Michalski, Vincent and Arbel, Tal and Pal, Chris and Varoquaux, Gael and Vincent, Pascal},
      journal={Proceedings of Machine Learning and Systems},
      volume={3},
      year={2021}
    }
