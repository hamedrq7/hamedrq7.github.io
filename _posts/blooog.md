---
title:  "Latent Traversal"
date: 2000-08-05
---


As a part of this project, which was a homework for neural network course, i trained deep convolutional GAN on CIFAR10 and mamals of REAL domain of DomainNet dataset. 
The fake images are pretty satisfactory, for the domain net, they do look like mammals if i take off my glasses :) 

by looking at the fake images i noticed that model produces images that look real only if your eyes are blury / you have water on your eyes. the overall scheme of the images look like the dataset, if you pan out 10 x 10 of the fake images and put it side by side of another 10 x 10 image grid of the original dataset, one might think they are all real images of the dataset at first glance. this is largely possible since the color scheme and background scheme of the fake images is similar to real images. in other words the model can "easily" get away of producing detailed images by learning color scheme and background. 

i couldn't get any more out of the models, so i used a simpler dataset of clipart domain of the domain net. in this domain, the details are more noticable and the fake images are easily recogonizble by eye. 
![[real vs fake images-299.png|500]]
### Latent Traversal: 
at the time of doing this homework, i stumbled upon this figure in the paper MMVAE that i was reading and wanted to see the latent traversal for gans: .... 

After watching some of the generated images, i collected some of the more meaningful ones and traced what noise was fed to the model that produced the images. then i traversed through each dimension, while fixing the other dimensions. while not all the dimensions are meaningful (since i haven't regularized the space at all), some at least looks interesting. 


### 3D angle: 
	![[27.jpg]]

### Background:


Here are some good fake images as a bonus: 
