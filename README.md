# ASEFall

Liu, K. C., Hung, K. H., Hsieh, C. Y., Huang, H. Y., Chan, C. T., & Tsao, Y. (2021). Deep Learning Based Signal Enhancement of Low-Resolution Accelerometer for Fall Detection Systems. IEEE Transactions on Cognitive and Developmental Systems.


DOI = https://doi.org/10.1016/j.bspc.2021.103104

## Abstract

In the last two decades, fall detection (FD) systems have been developed as a popular assistive technology. To support long-term FD services, various power-saving strategies have been implemented. Among them, a reduced sampling rate is a common approach for an energy-efficient system in the real world. However, the performance of FD systems is diminished owing to low-resolution (LR) accelerometer signals. To improve the detection accuracy with LR accelerometer signals, several technical challenges must be considered, including mismatch of effective features and the degradation effects. In this work, a deeplearning-based accelerometer signal enhancement (ASE) model is proposed as a front-end processor to help typical LR-FD systems achieve better detection performance. The proposed ASE model based on a deep denoising convolutional autoencoder architecture reconstructs high-resolution (HR) signals from the LR signals by learning the relationship between the LR and HR signals. The results show that the FD system using support vector machine and the proposed ASE model at an extremely low sampling rate (sampling rate < 2 Hz) achieved 97.34% and 90.52% accuracies in the SisFall and FallAllD datasets, respectively, while those without ASE models only achieved 95.92% and 87.47% accuracies in the SisFall and FallAllD datasets, respectively. The results also demonstrate that the proposed ASE mode can be suitably combined with deep-learning-based FD systems.


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
@ARTICLE{9552232,  author={Liu, Kai-Chun and Hung, Kuo-Hsuan and Hsieh, Chia-Yeh and Huang, Hsiang-Yun and Chan, Chia-Tai and Tsao, Yu},  journal={IEEE Transactions on Cognitive and Developmental Systems},   title={Deep Learning Based Signal Enhancement of Low-Resolution Accelerometer for Fall Detection Systems},   year={2021},  volume={},  number={},  pages={1-1},  doi={10.1109/TCDS.2021.3116228}}
```

## Contact
Feel free to contact Kai-Chun Liu (t22302856@gmail.com) or Yu-Der Lin (ydlin@fcu.edu.tw). Welcom any quesntion or discussion. 
