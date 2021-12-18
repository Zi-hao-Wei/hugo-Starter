---
title: A-ESRGAN
date: 2021-12-18T20:03:37.480Z
summary: A-ESRGAN aims to provide better super-resolution images by using
  multi-scale attention U-net discriminators.
draft: false
featured: false
authors:
  - Zihao Wei
  - Yidong Huang
  - Yuang Chen
  - Chenhao Zheng
categories:
  - Deep Learning
links:
  - url: https://github.com/aesrgan/A-ESRGAN
    icon_pack: fab
    icon: github
    name: Project Link
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Blind image super-resolution(SR) is a long-standing task in CV that aims to restore low-resolution(LR) images suffering from unknown and complex distortions. Recent work has largely focused on adopting more complicated degradation models to emulate real-world degradations. The resulting models have made breakthroughs in perceptual loss and yield perceptually convincing results. However, the limitation brought by current generative adversarial network(GAN) structures is still significant: treating pixels equally leads to the ignorance of the image’s structural features, and results in performance drawbacks such as twisted lines \[1] and background over-sharpening or blurring. In this paper, we present A-ESRGAN, a GAN model for blind SR tasks featuring an attention U-Net based, multi-scale discriminator that can be seamlessly integrated with other generators. To our knowledge, this is the first work to introduce attention U-Net structure as the discriminator of GAN to solve blind SR problems. And the paper also gives an interpretation for the mechanism behind multi-scale attention U-Net that brings performance breakthrough to the model. Through comparison experiments with prior works, our model presents state-of-the-art level performance on the non-reference natural image quality evaluator(NIQE) \[2] metric. And our ablation studies have shown that with our discriminator, the RRDB \[3] based generator can leverage the structural features of an image in multiple scales, and consequently yields more perceptually realistic high-resolution(HR) images compared to prior works.