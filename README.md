# Anomaly-detection-using-Variational-Autoencoder-VAE


![result image](https://jp.mathworks.com/matlabcentral/mlc-downloads/downloads/4430b386-20cc-412b-a4bb-1b7180b7d447/5abdedb4-f118-4fd1-bf4f-12f8e3400350/images/screenshot.JPG)


On shipping inspection for chemical materials, clothing, and food materials, etc, it is necessary to detect defects and impurities in normal products.
In the following link, I shared codes to detect and localize anomalies using CAE with only images for training.

In this demo, you can learn how to apply Variational Autoencoder(VAE) to this task instead of CAE.
VAEs use a probability distribution on the latent space, and sample from this distribution to generate new data.

## **Requirements**
- [MATLAB](https://jp.mathworks.com/products/matlab.html)
- [Deep Learning Toolbox](https://jp.mathworks.com/products/deep-learning.html)
- [Image Processing Toolbox](https://jp.mathworks.com/products/image.html)
- [Computer Vision Toolbox](https://jp.mathworks.com/products/computer-vision.html)
- [Parallel Computing Toolbox](https://jp.mathworks.com/products/parallel-computing.html)

MATLAB version should be R2019b and later 


## **Usage**

-	EN_VAE_Anomalydetection.mlx ・Example showing how to train the VAE model in English
-	JP_VAE_Anomalydetection.mlx  ・Example showing how to train the VAE model in  Japanese


# **Reference**
Auto-Encoding Variational Bayes [2013]
Diederik P Kingma, Max Welling
https://arxiv.org/pdf/1312.6114.pdf



Copyright 2019-2020 The MathWorks, Inc.
