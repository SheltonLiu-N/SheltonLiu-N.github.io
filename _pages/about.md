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

My name is Xiaogeng Liu, currently a second-year Ph.D. student in Information Science at the University of Wisconsin-Madison. I am honored to conduct my research under the esteemed guidance of Professor [Chaowei Xiao](https://xiaocw11.github.io/#about), who specializes in security, privacy, and machine learning, with the goal of building socially responsible machine learning systems. I obtained my Master's degree from Huazhong University of Science and Technology in 2023, and was fortunate to be a member of [TAI group](http://trustai.group), mentored by Professor [Shengshan Hu](http://faculty.hust.edu.cn/HUSHENGSHAN/zh_CN/index.htm).

My research interests lie in trustworthy AI, especially the robustness of machine learning models that emphasizes the model's ability to maintain performance and resist any kind of attacks or unexpected inputs. I have published several papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=Gvs5nz8AAAAJ'>google scholar citations <a href='[https://scholar.google.com/citations?user=DhtAFkwAAAAJ](https://scholar.google.com/citations?user=Gvs5nz8AAAAJ)'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. I am always open to collaboration and the exchange of ideas. If you'd like to discuss potential research opportunities or simply connect, please don't hesitate to reach out to me at **xiaogeng.liu@wisc.edu**


# 🔥 News
<ul>
    <li>
        [2024-02] <span style="color:red">One paper is accepted by USENIX Security 2024</span>, thanks for all of my collaborators. 
        "Don’t Listen To Me: Understanding and Exploring Jailbreak Prompts of Large Language Models" Zhiyuan Yu, <strong>Xiaogeng Liu</strong>, Shunning Liang, Zach Cameron, Chaowei Xiao, Ning Zhang.
    </li>
    <li>
        [2024-01] <span style="color:red">One paper is accepted by ICLR 2024</span>, thanks for all of my collaborators. 
        "AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models" <strong>Xiaogeng Liu</strong>, Nan Xu, Muhao Chen, Chaowei Xiao.
    </li>
    <li>
        [2023-07] <span style="color:red">One paper is accepted by S&amp;P 2024</span>, thanks for all of my collaborators. 
        "Why Does Little Robustness Help? A Further Step Towards Understanding Adversarial Transferability" Yechao Zhang, Shengshan Hu, Leo Yu Zhang, Junyu Shi, Minghui Li, <strong>Xiaogeng Liu</strong>, Wei Wan, Hai Jin.
    </li>
</ul>

<details>
  <summary>More</summary>
<ul>
    <li>
        [2023-07] <span style="color:red">One paper is accepted by ACM MM 2023</span>, thanks for all of my collaborators. 
        "PointCRT: Detecting Backdoor in 3D Point Cloud via Corruption Robustness" Shengshan Hu, Wei Liu, Minghui Li, Yechao Zhang, <strong>Xiaogeng Liu</strong>, Xianlong Wang, Leo Yu Zhang.
    </li>
    <li>
        [2023-02] <span style="color:red">One paper is accepted by CVPR 2023</span>, thanks for all of my collaborators. 
        "Detecting Backdoors During the Inference Stage Based on Corruption Robustness Consistency" <strong>Xiaogeng Liu</strong>, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao.
    </li>
    <li>
        [2022-09] Our team (Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang, Ziqi Zou, Xianlong Wang) at 
        <a href="https://www.zgc-aisc.com/en">AISC2022-Physical World Adversarial Face Recognition</a> (Rank 5/178).
    </li>
    <li>
        [2022-06] Our team (Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang, Shengshan Hu) wins the third prize at 
        <a href="https://artofrobust.github.io/#challenge">CVPR2022 Art Of Robustness Workshop: Open-Set Defence</a> (Rank 3/156).
    </li>
    <li>
        [2022-02] One paper is shared at CVPR 2022 Art Of Robustness Workshop, thanks for all of my collaborators. 
        "Towards Efficient Data-Centric Robust Machine Learning with Noise-Based Augmentation" <strong>Xiaogeng Liu</strong>, Haoyu Wang, Yechao Zhang, Fangzhou Wu, Shengshan Hu.
    </li>
    <li>
        [2022-09] I am awarded the <span style="color:red">Chinese National Scholarship</span> for Graduate Students.
    </li>
    <li>
        [2022-02] <span style="color:red">One paper is accepted by CVPR 2022</span>, thanks for all of my collaborators. 
        "Protecting Facial Privacy: Generating Adversarial Identity Masks via Style-Robust Makeup Transfer" Shengshan Hu, <strong>Xiaogeng Liu</strong>, Yechao Zhang, Minghui Li, Leo Yu Zhang, Hai Jin, Libing Wu.
    </li>
    <li>
        [2022-01] Our team (Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang) at 
        <a href="https://tianchi.aliyun.com/competition/entrance/531939/introduction">Tianchi: AAAI2022 Secure AI Challenger Program Phase 8: Data-Centric Robust Machine Learning Competition</a> (Rank 8/3691).
    </li>
    <li>
        [2021-10] Our team (Haoyu Wang, <strong>Xiaogeng Liu</strong>, Yechao Zhang) at 
        <a href="https://security.oppo.com/challenge/home.html">OPPO AI Challenge - Face Recognition Competition</a> (Rank 14/2349).
    </li>
    <li>
        [2021-04] <span style="color:red">One paper is accepted by ACM MM 2021</span>, thanks for all of my collaborators. 
        "Advhash: Set-to-set Targeted Attack on Deep Hashing with One Single Adversarial Patch" Shengshan Hu, Yechao Zhang, <strong>Xiaogeng Liu</strong>, Leo Yu Zhang, Minghui Li, Hai Jin.
    </li>
</ul>
</details>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
