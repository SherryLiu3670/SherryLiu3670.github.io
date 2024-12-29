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

👋 I am a final year M.S. student at the Technical University of Denmark with the Full Tuition Fee Waiver (30 per year). Previously, I was an intern in computer vision at [Teton](https://www.teton.ai/) and [Volvo Cars](https://www.volvocars.com/), and I am a research assistant at [UCLA](https://www.ucla.edu/). I received my bachelor's degree from Tongji University with the Outstanding Graduate Honor and conducted research at the Institute of Intelligent Vehicles (TJU-IIV) directed by [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ) and [Prof. Hong Chen](https://scholar.google.com/citations?user=n_eA148AAAAJ&hl). 

My experience focuses on computer vision and robot learning. [**I am searching for full positions in 2025**]()

# 🔥 News
- *2024.12*: &nbsp;👏 Our [V2XPnP](https://mobility-lab.seas.ucla.edu/v2xpnp/) paper on cooperative perception and prediction has been released. Enjoy it! 
- *2024.05*: &nbsp;👏 Our unsupervised reinforcement learning papers on autonomous driving have been accepted by [_IEEE Transactions on Intelligent Transportation Systems_](https://ieeexplore.ieee.org/abstract/document/10538221) (Top-ranked in ITS Filed, IF:8.2)!
- *2024.01*: &nbsp;💻 Start my research assistant in [UCLA](https://www.ucla.edu/), focusing on prediction model implementation and map generation.
- *2024.01*: &nbsp;💻 Start my student project in [Teton](https://www.teton.ai/), focusing on implementation and test Yolo-based 3D human mesh recovery model.
- *2023.06*: &nbsp;🎉 Graduated from Tongji University with Outstanding Graduate Honor!
- *2023.03*: &nbsp;🎉 Received the [DTU](https://www.dtu.dk/english/) ASU (Autonomous Systems) Master offer with [Full Tuition Fee Waiver (30 per year)]()!
- *2022.10*: &nbsp;💻 Start my internship in [Volvo Cars](https://www.volvocars.com/), focusing on the development and implementation of a car defect detection model.

# 📖 Educations
- *2023.09 - 2025.06*, M.S., Autonomous Systems, <img src='images/DTU_Logo.jpg' style='width: 20px; height: auto; vertical-align:-33%; margin-right:0px;'> Technical University of Denmark (DTU), Copenhagen, Denmark **(Full Tuition Fee Waiver)**
- *2018.09 - 2023.06*, B.Eng., Automotive Engineering, <img src='images/Tongji_logo.png' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> Tongji University (Tongji), Shanghai, China **(Outstanding Graduate,Top 1%)**

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><img src='images/V2XPnP_framework.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction**

Zewei Zhou, Hao Xiang, Zhaoliang Zheng, Seth Z Zhao, Mingyue Lei, Yun Zhang, Tianhui Cai, **Xinyi Liu**, Johnson Liu, Maheswari Bajji, Jacob Pham, Xin Xia, Zhiyu Huang, Bolei Zhou, Jiaqi Ma

_**arXiv**_, 2024 \| [_**Paper**_](https://arxiv.org/abs/2412.01812) \| [_**Project**_](https://mobility-lab.seas.ucla.edu/v2xpnp/) \| [![](https://img.shields.io/github/stars/Zewei-Zhou/V2XPnP?style=social&label=Code%20Stars)](https://github.com/Zewei-Zhou/V2XPnP)

- We proposed V2XPnP, the first open-source V2X spatio-temporal fusion framework for cooperative perception and prediction, and V2XPnP Sequential Dataset, the first large-scale, real-world V2X sequential dataset featuring multiple agents and all V2X collaboration modes (VC, IC, V2V, I2I).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/TITS.png' alt="sym" width="95%"></div>
<div class='paper-box-text' markdown="1">

**Unsupervised Reinforcement Learning for Multi-Task Autonomous Driving: Expanding Skills and Cultivating Curiosity**

Zhenyu Ma, **Xinyi Liu**, Yanjun Huang

_**IEEE Transactions on Intelligent Transportation Systems**_, 2024

Top-ranked in ITS Filed, IF:8.2 \| [_**Paper**_](https://ieeexplore.ieee.org/abstract/document/10538221) 


- We introduced an unsupervised reinforcement learning method, Improved Contrastive Intrinsic Control (CIC), to help autonomous driving learn general skills and improve the generalization in different driving tasks.
</div>
</div>


# 🔬 Projects

<div class='paper-box'><div class='paper-box-image'><img src='images/volvo.png' alt="sym" width="90%"></div>
<div class='paper-box-text' markdown="1">

**Automatic car body defect detection system**

[Volvo Cars](https://www.volvocars.com/), Shanghai, China, *2022.08 - 2022.10*


**Internship**

- Trained a defect detection model using Yolo v5, which can sort car body defects into dents and scratches, sort car seat
defects into five types, whose accuracy arrived at 89% and 84% respectively in the test sets
- Programmed the back-end API based on Django, whose functions include user-information management, image sets and detection algorithms upload, defect detection and results display

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/slam.gif' alt="sym" width="85%"></div>
<div class='paper-box-text' markdown="1">

**Indoor High Precision Positioning and Navigation System Based on VSLAM**

[Tongji University](), Shanghai, China, *2020.04 - 2021.04*


Student Innovatation Training Program (SITP), **Team Leader**

- Built 3D point cloud map using 2 ORB-SLAM2 frames
- Developed WeChat navigation applet based on Feng-map open source map
</div>
</div>


# 🎖 Honors and Awards
- *2023* &nbsp; Tongji Outstanding Student (**Top 1%**)
- *2022* &nbsp; Third Prize of Challenge Cup Academic Science and Technology Competition, China (**2.2% of 22,000**)
- *2022* &nbsp; Silver Model in Formula Student, China (**Ranking: 2/51**)
- *2022* &nbsp; Infineon Technologies Scholarship (**Top 3%**)
- *2021 & 2020* &nbsp; Weichai Scholarship (_Highest endowed scholarship in Tongji sponsored by Weichai Co., Ltd._, **Top 2%**, twice)
- *2019* &nbsp; National Scholarship, China (_Highest scholarship awarded by the Chinese government_, **Top 0.2%**)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experience
- *2024.01 - 2024.11*, [UCLA](https://www.teton.ai/), Los Angeles,U.S. (Remote) \| **Reseach Assistant**
- *2024.01 - 2024.05*, [Teton](https://www.volvocars.com/), Shanghai, China. \| **Student Project**
- *2022.08 - 2022.10*, [Volvo Cars](https://www.volvocars.com/), Shanghai, China. \| **Internship**
- *2021.08 - 2023.06*, [Institute of Intelligent Vehicles (TJU-IIV)](), Tongji University, China. \| **Reseach Assistant**



<!-- # 🏓 Miscellaneous
- I am a big fan of guitar, especially [Fingerstyle](https://en.wikipedia.org/wiki/Fingerstyle_guitar). My favorite acoustic guitarist is [Satoshi Gogo](https://en.gogosatoshi.com/). I also enjoy playing ping pong and badminton.
- I have some experience in graphic design, and I designed the logo for the Joint Lab [SFVGL](https://csrf.ac.uk/international/china-srf-centre/) of Tongji and Cambridge. -->