---
title: "Protecting Facial Privacy: Generating Adversarial Identity Masks via Style-Robust Makeup Transfer"
collection: publications
permalink: /publication/2023-06-01-Detecting-Backdoors
excerpt: 'In this paper, we propose the test-time corruption robustness consistency evaluation (TeCo), a novel test-time trigger sample detection method that only needs the hard-label outputs of the victim models without any extra information.'
date: 2023-06-01
venue: 'CVPR 2023'
authors: '**Xiaogeng Liu**, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao.'
paperurl: 'http://sheltonliu-n.github.io/files/Liu_Detecting_Backdoors_During_the_Inference_Stage_Based_on_Corruption_Robustness_CVPR_2023_paper.pdf'
code: 'https://github.com/CGCL-codes/TeCo'
---
Authors: **Xiaogeng Liu**, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao.

Abstract: Deep neural networks are proven to be vulnerable to backdoor attacks. Detecting the trigger samples during the inference stage, ie, the test-time trigger sample detection, can prevent the backdoor from being triggered. However, existing detection methods often require the defenders to have high accessibility to victim models, extra clean data, or knowledge about the appearance of backdoor triggers, limiting their practicality. In this paper, we propose the test-time corruption robustness consistency evaluation (TeCo), a novel test-time trigger sample detection method that only needs the hard-label outputs of the victim models without any extra information. Our journey begins with the intriguing observation that the backdoor-infected models have similar performance across different image corruptions for the clean images, but perform discrepantly for the trigger samples. Based on this phenomenon, we design TeCo to evaluate test-time robustness consistency by calculating the deviation of severity that leads to predictions' transition across different corruptions. Extensive experiments demonstrate that compared with state-of-the-art defenses, which even require either certain information about the trigger types or accessibility of clean data, TeCo outperforms them on different backdoor attacks, datasets, and model architectures, enjoying a higher AUROC by 10% and 5 times of stability.

<img src="http://sheltonliu-n.github.io/files/Liu_Detecting_Backdoors_During_the_Inference_Stage_Based_on_Corruption_Robustness_CVPR_2023_paper.png" width="700"/>

[Download paper here](http://sheltonliu-n.github.io/files/Liu_Detecting_Backdoors_During_the_Inference_Stage_Based_on_Corruption_Robustness_CVPR_2023_paper.pdf)

[Code](https://github.com/CGCL-codes/TeCo)
