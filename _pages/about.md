---
permalink: /
title: "Xinyi Liu - Homepage"
excerpt: "Xinyi Liu is a student researcher at Microsoft and final year master's student at DTU of Autonomous Systems."
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

👋 I am a student researcher at <img src='images/Microsoft_logo.png' style='width: 18px; height: auto; vertical-align:-18%; margin-right:0px; margin-right:1px;'> [Microsoft](https://news.microsoft.com/source/) and a final year M.S. student at the [Technical University of Denmark](https://www.dtu.dk/english/) with the Full Tuition Fee Waiver (30 per year). Previously, I was an intern in computer vision at <img src='images/teton_ai_logo.jpeg' style='width: 24px; height: auto; vertical-align:-25%; margin-left:0px;'> [Teton](https://www.teton.ai/) and <img src='images/volvocars_logo.jpeg' style='width: 24px; height: auto; vertical-align:-25%; margin-left:0px;'>  [Volvo Cars](https://www.volvocars.com/), and I am a research assistant at  <img src='images/ucla_seal.jpg' style='width: 20px; height: auto; vertical-align:-18%; margin-left:-1px;'> [UCLA](https://www.ucla.edu/). I received my bachelor's degree from Tongji University with the Outstanding Graduate Honor and conducted research at the Institute of Intelligent Vehicles (TJU-IIV) directed by [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ) and [Prof. Hong Chen](https://scholar.google.com/citations?user=n_eA148AAAAJ&hl). 

My experience focuses on computer vision and robot learning with deep learning and generative models. [**I am searching for full positions in 2025**]()

# 🔥 News
- *2025.06*: &nbsp;👏 Our [V2XPnP](https://mobility-lab.seas.ucla.edu/v2xpnp/) paper on cooperative perception and prediction has been accepted by [ICCV 2025](https://iccv.thecvf.com/)!
- *2025.02*: &nbsp;💻 Start my student researcher in [Microsoft](https://news.microsoft.com/source/), focusing on robot agent for manipulation with LLM.
- *2024.05*: &nbsp;👏 Our unsupervised reinforcement learning papers on autonomous driving have been accepted by [_IEEE Transactions on Intelligent Transportation Systems_](https://ieeexplore.ieee.org/abstract/document/10538221) (Top-ranked in ITS Filed, IF:8.2)!
- *2024.01*: &nbsp;💻 Start my research assistant in [UCLA](https://www.ucla.edu/), focusing on prediction model implementation and map generation.
- *2024.01*: &nbsp;💻 Start my student project in [Teton](https://www.teton.ai/), focusing on implementation and test Yolo-based 3D human mesh recovery model.
- *2023.06*: &nbsp;🎉 Graduated from Tongji University with Outstanding Graduate Honor!
- *2023.03*: &nbsp;🎉 Received the [DTU](https://www.dtu.dk/english/) ASU (Autonomous Systems) Master offer with [Full Tuition Fee Waiver (30 per year)]()!
- *2022.10*: &nbsp;💻 Start my internship in [Volvo Cars](https://www.volvocars.com/), focusing on the development and implementation of a car defect detection model.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><img src='images/RobotAgent.gif' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">


**RoboCopilot: An LLM-based Robot Agent with Natural Language Instruction**

**Xinyi Liu**<span style="color:#7a8288;">, Mohammadreza Fani Sani, Bahram Zarrin, Roberto Galeazzi </span>

RobotCopilot integrated large language models with real-time perception and control modules, enabling high-level natural language commands to guide robotic pick-and-place operations. Successfully deployed on Universal Robot, demonstrating robust performance in dynamic environments.

[arXiv, 2025]() \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>]() \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>]() 


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/V2XPnP.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction**

<span style="color:#7a8288;">Zewei Zhou, Hao Xiang, Zhaoliang Zheng, Seth Z Zhao, Mingyue Lei, Yun Zhang, Tianhui Cai, </span>**Xinyi Liu**<span style="color:#7a8288;">, Johnson Liu, Maheswari Bajji, Xin Xia, Zhiyu Huang, Bolei Zhou, Jiaqi Ma</span>

V2XPnP includes the first open-source V2X spatio-temporal fusion framework for cooperative perception and prediction and the first real-world V2X sequential dataset featuring all V2X collaboration modes (VC, IC, V2V, I2I).

[ICCV, 2025](https://iccv.thecvf.com/) & [RSS MRS Workshop, 2025](https://mrs-workshop.github.io/rss25/papers/) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2412.01812) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://mobility-lab.seas.ucla.edu/v2xpnp/) \| [![](https://img.shields.io/github/stars/Zewei-Zhou/V2XPnP?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/Zewei-Zhou/V2XPnP)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/TITS.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Unsupervised Reinforcement Learning for Multi-Task Autonomous Driving: Expanding Skills and Cultivating Curiosity**

<span style="color:#7a8288;">Zhenyu Ma, </span>**Xinyi Liu**<span style="color:#7a8288;">, Yanjun Huang</span>


We introduced an unsupervised reinforcement learning method, Improved Contrastive Intrinsic Control (CIC), to help autonomous driving learn general skills and improve the generalization in different driving tasks.

[IEEE Transactions on Intelligent Transportation Systems](https://iccv.thecvf.com/)\| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://ieeexplore.ieee.org/abstract/document/10538221)

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
- *2023* &nbsp; [DTU Full Tuition Fee Waiver]() (**30 per year**)
- *2023* &nbsp; [Tongji Outstanding Student]() (**Top 1%**)
- *2022* &nbsp; Third Prize of Challenge Cup Academic Science and Technology Competition, China (**2.2% of 22,000**)
- *2022* &nbsp; Silver Model in Formula Student, China (**Ranking: 2/51**)
- *2022* &nbsp; Infineon Technologies Scholarship (**Top 3%**)
- *2021 & 2020* &nbsp; Weichai Scholarship (_Highest endowed scholarship in Tongji sponsored by Weichai Co., Ltd._, **Top 2%**, twice)
- *2019* &nbsp; National Scholarship, China (_Highest scholarship awarded by the Chinese government_, **Top 0.2%**)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 📖 Educations
- *2023.09 - 2025.06*, M.S., Autonomous Systems, <img src='images/DTU_Logo.jpg' style='width: 20px; height: auto; vertical-align:-33%; margin-right:0px;'> Technical University of Denmark (DTU), Copenhagen, Denmark **(Full Tuition Fee Waiver)**
- *2018.09 - 2023.06*, B.Eng., Automotive Engineering, <img src='images/Tongji_logo.png' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> Tongji University (Tongji), Shanghai, China **(Outstanding Graduate,Top 1%)**


# 💻 Experience
- *2025.02 - Present* &nbsp;  <img src='images/Microsoft_logo.png' style='width: 18px; height: auto; vertical-align:-18%; margin-right:0px; margin-right:1px;'> [Microsoft](https://news.microsoft.com/source/), Copenhagen, Denmark. \| **Student Researcher**
- *2024.01 - 2024.11* &nbsp; <img src='images/ucla_seal.jpg' style='width: 20px; height: auto; vertical-align:-18%; margin-left:-2px; margin-right:1px;'> [UCLA](https://www.teton.ai/), Los Angeles,U.S. (Remote) \| **Reseach Assistant**
- *2024.01 - 2024.05* &nbsp; <img src='images/teton_ai_logo.jpeg' style='width: 24px; height: auto; vertical-align:-22%; margin-left:-4.5px; margin-right:0.5px;'> [Teton](https://www.volvocars.com/), Copenhagen, Denmark. \| **Student Project**
- *2022.08 - 2022.10* &nbsp; <img src='images/volvocars_logo.jpeg' style='width: 24px; height: auto; vertical-align:-22%; margin-left:-4.5px; margin-right:0.5px;'> [Volvo Cars](https://www.volvocars.com/), Shanghai, China. \| **Internship**
- *2021.08 - 2023.06* &nbsp; <img src='images/Tongji_logo.png' style='width: 18px; height: auto; vertical-align:-22%; margin-left:-2px; margin-right:1.5px;'>  [Institute of Intelligent Vehicles (TJU-IIV)](), Tongji University, China. \| **Reseach Assistant**



<!-- # 🏓 Miscellaneous
- I am a big fan of guitar, especially [Fingerstyle](https://en.wikipedia.org/wiki/Fingerstyle_guitar). My favorite acoustic guitarist is [Satoshi Gogo](https://en.gogosatoshi.com/). I also enjoy playing ping pong and badminton.
- I have some experience in graphic design, and I designed the logo for the Joint Lab [SFVGL](https://csrf.ac.uk/international/china-srf-centre/) of Tongji and Cambridge. -->