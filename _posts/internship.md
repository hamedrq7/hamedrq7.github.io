---
title: finally finished my internship
date: 2023-10-17
---
I finally finished writing my report for my summer internship! I started working at Neurosina in late July. The internship project involved developing a seizure detection model using multimodal biosignals from the Empatica E4 wristband.

This summer internship was my first job outside of university, in a more professional setting. Although I hadn't previously worked with biomedical data, I knew it needed way more preprocessing and data cleaning than image benchmark datasets. However, I was still surprised at how much preprocessing it required. In addition to missing data, some were inaccurate, and due to the large volume of the data, we couldn't manually clean it up. Instead, we had to use a signal quality evaluation algorithm to generate a signal quality control signal and detect any invalid data.

The temporal aspect of data collected over 6 months was my primary challenge. While in an image, each sample is simply a HxWxC matrix, working with 5 signals over 6 months took more work. Defining one "sample" became a difficult task. It became more clear to me after reading some other papers that tackled seizure prediction using temporal biosignals.

One of the challenges I faced was figuring out how to use machine learning methods I've learned on biosignals effectively. While there are a lot of promising methods for image and text analysis, it's not entirely clear how well they'll work for biosignals. For example, Applying ZCA whitening on images has a noticeable impact that can be perceived visually ([link](https://bbabenko.github.io/low-level-features/)). However, what effect will it have on a single epoch of biosignals?


Here is my final report by the way: 
https://github.com/hamedrq7/hamedrq7.github.io/blob/master/assets/posts/internship/Automatic%20epileptic%20seizure%20detection%20using%20multimodal%20biosignals%20recorded%20from%20a%20wearable%20device.pdf

Overall, this internship was a positive experience for me. I not only gained new experiences working with real-world data but also developed my professional skills. 

