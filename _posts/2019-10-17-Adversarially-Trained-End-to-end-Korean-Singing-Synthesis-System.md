---
title: "Adversarially Trained End-to-end Korean Singing Synthesis System"
date: 2019-10-17 15:33:50 -0400
categories: singing-synthesis
---

# ABSTRACT


#### In this paper, we propose an end-to-end Korean singing voice synthesis system from lyrics and a symbolic melody using the following three novel approaches: 1) phonetic enhancement masking, 2) local conditioning of text and pitch to the super-resolution network, and 3) conditional adversarial training. The proposed system consists of two main modules; a mel-synthesis network that generates a mel-spectrogram from the given input information, and a super-resolution network that upsamples the generated mel-spectrogram into a linear-spectrogram. In the mel-synthesis network, phonetic enhancement masking is applied to generate implicit formant masks solely from the input text, which enables a more accurate phonetic control of singing voice. In addition, we show that two other proposed methods -- local conditioning of text and pitch, and conditional adversarial training -- are crucial for a realistic generation of the human singing voice in the super-resolution process. Finally, both quantitative and qualitative evaluations are conducted, confirming the validity of all proposed methods.

#### Check out the [paper]

[paper]: https://arxiv.org/abs/1908.01919
