# CycleGAN

The primary objective of this task is to develop a CycleGAN, a type of Generative Adversarial Network (GAN), for the purpose of transforming images within the MNIST dataset. Specifically, the images of digits are intended to be colorized, with each digit associated with a predetermined color. The dataset is prepared in two versions, wherein distinct predetermined colors are assigned to the digits. The model architecture consists of generators and discriminators. 

The generator employs Convolutional Neural Network (CNN) layers featuring convolution, instance normalization, and leaky Rectified Linear Unit (ReLU) activation.
Additionally, residual blocks are incorporated to address potential issues related to vanishing gradients.

On the other hand, the discriminator utilizes CNN layers with instance normalization, leaky ReLU activation, and concludes with a final convolutional layer incorporating sigmoid activation for binary classification.

The training process follows an adversarial approach, where the generators aim to produce realistic images, and the discriminators aim to distinguish between genuine and generated images. The loss function encompasses adversarial losses for both generators and discriminators, alongside a cycle consistency loss.  
