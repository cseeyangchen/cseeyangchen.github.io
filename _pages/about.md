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

I am currently a third-year master's student under the supervision of [Prof. Ling Wang](https://faculty.uestc.edu.cn/eewangling/zh_CN/index.htm) at the [School of Information and Communication Engineering](https://www.sice.uestc.edu.cn/), [University of Electronic Science and Technology of China (UESTC)](https://www.uestc.edu.cn/3974ba6dfa50d5c04a9414d3ce8bfd34.html?n=8e7z368tn51) in Chengdu, China, where I will graduate and receive my M.Eng. degree. Prior to that, I received my B.Sc. degree in Electronic Information Science and Technology from the [School of Physics](https://www.sp.uestc.edu.cn/) of UESTC in Jun. 2021. Concurrently I obtained a B.B.A. degree in Business Administration from the [School of Management and Economics](https://www.mgmt.uestc.edu.cn/index.htm) of UESTC at the same period. Looking toward the future, I am honored to have the opportunity to pursue a Ph.D. degree under the supervision of [Prof. Jingcai Guo](https://jingcaiguo.github.io/), with Department of Computing at [Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/) in Hong Kong SAR, starting in Sep. 2024. 

My research interest includes **Computer Vision**, **Human Action Recognition**, **Zero/Few-shot Learning** and **AI+Healthcare**. If you share similar interests or are open to discussing academic research, please feel free to email me at [csychen@std.uestc.edu.cn](). I believe this form of mutual learning will create new opportunities for interesting research, benefiting all of us. 

# 📖 Educations
- *2021.09 - 2024.06 (now)*, M.Eng., University of Electronic Science and Technology of China, Chengdu, China (Supervisor: Prof. Ling Wang)
- *2018.09 - 2021.06*, B.B.A., University of Electronic Science and Technology of China, Chengdu, China
- *2017.09 - 2021.06*, B.Sc., University of Electronic Science and Technology of China, Chengdu, China

