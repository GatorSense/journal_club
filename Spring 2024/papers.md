# Paper List - Spring 2024
**Please utilize the following paper list as a "heavily-weighted" guideline for your journal club presentation. While you are not required to stay within this paper list, the provided references have been chosen from well-reviewed and well-cited publications.**

## Table of Contents
1. [Overall Comments](#overall-comments)
1. [Adaptive Convolutions](#adaptive-convolutions)
    1. [Grid-Based](#grid-based)
        1. [1-Dimensional](#1-dimensional)
        1. [2-Dimensional](#2-dimensional)
        1. [3-Dimensional](#3-dimensional)
    1. [Point-Based (Sparse-Grid)](#point-based-sparse-grid)
    1. [Hyperspectral Data Applications](#hyperspectral-data-applications)
    1. [Other Applications](#other-applications)
1. [Additional Resources](#additional-resources)

## Overall Comments
- Idea of adaptive convolution filters may be categorized into 1D, 2D, 3D, point cloud (graphical)…?
- Paper Research Trends:
    - More weights per channel (multiple filters that are somehow combined into one filter)
    - Gaussian parameters to control receptive field size.
    - Channel-based versus spatial-based (should probably focus on spatial-based)

## Adaptive Convolutions

### Grid-Based

#### 1-Dimensional

1. Q. Xiao et al., “Dynamic sparse network for time series classification: Learning what to ‘see.’” [nips 2022 link](https://proceedings.neurips.cc/paper_files/paper/2022/file/6b055b95d689b1f704d8f92191cdb788-Paper-Conference.pdf) (accessed Jan. 30, 2024).

#### 2-Dimensional

2. H. Su, V. Jampani, D. Sun, O. Gallo, E. Learned-Miller, and J. Kautz, “Pixel-Adaptive Convolutional Neural Networks,” in 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), IEEE, Jun. 2019. doi: 10.1109/cvpr.2019.01142.

3. D. Tabernik, M. Kristan, and A. Leonardis, “Spatially-Adaptive Filter Units for Compact and Efficient Deep Neural Networks,” Int. J. Comput. Vis., vol. 128, no. 8, pp. 2049–2067, Sep. 2020.

4. W. Wang et al., “InternImage: Exploring large-scale vision foundation models with deformable convolutions,” in 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), IEEE, Jun. 2023. doi: 10.1109/cvpr52729.2023.01385.

5. J. Zamora Esquivel, A. Cruz Vargas, P. Lopez Meyer, and O. Tickoo, “Adaptive Convolutional Kernels,” in 2019 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW), IEEE, Oct. 2019. doi: 10.1109/iccvw.2019.00249.

6. X. Zhu, H. Hu, S. Lin, and J. Dai, “Deformable ConvNets V2: More Deformable, Better Results,” in 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), IEEE, Jun. 2019. doi: 10.1109/cvpr.2019.00953.

#### 3-Dimensional

7. T. W. Mitchel, V. G. Kim, and M. Kazhdan, “Field Convolutions for Surface CNNs,” in 2021 IEEE/CVF International Conference on Computer Vision (ICCV), IEEE, Oct. 2021. doi: 10.1109/iccv48922.2021.00985.

### Point-Based (Sparse-Grid)

8. Y. Wang, Y. Sun, Z. Liu, S. E. Sarma, M. M. Bronstein, and J. M. Solomon, "Dynamic Graph CNN for Learning on Point Clouds," ACM Trans. Graph., vol. 38, no. 5, pp. 1–12, Oct. 2019.

9. M. Wei et al., "AGConv: Adaptive Graph Convolution on 3D Point Clouds," IEEE Trans. Pattern Anal. Mach. Intell., vol. 45, no. 8, pp. 9374–9392, Aug. 2023.

10. W. Wu, L. Fuxin, and Q. Shan, "PointConvFormer: Revenge of the Point-based convolution," in 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), IEEE, Jun. 2023. doi: 10.1109/cvpr52729.2023.02088.

11. C. Xu et al., "SqueezeSegV3: Spatially-Adaptive Convolution for Efficient Point-Cloud Segmentation," arXiv [cs.CV], Apr. 03, 2020. [Online]. Available: [arXiv:2004.01803](http://arxiv.org/abs/2004.01803)

### Hyperspectral Data Applications

12. Jia, Sen, et al. "Structure-Adaptive Convolutional Neural Network for Hyperspectral Image Classification." IEEE Transactions on Geoscience and Remote Sensing (2023).

13. Ren, Qi, et al. "Multiscale adaptive convolution for hyperspectral image classification." IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 15 (2022): 5115-5130.


### Other Applications

14. Chandran, Prashanth, et al. "Adaptive convolutions for structure-aware style transfer." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2021.

15. R. Zhang, S. Tang, Y. Zhang, J. Li, and S. Yan, "Perspective-Adaptive Convolutions for Scene Parsing," IEEE Trans. Pattern Anal. Mach. Intell., vol. 42, no. 4, pp. 909–924, Apr. 2020.

### Summer 2024 - Additions
The following has been briefly skimmed and may or may not be a good representative of "adaptive" convolutions.

16. X. He, B. Wang, Y. Hu, J. Gao, Y. Sun, and B. Yin, "Parallelly Adaptive Graph Convolutional Clustering Model," IEEE Trans Neural Netw Learn Syst, vol. 35, no. 4, pp. 4451–4464, Apr. 2024.

## Additional Resources
**These are not recommended for Journal Club presentations** but are provided for quick reference to background information that may aid the group in understanding related topics.

- J. Dai et al., “Deformable convolutional networks,” in Proceedings of the IEEE international conference on computer vision, 2017, pp. 764–773.

- P. Dewaele, L. Van Gool, A. Wambacq, and A. Oosterlinck, “Texture inspection with self-adaptive convolution filters,” in [1988 Proceedings] 9th International Conference on Pattern Recognition, IEEE, 1988, pp. 56–60 vol.1.

- P. F. Felzenszwalb, R. B. Girshick, D. McAllester, and D. Ramanan, “Object detection with discriminatively trained part-based models,” IEEE Trans. Pattern Anal. Mach. Intell., vol. 32, no. 9, pp. 1627–1645, Sep. 2010.

- M. Jaderberg, K. Simonyan, A. Zisserman, and Others, “Spatial transformer networks,” Adv. Neural Inf. Process. Syst., vol. 28, 2015, [Online]. Available: [nips 2015 link](https://proceedings.neurips.cc/paper_files/paper/2015/file/33ceb07bf4eeb3da587e268d663aba1a-Paper.pdf).

- T. W. Mitchel, B. Brown, D. Koller, T. Weyrich, S. Rusinkiewicz, and M. Kazhdan, “Efficient Spatially Adaptive Convolution and Correlation,” arXiv [cs.CV], Jun. 23, 2020. [Online]. Available: [arXiv:2006.13188](http://arxiv.org/abs/2006.13188).

- S. Song, M.-C. Sagong, S.-W. Jung, and S.-J. Ko, “Semantic and Instance-Aware Pixel-Adaptive Convolution for Panoptic Segmentation,” in 2023 IEEE International Conference on Image Processing (ICIP), IEEE, Oct. 2023, pp. 16–20.
    - Interesting idea but unpublished.
