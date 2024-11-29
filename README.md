### ![red](https://via.placeholder.com/15/f03c15/000000?text=+) This repository is no longer maintained. It has been relocated to <a href="https://github.com/TrustAIoT/TSI-GAN">TSI-GAN</a>, where active updates and maintenance will continue.

## TSI-GAN: Unsupervised Time Series Anomaly Detection using Convolutional Cycle-Consistent Generative Adversarial Networks

### Abstract

Anomaly detection is widely used in network intrusion detection, autonomous driving, medical diagnosis, credit card frauds, etc. However, several key challenges remain open, such as lack of ground truth labels, presence of complex temporal patterns, and generalizing over different datasets. This paper proposes TSI-GAN, an unsupervised anomaly detection model for time-series that can learn complex temporal patterns automatically and generalize well, i.e., no need for choosing dataset-specific parameters, making statistical assumptions about underlying data, or changing model architectures. To achieve these goals, we convert each input time-series into a sequence of 2D images using two encoding techniques with the intent of capturing temporal patterns and various types of deviance. Moreover, we design a reconstructive GAN that uses convolutional layers in an encoder-decoder network and employs cycle-consistency loss during training to ensure that inverse mappings are accurate as well. In addition, we also instrument a Hodrick-Prescott filter in post-processing to mitigate false positives. We evaluate TSI-GAN using 250 well-curated and harder-than-usual datasets and compare with 8 state-of-the-art baseline methods. The results demonstrate the superiority of TSI-GAN to all the baselines, offering an overall performance improvement of 13% and 31% over the second-best performer MERLIN and the third-best performer LSTM-AE, respectively.

### Citation

```
@conference{pakdd23tsigan,
author = {Shyam S. Saravanan and Tie Luo and Mao Van Ngo},
title = {{TSI-GAN}: Unsupervised Time Series Anomaly Detection using Convolutional Cycle-Consistent Generative Adversarial Networks},
booktitle = {27th Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD)},
month = may,
year  = {2023},
}

```
