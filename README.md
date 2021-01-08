# DoubleUnet-pytroch-implementation
Aim to build a flexible structure with doubleunet structure.
Implement double-unet according to the paper "DoubleU-Net: A Deep Convolutional NeuralNetwork for Medical Image Segmentation"
add a few changes:
1.upsample method with transpose convolution so the parameters can be learned.
2.change bilinear layer into 1x1 conv.
3.a few changes on the shortcuts.
3.so far still build with vgg19-bn as base model.
