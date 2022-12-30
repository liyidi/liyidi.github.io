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

I am currently an Associate Professor at University of Science and Technology Beijing (USTB). Prior to that I worked as a research fellow at National University of Singapore (NUS), Singapore, supervised by Prof. [Haizhou Li (李海洲)](https://colips.org/~eleliha/). I received my Ph.D. degree from Queen Mary, University of London (QMUL), U.K., under the supervision of Prof. [Andrea Cavallaro](http://www.eecs.qmul.ac.uk/~andrea/). During my Ph.D. degree, I went to Fondazione Bruno Kessler [(FBK)](https://www.fbk.eu/en/), Trento, Italy, as a research assistant, supervised by Dr. [Maurizio Omologo](https://www.amazon.science/author/maurizio-omologo) and Dr. [Alessio Brutti](https://ict.fbk.eu/people/detail/alessio-brutti-fbk-speech-processing/). I received my B.Eng. and M.Sc. degrees both from the University of Edinburgh, U.K., supervised by Prof. [James Hopgood](https://www.eng.ed.ac.uk/about/people/dr-james-r-hopgood).

My research interest mainly focuses on audio-visual fusion, includes speech processing, speaker localization and tracking, active speaker detection, gesture synthesis, automatic speech recognition. I have published more than 20 papers at the top-tiered international AI journals/conferences such as TMM, TASLP, TII, ACM MM, ICRA ICASSP, INTERSPEECH.

🔥 News

🎉🎉 Our lab in USTB is actively looking for research assistants and postgraduate students. Please contact me at qianxy@ustb.edu.cn for more details.
开展以深度学习为核心的<font color="red"> 语音信号处理、多模态人机交互研究 </font>，学生可以根据兴趣自由选择，欢迎对研究感兴趣的同学联系我~

# 📜 Research Area
<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Speech Processing </font>: <BR>&nbsp;&nbsp; Speaker recognition and verification 说话人识别<br> Speech separation and extraction</td>
    <td style="border: none;"> <font color="#0b5394"> Computer Vision </font>: <BR>&nbsp;&nbsp; Face recognition; Face detection; Lip reading；Gesture synthesis</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Multi-modal Processing </font>: <BR>&nbsp;&nbsp; Audio-visual active speaker detection; Speaker Localization and Tracking</td>
    <td style="border: none;"> <font color="#0b5394"> Self-supervised Learning </font>: <BR>&nbsp;&nbsp; Self-supervised speech processing </td>
  </tr>
</table>

# 💻 Research Experiences
- *2022.10 - Present*, Associate Professor, University of Science and Technology of Beijing (USTB), Beijing, China.
- *2022.03 - 2022.09*, Visiting Scholar, Chinese University of Hong Kong (CUHKSZ), Shenzhen, China.
- *2020.02 - 2022.02*, Research Fellow, National University of Singapore (NUS), Singapore.
- *2017.04 - 2018.12*, Research Asistant, Fondazione Bruno Kessler (FBK), Trento, Italy.
- *2014.06 - 2014.08*, Research Asistant, Heriot-Watt University (HWU), Edinburgh, United Kingdom.

# 📖 Educations
- *2015.11 - 2019.11*, Ph.D. in Computer Scicence, Queen Mary, University of London (QMUL), London, U.K. 
- *2014.08 - 2015.08*, M.Sc. in Signal Processing and Communications, University of Edinburgh (UoE), U.K.  (Distinction) 
- *2012.09 - 2014.06*, B.Eng. in Electronics and Electrical Engineering, University of Edinburgh (UoE), U.K. (First Class Honors) 
- *2010.09 - 2012.06*, B.Eng. in Information Engineering, Nanjing University of Aeronautics and Astronautics (NUAA), Nanjing, China. (Top: 3%)


# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

-- **2022** --
- **Xinyuan Qian**, Zhengdong Wang, Jiadong Wang, Guohui Guan, Haizhou Li, [Audio-Visual Cross-Attention Network for Robotic Speaker Tracking](https://ieeexplore.ieee.org/document/9968308)，**TASLP**, 2022.
- **Xinyuan Qian**, Qiquan Zhang, Guohui Guan and Wei Xue, [Deep Audio-visual Beamforming for Speaker Localization](https://ieeexplore.ieee.org/document/9750883), **SPL**, 2022.
- **Xinyuan Qian**, Jichen Yang, Alessio Brutti, [Speaker Front-back Disambiguity using Multi-channel Speech Signals](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ell2.12666?af=R), **Electronics Letters** 2022.
- Zexu Pan, **Xinyuan Qian<sup>`*`</sup>**, Haizhou Li, [Speaker Extraction with Co-Speech Gestures Cue](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9774925), **SPL**, 2022.
- Qiquan Zhang, **Xinyuan Qian<sup>`*`</sup>**, Zhaoheng Ni, Aaron Nicolson, Eliathamby Ambikairajah, Haizhou Li, [TFA-SE: A Time-Frequency Attention Module for Neural Speech Enhancement](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9966661), **TASLP**, 2022.
- Hongxu Zhu, Qiquan Zhang, Peng Gao, **Xinyuan Qian**, [Speech-Oriented Sparse Attention Denoising for Voice User Interface Toward Industry 5.0](https://ieeexplore.ieee.org/abstract/document/9893339/), **TII**, 2022.
- Yanjie Fu, Meng Ge, Haoran Yin, **Xinyuan Qian**, Longbiao Wang, Gaoyan Zhang, Jianwu Dang, [Iterative Sound Source Localization for Unknown Number of Sources](https://arxiv.org/abs/2206.12273), **TNTERSPEECH**, 2022.

-- **2021** --
- **Xinyuan Qian**, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [Audio-visual tracking of concurrent speakers](https://ieeexplore.ieee.org/document/9362311), **TMM**,2021.
- **Xinyuan Qian**, Qi Liu, Jiadong Wang, Haizhou Li, [Three-Dimensional Speaker Localization: Audio-Refined Visual Scaling Factor Estimation](https://ieeexplore.ieee.org/document/9466446), **SPL**, 2021.
- **Xinyuan Qian**, Bidisha Sharma, Amine El Abridi, Haizhou Li, [SLoClas: A Database for Joint Sound Localization and Classification](https://arxiv.org/abs/2108.02539), **COCOSDA**, 2021, **best paper award**.
- **Xinyuan Qian**, Maulik Madhavi, Zexu Pan, Jiadong Wang, Haizhou Li, [Multi-target DoA estimation with an audio-visual fusion mechanism](https://ieeexplore.ieee.org/document/9413776), **ICASSP**, 2021.
- Jiadong Wang, **Xinyuan Qian<sup>`*`</sup>**, Zihan Pan, Malu Zhang, Haizhou Li, [GCC-PHAT with Speech-oriented Attention for Robotic Sound Source Localization](https://ieeexplore.ieee.org/document/9561885), **ICRA**, 2021.
- Ruijie Tao, Zexu Pan, Rohan Kumar Das, **Xinyuan Qian**, Mike Zheng Shou, Haizhou Li, [Is Someone Speaking? Exploring Long-term Temporal Features for Audio-visual Active Speaker Detection](https://arxiv.org/abs/2107.06592), **ACM MM**, 2021.

-- **2020** --
- Shoufeng Lin<sup>`#`</sup>, **Xinyuan Qian<sup>`#`</sup>**, [Audio-Visual Multi-Speaker Tracking Based on the GLMB Framework](https://www.isca-speech.org/archive_v0/Interspeech_2020/pdfs/1969.pdf), **INTERSPEECH**, 2021.

-- **2019 and Before** --
- **Xinyuan Qian**, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [Multi-speaker tracking from an audio–visual sensing device](https://ieeexplore.ieee.org/document/8656587), **TMM**, 2019.
- **Xinyuan Qian**, Alessio Xompero, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [3D mouth tracking from a compact microphone array co-located with a camera](https://ieeexplore.ieee.org/document/8461323), **ICASSP**，2018.
- Oswald Lanz, Alessio Brutti, Alessio Xompero, **Xinyuan Qian**, Maurizio Omologo, Andrea Cavallaro, [Accurate Target Annotation in 3D from Multimodal Streams](https://ieeexplore.ieee.org/document/8682619), **ICASSP**，2018.
- **Xinyuan Qian**, Alessio Brutti,  Maurizio Omologo, Andrea Cavallaro, [3D audio-visual speaker tracking with an adaptive particle filter](https://ieeexplore.ieee.org/abstract/document/7952686), **ICASSP**，2017.
- Deepayan Bhowmik, Andrew Wallace, Robert Stewart, **Xinyuan Qian**, Greg Michaelson, [Profile driven dataflow optimisation of mean shift visual tracking](https://ieeexplore.ieee.org/document/7032066), **GlobalSIP**，2014.

# 🎖 Certifications and Awards
- Best Paper Award, COCOSDA, 2021
- The 3rd place winner in the ActivityNet Challenge (Speaker), CVPR Workshop, 2021
- Outstanding international research associatant,  FBK, Trento, Italy, 2019
- Full Ph.D. scholarship in QMUL, London, U.K., 2015-2019
- Outstanding Youth Female Research Engineer Scholarship, Edinburgh, U.K., 2014
- Excellent international student scholarship, Edinburgh, U.K., 2013-2014
- Shanghai 801 scholarship, 2011
- First-Class Scholarship Award, NUAA, Nanjing, China, 2010-2011

# 👔 Projects
- Human Robot Interaction Project-Phase 1, Singapore, 2020-2022
- Huawei Research&Design Project, Shenzhen, China, 2022
- Shenzhen Research Institute of Big Data Internal Project (SRIBD), Shenzhen, China, 2022

# 💬 Reviewer
- Reviewer of TASLP, TMM, Neural Networks, ICASSP, INTERSPEECH, SPL, ICPR
