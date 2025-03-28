# SAR2RGB

SAR2RGB is a Generative AI project to generate RGB images from Synthetic Aperture Radar (SAR) images. The best results were achieved using Diffusion with ControlNet

Dataset: [2025 IEEE GRSS Data Fusion Contest Track 1](https://www.grss-ieee.org/technical-committees/image-analysis-and-data-fusion/?tab=data-fusion-contest)

## ControlNet + Stable Diffusion v1-5

![controlnet_1](https://github.com/canmike/sar2rgb/blob/main/figures/controlnet_1.png)

![controlnet_2](https://github.com/canmike/sar2rgb/blob/main/figures/controlnet_2.png)

Paper: [Adding Conditional Control to Text-to-Image Diffusion Models](https://arxiv.org/abs/2302.05543)

Notebook: [controlnet_diffusion_v5.ipynb](https://github.com/canmike/sar2rgb/blob/main/notebooks/controlnet_diffusion_v5.ipynb)

## Pix2Pix

![pix2pix_1](https://github.com/canmike/sar2rgb/blob/main/figures/pix2pix_1.png)

![pix2pix_2](https://github.com/canmike/sar2rgb/blob/main/figures/pix2pix_2.png)

Paper: [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)

Notebook: [pix2pix_v2.ipynb](https://github.com/canmike/sar2rgb/blob/main/notebooks/pix2pix_v2.ipynb)

## Conditional Variational Autoencoder

![cVAE_1](https://github.com/canmike/sar2rgb/blob/main/figures/cVAE_1.png)

![cVAE_2](https://github.com/canmike/sar2rgb/blob/main/figures/cVAE_2.png)

Paper: [Learning Structured Output Representation using Deep Conditional Generative Models](https://papers.nips.cc/paper_files/paper/2015/hash/8d55a249e6baa5c06772297520da2051-Abstract.html)

Notebook: [cVAE_v2_img128_ldim2048_b0.25.ipynb](https://github.com/canmike/sar2rgb/blob/main/notebooks/cVAE_v2_img128_ldim2048_b0.25.ipynb)
