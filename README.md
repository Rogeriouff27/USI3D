# Unsupervised Learning for Intrinsic Image Decomposition from a Single Image

![Python 3.6](https://img.shields.io/badge/python-3.6-DodgerBlue.svg?style=plastic)
![Pytorch 1.10](https://img.shields.io/badge/pytorch-1.2.0-DodgerBlue.svg?style=plastic)
![CUDA 10.0](https://img.shields.io/badge/cuda-10.0-DodgerBlue.svg?style=plastic)
![License CC BY-NC](https://img.shields.io/badge/license-CC_BY--NC-DodgerBlue.svg?style=plastic)

<div align=center>  <img src="figures/teaser.jpg" alt="Introduction" width="500" align="bottom" /> </div>

**Picture:** *Examples of single image layer separation: reflection separation and intrinsic image decomposition.*

<div align=center>  <img src="./figures/main_image.jpg" alt="Teaser image" width="800" align="center" /> </div>

**Picture:** *The proposed architecture.*

<div align=center>  <img src="./figures/MPI-results.jpg" alt="Teaser image" width="800" align="center" /> </div>

**Picture:** *Visual results on MPI Sintel benchmark.*

This repository contains the official PyTorch implementation of the following paper:

> **Separate In Latent Space: Unsupervised Single Image Layer Separation**<br>
>  Yunfei Liu, Yu Li, Shaodi You, Feng Lu<br> https://arxiv.org/abs/1911.09930 
> 
>**Abstract:**   Intrinsic image decomposition, which is an essential task in computer vision, aims to infer the reflectance and shading of the scene. It is challenging since it needs to separate one image into two components. To tackle this, conventional methods introduce various priors to constrain the solution, yet with limited performance. Meanwhile, the problem is typically solved by supervised learning methods, which is actually not an ideal solution since obtaining ground truth reflectance and shading for massive general natural scenes is challenging and even impossible. In this paper, we propose a novel unsupervised intrinsic image decomposition framework, which relies on neither labeled training data nor hand-crafted priors. Instead, it directly learns the latent feature of reflectance and shading from unsupervised and uncorrelated data. To enable this, we explore the independence between reflectance and shading, the domain invariant content constraint and the physical constraint. Extensive experiments on both synthetic and real image datasets demonstrate consistently superior performance of the proposed method. 

## Resources

Material related to our paper is available via the following links:

- Paper:  https://arxiv.org/abs/1911.09930 
- Project: Coming soon!
- Code: https://github.com/DreamtaleCore/UnsupervisedInsinsic

## System requirements

* Only Linux is tested, Windows is under test.
* 64-bit Python 3.6 installation. 
* PyTorch 1.2.0 or newer with GPU support.
* One or more high-end NVIDIA GPUs with at least 8GB of DRAM.
* NVIDIA driver 391.35 or newer, CUDA toolkit 9.0 or newer, cuDNN 7.3.1 or newer.

## Playing with pre-trained networks and training

Coming soon!