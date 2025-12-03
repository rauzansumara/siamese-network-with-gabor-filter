# Siamese Network with Gabor Filter for Handwritten Digit Recognition

This repository contains the implementation of a Siamese Neural Network enhanced with Gabor Filters for the recognition of handwritten digits. This approach leverages the texture analysis capabilities of Gabor filters combined with the few-shot learning capabilities of Siamese networks to improve classification performance.

## 📖 Table of Contents
- [About the Project](#about-the-project)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Citation](#citation)
- [License](#license)

## 🧐 About the Project

Standard Convolutional Neural Networks (CNNs) often require large amounts of data. This project implements a method to recognize handwritten digits (such as MNIST or custom datasets) using a **Siamese Network** architecture.

## ⚙️ Methodology

The architecture follows the approach described in the referenced paper:
1.  **Input:** Pairs of handwritten digit images.
2.  **Gabor Filtering:** Application of Gabor filters to extract texture features.
3.  **Feature Extraction:** Shared weight sub-networks (sister networks) process the filtered inputs.
4.  **Distance Metric:** Euclidean distance is calculated between the feature vectors.
5.  **Output:** A similarity score indicating if the digits belong to the same class.

## 📄 Citation

If you use this code or the methodology implemented here for your research, please cite the following paper:

### APA Format
Sumara, R., & Ihwani, I. L. (2023). Siamese Network with Gabor Filter for Recognizing Handwritten Digits. In O. Gervasi et al. (Eds.), *Computational Science and Its Applications – ICCSA 2023* (LNCS Vol. 13957). Springer, Cham. https://doi.org/10.1007/978-3-031-36808-0_3

### BibTeX
```bibtex
@inproceedings{sumara2023siamese,
  author    = {Sumara, R. and Ihwani, I.L.},
  title     = {Siamese Network with Gabor Filter for Recognizing Handwritten Digits},
  booktitle = {Computational Science and Its Applications – ICCSA 2023},
  series    = {Lecture Notes in Computer Science},
  volume    = {13957},
  publisher = {Springer, Cham},
  year      = {2023},
  doi       = {10.1007/978-3-031-36808-0_3}
}
