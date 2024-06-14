# Asymetry assessment within skin lesion for computer aided diagnosis of melanoma

:construction: This repository is still under construction and more features will be added soon. :construction:

Welcome to the official repository for the paper ["Fusion between an Algorithm Based on the Characterization of Melanocytic Lesions' Asymmetry with an Ensemble of Convolutional Neural Networks for Melanoma Detection"](https://www.jidonline.org/article/S0022-202X(24)00078-2/fulltext).

![lafiguredelarticle](https://github.com/JulesCollenne/MelanomaAsymmetry/assets/43369571/88b40f22-6041-4de6-a769-54d38384de2d)

## Abstract
Melanoma is still a major health problem worldwide. Early diagnosis is the first step toward reducing its mortality, but it remains a challenge even for experienced dermatologists. Although computer-aided systems have been developed to help diagnosis, the lack of insight into their predictions is still a significant limitation toward acceptance by the medical community. To tackle this issue, we designed handcrafted expert features representing color asymmetry within the lesions, which are parts of the approach used by dermatologists in their daily practice. These features are given to an artificial neural network classifying between nevi and melanoma. We compare our results with an ensemble of 7 state-of-the-art convolutional neural networks and merge the 2 approaches by computing the average prediction. Our experiments are done on a subset of the International Skin Imaging Collaboration 2019 dataset (6296 nevi, 1361 melanomas). The artificial neural network based on asymmetry achieved an area under the curve of 0.873, sensitivity of 90%, and specificity of 67%; the convolutional neural network approach achieved an area under the curve of 0.938, sensitivity of 91%, and specificity of 82%; and the fusion of both approaches achieved an area under the curve of 0.942, sensitivity of 92%, and specificity of 82%. Merging the knowledge of dermatologists with convolutional neural networks showed high performance for melanoma detection, encouraging collaboration between computer science and medical fields.

## Getting started

Feature computation is in CleanMela.
Training, validation, and testing of all models (ANN, CNN, and ensemble method) are in MélanomeMultiModal.
The code will be refactored in the future!

##  Citation
If you find our work useful in your research, please consider citing:

```
@article{COLLENNE2024,
title = {Fusion between an Algorithm Based on the Characterization of Melanocytic Lesions' Asymmetry with an Ensemble of Convolutional Neural Networks for Melanoma Detection},
journal = {Journal of Investigative Dermatology},
year = {2024},
issn = {0022-202X},
doi = {https://doi.org/10.1016/j.jid.2023.09.289},
url = {https://www.sciencedirect.com/science/article/pii/S0022202X24000782},
author = {Jules Collenne and Jilliana Monnier and Rabah Iguernaissi and Motasem Nawaf and Marie-Aleth Richard and Jean-Jacques Grob and Caroline Gaudy-Marqueste and Séverine Dubuisson and Djamal Merad},
keywords = {Asymmetry, Bioinformatics, Computer-aided diagnosis, Machine learning, Melanoma},
abstract = {Melanoma is still a major health problem worldwide. Early diagnosis is the first step toward reducing its mortality, but it remains a challenge even for experienced dermatologists. Although computer-aided systems have been developed to help diagnosis, the lack of insight into their predictions is still a significant limitation toward acceptance by the medical community. To tackle this issue, we designed handcrafted expert features representing color asymmetry within the lesions, which are parts of the approach used by dermatologists in their daily practice. These features are given to an artificial neural network classifying between nevi and melanoma. We compare our results with an ensemble of 7 state-of-the-art convolutional neural networks and merge the 2 approaches by computing the average prediction. Our experiments are done on a subset of the International Skin Imaging Collaboration 2019 dataset (6296 nevi, 1361 melanomas). The artificial neural network based on asymmetry achieved an area under the curve of 0.873, sensitivity of 90%, and specificity of 67%; the convolutional neural network approach achieved an area under the curve of 0.938, sensitivity of 91%, and specificity of 82%; and the fusion of both approaches achieved an area under the curve of 0.942, sensitivity of 92%, and specificity of 82%. Merging the knowledge of dermatologists with convolutional neural networks showed high performance for melanoma detection, encouraging collaboration between computer science and medical fields.}
}
```