# 🔥 News
- *2023.12*: &nbsp;🎉🎉 I am admitted to the Ph.D. program at Hong Kong Polytechnic University, under the supervision of [Prof. Jingcai Guo](https://jingcaiguo.github.io/).
- *2023.10*: &nbsp;🎉🎉 One paper has been accepted by BIBM 2023!
- *2023.10*: &nbsp;🎉🎉 One paper has been accepted by [Journal of Visual Communication and Image Representation (JVCIR)](https://www.sciencedirect.com/journal/journal-of-visual-communication-and-image-representation)!
- *2023.10*: &nbsp;🎉🎉 One paper has been accepted by [Engineering Applications of Artificial Intelligence (EAAI)](https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence)!
- *2023.04*: &nbsp;🎉🎉 One paper has been accepted by EMBC 2023!

# 📝 Publications 
## Published and Accepted Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BIBM23</div><img src='images/BIBM23.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PLFormer: Prompt Learning for Early Warning of Unplanned Extubation in ICU]()

**Yang Chen**, Tian He, Xu Gao, Hong Cheng, Ling Wang*

*IEEE International Conference on Bioinformatics and Biomedicine* (BIBM23, CCF-B), 2023.

**Contribution:** We design a PLFormer approach based on spatial-temporal prior knowledge prompts related to patients' actions to strategically optimize and guied the learning process towards significant body parts of patients.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI</div><img src='images/EAAI.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatio-Temporal Features for Fast Early Warning of Unplanned Self-Extubation in ICU](https://authors.elsevier.com/c/1hxKT3OWJ94sLz)

**Yang Chen**, Ling Wang*, Guorong Wang, Shuang Yang, Yingying Wang, MingFang Xiang, Xuan Zhang, Hui Chen, Dekun Hu, Hong Cheng

*Engineering Applications of Artificial Intelligence* (EAAI, CCF-C, JCR-Q1/中科院1区/IF=8.0), 2023

**Contribution:** This is the first work for early warning of patients' unplanned self-extubation behaviours in ICU by non-invasive and non-contacted RGB monitory videos.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JVCIR</div><img src='images/JVCI.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-view Graph Convolution Network for the Recognition of Human Action with Spatial and Temporal Occlusion Problems](https://authors.elsevier.com/c/1hyLm3k8X3qOxV)

**Yang Chen**, Ling Wang*, Dekun Hu, Hong Cheng

*Journal of Visual Communication and Image Representation* (JVCIR, CCF-C, JCR-Q2/中科院3区/IF=2.6), 2023.

**Contribution:** We propose a separable multi-view information fusion module MGL with the property of "plug-and-play" for occlusion challenges in human action recognition.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMBC23</div><img src='images/EMBC23.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[STformer: Spatial-Temporal Transformer for Early Warning of Unplanned Extubation in ICU](https://ieeexplore.ieee.org/document/10340923)

**Yang Chen**, Shuang Yang, Yingyin Wang, Guorong Wang, Hong Cheng, Ling Wang*

*45th Annual International Conference of the IEEE Engineering in Medicine and Biology Society* (EMBC23), 2023.

**Contribution:** We propose a lightweight STformer based on spatial-temporal self-attention mechanisms to explore ICU patients' spatial representation and long-term dependency on ICU patients' fine-grained actions.

</div>
</div>



<!-- ## Submitted Papers
- [Vision-Language Meets the Skeleton: A Novel Pre-training Paradigm with Large Multimodal Models](), <br />
**Yang Chen**, Tian He, Junfeng Fu, Ling Wang*, Jingcai Guo, Hong Cheng, <br />


- [Vision-Instructed Language Prompts Assist Skeleton-Based Action Recognition: Bridging Environmental Information Gaps](), <br />
Tian He, **Yang Chen**, Xu Gao, Ling Wang, Hong Cheng*, <br />


- [An Expert-Knowledge-based Graph Convolutional Network for Skeleton-based Physical Rehabilitation Exercises Assessment](), <br />
Tian He, **Yang Chen**, Ling Wang, Hong Cheng*, <br />


- [Semantic Assisted Two-Stream Transformer for Early Warning of Abnormal Action in ICU](), <br />
**Yang Chen**, Ling Wang*, Guorong Wang, Shuang Yang, Yingyin Wang, Dekun Hu, Hong Cheng, <br />
<!-- Submitted to *Computer Methods and Programs in Biomedicine* (CMPB, JCR-Q1/中科院2区/IF=6.1, Under Review), 2023 -->


## Patents
- [A Method for Optimizing Dietary Energy Intake in Cancer Patients (一种肿瘤患者膳食能量摄入优化方法)](), <br />
Tian Zhang, Yao Liu, **Yang Chen**, Ling Wang, Guorong Wang, Jing Qiu, Yufang Ren, Hongyan Zhou, Yuliang Gao, Xianggang Zhang, Min Tang, Kewang Li, Xiaowei Meng, Mingmin Liu, Ling Wang<br />
Public Number: CN 116665843 B, Application Date: 2023-07-28, Public Date: 2023-10-13

- [A Approach for Early Warning of Self-extubation Behavior of ICU Patients Based on RGB Video Monitoring (一种基于RGB视频监控的ICU患者自拔管行为预警方法)](), <br />
**Yang Chen**, Ling Wang, Yingyin Wang, Shuang Yang, Guorong Wang, <br />
Application Number: CN202211237998.8, Application Date: 2022-10-10, Public Date: 2023-01-03


# 🎖 Honors and Awards
- *2023.10* The First Prize Academic Scholarship.
- *2022.10* The Third Prize Academic Scholarship.
- *2022.10* IEEEXtreme 16.0 Programming Winner (Top 13% Globally).
- *2022.04* The Third Prize in the Huawei Software Elite Challenge-2022.
- *2021.10* The First Prize Academic Scholarship.
- *2020.10* The Excellent Academic Scholarship.
- *2020.05* Meritorious Winner in COMAP'S Mathematical Contest in Modeling (Top 6% Globally).
- *2019.10* The Excellent Academic Scholarship.
- *2018.10* The Pacesetter Student Scholarship. 

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Services
## Journal Reviewer
- Reviewer for IEEE Journal of Biomedical and Health Informatics (IEEE JBHI)
- Reviewer for Biomedical Signal Processing and Control (BSPC)
- Reviewer for IEEE Open Journal of the Computer Society (IEEE OJ-CS)
  
## Conference Reviewer
- Medical Image Computing and Computer Assisted Intervention (MICCAI 2024)
- International Conference on Machine Learning (ICML 2024)
- ACM Multimedia (ACM-MM 2024)
