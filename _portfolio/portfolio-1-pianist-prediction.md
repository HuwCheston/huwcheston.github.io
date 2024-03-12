---
title: "Jazz Performer Identification Model"
excerpt: "An automated pipeline that uses <b>deep-learning assisted audio signal processing</b> to <b>identify the performer</b> playing on a given jazz recording.<br><img src='/images/pianist-prediction_img.png'>"
collection: portfolio
---

<img src='/images/pianist-prediction_img.png' href="https://huwcheston.github.io/Cambridge-Jazz-Trio-Database/_static/prediction-app.html">

**Run the model on your own tracks online!** <a target="_blank" href="https://colab.research.google.com/github/HuwCheston/Cambridge-Jazz-Trio-Database/blob/main/example.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a><br>
**Explore the model predictions interactively!** [![Code](http://img.shields.io/badge/Open_Prediction_Map-blue)](https://huwcheston.github.io/Cambridge-Jazz-Trio-Database/_static/prediction-app.html)<br>

[![Code](http://img.shields.io/badge/Code-available_on_GitHub-purple)](https://github.com/HuwCheston/Cambridge-Jazz-Trio-Database) [![Documentation](http://img.shields.io/badge/Documentation-available_online-purple)](https://huwcheston.github.io/Cambridge-Jazz-Trio-Database/)

Great musicians and artists have a **unique style** that is recognisable as 'theirs'; arguably, this is what makes them great! But, while the differences in style between any two performers are often evident intuitively, they can be **hard to describe in words**. We developed an automated pipeline that can identify the piano player on a jazz recording with a degree of accuracy **over five times better than chance** alone. 

Using **deep-learning assisted signal processing,** the pipeline works directly on an audio recording and extracts a suite of musical features that constitute its **stylistic fingerprint**. The pipeline is trained on the [Cambridge Jazz Trio Database]({{ site.baseurl }}/publications/2024-01-31-cambridge-jazz-trio-database-paper/), a dataset of approximately 16 hours of commercial recordings with onset and beat annotations. The pipeline has applications to **music engineering** (recommendation and classification algorithms), **education** (providing feedback to performers) and **broader science** (joint action, forensic stylometry). Our work showcases how machine learning can bridge the gap between intuition and quantifiable analysis of art, presenting a paradigm applicable across many domains.