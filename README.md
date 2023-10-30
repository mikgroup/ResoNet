# ResoNet: Noise-Trained Physics-Informed MRI Off-Resonance Correction

This is our project page for our work published at NeurIPS 2023. Code is coming soon!

### [OpenReview](https://openreview.net/forum?id=Ia4dmqst0Z)
### [NeurIPS site](https://neurips.cc/virtual/2023/poster/72112)

_Magnetic Resonance Imaging (MRI) is a powerful medical imaging modality that offers diagnostic information without harmful ionizing radiation. Unlike optical imaging, MRI sequentially samples the spatial Fourier domain (k-space) of the image. Measurements are collected in multiple shots, or readouts, and in each shot, data along a smooth trajectory is sampled. Conventional MRI data acquisition relies on sampling k-space row-by-row in short intervals, which is slow and inefficient. More efficient, non-Cartesian sampling trajectories (e.g., Spirals) use longer data readout intervals, but are more susceptible to magnetic field inhomogeneities, leading to off-resonance artifacts. Spiral trajectories cause off-resonance blurring in the image, and the mathematics of this blurring resembles that of optical blurring, where magnetic field variation corresponds to depth and readout duration to aperture size. Off-resonance blurring is a system issue with a physics-based, accurate forward model. We present a physics-informed deep learning framework for off-resonance correction in MRI, which is trained exclusively on synthetic, noise-like data with representative marginal statistics. Our approach allows for fat/water separation and is compatible with parallel imaging acceleration. Through end-to-end training using synthetic randomized data (i.e., noise-like images, coil sensitivities, field maps), we train the network to reverse off-resonance effects across diverse anatomies and contrasts without retraining. We demonstrate the effectiveness of our approach through results on phantom and in-vivo data. This work has the potential to facilitate the clinical adoption of non-Cartesian sampling trajectories, enabling efficient, rapid, and motion-robust MRI scans._ 

![alt text](figures/poster.png)




### BibTex

```
@inproceedings{
goyeneche2023resonet,
title={ResoNet: Noise-Trained Physics-Informed MRI Off-Resonance Correction},
author={Alfredo De Goyeneche and Shreya Ramachandran and Ke Wang and Ekin Karasan and Joseph Yitan Cheng and Stella X. Yu and Michael Lustig},
booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
year={2023},
url={https://openreview.net/forum?id=Ia4dmqst0Z}
}
```
