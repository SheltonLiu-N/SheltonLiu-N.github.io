---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Xiaogeng Liu (Chinese: 刘晓耕), currently a third-year Ph.D. student in ECE at the Johns Hopkins University DSAI institute. I am honored to conduct my research under the esteemed guidance of Professor [Chaowei Xiao](https://xiaocw11.github.io/#about). My research interests lie in trustworthy AI, especially the robustness of machine learning models that emphasizes the model's ability to maintain performance and resist any kind of unexpected inputs. I am honored to be awarded the <a href="https://research.nvidia.com/graduate-fellowships/2025" target="_blank">NVIDIA 2025-2026 Graduate Fellowship</a>. 

I am always open to collaboration and the exchange of ideas. If you'd like to discuss potential research opportunities or simply connect, please don't hesitate to reach out to me at **xliu316@jhu.edu**

# 🔥 News
(<sup>*</sup> represents equal contribution)
<ul>
    <li>
        [2025-09] <span style="color:red">One papers is accepted by NeurIPS 2025 </span>, thanks for all of my collaborators. <br> 
        <a href="https://arxiv.org/abs/2506.12104" target="_blank">"DRIFT: Dynamic Rule-Based Defense with Injection Isolation for Securing LLM Agents"</a> <br> 
        <i>Hao Li, <strong>Xiaogeng Liu</strong>, Hung-Chun Chiu, Dianqi Li, Ning Zhang, Chaowei Xiao. </i> <br>
    </li>
    <li>
        [2025-08] &nbsp;🎓 Update: I’ve transferred to <a href="https://engineering.jhu.edu/Datascience-AI/" target="_blank">Johns Hopkins University DSAI institute</a> to continue my PhD study (still in Professor Chaowei Xiao’s lab)! Excited to explore new collaborations! <br>
    </li>
    <li>
        [2025-05] <span style="color:red">Two papers are accepted by ACL 2025 </span>, thanks for all of my collaborators. <br> 
        <a href="https://arxiv.org/abs/2410.22770" target="_blank">"InjecGuard: Benchmarking and Mitigating Over-defense in Prompt Injection Guardrail Models"</a> (Main) <br> 
        <i>Hao Li<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Ning Zhang, Chaowei Xiao.</i> <br>
        <a href="https://arxiv.org/abs/2502.11448" target="_blank">"AGrail: A Lifelong Agent Guardrail with Effective and Adaptive Safety Detection"</a> (Main) <br> 
        <i>Weidi Luo, Shenghong Dai, <strong>Xiaogeng Liu</strong>, Suman Banerjee, Huan Sun, Muhao Chen, Chaowei Xiao.</i>
    </li>
    <li>
        [2025-05] &nbsp;🎉🎉 Our <a href="https://eddyluo1232.github.io/JailBreakV28K/" target="_blank">paper</a> on benchmarking the robustness of VLMs against jailbreak attacks is <span style="color:red">honored to be awarded</span> by the <a href="https://www.mlsafety.org/safebench/winners" target="_blank">SafeBench competition</a>! Huge thanks to all my collaborators and to the Center for AI Safety. <br>
    </li>
    <li>
        [2025-05] <span style="color:red">One paper is accepted by ICML 2025</span>, thanks for all of my collaborators. <br> 
         <a href="https://openreview.net/forum?id=vOxaD3hhPt" target="_blank">"MetaAgent: Automatically Building Multi-Agent System based on Finite State Machine"</a> <br>
        <i>Yaolun Zhang, <strong>Xiaogeng Liu</strong>, Chaowei Xiao.</i>
    </li>
    <li>
        [2025-01] <span style="color:red">Three papers are accepted by ICLR 2025</span>, thanks for all of my collaborators. <br> 
        <a href="https://arxiv.org/abs/2410.05295" target="_blank">"AutoDAN-Turbo: A Lifelong Agent for Strategy Self-Exploration to Jailbreak LLMs"</a> (<span style="color:red">Spotlight, 5.1%</span>) <br> 
        <i><strong>Xiaogeng Liu<sup>*</sup></strong>, Peiran Li<sup>*</sup>, Edward Suh, Yevgeniy Vorobeychik, Zhuoqing Mao, Somesh Jha, Patrick McDaniel, Huan Sun, Bo Li, Chaowei Xiao.</i> <br>
        <a href="https://openreview.net/forum?id=KRMSH1GxUK&" target="_blank">"Can Watermarks be Used to Detect LLM IP Infringement For Free?"</a> <br>
        <i>Zhengyue Zhao, <strong>Xiaogeng Liu</strong>, Somesh Jha, Patrick McDaniel, Bo Li, Chaowei Xiao.</i> <br>
        <a href="https://arxiv.org/abs/2406.09411" target="_blank">"MuirBench: A Comprehensive Benchmark for Robust Multi-image Understanding"</a> <br>
        <i>Fei Wang, Xingyu Fu, James Y. Huang<sup>*</sup>, Zekun Li<sup>*</sup>, Qin Liu<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Mingyu Derek Ma<sup>*</sup>, Nan Xu<sup>*</sup>, Wenxuan Zhou<sup>*</sup>, Kai Zhang, Tianyi Lorena Yan, Wenjie Jacky Mo, Hsiang-Hui Liu, Pan Lu, Chunyuan Li, Chaowei Xiao, Kai-Wei Chang, Dan Roth, Sheng Zhang, Hoifung Poon, Muhao Chen.</i>
    </li>
    <li>
        [2025-01] <span style="color:red">Two papers are accepted by NAACL 2025</span>, thanks for all of my collaborators.
    </li>
    <li>
        [2024-12] &nbsp;🎉🎉 I am <span style="color:red">honored to be awarded</span> the <a href="https://blogs.nvidia.com/blog/graduate-fellowship-recipients-2025-2026/" target="_blank"><strong>NVIDIA 2025-2026 Graduate Fellowship</strong></a>! I cannot fully express my gratitude to everyone who has supported me—my peers, my collaborators, my advisor, and all who have offered their guidance along the way. <br> 
    </li>
    <li>
        [2024-08] &nbsp;🎉🎉 Our <a href="https://www.usenix.org/conference/usenixsecurity24/presentation/yu-zhiyuan" target="_blank">paper</a> about understanding jailbreak attacks wins the <span style="color:red;"><strong>Distinguished Paper Award</strong> in 33rd USENIX Security Symposium (USENIX Security'24)</span>!, thanks for all of my collaborators. <br> 
    </li>
    <li>
        [2024-07] <span style="color:red">One paper is accepted by COLM 2024</span>, thanks for all of my collaborators. <br> 
         <a href="https://arxiv.org/abs/2404.03027" target="_blank">"JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks"</a> <br>
        <i>Weidi Luo<sup>*</sup>, Siyuan Ma<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Xiaoyu Guo, Chaowei Xiao.</i>
    </li>
    <li>
        [2024-07] <span style="color:red">One paper is accepted by ECCV 2024</span>, thanks for all of my collaborators. <br>
        <a href="https://arxiv.org/abs/2403.09513" target="_blank">"AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting"</a> <br>
        <i>Yu Wang<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Yu Li, Muhao Chen, Chaowei Xiao.</i>
    </li>
    <li>
        [2024-02] <span style="color:red">One paper is accepted by USENIX Security 2024</span>, thanks for all of my collaborators. <br>
        <a href="https://www.usenix.org/conference/usenixsecurity24/presentation/yu-zhiyuan" target="_blank">"Don’t Listen To Me: Understanding and Exploring Jailbreak Prompts of Large Language Models"</a> <br>
        <i>Zhiyuan Yu, <strong>Xiaogeng Liu</strong>, Shunning Liang, Zach Cameron, Chaowei Xiao, Ning Zhang.</i>
    </li>
    <li>
        [2024-01] <span style="color:red">One paper is accepted by ICLR 2024</span>, thanks for all of my collaborators. <br>
        <a href="https://arxiv.org/abs/2310.04451" target="_blank">"AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models"</a> <br>
        <i><strong>Xiaogeng Liu</strong>, Nan Xu, Muhao Chen, Chaowei Xiao.</i>
    </li>
</ul>

<details>
  <summary>More</summary>
<ul>
    <li>
        [2023-07] <span style="color:red">One paper is accepted by S&amp;P 2024</span>, thanks for all of my collaborators. <br>
        <a href="https://www.computer.org/csdl/proceedings-article/sp/2024/313000a010/1RjE9Osvfgs" target="_blank">"Why Does Little Robustness Help? A Further Step Towards Understanding Adversarial Transferability"</a> <br>
        <i>Yechao Zhang, Shengshan Hu, Leo Yu Zhang, Junyu Shi, Minghui Li, <strong>Xiaogeng Liu</strong>, Wei Wan, Hai Jin.</i>
    </li>
    <li>
        [2023-07] <span style="color:red">One paper is accepted by ACM MM 2023</span>, thanks for all of my collaborators. <br>
        <a href="https://dl.acm.org/doi/abs/10.1145/3581783.3612456" target="_blank">"PointCRT: Detecting Backdoor in 3D Point Cloud via Corruption Robustness"</a> <br>
        <i>Shengshan Hu, Wei Liu, Minghui Li, Yechao Zhang, <strong>Xiaogeng Liu</strong>, Xianlong Wang, Leo Yu Zhang.</i>
    </li>
    <li>
        [2023-02] <span style="color:red">One paper is accepted by CVPR 2023</span>, thanks for all of my collaborators. <br>
        <a href="https://openaccess.thecvf.com/content/CVPR2023/html/Liu_Detecting_Backdoors_During_the_Inference_Stage_Based_on_Corruption_Robustness_CVPR_2023_paper.html" target="_blank">"Detecting Backdoors During the Inference Stage Based on Corruption Robustness Consistency"</a> <br>
        <i><strong>Xiaogeng Liu</strong>, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao.</i>
    </li>
    <li>
        [2022-09] Our team (<i>Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang, Ziqi Zou, Xianlong Wang</i>) at 
        <a href="https://www.zgc-aisc.com/en">AISC2022-Physical World Adversarial Face Recognition</a> (Rank 5/178).
    </li>
    <li>
        [2022-06] Our team (<i>Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang, Shengshan Hu</i>) wins the third prize at 
        <a href="https://artofrobust.github.io/#challenge">CVPR2022 Art Of Robustness Workshop: Open-Set Defence</a> (Rank 3/156).
    </li>
    <li>
        [2022-02] One paper is shared at CVPR 2022 Art Of Robustness Workshop, thanks for all of my collaborators. <br>
        <a href="https://arxiv.org/abs/2203.03810" target="_blank">"Towards Efficient Data-Centric Robust Machine Learning with Noise-Based Augmentation"</a> <br>
        <i><strong>Xiaogeng Liu</strong>, Haoyu Wang, Yechao Zhang, Fangzhou Wu, Shengshan Hu.</i>
    </li>
    <li>
        [2022-09] I am awarded the <span style="color:red">Chinese National Scholarship</span> for Graduate Students (Top 1%)!.
    </li>
    <li>
        [2022-02] <span style="color:red">One paper is accepted by CVPR 2022</span>, thanks for all of my collaborators. <br>
        <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Protecting_Facial_Privacy_Generating_Adversarial_Identity_Masks_via_Style-Robust_Makeup_CVPR_2022_paper.html" target="_blank">"Protecting Facial Privacy: Generating Adversarial Identity Masks via Style-Robust Makeup Transfer"</a> <br>
        <i>Shengshan Hu, <strong>Xiaogeng Liu</strong>, Yechao Zhang, Minghui Li, Leo Yu Zhang, Hai Jin, Libing Wu.</i>
    </li>
    <li>
        [2022-01] Our team (<i>Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang</i>) at 
        <a href="https://tianchi.aliyun.com/competition/entrance/531939/introduction">Tianchi: AAAI2022 Secure AI Challenger Program Phase 8: Data-Centric Robust Machine Learning Competition</a> (Rank 8/3691).
    </li>
    <li>
        [2021-10] Our team (<i>Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang</i>) at 
        <a href="https://security.oppo.com/challenge/home.html">OPPO AI Challenge - Face Recognition Competition</a> (Rank 14/2349).
    </li>
    <li>
        [2021-04] <span style="color:red">One paper is accepted by ACM MM 2021</span>, thanks for all of my collaborators. <br>
        <a href="https://dl.acm.org/doi/abs/10.1145/3474085.3475396" target="_blank">"Advhash: Set-to-set Targeted Attack on Deep Hashing with One Single Adversarial Patch"</a> <br>
        <i>Shengshan Hu, Yechao Zhang, <strong>Xiaogeng Liu</strong>, Leo Yu Zhang, Minghui Li, Hai Jin.</i>
    </li>
</ul>
</details>

# 💥 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/doxing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Doxing via the Lens: Revealing Location-related Privacy Leakage on Multi-modal Large Reasoning Models](https://arxiv.org/abs/2504.19373)

Weidi Luo<sup>*</sup>, Qiming Zhang<sup>*</sup>, Tianyu Lu<sup>*</sup>, <strong>Xiaogeng Liu</strong>, Bin Hu, Yue Zhao, Jieyu Zhao, Song Gao, Patrick McDaniel, Zhen Xiang, Chaowei Xiao

[**Project Page**](https://doxbench.github.io/) \| [**Media Press (机器之心 Synced)**](https://mp.weixin.qq.com/s/_pDsKWz9f9rjXFHWN2UJ_A) \| <strong>23,000+</strong> views, <strong>1,300+</strong> shares
- We introduce a three-level visual privacy risk framework to categorize and evaluate the potential for location inference from images. We also present DoxBench, a new dataset of 500 real-world images designed to test various privacy scenarios, and find that advanced AI models consistently surpass non-expert humans in geolocation tasks.
- To better understand these risks, we propose ClueMiner, a framework to identify the types of visual clues models use for location inference. We also introduce GeoMiner, a collaborative attack framework that demonstrates how the geolocation capabilities of these models can be amplified, highlighting a significant privacy threat.
</div>
</div>

# 📝 Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 Spotlight</div><img src='images/autodan-turbo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoDAN-Turbo: A Lifelong Agent for Strategy Self-Exploration to Jailbreak LLMs](https://arxiv.org/abs/2410.05295)

<strong>Xiaogeng Liu<sup>*</sup></strong>, Peiran Li<sup>*</sup>, Edward Suh, Yevgeniy Vorobeychik, Zhuoqing Mao, Somesh Jha, Patrick McDaniel, Huan Sun, Bo Li, Chaowei Xiao

[**Project Page**](https://autodans.github.io/AutoDAN-Turbo) \| [![](https://img.shields.io/github/stars/SaFoLab-WISC/AutoDAN-Turbo?style=social&label=Code Stars)](https://github.com/SaFoLab-WISC/AutoDAN-Turbo)
- We propose AutoDAN-Turbo, a black-box jailbreak method that can automatically discover as many jailbreak strategies as possible from scratch, without any human intervention or predefined scopes (e.g., specified candidate strategies), and use them for red-teaming. Notably, AutoDAN-Turbo achieves an 88.5 attack success rate on GPT-4-1106-turbo. In addition, AutoDAN-Turbo is a unified framework that can incorporate existing human-designed jailbreak strategies in a plug-and-play manner. By integrating human-designed strategies, AutoDAN-Turbo can even achieve a higher attack success rate of 93.4 on GPT-4-1106-turbo.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/autodan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models](https://arxiv.org/abs/2310.04451)

**Xiaogeng Liu**, Nan Xu, Muhao Chen, Chaowei Xiao

[**Project Page**](https://autodans.github.io/AutoDAN/) \| [![](https://img.shields.io/github/stars/SheltonLiu-N/AutoDAN?style=social&label=Code Stars)](https://github.com/SheltonLiu-N/AutoDAN)
- This pioneering work focuses on the adversarial robustness of the safety alignment of LLMs, and introduces AutoDAN, a novel hierarchical genetic algorithm that automatically generates stealthy jailbreak prompts for LLMs, preserving semantic meaningfulness while bypassing existing defenses like perplexity detection.
- It is one of the strongest jailbreak attacks in public benchmarks ([Harmbench](https://www.harmbench.org), [Easyjailbreak](http://easyjailbreak.org)).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX Security 2024 Distinguished Paper Award</div><img src='images/dont_listen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Don't Listen To Me: Understanding and Exploring Jailbreak Prompts of Large Language Models](https://www.usenix.org/conference/usenixsecurity24/presentation/yu-zhiyuan)

Zhiyuan Yu, **Xiaogeng Liu**, Shunning Liang, Zach Cameron, Chaowei Xiao, Ning Zhang

[**Project Page**](https://github.com/WUSTL-CSPL/LLMJailbreak) 
- This work is a comprehensive systematization of jailbreak prompts in LLMs, categorizing them into five types and analyzing their effectiveness based on 448 prompts collected from online forums.
- We also introduce a human-AI cooperative framework for automating jailbreak prompt generation, achieving success in transforming 766 failed prompts into harmful outputs, demonstrating the feasibility of automating such attacks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Main</div><img src='images/injecguard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InjecGuard: Benchmarking and Mitigating Over-defense in Prompt Injection Guardrail Models](https://arxiv.org/abs/2410.22770)

Hao Li<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Ning Zhang, Chaowei Xiao

[**Project Page**](https://injecguard.github.io) \| [**Model**](https://huggingface.co/leolee99/InjecGuard) \| [**Dataset**](https://huggingface.co/datasets/leolee99/NotInject)
- We propose InjecGuard, a lightweight model designed to defend against prompt injection attacks. It delivers strong performance across benign, malicious, and over-defense accuracy metrics, surpassing existing guard models such as PromptGuard, ProtectAIv2, and LakeraAI. Despite its compact size, with model parameters of only 184MB, InjecGuard achieves competitive performance comparable to advanced commercial large language models like GPT-4.
- We also introduce [NotInject](https://huggingface.co/datasets/leolee99/NotInject), an evaluation dataset that systematically measures over-defense across various prompt guard models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/adashield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting](https://arxiv.org/abs/2403.09513)

Yu Wang<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Yu Li, Muhao Chen, Chaowei Xiao

[**Project Page**](https://rain305f.github.io/AdaShield-Project/) 
- This paper presents AdaShield, a novel adaptive defense mechanism designed to safeguard MLLMs against structure-based jailbreak attacks by using defense prompts without requiring fine-tuning or additional training.
- AdaShield achieves state-of-the-art performance, significantly improving defense robustness across multiple MLLMs while maintaining general performance on benign tasks, through its adaptive auto-refinement framework that customizes defense prompts to various attack scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLM 2024 and SafeBench Award</div><img src='images/jailbreakv28k.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks](https://arxiv.org/abs/2404.03027)

Weidi Luo<sup>*</sup>, Siyuan Ma<sup>*</sup>, <strong>Xiaogeng Liu<sup>*</sup></strong>, Xiaoyu Guo, Chaowei Xiao

[**Project Page**](https://eddyluo1232.github.io/JailBreakV28K/) 
- This work introduces JailBreakV-28K, a comprehensive benchmark for evaluating the robustness of MLLMs against both text-based and image-based jailbreak attacks, and RedTeam-2K, a dataset of 2,000 malicious queries covering 16 safety policies aimed at testing the vulnerabilities of LLMs and MLLMs.
- The benchmark highlights the transferability of jailbreak techniques from LLMs to MLLMs, revealing significant vulnerabilities in MLLMs' ability to handle malicious inputs across text and visual modalities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/teco.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Detecting Backdoors During the Inference Stage Based on Corruption Robustness Consistency](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_Detecting_Backdoors_During_the_Inference_Stage_Based_on_Corruption_Robustness_CVPR_2023_paper.html)

**Xiaogeng Liu**, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao

[**Project Page**](https://github.com/CGCL-codes/TeCo) <strong><span class='show_paper_citations' data='Gvs5nz8AAAAJ:2osOgNQ5qMEC'></span></strong>
- This paper introduces TeCo, a novel test-time trigger sample detection method that leverages the anomaly in corruption robustness consistency between clean and trigger samples, requiring only hard-label outputs and no additional data or assumptions.
- TeCo significantly outperforms state-of-the-art methods on various backdoor attacks and benchmarks, improving the AUROC by 10% and achieving 5 times the stability of existing methods.
</div>
</div>

# 🎖 Honors and Awards
- *2024.12* <span style="color:red;">NVIDIA 2025-2026 Graduate Fellowship</span>
- *2024.08* <span style="color:red;">Distinguished Paper Award</span> in 33rd USENIX Security Symposium (USENIX Security'24)
- *2022.10* Chinese National Scholarship (Top 1%)

# 📖 Educations
- *2025.09 - present*, Ph.D, Johns Hopkins University, Baltimore, Maryland, USA.
- *2023.09 - 2025.06*, Ph.D, University of Wisconsin-Madison, Madison, Wisconsin, USA.
- *2020.09 - 2023.06*, Master, Huazhong University of Science and Technology, Wuhan, Hubei, China.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
