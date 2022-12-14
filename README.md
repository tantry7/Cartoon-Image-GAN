Generating cartoon faces using a Deep Convolutional Generative Adversarial Network (DCGAN).    

# Dataset 
The dataset is taken from [here](https://google.github.io/cartoonset/download.html). 
processed using a face detector based on the repo https://github.com/nagadomi/lbpcascade_animeface. 
The dataset contains images of size 64 by 64 pixels.  
# Objective 
- The objective of the project is to generate images of Cartoon faces using a Deep Convolutional GAN. 
- The DCGAN has two networks, the 'generator' and the 'discriminator'.   
- The generator takes in a random vector which then uses transposed convolutions to generate an image out of it.   
- The discriminator is a Convolutional network which then classifies whether an image is real or fake. It takes in samples of images from the dataset  and also images generated by the generator.  
- Both networks try to improve each other's performance through backpropagation.
