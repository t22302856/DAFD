# DAFD

Liu, K. C., Chan, M., Kuo, H. C., Hsieh, C. Y., Huang, H. Y., Chan, C. T., & Tsao, Y. (2021). Domain-adaptive fall detection using deep adversarial training. IEEE transactions on neural systems and rehabilitation engineering, 29, 1243-1251.


DOI = https://doi.org/10.1109/TNSRE.2021.3089685

## Abstract

Fall detection (FD) systems are important assistive technologies for healthcare that can detect emergency fall events and alert caregivers. However, it is not easy to obtain large-scale annotated fall events with various specifications of sensors or sensor positions during the implementation of accurate FD systems. Moreover, the knowledge obtained through machine learning has been restricted to tasks in the same domain. The mismatch between different domains might hinder the performance of FD systems. Cross-domain knowledge transfer is very beneficial for machine-learning based FD systems to train a reliable FD model with well-labeled data in new environments. In this study, we propose domain-adaptive fall detection (DAFD) using deep adversarial training (DAT) to tackle cross-domain problems, such as cross-position and cross-configuration. The proposed DAFD can transfer knowledge from the source domain to the target domain by minimizing the domain discrepancy to avoid mismatch problems. The experimental results show that the average F1-score improvement when using DAFD ranges from 1.5% to 7% in the cross-position scenario, and from 3.5% to 12% in the cross-configuration scenario, compared to using the conventional FD model without domain adaptation training. The results demonstrate that the proposed DAFD successfully helps to deal with cross-domain problems and to achieve better detection performance.


## DAGAF in Python

### Requirements

1. Python >= 2.7
- Install Python using the Anaconda is reommand.
2. numpy
- Install using pip (``pip install numpy``)
3. scipy
- install using pip (``pip install scipy``)
4. matplotlib
- install using pip (``pip install matplotlib``)

### Usage



## Citation
If you would like to use this package and function, please cite this paper:

```
@ARTICLE{9456857,
  author={Liu, Kai-Chun and Chan, Michael and Kuo, Heng-Cheng and Hsieh, Chia-Yeh and Huang, Hsiang-Yun and Chan, Chia-Tai and Tsao, Yu},
  journal={IEEE Transactions on Neural Systems and Rehabilitation Engineering}, 
  title={Domain-Adaptive Fall Detection Using Deep Adversarial Training}, 
  year={2021},
  volume={29},
  number={},
  pages={1243-1251},
  doi={10.1109/TNSRE.2021.3089685}}
```

## Contact
Feel free to contact Kai-Chun Liu (t22302856@gmail.com). Welcom any quesntion or discussion. 
