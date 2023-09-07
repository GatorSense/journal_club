# Paper List
**Subject to Change: The paper team and professors reserve the right to modify the following paper list throughout the semester as they may agree at a later date.**

## Table of Contents
1. [Overall Comments](#overall-comments)
2. [Some Keywords to Understand](#some-keywords-to-understand)
3. [Presenters' Challenge: "Meaningful UQ"](#presenters-challenge-meaningful-uq)
4. [Uncertainty Quantification Fundamentals](#uncertainty-quantification-fundamentals)
5. [Current Methodologies](#current-methodologies)
    1. [Safety-Critical Tasks](#safety-critical-tasks)
    1. [Structural Health Monitoring](#structural-health-monitoring)
    1. [Remote Sensing](#remote-sensing)
    1. [Medical](#medical)
6. [Future Directions and Possibilities](#future-directions-and-possibilities)
8. [Additional Resources](#additional-resources)

## Overall Comments
- Most papers were pulled from references in the survey by Abdar et al. below. There is an additional survey by Gawlikowski that provided more recent works. See the Additional Resources section below for both.
- Some papers combine Uncertainty Quantification (UQ) techniques.
- Unmentioned related topics:
    - Reinforcement learning UQ
    - Explainable AI (except for a few papers with small overlapping interest)
    - Additional methods
- Two paper sections exist: “Fundamentals and Current Methodologies” and “Future Directions”. **The paper team is not allowing papers in the latter section to be chosen until 11/1/2023** due the sparsity of such papers and the continual re-use of the fundamentals in current methodologies.

## Some Keywords to Understand
- Aleatoric and epistemic uncertainty
- Reducible and irreducible uncertainty
- Uncertainty quantification/awareness
- Predictive uncertainty
- Conformal predictions

## Presenters' Challenge: "Meaningful UQ"
If it’s not completely obvious in a paper, **the presenters** are challenged to address the following question in their presentation: _How might we translate the Bayesian, ensemble, and theoretical metrics into more meaningful UQ metrics for our labs’ particular applications?_

## Uncertainty Quantification Fundamentals

1. Y. Gal and Z. Ghahramani, “Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning,” in Proceedings of The 33rd International Conference on Machine Learning, M. F. Balcan and K. Q. Weinberger, Eds., in Proceedings of Machine Learning Research, vol. 48. New York, New York, USA: PMLR, 20--22 Jun 2016, pp. 1050–1059.
2. M. Teye, H. Azizpour, and K. Smith, “Bayesian Uncertainty Estimation for Batch Normalized Deep Networks,” in Proceedings of the 35th International Conference on Machine Learning, J. Dy and A. Krause, Eds., in Proceedings of Machine Learning Research, vol. 80. PMLR, 10--15 Jul 2018, pp. 4907–4916.
3. R. Zhang, C. Li, J. Zhang, C. Chen, and A. G. Wilson, “Cyclical Stochastic Gradient MCMC for Bayesian Deep Learning,” arXiv [cs.LG], Feb. 11, 2019. [Online]. Available: http://arxiv.org/abs/1902.03932
Note: This is a highly cited paper that builds off multiple works not mentioned in this paper list.
4. S. Hernández, D. Vergara, M. Valdenegro-Toro, and F. Jorquera, “Improving predictive uncertainty estimation using Dropout–Hamiltonian Monte Carlo,” Soft Computing, vol. 24, no. 6, pp. 4307–4322, Mar. 2020.
Note: This isn’t well-cited but demonstrates a way to combine two techniques. At face value, they appear to have good analysis of data/model evaluation.
5. T. Salimans, D. Kingma, and M. Welling, “Markov Chain Monte Carlo and Variational Inference: Bridging the Gap,” in Proceedings of the 32nd International Conference on Machine Learning, F. Bach and D. Blei, Eds., in Proceedings of Machine Learning Research, vol. 37. Lille, France: PMLR, 07--09 Jul 2015, pp. 1218–1226.
6. V. Böhm, F. Lanusse, and U. Seljak, “Uncertainty Quantification with Generative Models,” arXiv [stat.ML], Oct. 22, 2019. [Online]. Available: http://arxiv.org/abs/1910.10046
7. A. Foong, D. Burt, Y. Li, and R. Turner, “On the Expressiveness of Approximate Inference in Bayesian Neural Networks,” in Advances in Neural Information Processing Systems, H. Larochelle, M. Ranzato, R. Hadsell, M. F. Balcan, and H. Lin, Eds., Curran Associates, Inc., 2020, pp. 15897–15908.
8. C. Blundell, J. Cornebise, K. Kavukcuoglu, and D. Wierstra, “Weight Uncertainty in Neural Networks,” vol. 37, pp. 1613–1622, 07--09 Jul 2015.
9. Lakshminarayanan B, Pritzel A, Blundell C,  “Simple and scalable predictive uncertainty estimation using deep ensembles,” in Advances in neural information processing systems 30, 2017.
10. Ovadia Y, Fertig E, Ren J, Nado Z, Sculley D, Nowozin S, Dillon J, Lakshminarayanan B, Snoek J, “Can you trust your model’s uncertainty? Evaluating predictive uncertainty under dataset shift,” in Advances in neural information processing systems 32, 2019.

## Current Methodologies

11. G. Wang, W. Li, M. Aertsen, J. Deprest, S. Ourselin, and T. Vercauteren, “Aleatoric uncertainty estimation with test-time augmentation for medical image segmentation with convolutional neural networks,” Neurocomputing, vol. 335, pp. 34–45, Sep. 2019.
12. W. Zhou and M. A. Anastasio, “Markov-Chain Monte Carlo approximation of the Ideal Observer using generative adversarial networks,” in Medical Imaging 2020: Image Perception, Observer Performance, and Technology Assessment, SPIE, Mar. 2020, pp. 46–52.
13. Sajedi, Seyed Omid & Liang, Xiao. (2020). Uncertainty-assisted deep vision structural health monitoring. Computer-Aided Civil and Infrastructure Engineering. 36. 10.1111/mice.12580.
14. K. Posch and J. Pilz, “Correlated Parameters to Accurately Measure Uncertainty in Deep Neural Networks,” IEEE Trans Neural Netw Learn Syst, vol. 32, no. 3, pp. 1037–1051, Mar. 2021.
    1. _Supporting Work_: K. Posch, J. Steinbrener, and J. Pilz, “Variational Inference to Measure Model Uncertainty in Deep Neural Networks,” arXiv [stat.ML], Feb. 26, 2019. [Online]. Available: http://arxiv.org/abs/1902.10189
15. M. Subedar, R. Krishnan, P. L. Meyer, O. Tickoo, and J. Huang, “Uncertainty-aware audiovisual activity recognition using deep Bayesian variational inference,” in 2019 IEEE/CVF International Conference on Computer Vision (ICCV), IEEE, Oct. 2019. doi: 10.1109/iccv.2019.00640.
16. V. Edupuganti, M. Mardani, S. Vasanawala, and J. Pauly, “Uncertainty Quantification in Deep MRI Reconstruction,” IEEE Trans. Med. Imaging, vol. 40, no. 1, pp. 239–250, Jan. 2021.
17. Y. Gal, R. Islam, and Z. Ghahramani, “Deep Bayesian Active Learning with Image Data,” in Proceedings of the 34th International Conference on Machine Learning, D. Precup and Y. W. Teh, Eds., in Proceedings of Machine Learning Research, vol. 70. PMLR, 06--11 Aug 2017, pp. 1183–1192.
18. M. Rottmann, K. Kahl, and H. Gottschalk, “Deep Bayesian Active Semi-Supervised Learning,” in 2018 17th IEEE International Conference on Machine Learning and Applications (ICMLA), Dec. 2018, pp. 158–164.
19. A. Kirsch, J. van Amersfoort, and Y. Gal, “BatchBALD: Efficient and Diverse Batch Acquisition for Deep Bayesian Active Learning,” in Proceedings of the 33rd International Conference on Neural Information Processing Systems, Red Hook, NY, USA: Curran Associates Inc., 2019.
20. S. Ebrahimi, M. Elhoseiny, T. Darrell, and M. Rohrbach, “Uncertainty-guided Continual Learning with Bayesian Neural Networks,” arXiv [cs.LG], Jun. 06, 2019. [Online]. Available: http://arxiv.org/abs/1906.02425
21. Gustafsson FK, Danelljan M, Schon TB, “Evaluating scalable Bayesian deep learning methods for robust computer vision,” in proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops, pp 318–319, 2020.
22. Rahaman R, Thiery A, “Uncertainty Quantification and Deep Ensembles,” in Advances in neural information processing systems 34, 2021.
23. Gal, Yarin, and Zoubin Ghahramani, "A theoretically grounded application of dropout in recurrent neural networks," in Advances in neural information processing systems 29 (2016).

#### Safety-Critical Tasks

24. Jing Lei, Max G’Sell, Alessandro Rinaldo, Ryan J. Tibshirani & Larry Wasserman (2018) Distribution-Free Predictive Inference for Regression, Journal of the American Statistical Association, 113:523, 1094-1111, DOI: 10.1080/01621459.2017.1307116.
25. Lars Lindemann, Xin Qin, Jyotirmoy V. Deshmukh, and George J. Pappas. 2023. Conformal Prediction for STL Runtime Verification. Proceedings of the ACM/IEEE 14th International Conference on Cyber-Physical Systems (with CPS-IoT Week 2023) (ICCPS '23). Association for Computing Machinery, New York, NY, USA, 142–153. https://doi.org/10.1145/3576841.3585927.
26. X. Qin, Y. Xia, A. Zutshi, C. Fan and J. V. Deshmukh, "Statistical Verification of Cyber-Physical Systems using Surrogate Models and Conformal Inference," 2022 ACM/IEEE 13th International Conference on Cyber-Physical Systems (ICCPS), Milano, Italy, 2022, pp. 116-126, doi: 10.1109/ICCPS54341.2022.00017.
27. M. A. Langford and B. H. C. Cheng, "“Know What You Know”: Predicting Behavior for Learning-Enabled Systems When Facing Uncertainty," 2021 International Symposium on Software Engineering for Adaptive and Self-Managing Systems (SEAMS), Madrid, Spain, 2021, pp. 78-89, doi: 10.1109/SEAMS51251.2021.00020.
28. Y. Chou, H. Yoon and S. Sankaranarayanan, "Predictive Runtime Monitoring of Vehicle Models Using Bayesian Estimation and Reachability Analysis," 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Las Vegas, NV, USA, 2020, pp. 2111-2118, doi: 10.1109/IROS45743.2020.9340755.
29. S. Bansal, M. Chen, S. Herbert and C. J. Tomlin, "Hamilton-Jacobi reachability: A brief overview and recent advances," 2017 IEEE 56th Annual Conference on Decision and Control (CDC), Melbourne, VIC, Australia, 2017, pp. 2242-2253, doi: 10.1109/CDC.2017.8263977.
30. Mojtaba Zarei, Yu Wang, and Miroslav Pajic. 2020. Statistical verification of learning-based cyber-physical systems. In Proceedings of the 23rd International Conference on Hybrid Systems: Computation and Control (HSCC '20). Association for Computing Machinery, New York, NY, USA, Article 12, 1–7. https://doi.org/10.1145/3365365.3382209
31. Cleaveland, M., Lindemann, L., Ivanov, R. and Pappas, G.J., 2022. Risk verification of stochastic systems with neural network controllers. Artificial Intelligence, 313, p.103782.
32. Bakirtzis, G., Carr, S., Danks, D., & Topcu, U. (2023). Dynamic certification for autonomous systems. Communications of the ACM, 66(9), 64-72.
33. S. B. Liu, B. Schürmann and M. Althoff, "Guarantees for Real Robotic Systems: Unifying Formal Controller Synthesis and Reachset-Conformant Identification," in IEEE Transactions on Robotics, doi: 10.1109/TRO.2023.3277268.
34. Maidens, J., & Arcak, M. (2018). Exploiting symmetry for discrete-time reachability computations. IEEE Control Systems Letters, 2(2), 213-217.
35. S. Yaghoubi, K. Majd, G. Fainekos, T. Yamaguchi, D. Prokhorov and B. Hoxha, "Risk-Bounded Control Using Stochastic Barrier Functions," in IEEE Control Systems Letters, vol. 5, no. 5, pp. 1831-1836, Nov. 2021, doi: 10.1109/LCSYS.2020.3043287.
36. Muthali, A., Shen, H., Deglurkar, S., Lim, M. H., Roelofs, R., Faust, A., & Tomlin, C. (2023). Multi-agent reachability calibration with conformal prediction. arXiv preprint arXiv:2304.00432.
37. X. Chen and S. Sankaranarayanan, "Decomposed Reachability Analysis for Nonlinear Systems," 2016 IEEE Real-Time Systems Symposium (RTSS), Porto, Portugal, 2016, pp. 13-24, doi: 10.1109/RTSS.2016.011. 

#### Structural Health Monitoring

38. Pyle RJ, Hughes RR, Ali AAS, Wilcox PD. Uncertainty Quantification for Deep Learning in Ultrasonic Crack Characterization. IEEE Trans Ultrason Ferroelectr Freq Control. 2022 Jul;69(7):2339-2351. doi: 10.1109/TUFFC.2022.3176926. Epub 2022 Jun 30. PMID: 35604965.
39. Song, Homin & Yang, Yongchao. (2022). Uncertainty quantification in super-resolution guided wave array imaging using a variational Bayesian deep learning approach. NDT & E International. 133. 102753. 10.1016/j.ndteint.2022.102753.

#### Remote Sensing

40. Q. Song, C. M. Albrecht, Z. Xiong, and X. X. Zhu, “Biomass Estimation and Uncertainty Quantification From Tree Height,” IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 16, pp. 4833–4845, 2023.
41. J. Gawlikowski, S. Saha, A. Kruspe, and X. X. Zhu, “An Advanced Dirichlet Prior Network for Out-of-Distribution Detection in Remote Sensing,” IEEE Trans. Geosci. Remote Sens., vol. 60, pp. 1–19, 2022.

##### Medical

42. S. Calderon-Ramirez et al., "Improving Uncertainty Estimation With Semi-Supervised Deep Learning for COVID-19 Detection Using Chest X-Ray Images," in IEEE Access, vol. 9, pp. 85442-85454, 2021, doi: 10.1109/ACCESS.2021.3085418.
43. Valen, J., Balki, I., Mendez, M. et al. Quantifying uncertainty in machine learning classifiers for medical imaging. Int J CARS 17, 711–718 (2022). https://doi.org/10.1007/s11548-022-02578-3
44. Seebock P, Orlando JI, Schlegl T, Waldstein SM, Bogunovic H, Klimscha S, Langs G, Schmidt-Erfurth U, “Exploiting epistemic uncertainty of anatomy segmentation for anomaly detection in retinal OCT,” in IEEE Trans Med Imaging 39:97-98, 2020
45. Eaton-Rosen Z, Bragman F, Bisdas S, Ourselin S, Cardoso MJ, “Towards safe deep learning: accurately quantifying biomarker uncertainty in neural network predictions,” in International conference on medical image computing and computer-assisted intervention, Springer, pp 691–699, 2018.

## Future Directions and Possibilities
***NOTE: Papers Closed Until 11/1/2023***

46. K. T. P. Nguyen, K. Medjaher, and C. Gogu, “Probabilistic deep learning methodology for uncertainty quantification of remaining useful lifetime of multi-component systems,” Reliab. Eng. Syst. Saf., vol. 222, p. 108383, Jun. 2022.
47. J. P. Janet, C. Duan, T. Yang, A. Nandy, and H. J. Kulik, “A quantitative uncertainty metric controls error in neural network-driven chemical discovery,” Chem. Sci., vol. 10, no. 34, pp. 7913–7922, Sep. 2019.
48. C. I. Yang and Y.-P. Li, “Explainable uncertainty quantifications for deep learning-based molecular property prediction,” J. Cheminform., vol. 15, no. 1, p. 13, Feb. 2023.
49. H. Wang, D. Joshi, S. Wang and Q. Ji, "Gradient-based Uncertainty Attribution for Explainable Bayesian Deep Learning," 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), Vancouver, BC, Canada, 2023, pp. 12044-12053, doi: 10.1109/CVPR52729.2023.01159.
50. C. Baek, Y. Jiang, A. Raghunathan, and Z. Kolter, “Agreement-on-the-Line: Predicting the Performance of Neural Networks under Distribution Shift,” in Advances in Neural Information Processing Systems 35 (NeurIPS 2022), Jun. 2022. [Online]. Available: https://proceedings.neurips.cc/paper_files/paper/2022/hash/7a8d388b7a17df480856dff1cc079b08-Abstract-Conference.html
51. R. Cipolla, Y. Gal and A. Kendall, "Multi-task Learning Using Uncertainty to Weigh Losses for Scene Geometry and Semantics," in 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), Salt Lake City, UT, USA, 2018 pp. 7482-7491. doi: 10.1109/CVPR.2018.00781.

## Additional Resources
**These are not open for Journal Club presentations** but are provided for quick reference to background information that may aid the group in understanding related topics.

#### UQ in DL Surveys
- M. Abdar et al., “A review of uncertainty quantification in deep learning: Techniques, applications and challenges,” Inf. Fusion, vol. 76, pp. 243–297, Dec. 2021.
- J. Gawlikowski et al., “A survey of uncertainty in deep neural networks,” Artificial Intelligence Review, Jul. 2023, doi: 10.1007/s10462-023-10562-9.

#### Epistemic vs. Aleatoric Uncertainty
- João Caldeira and Brian Nord 2021 Mach. Learn.: Sci. Technol. 2 015002. DOI 10.1088/2632-2153/aba6f3
- Hüllermeier, E., Waegeman, W. “Aleatoric and epistemic uncertainty in machine learning: an introduction to concepts and methods.” Mach Learn 110, 457–506 (2021). https://doi.org/10.1007/s10994-021-05946-3
- Kendall, A., & Gal, Y. (2017). What uncertainties do we need in bayesian deep learning for computer vision?. Advances in neural information processing systems, 30. 

#### Bayesian Deep Learning
- L. V. Jospin, H. Laga, F. Boussaid, W. Buntine, and M. Bennamoun, “Hands-On Bayesian Neural Networks—A Tutorial for Deep Learning Users,” IEEE Comput. Intell. Mag., vol. 17, no. 2, pp. 29–48, May 2022.
- H. Wang and D.-Y. Yeung, “A Survey on Bayesian Deep Learning,” arXiv [stat.ML], Apr. 06, 2016. [Online]. Available: http://arxiv.org/abs/1604.01662

#### Langevin Dynamics
- M. Welling and Y. W. Teh, “Bayesian Learning via Stochastic Gradient Langevin Dynamics,” in Proceedings of the 28th International Conference on International Conference on Machine Learning, in ICML’11. Madison, WI, USA: Omnipress, 2011, pp. 681–688.
- S. Thaler, G. Doehner, and J. Zavadlav, “Scalable Bayesian Uncertainty Quantification for Neural Network Potentials: Promise and Pitfalls,” J. Chem. Theory Comput., vol. 19, no. 14, pp. 4520–4532, Jul. 2023.

#### Laplacian Methods
- H. Ritter, A. Botev, and D. Barber, “A Scalable Laplace Approximation for Neural Networks,” in 6th International Conference on Learning Representations, ICLR 2018 - Conference Track Proceedings, in International Conference on Learning Representations (ICLR), vol. 6. Vancouver, Canada: International Conference on Representation Learning, 2018.
- A. Kristiadi, M. Hein, and P. Hennig, “Learnable uncertainty under Laplace approximations,” in Proceedings of the Thirty-Seventh Conference on Uncertainty in Artificial Intelligence, C. de Campos and M. H. Maathuis, Eds., in Proceedings of Machine Learning Research, vol. 161. PMLR, 27--30 Jul 2021, pp. 344–353.

#### Variational Inference
- M. I. Jordan, Z. Ghahramani, T. S. Jaakkola, and L. K. Saul, “An Introduction to Variational Methods for Graphical Models,” Mach. Learn., vol. 37, no. 2, pp. 183–233, Nov. 1999.
- D. M. Blei, A. Kucukelbir, and J. D. McAuliffe, “Variational Inference: A Review for Statisticians,” arXiv [stat.CO], Jan. 04, 2016. [Online]. Available: http://arxiv.org/abs/1601.00670

#### Mixture Density Networks for Structural Health Monitoring (paper by Dr. Harley)
- I. D. Khurjekar and J. B. Harley, “Uncertainty aware deep neural network for multistatic localization with application to ultrasonic structural health monitoring,” 2020, arXiv:2007.06814.

#### Conformal Methods
- Angelopoulos, Anastasios N., and Stephen Bates. "A gentle introduction to conformal prediction and distribution-free uncertainty quantification." arXiv preprint arXiv:2107.07511 (2021).
- Shafer, G., & Vovk, V. (2008). A Tutorial on Conformal Prediction. Journal of Machine Learning Research, 9(3).
