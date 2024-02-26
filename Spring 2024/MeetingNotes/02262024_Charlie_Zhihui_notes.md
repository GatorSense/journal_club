# Meeting Summary for Journal Club Spring 2024

**Date & Time:** Feb 26, 2024 09:24 AM Eastern Time (US and Canada)
**Meeting ID:** 963 8959 6551

## Quick recap

Mala discussed several topics related to image processing and convolutional networks. She proposed a solution involving the introduction of a pixel adaptive convolution network, highlighting the shortcomings of previous methods. She also discussed the use of a dynamic convolution layer and the challenges it poses. Additionally, she explained the idea of a Convolutional Adjustable Filter and the details of an image processing function, focusing on the use of Gaussian kernels and image coordinates.

## Summary

### Introducing Pixel Adaptive Convolution Network

Mala discussed problems with previous methods and proposed a solution involving the introduction of a pixel adaptive convolution network. She highlighted the shortcomings of the previous method, such as not being replenishable and being too specific. Mala proposed the use of a separate network to predict the waste of their theater. She also discussed the use of a dynamic convolution layer and the challenges it poses, such as considerable computation overheads and the need to restrict the dimension of features. Finally, Mala explained the idea of a Convolutional Adjustable Filter (CAF) which could capture features from the original input and use a kernel on that feature to extract content-related values.

### Image Processing Function Details Discussed

Mala discussed the details of an image processing function, focusing on the use of Gaussian kernels and image coordinates. There were several questions about the size and structure of the vectors involved, which Mala clarified contained image coordinates and color information. Mala also touched on the role of a special spatial filter and the possibility of learning the value of 'K'. She suggested revisiting the topic to ensure all participants understood the concepts. Mala also discussed the initialization and learning process of a kernel, expressing confusion about the parameters that needed to be initialized and what needed to be learned. She clarified that the kernel was not learned but was used in the learning process, though she found it unclear what exactly needed to be learned.



### Sliding Window Method and Semantic Segmentation Discussion

Mala discussed the sliding window method in standard convolution, focusing on the dimensionality of Fi and Fj and the assignment of weights to pixel values based on their similarity to the center point. She also touched on scaling the width and output of the kernel in relation to input pixels, the process of discarding pixels that are not similar to the central pixel, and the concept of a fully connected network. Towards the end, Mala discussed the application of the Psc in semantic segmentation tasks, noting that it provides more specific information compared to a fully connected network.


### Performance, Upscaling, and Training of a New Feature

Mala and her team discussed the performance of a new feature in their system that was having trouble distinguishing between similar neighbors. She proposed a method to upscale a low-resolution signal using a high-resolution signal of a different form, such as an RGB image. The team also touched on the training of their PAC function and the use of a trained W function. Mala addressed the idea of using the bottom left block to train weights on the Pac layer without needing pairs of X and X. She highlighted several projects related to data resolution enhancement and retraining of algorithms, including a Navy-funded project involving new, higher resolution sensors, a project involving tree species classification, and an ended project that involved imaging plant roots in the field using low resolution X-ray data.


### Random Fields and Logistic Regression Discussion

Mala discussed the fifth section of a paper about random fields and logistic regression, emphasizing the method's difference from traditional logistic regression by treating each pixel independently. She also explained the use of the Kronecker delta function to determine pixel averages. The conversation delved into the complexities of minimizing the Kullback-Leibler divergence. Mala also introduced a generalized spatial convolution method with improved information about function values, which she described as a simplified version of a Convolutional Neural Network (CNN). She highlighted that the method doesn't require destroying old networks to work and can be applied to pre-trained models. Mala expressed skepticism about the method's content-agnostic claim, arguing that it doesn't use the image's content to pick weights.
