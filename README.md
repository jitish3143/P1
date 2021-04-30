# Day to Night Colour Transfer using Deep Neural Networks

The project performs style transfer and is implemented using a ResNet-50 pre-trained model using U-Net style skip connections. The first input to the architecture is the conetnt image and the second input to the architecture is the results generated by the [PWCT](https://arxiv.org/abs/1802.06474) algorithm, which our project follows upon. Our algorithm works as post-processing step in removing the artefacts from the PWCT generated results. The resultant output image from out algorithm looks photorealistic with less artefacts compared to the original PWCT algorithm. 


