---
title: "Identifying hip-hop samples with deep-learning"
excerpt: "Sampling involves reusing recorded music or sounds from another source and is common in genres like hip-hop and rap. We trained a deep learning model to identify samples in a large music catalog from Spotify and developed an interactive web application <br><img src='/images/sampleid-webapp_img.PNG'>"
collection: portfolio
---

<img src='/images/sampleid-webapp_img.PNG' href="https://huwcheston.github.io/sample-id-webapp/sample_explorer/sample_explorer.html">

 [![Paper](http://img.shields.io/badge/Paper-DOI:_10.48550/arXiv.2502.06364-blue)](https://doi.org/10.48550/arXiv.2502.06364) [![Webapp](http://img.shields.io/badge/Explore_the_model_predictions-blue)](https://huwcheston.github.io/sample-id-webapp/sample_explorer/sample_explorer.html)<br>

Sampling involves reusing recorded music or sounds from another source and is common in genres like hip-hop and rap. Numerous services have emerged that allow users to identify connections between samples and the songs that incorporate them, with the goal of enhancing music discovery.

We trained a neural network on an artificial dataset of **fake samples** and demonstrated that it can out-perform previous algorithms (e.g., Shazam) in detecting samples by **over 9 times**. Our model can also recognise samples that have been pitch shifted and time stretched. It is even capable of locating the position of the original sample to within five seconds for over half of the recordings we tested.

We visualised the predictions of the model using an [interactive web application](https://huwcheston.github.io/sample-id-webapp/sample_explorer/sample_explorer.html). You can click the "Play Track" and "Play Sample" buttons to see where the model thinks the sample comes from originally. **All timestamps were located automatically with no human input.**

**Work completed as an intern at [Spotify Research (Audio Intelligence)](https://research.atspotify.com/audio-intelligence/)**