## Low-Light Image Restoration in Limited  Labeled Training Data Regime 


### Abstract

Convolutional neural networks based low-light image restoration models require large amounts of aligned low-light and ground-truth image pairs for training. Capturing such a large aligned dataset is very tedious. Thus, we study the problem when only very few labeled image pairs are available for training. We propose a novel and effective way to create more low-light and ground-truth image pairs. We introduce a contrast distortion auto-encoder framework that learns to disentangle the contrast distortion and content features from a low-light image. The contrast distortion features from a low-light image are then fused with the content features from another pristine image to create a low-light version of the pristine image. We then use the generated data to train low-light image restoration models. We evaluate our data generation method in the 5-shot and 10-shot labeled data settings to show the effective performance of our models.


[Imgur](https://imgur.com/Bs7fTsV)

