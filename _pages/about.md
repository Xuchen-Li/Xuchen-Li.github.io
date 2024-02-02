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

# 👨🏻‍💻 About Me

I am **Xuchen Li <font face="楷体" >(李旭宸)</font>**, an incoming Ph.D. student at **<a href="http://english.ia.cas.cn/">Institute of Automation, Chinese Academy of Sciences (CASIA)</a>**, supervised by **<a href="https://people.ucas.ac.cn/~huangkaiqi?language=en">Prof. Kaiqi Huang</a>** (IAPR Fellow) at **<a href="http://www.crise.ia.ac.cn/"> Center for Research on Intelligent System and Engineering (CRISE)</a>**.

Currently, I am a fourth-year undergraduate student majoring in Computer Science and Technology at **<a href="https://scs.bupt.edu.cn/"> School of Computer Science (SCS)</a>** at **<a href="https://www.bupt.edu.cn/"> Beijing University of Posts and Telecommunications (BUPT)</a>**.

I am very grateful to work with **<a href="https://huuuuusy.github.io/">Dr. Shiyu Hu</a>**, which has a significant impact on me. I am also grateful to grow up and study with my twin brother Xuzhao Li, which is a truly unique and special experience for me.


# 🔥 News

- **2023.12** : 🏆 Obtain **China National Scholarship** with a rank of **1/455 (0.22%)** (highest honor for undergraduates in China, awarded to top 1% students of BUPT)!
- **2023.09** : 📝 One paper has been accepted by **the 37th Conference on Neural Information Processing Systems** (NeurIPS, CCF-A Conference, Poster)!
- **2022.12** : 🏆 Obtain **China National Scholarship** with a rank of **2/430 (0.47%)** (highest honor for undergraduates in China, awarded to top 1% students of BUPT)!

# 🔬 Research Interests

## Visual Object Tracking (VOT)

- Research in visual object tracking algorithms within diverse scenes, exemplified by benchmarks like GIT, LaSOT, and GOT-10k, aims to enhance the understanding and performance of single object tracking in various scenarios.
- Delving into the robustness and generalization aspects of single object tracking algorithms is crucial. This research investigates the algorithms' ability to adapt across diverse scenarios, ensuring consistent and reliable performance.

## Visual Language Tracking (VLT)

- Within the domain of Visual Language Tracking (VLT), there is a focus on multi-modal tracking, addressing challenges related to integrating visual and linguistic information for improved tracking accuracy.
- Research in VLT extends to tasks involving comprehensive video understanding. This encompasses efforts to enhance the algorithms' capability to interpret and contextualize objects in videos based on linguistic input.
- The exploration of human-computer interaction patterns employs Large Language Models (LLMs) in conjunction with visual language tracking as a proxy task. This approach facilitates a deeper understanding of user interactions with visual content, contributing to the development of interactions that are more intuitive and user-friendly.

# 📖 Educations

<div class='school-box'>
<div><img src='images/BUPT.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2020.09 - now, Undergraduate student<br>
Computer Science and Technology, Ranking 4/442 (0.9%)<br>
School of Computer Science<br>
Beijing University of Posts and Telecommunications, Beijing
</div>
</div>

# 💻 Research Experiences

