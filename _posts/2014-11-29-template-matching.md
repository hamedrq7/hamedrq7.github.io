---
title:  "First Blog"
date:   2222-11-29
---

# Latent Traversal
As a part of this project, which was a homework for neural network course, i trained deep convolutional GAN on CIFAR10 and mamals of REAL domain of DomainNet dataset. 
The fake images are pretty satisfactory, for the domain net, they do look like mammals if i take off my glasses :) 

by looking at the fake images i noticed that model produces images that look real only if your eyes are blury / you have water on your eyes. the overall scheme of the images look like the dataset, if you pan out 10 x 10 of the fake images and put it side by side of another 10 x 10 image grid of the original dataset, one might think they are all real images of the dataset at first glance. this is largely possible since the color scheme and background scheme of the fake images is similar to real images. in other words the model can "easily" get away of producing detailed images by learning color scheme and background. 

i couldn't get any more out of the models, so i used a simpler dataset of clipart domain of the domain net. in this domain, the details are more noticable and the fake images are easily recogonizble by eye. 
