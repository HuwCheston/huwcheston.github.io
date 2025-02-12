---
title: "Automatic Identification of Samples in Hip-Hop Music via Multi-Loss Training and an Artificial Dataset"
collection: publications
preprint: true
excerpt: 'We show that a convolutional neural network trained on an artificial dataset can identify real-world samples in commercial hip-hop music. Our model achieves 13% greater precision on real-world instances of sampling than a fingerprinting system using acoustic landmarks (Shazam-style), and can recognize samples that have been both pitch shifted and time stretched.'
date: 2025-12-02
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2502.06364'
imgurl: '/images/sample_tsne_img.png'
citation: 'Cheston H, Van Balen J, & Durand S. Automatic Identification of Samples in Hip-Hop Music via Multi-Loss Training and an Artificial Dataset. <i>arXiv</i>. 2025; arXiv:2502.06364 [cs.SD].'
---

<img src='/images/sample_tsne_img.png'>

 [![Paper](http://img.shields.io/badge/Paper-DOI:_10.48550/arXiv.2502.06364-blue)](https://doi.org/10.48550/arXiv.2502.06364)
 [![Code](http://img.shields.io/badge/Code-Coming_Soon-red)](https://doi.org/10.48550/arXiv.2502.06364)

Sampling, the practice of reusing recorded music or sounds from another source in a new work, is common in popular music genres like hip-hop and rap. Numerous services have emerged that allow users to identify connections between samples and the songs that incorporate them, with the goal of enhancing music discovery. Designing a system that can perform the same task automatically is challenging, as samples are commonly altered with audio effects like pitch- and time-stretching and may only be seconds long. Progress on this task has been minimal and is further blocked by the limited availability of training data. Here, we show that a convolutional neural network trained on an artificial dataset can identify real-world samples in commercial hip-hop music. We extract vocal, harmonic, and percussive elements from several databases of non-commercial music recordings using audio source separation, and train the model to fingerprint a subset of these elements in transformed versions of the original audio. We optimize the model using a joint classification and metric learning loss and show that it achieves 13% greater precision on real-world instances of sampling than a fingerprinting system using acoustic landmarks, and that it can recognize samples that have been both pitch shifted and time stretched. We also show that, for half of the commercial music recordings we tested, our model is capable of locating the position of a sample to within five seconds.

**Work completed as an intern at [Spotify Research (Audio Intelligence)](https://research.atspotify.com/audio-intelligence/)**