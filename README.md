# 3D-Hyper-UNET for Hyperspectral Image Classification.

## Description

A novel CNN called the 3-D Hyper-UNET for Hyperspectral Image Segmentation. It utilises the spatial and spectral features of HSI using 3-D convolutions to analyse and provide better results.
3D convolutions is a relatively new technique used in the domain of hyperspectral data classification, however, there is no dedicated model for segmentation tasks of HSI data. The 3D Hyper-UNET model proposed here is partly inspired from the UNET architecture, with an additional feature of 3D convolution and the 3D transpose convolution layers.

## Model

<div align="center"><img src="https://github.com/nishchaljs/3D-Hyper-UNET/blob/main/3D_Unet_Mod.png" width="50%" height="50%" /></div>

Fig: Proposed 3D-Hyper-UNET Model with 3D convolutions for hyperspectral image (HSI) classification.  

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/)
- [Tensorflow](https://github.com/tensorflow/tensorflow/)
- [Keras](https://github.com/fchollet/keras)

## Results

<div align="center"><img src="https://github.com/nishchaljs/3D-Hyper-UNET/blob/main/results.png"/></div>


#### Detailed results can be found in the [RVCE_ISRO_Paper](RVCE_ISRO_Paper.pdf)

## Citation
   

## Acknowledgement

Part of this code is from a implementation of Classification of HSI using CNN by [HybridSN](https://github.com/gokriznastic/HybridSN).
