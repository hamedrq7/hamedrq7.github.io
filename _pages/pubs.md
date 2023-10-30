---
layoutl: defaults
title: "Projects"
permalink: "/projects.html"
---
please see [my github page](https://github.com/hamedrq7) for more updated information.


### "Factorizing MultiModal Variational AutoEncoders using InfoNCE" 
- Explored state of the art MultiModal VAEs for learning a factorized representation by utilizing infoNCE.
- Experimented with different VAEs and parameters to find their effectiveness in a multimodal image dataset.
- Used MMVAE as a baseline model to learn modality-specific and joint multimodal space for cross-modal and joint generation.
- Experimented with MNIST-SVHN to do cross-modal/unimodal/joint generation.
  
[[Repository](https://github.com/hamedrq7/factorizing-mmvae)]

### "Unsupervised Visual Feature Learning with DCGAN and AE"
- Trained a Deep Convolutional GAN on DomainNet real domain and CIFAR10 images.
- Used The Discriminator of GAN as a feature extractor to classify images with random forest.
- Trained a Denoising AutoEncoder on DomainNet real domain and CIFAR10 images and used the encoder as a feature extractor to further classify images.

[[Repository](https://github.com/hamedrq7/Unsupervised-Visual-Feature-Learning-with-DCGAN-and-AE)]


### "Sentiment Classiﬁcation on Amazon review dataset"
- Experimented with different architectures of MultiLayer RNN, LSTM, and GRU to train a model for sentiment analysis on the Magazine Subscription category of the Amazon review dataset.
-  Implemented a custom batch sampler to produce similar-length data for each batch in order to utilize the full
potential of RNNs.

[[Repository](https://github.com/hamedrq7/Sentiment-Classification-on-Amazon-review-dataset)]

### "Transfer Learning for image classification"
- Used various pre-trained models (Resnet18, VGG11, Densenet121, trained on imagenet) for Dogs vs Cats dataset.
- Evaluated different transfer learning techniques (block-wise freezing, layer-wise learning rates, fine-tuning
with layer warmup) to find an optimal strategy for training classifying Dogs vs Cats dataset.

[[Repository](https://github.com/hamedrq7/Transfer-Learning-for-image-classification)]
