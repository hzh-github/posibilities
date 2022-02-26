### 1. Background introduction of Chinese herbal medicine identification project

As General Secretary Xi Jinping said: "Traditional Chinese medicine is the treasure of ancient Chinese science and the key to unlocking the treasure house of Chinese civilization." In fact, Chinese herbal medicine has been quietly integrated into all aspects of our lives, such as the toothpaste we use, many of which have been added to Chinese medicine The extract of Chinese medicine, through "Chinese medicine tooth care", uses the efficacy of Chinese medicine to relieve problems such as gum pain. Another example is the wolfberry that mothers often put in chicken soup, which has the functions of nourishing the liver, improving eyesight, moistening the lungs and soothing the nerves, increasing the nutritional value of chicken soup. Through the identification of Chinese herbal medicines, it can not only make the Chinese herbal medicines who silently dedicate to us better known, but also help Chinese medicine practitioners to better guide patients to grasp and use medicines. It can even be deployed in mobile apps or small programs, making it more convenient and easy to use.

### 2. Data introduction

The "Chinese herbal medicine identification" data set contains 5 categories, namely honeysuckle, Codonopsis, lily, wolfberry, and locust flower, with a total of 902 pictures. You can obtain more detailed data information by running the get_data_list function in the code, as shown in the figure

![Dataset Details](https://github.com/hzh-github/posibilities/blob/main/Dataset_Details.png)

### Three, model introduction

Chinese herbal medicine identification by VGG network. VGG is one of the most popular CNN models. It was proposed in the paper "Very Deep Convolutional Networks For Large-scale Image Recognition" by Simonyan and Zisserman at the ICLR 2015 conference in 2014. Geometry Group. It consists of 5 layers of convolution layers, 3 layers of fully connected layers, and softmax output layers. By increasing the depth of the network to improve the final performance of the network, the error rate is greatly reduced.

![VGG model](https://github.com/hzh-github/posibilities/blob/main/VGG_model.png)

 _Image source: Dahua CNN classic model: VGGNet_
