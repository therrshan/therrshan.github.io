---
name: AOD NET - PyTorch implementation.
tools: [Pytorch, CNN, Python]
image: https://raw.githubusercontent.com/therrshan/therrshan.github.io/main/assets/img/3.png
description: A pytorch implementation of AOD-Net - All-in-One Network for Dehazing
---

# AOD NET - PyTorch implementation.
<br>


<p style='text-align: justify;'> AOD NET : All in One Dehazer Network is a custom fog removal model on the hazy images using transmission maps and atmospheric guided light. It is designed based on a re-formulated atmospheric scattering model. Instead of estimating the transmission matrix and the atmospheric light separately as most previous models did, AOD-Net directly generates the clean image through a light-weight CNN. </p>
[Boyiliee/AOD-Net](https://github.com/Boyiliee/AOD-Net) the original author's project, developed based on pycaffe, only has pre-trained model and inference code.

<br>
![](https://www.researchgate.net/profile/Zhangyang-Wang/publication/319662852/figure/fig1/AS:538546299314176@1505410851554/The-AOD-Net-architecture-for-single-image-dehazing-Li-et-al-2017a-2017b-which.png)
<br>

<p style='text-align: justify;'> This implementation however consists both train and test files. The pretrained weights of the models are used to test the model on the images. The pytorch implemetation of the All in One Networkm for Dehazingn was inspired from this.</p> [Repo](https://github.com/walsvid/AOD-Net-PyTorch).

<br>

### Results


Test Image             |  Output Image
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/therrshan/FogRemoval-AODNET/main/test_images/test.png)  |  ![](https://raw.githubusercontent.com/therrshan/FogRemoval-AODNET/main/Results/test.png)


<br>
{% include elements/button.html link="https://github.com/therrshan/FogRemoval-AODNET" text="GitHub" block=true %}