# Meeting Summary for Journal Club Spring 2024

**Date & Time:** Feb 12, 2024 09:31 AM Eastern Time (US and Canada)  
**Meeting ID:** 963 8959 6551

## Quick recap

The meeting primarily focused on the limitations of convolutional neural networks (CNNs) and potential enhancements. The conversation explored the fixed kernel size in CNNs and its impact on adaptability to different objects and learning additional transformations. The meeting also delved into the workings of a model that uses pixel values and offsets to generate an output feature map. The discussion further explored the process of deformable region of interest pooling, position-sensitive region of interest pooling, and the training process of the offsets in this system.

## Summary

### CNN Limitations in Geometric Transformations

Alina Zare and MALA 7200 discussed the limitations of convolutional neural networks (CNNs) in modeling geometric transformations. They explored how the fixed kernel size in CNNs restricts their ability to adapt to different objects and learn additional transformations, which MALA 7200 referred to as a "current flaw". They also discussed the concept of receptive fields in CNNs, with MALA 7200 explaining that the receptive field remains constant throughout all layers. The possibility of enhancing receptive fields with deformal convolutions was also discussed, with MALA 7200 suggesting that these could be incorporated into any existing CNN.

### Model and Deformable Feature Mapping Discussion

Mala 7200 discussed the workings of a particular model that uses pixel values and offsets to generate an output feature map. The model employs a 3x3 kernel and weights, with parameters such as the kernel weights and shifts being learned during training. The conversation also touched on deformable models, which alter the sampling location, and the use of bilinear interpolation to view fractional indices of the image. Mala clarified that there are no explicit constraints on the shift, known as Delta Pm, which will converge if it's outside the image boundaries. The discussion also explored the process of deformable region of interest pooling, which involves spreading regions of interest across the input feature maps, offsetting these regions, and taking the pixel values from the entire offset regions. The output is then normalized by the number of pixels in the bin to prevent an enormous number in the outputs.

### Normalizing and Scaling Delta P Hat Values Explained

MALA 7200 explained the process of normalizing and scaling the Delta P hat values in relation to the width and height of the region of interest. He also touched on the concept of position-sensitive region of interest pooling, which involves taking the regions
