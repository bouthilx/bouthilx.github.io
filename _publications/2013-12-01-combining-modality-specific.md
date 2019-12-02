---
title: "Combining modality specific deep neural networks for emotion recognition in video"
collection: publications
permalink: /publication/2013-12-01-combining-modality-specific
excerpt: 'Add except...'
month: dec
year: 2013
date: 2013-12-01
venue: Proceedings of the 15th ACM on International conference on multimodal interaction
authors: Samira Ebrahimi Kahou, Christopher Pal, Xavier Bouthillier, Pierre Froumenty, Çaglar Gülçehre, Roland Memisevic, Pascal Vincent, Aaron Courville, Yoshua Bengio, Raul Chandias Ferrari and others
paperurl: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.699.3422&rep=rep1&type=pdf
type: conference
citation: ''
---

In this paper we present the techniques used for the University of Montréal's team
submissions to the 2013 Emotion Recognition in the Wild Challenge. The challenge is to
classify the emotions expressed by the primary human subject in short video clips
extracted from feature length movies. This involves the analysis of video clips of acted
scenes lasting approximately one-two seconds, including the audio track which may
contain human voices as well as background music. Our approach combines multiple deep
neural networks for different data modalities, including: (1) a deep convolutional
neural network for the analysis of facial expressions within video frames; (2) a deep
belief net to capture audio information; (3) a deep autoencoder to model the
spatio-temporal information produced by the human actions depicted within the entire
scene; and (4) a shallow network architecture focused on extracted features of the mouth
of the primary human subject in the scene. We discuss each of these techniques, their
performance characteristics and different strategies to aggregate their predictions. Our
best single model was a convolutional neural network trained to predict emotions from
static frames using two large data sets, the Toronto Face Database and our own set of
faces images harvested from Google image search, followed by a per frame aggregation
strategy that used the challenge training data. This yielded a test set accuracy of
35.58%. Using our best strategy for aggregating our top performing models into a single
predictor we were able to produce an accuracy of 41.03% on the challenge test set. These
compare favorably to the challenge baseline test set accuracy of 27.56%.

BibTeX:

    @inproceedings{kahou2013combining,
        author = {Kahou, Samira Ebrahimi and Pal, Christopher and Bouthillier, Xavier and Froumenty, Pierre and G{\"u}l{\c{c}}ehre, {\c{C}}aglar and Memisevic, Roland and Vincent, Pascal and Courville, Aaron and Bengio, Yoshua and Ferrari, Raul Chandias and others},
        booktitle = {Proceedings of the 15th ACM on International conference on multimodal interaction},
        month = {dec},
        organization = {ACM},
        pages = {543--550},
        title = {Combining modality specific deep neural networks for emotion recognition in video},
        url = {http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.699.3422&rep=rep1&type=pdf},
        year = {2013}
    }
    
    
