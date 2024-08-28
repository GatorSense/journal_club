# Paper List - Fall 2024
**Please utilize the following paper list as a "heavily-weighted" guideline for your journal club presentation. While you are not required to stay within this paper list, the provided references have been chosen from well-reviewed and well-cited publications.**

## Table of Contents
1. [Overall Comments](#overall-comments)
1. [NN-based State-Space Models](#nn-based-state-space-models)
    1. [Fundamental Publications](#fundamental-publications)
    1. [Applications - Autonomous Driving](#applications---autonomous-driving)
    1. [Applications - Remote Sensing](#applications---remote-sensing)
    1. [Applications - Physics-Informed ML](#applications---physics-informed-ml)
    1. [Other Applications](#other-applications)
        1. [Tracking](#tracking)
        1. [Decision and Planning](#decision-and-planning)
        1. [Language Modeling](#language-modeling)
1. [Additional Resources](#additional-resources)

## Overall Comments
- Deep State-Space Models (SSMs) have surged in popularity due to problems with Transformers.
- Potential Keywords:
    - Structured state-space models
    - Scanning Paths
    - Long-range dependencies

## NN-based State-Space Models

### Fundamental Publications

1. A. Gu, K. Goel, and C. Re, "Efficiently Modeling Long Sequences with Structured State Spaces," in International Conference on Learning Representations, 2021. [Paper Link](https://openreview.net/pdf?id=uYLFoz1vlAC)
    - [Follow-up ("Mamba", rejected for ICLR’24 for some reason)](https://arxiv.org/abs/2312.00752)

1. A. Klushyn, R. Kurle, M. Soelch, B. Cseke, and P. van der Smagt, "Latent Matters: Learning Deep State-Space Models," Advances in Neural Information Processing Systems, vol. 34, pp. 10234–10245, Dec. 2021. [Paper Link](https://proceedings.neurips.cc/paper_files/paper/2021/file/54b2b21af94108d83c2a909d5b0a6a50-Paper.pdf)

1. A. Gupta and J. Berant, "Diagonal state spaces are as effective as structured state spaces," Neural Inf Process Syst, vol. abs/2203.14343, Mar. 2022. [Paper Link](https://arxiv.org/abs/2203.14343)

1. R. Hasani, M. Lechner, T.-H. Wang, M. Chahine, A. Amini, and D. Rus, "Liquid Structural State-Space Models," in The Eleventh International Conference on Learning Representations, 2022. [Paper Link](https://openreview.net/pdf?id=g4OTKRKfS7R)

1. G. Revach, N. Shlezinger, X. Ni, A. L. Escoriza, R. J. G. van Sloun, and Y. C. Eldar, "KalmanNet: Neural network aided Kalman filtering for partially known dynamics," IEEE Trans. Signal Process., vol. 70, pp. 1532–1547, 2022. [Paper Link](http://dx.doi.org/10.1109/TSP.2022.3158588)

1. L. Zhu, B. Liao, Q. Zhang, X. Wang, W. Liu, and X. Wang, "Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model," in International Conference on Machine Learning, 2024, pp. 62429–62442. [Paper Link](https://proceedings.mlr.press/v235/zhu24f.html)

1. Rangapuram, Syama Sundar, et al. "Deep state space models for time series forecasting." Advances in neural information processing systems, 31, 2018. [Paper Link](https://proceedings.neurips.cc/paper/2018/hash/5cf68969fb67aa6082363a6d4e6468e2-Abstract.html)

1. Mücke, Nikolaj T., Sander M. Bohté, and Cornelis W. Oosterlee. “The Deep Latent Space Particle Filter for Real-Time Data Assimilation with Uncertainty Quantification.” Scientific Reports 14, no. 1 (August 21, 2024): 19447. [Paper Link](https://doi.org/10.1038/s41598-024-69901-7)


### Applications - Autonomous Driving
9. H. Wen, X. Chen, G. Papagiannis, C. Hu, and Y. Li, "End-to-end semi-supervised learning for differentiable particle filters," in 2021 IEEE International Conference on Robotics and Automation (ICRA), Xi’an, China, 2021. [Paper Link](http://dx.doi.org/10.1109/ICRA48506.2021.9561889)

9. Cui H, Nguyen T, Chou F C, et al. Deep kinematic models for kinematically feasible vehicle trajectory predictions[C]//2020 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2020: 10563-10569. [Paper Link](http://dx.doi.org/10.1109/icra40945.2020.9197560)

### Applications - Remote Sensing

11. G. Fu, F. Xiong, J. Lu, and J. Zhou, "SSUMamba: Spatial-spectral selective state space model for hyperspectral image denoising," IEEE Trans. Geosci. Remote Sens., vol. PP, no. 99, pp. 1–1, 2024. [Paper Link](https://ieeexplore.ieee.org/document/10643108)

11. K. Chen, B. Chen, C. Liu, W. Li, Z. Zou, and Z. Shi, "RSMamba: Remote sensing image classification with state space model," IEEE Geosci. Remote Sens. Lett., vol. 21, pp. 1–5, 2024. [Paper Link](https://ieeexplore.ieee.org/document/10542538)

11. X. Ma, X. Zhang, and M.-O. Pun, "RS^3mamba: Visual state space model for remote sensing image semantic segmentation," IEEE Geosci. Remote Sens. Lett., vol. 21, pp. 1–5, 2024. [Paper Link](https://ieeexplore.ieee.org/document/10556777)
    - ***Please present the RSMamba paper first if it hasn’t been presented already.***

11. Y. Wang, W. Yuan, F. Xie, and B. Lin, "ESatSR: Enhancing super-resolution for satellite remote sensing images with state space model and spatial context," Remote Sens. (Basel), vol. 16, no. 11, p. 1956, May 2024. [Paper Link](https://www.mdpi.com/2072-4292/16/11/1956)


### Applications - Physics-Informed ML

15. Florian Arnold, Rudibert King, "State–space modeling for control based on physics-informed neural networks," Engineering Applications of Artificial Intelligence, vol. 101, ISSN 0952-1976, 2021. [Paper Link](https://doi.org/10.1016/j.engappai.2021.104195)

15. Chrosniak J, Ning J, Behl M. Deep Dynamics: Vehicle Dynamics Modeling with a Physics-Constrained Neural Network for Autonomous Racing[J]. IEEE Robotics and Automation Letters, 2024. [Paper Link](https://arxiv.org/abs/2312.04374)

### Other Applications

#### Tracking
14. K. Wang, J. Chen, Z. Song, Y. Wang, and C. Yang, "Deep neural network-embedded stochastic nonlinear state-space models and their applications to process monitoring," IEEE Trans. Neural Netw. Learn. Syst., vol. 33, no. 12, pp. 7682–7694, Dec. 2022. [Paper Link](http://dx.doi.org/10.1109/TNNLS.2021.3086323)

14. V. D. Stanojevic and B. T. Todorovic, "BoostTrack: boosting the similarity measure and detection confidence for improved multiple object tracking," Mach. Vis. Appl., vol. 35, no. 3, pp. 1–15, May 2024. [Paper Link](http://dx.doi.org/10.1007/s00138-024-01531-5)
    - N. Wojke, A. Bewley, and D. Paulus, "Simple online and realtime tracking with a deep association metric," in 2017 IEEE International Conference on Image Processing (ICIP), Beijing, 2017, pp. 3645–3649. [Paper Link](http://dx.doi.org/10.1109/ICIP.2017.8296962)
    - A. Bewley, Z. Ge, L. Ott, F. Ramos, and B. Upcroft, "Simple online and realtime tracking," in 2016 IEEE International Conference on Image Processing (ICIP), Phoenix, AZ, USA, 2016, pp. 3464–3468. [Paper Link](http://dx.doi.org/10.1109/ICIP.2016.7533003)

14. Y.-H. Wang, J.-W. Hsieh, P.-Y. Chen, M.-C. Chang, H. H. So, and X. Li, "SMILEtrack: SiMIlarity LEarning for occlusion-aware Multiple Object Tracking," arXiv [cs.CV], 16-Nov-2022. [Paper Link](https://arxiv.org/abs/2211.08824)
    - Accepted to AAAI’24

14. K. Yi et al., "UCMCTrack: Multi-object tracking with uniform Camera Motion Compensation," arXiv [cs.CV], 14-Dec-2023. [Paper Link](https://arxiv.org/abs/2312.08952)
    - Accepted to AAAI’24

#### Decision and Planning
18. Y. Han and P. Gmytrasiewicz, "IPOMDP-net: A deep neural network for partially observable multi-agent planning using interactive POMDPs," Proc. Conf. AAAI Artif. Intell., vol. 33, no. 01, pp. 6062–6069, Jul. 2019. [Paper Link](http://dx.doi.org/10.1609/aaai.v33i01.33016062)

18. C. Stöckl, Y. Yang, and W. Maass, "Local prediction-learning in high-dimensional spaces enables neural networks to plan," Nat. Commun., vol. 15, no. 1, p. 2344, Mar. 2024. [Paper Link](http://dx.doi.org/10.1038/s41467-024-46586-0)

18. Gelada C, Kumar S, Buckman J, et al. Deepmdp: Learning continuous latent space models for representation learning//International conference on machine learning. PMLR, 2019: 2170-2179. [Paper Link](https://proceedings.mlr.press/v97/gelada19a/gelada19a.pdf)

#### Language Modeling
21. Liu T Y, Trager M, Achille A, et al. Meaning representations from trajectories in autoregressive models. arXiv preprint arXiv:2310.18348, 2023. [Paper Link](https://arxiv.org/abs/2310.18348)
    - Accepted to ICLR'24

## Additional Resources
Please do not present these for Journal Club presentations but use them for quick reference to background information that may aid the group in understanding related topics.

Jesús M. Zamarreño, Pastora Vega, "State space neural network. Properties and application", Neural Networks, vol. 11, no. 6, pp. 1099-1112, 1998. [Paper Link](https://doi.org/10.1016/S0893-6080(98)00074-4)

C. A. Alonso, J. Sieber, and M. N. Zeilinger, "State space models as foundation models: A control theoretic overview," arXiv [eess.SY], 25-Mar-2024.

J. Sieber, C. A. Alonso, A. Didier, M. N. Zeilinger, and A. Orvieto, "Understanding the differences in foundation models: Attention, State Space Models, and Recurrent Neural Networks," arXiv [cs.LG], 24-May-2024.