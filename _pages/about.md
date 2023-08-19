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

I am a Graduate Student at Beihang University, pursuing a Masters in Computer Science, a member of Intelligent recognition and image processing laboratory (IRIPLaboratory).

I’m currently working on Computer Vision, including:

- Image Restoration and Synthesis
- Object Detection
- Model Compression


# 🔥 News
- *2023.07*: &nbsp; One paper is accepted by ACM Multimedia 2023.
- *2022.10*: &nbsp; My github stars have exceeded 3000!🎉🎉.
- *2022.04*: &nbsp; I release a distributed training [template](https://github.com/Janspiry/distributed-pytorch-template) by Pytorch. Welcome to STAR!.
- *2022.01*: &nbsp; My [github project](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) is introduced in the Trending Research of [Papers with Code](https://paperswithcode.com/) and [Github](https://github.com/trending)!.
- *2021.06*: &nbsp; I'm graduate from Sichuan University and become a research internter in SenseTime.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM-MM 2023</div><img src='images/MIEP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- [MIEP: Channel Pruning with Multi-granular Importance Estimation for Object Detection](images/MIEP.pdf) -->
MIEP: Channel Pruning with Multi-granular Importance Estimation for Object Detection

**Liangwei Jiang**, Jiaxin Chen, Di Huang, Yunhong Yang
- MIEP achieves a better balance between accuracy and efficiency compared to lightweight object detectors, and generalizes well to various detection frameworks (e.g., Faster-RCNN and FSAF) and tasks (e.g., classification).
<!-- - Under 75% FLOPs reduction, MIEP achieves a 37.0% mAP on GFL with COCO. Specifically, MIEP compresses a 90%-FLOPs reduction in RetinaNet and Faster-RCNN, even retains 74.1% and 76.1% mAP on VOC, respectively. -->
</div>
</div>
<!-- - [MSN: Multi-directional Similarity Network for Hand-crafted and Deep-synthesized Copy-Move Forgery Detection](images/MSN.pdf), **Liangwei Jiang**, Jinluo Xie, Yecheng Huang, Hua Zhang, Hongyu Yang, Di Huang -->
- MSN: Multi-directional Similarity Network for Hand-crafted and Deep-synthesized Copy-Move Forgery Detection, **Liangwei Jiang**, Jinluo Xie, Yecheng Huang, Hua Zhang, Hongyu Yang, Di Huang


# 🎖 Honors and Awards
- *2020.08* National College Student Service Outsourcing innovation and Entrepreneurship Competition, **Second Award** (Final, Captain). 
- *2019.06* ICPC China and Silk-Road Contest, **Silver Medal** (Invitational).
- *2019.06* SiChuan University Outstanding Student.
- *2019.03* SiChuan Province LanQiao Cup Professional Talent Competition, **Second Award**.
- *2018-2020* National Inspirational Scholarship.
- *2018.11* National College Student Mathematics Competition, **Second Award**.
- *2018.06* SiChuan University Advanced Individual of Student Association.


# 📖 Educations
- *2021.09 - present*, Master, Beihang University, Computer Science.
- *2017.09 - 2021.06*, Undergraduate, Sichuan University, Computer Science.
<!-- # 💬 Invited Talks -->

# 💻 Internships
- *2023.05 - present*, Research intern at Baidu, Inc., Beijing, China 
  -  Duties included: Video and Image understand 
- *2021.06 - 2021.09*, Research intern at SenseTime, Beijing, China 
  -  Duties included: Image restoration and skin color detection 