* **2023.05 - Present** : Research intern on visual object tracking at **[Institute of Automation, Chinese Academy of Sciences (CASIA)](http://english.ia.cas.cn/)**,  advised by **[Prof. Kaiqi Huang](https://people.ucas.ac.cn/~huangkaiqi?language=en)**.
* **2023.05 - Present** : Participant of interdisciplinary symposia around computer vision (22 participants from 10+ universities, once a week) at **[Institute of Automation, Chinese Academy of Sciences (CASIA)](http://english.ia.cas.cn/)**,  initiated and organized by **[Dr. Shiyu Hu](https://huuuuusy.github.io/)**.
* **2023.04 - Present** : Member of Artificial Intelligence Elites Class at **[Institute of Automation, Chinese Academy of Sciences (CASIA)](http://english.ia.cas.cn/)**.
* **2023.01 - 2023.05** : Research intern on 3D scene reconstruction at **[Tsinghua University (THU)](https://www.tsinghua.edu.cn/en/)**,  advised by **[Prof. Haoqian Wang](https://scholar.google.com/citations?hl=zh-CN&user=eldgnIYAAAAJ&hl=en)**.

# 📝 Publications 

## Acceptance

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/MGIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and causal Relationship**

Shiyu Hu, Dailing Zhang, Meiqi Wu, Xiaokun Feng, **Xuchen Li**, Xin Zhao, Kaiqi Huang

NeurIPS 2023 (CCF-A Conference, Poster): **[the 37th Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2023)**<br>
  [[**PDF**](https://xuchen-li.github.io/files/MGIT.pdf)]
  [[**Poster**](https://xuchen-li.github.io/files/MGIT-poster.pdf)]
  [[**Slides**](https://xuchen-li.github.io/files/MGIT-Slides.pdf)]
  [[**Platform**](http://videocube.aitestunion.com/)]
  [[**Toolkit**](https://github.com/huuuuusy/videocube-toolkit)]
</div>
</div>

## Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-review">IJCAI 2024</div><img src='images/MemVLT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Remembering Target More Like Humans: A Robust Visual-Language Tracker with Adaptive Prompts**

Xiaokun Feng, **Xuchen Li**, Shiyu Hu, Dailing Zhang, Meiqi Wu, Xiaotang Chen, Kaiqi Huang

IJCAI 2024 (CCF-A Conference, Under Review): **[the 33rd International Joint Conference on Artificial Intelligence](https://ijcai24.org/)**<br>
</div>
</div>

# 🎖 Honors and Awards

- **2023 China National Scholarship** (My Rank: 1/455, 0.22%, highest honor for undergraduates in China, awarded to top 1% students), at BUPT, by Ministry of Education of China
* **2023 College Scholarship of University of Chinese Academy of Sciences** (only 17 students win this scholarship among 220 recommended postgraduate students), at CASIA, by University of Chinese Academy of Sciences
* **2023 National Third Prize** of Huawei Information and Communication Technology Competition Nationwide Final (team leader)
* **2023 National Third Prize** of China Robotics and Artificial Intelligence Competition
* **2023 National Level** College Students' Innovation and Entrepreneurship Training Program (team leader)
* **2023 National Level** College Students' Innovation and Entrepreneurship Training Program
* **2023 Beijing Municipal Merit Student** (only 36 students obtain this honor), at BUPT, by Beijing Municipal Education Commission
* **2022 China National Scholarship** (My Rank: 2/430, 0.47%, highest honor for undergraduates in China, awarded to top 1% students), at BUPT, by Ministry of Education of China
* **2022 Huawei AI Education Base Scholarship** (only 20 students win this scholarship among 3 colleges), at BUPT, by Ministry of Education of China and Huawei AI Education Base Joint Working Group
* **2022 National First Prize** of China Collegiate Computing Contest-Artificial Intelligence Innovation (only 7 teams win the first prize among 3,442 teams, team leader)
* **2022 Meritorious Winner** of Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling

# ⚙️ Maintained Projects

* **[VideoCube Platform](http://videocube.aitestunion.com/)** 
* **[SOTVerse Platform](http://metaverse.aitestunion.com/)**
* **[GOT-10k Platform](http://got-10k.aitestunion.com/)** 
* **[VideoCube Toolkit](https://github.com/huuuuusy/videocube-toolkit)**

# 🔗 For More Info

* **[Intelligence of Human-Computer Competition](http://turingai.ia.ac.cn/)**
* **[Research Group of Intelligent Gaming](http://www.ig.ia.ac.cn:81/)**
* **[Center for Research on Intelligent System and Engineering (CRISE)](http://www.crise.ia.ac.cn/)**
* **[Institute of Automation, Chinese Academy of Sciences (CASIA)](http://english.ia.cas.cn/)**
* **[University of Chinese Academy of Sciences (UCAS)](https://www.ucas.ac.cn/)**
* **[Beijing University of Posts and Telecommunications (BUPT)](https://www.bupt.edu.cn/)**

# ✉️ Contact

* lixuchen2024@ia.ac.cn (Main, Valid from 2023.10 - 2029.07)
* xuchenli@bupt.edu.cn (Valid from 2020.09 - 2024.07)
* xuchenli1030@gmail.com
