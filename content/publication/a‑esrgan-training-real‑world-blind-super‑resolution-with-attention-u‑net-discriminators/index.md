---
title: "A‑ESRGAN: Training Real‑World Blind Super‑Resolution with Attention
  U‑Net Discriminators"
subtitle: ""
publication_types:
  - "3"
publication: arxiv
abstract: "Blind image super-resolution(SR) is a long-standing task in CV that
  aims to restore low-resolution images suffering from unknown and complex
  distortions. Recent work has largely focused on adopting more complicated
  degradation models to emulate real-world degradations. The resulting models
  have made breakthroughs in perceptual loss and yield perceptually convincing
  results. However, the limitation brought by current generative adversarial
  network structures is still significant: treating pixels equally leads to the
  ignorance of the image's structural features, and results in performance
  drawbacks such as twisted lines and background over-sharpening or blurring. In
  this paper, we present A-ESRGAN, a GAN model for blind SR tasks featuring an
  attention U-Net based, multi-scale discriminator that can be seamlessly
  integrated with other generators. To our knowledge, this is the first work to
  introduce attention U-Net structure as the discriminator of GAN to solve blind
  SR problems. And the paper also gives an interpretation for the mechanism
  behind multi-scale attention U-Net that brings performance breakthrough to the
  model. Through comparison experiments with prior works, our model presents
  state-of-the-art level performance on the non-reference natural image quality
  evaluator metric. And our ablation studies have shown that with our
  discriminator, the RRDB based generator can leverage the structural features
  of an image in multiple scales, and consequently yields more perceptually
  realistic high-resolution images compared to prior works. "
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-12-29T20:23:31.217Z
---
