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

Hi! I am a 3rd-year undergraduate at <strong>Zhiyuan College (Honor, Top 10%), Shanghai Jiao Tong University</strong>.
My academic journey has been enriched by several research experiences.
Currently I am mentored by <a href="https://cs.uic.edu/profiles/philip-yu/">Prof. Philip S. Yu</a> at University of Illinois Chicago.
Most recently, I was a research intern at National University of Singapore under the supervision of <a href="https://www.comp.nus.edu.sg/~hebs/">Prof. Bingsheng He</a>.
Before that, I worked as an undergraduate researcher at Shanghai Jiao Tong University, mentored by <a href="https://shuaili8.github.io/">Prof. Shuai Li</a> and <a href="https://scholar.google.com/citations?user=6-ARmXsAAAAJ">Dr. Tong Yu</a>.
I've also had the privilege of collaborating with <a href="https://bcmi.sjtu.edu.cn/~blu/">Prof. Bao-Liang Lu</a> and <a href="https://weilongzheng.github.io/">Prof. Wei-Long Zheng</a>.

Besides research, I've excelled in competitive programming, winning awards in OI, ICPC, CCPC and various other contests, under the guidance of <a href="https://apex.sjtu.edu.cn/members/yyu">Prof. Yong Yu</a>. See my <a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a> for details.

My research interests are primarily focused on Large Language Models (Foundation Models) and Natural Language Processing. I'm always eager to engage in discussions about these topics, so please feel free to reach out if you'd like to chat!

<p style="text-align: center;">
<a href="mailto:sjtu18640985163@sjtu.edu.cn">Email</a> / 
<a href="https://www.linkedin.com/in/jizhou-guo-6971b6277">LinkedIn</a> / 
<a href="images/wechat.jpg">WeChat</a> /
<a href="images/qq.jpg">QQ</a> /
<a href="images/xiaohongshu.jpg">Xiaohongshu (RedNote)</a> /
<a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a>
</p>

# 🔥 News
- *2025.07*: &nbsp; <a href="https://arxiv.org/abs/2505.12225">ELHSR</a> is accepted to ICML 2025 AI for Math Workshop.
- *2025.06*: &nbsp; <a href="https://arxiv.org/abs/2410.10481">Llamdex</a> is accepted to ICML 2025 Data in Generative Models Workshop. See you in Vancouver!
- *2025.05*: &nbsp; Check out <a href="https://arxiv.org/abs/2505.12225">ELHSR</a>, a highly efficient reward model for LLMs.
- *2025.04*: &nbsp; _Cross-Stimulus Transfer Learning_ is accepted to EMBC 2025! 🎉
- *2024.10*: &nbsp; <a href="https://arxiv.org/abs/2410.10481">Llamdex</a> is on arXiv!
- *2024.09*: &nbsp; <a href="https://arxiv.org/abs/2405.18711">Internal Consistency</a> is accepted to NeurIPS 2024! 🎉
- *2024.05*: &nbsp; <a href="https://arxiv.org/abs/2405.18711">Internal Consistency</a> is on arXiv!

# 📝 Selected Publications 
_<sup>*</sup> denotes equal contribution_

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DIG-BUGS @ ICML 2025</div><img src='images/llamdex.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Model-based Large Language Model Customization as Service**

Zhaomin Wu\*, **Jizhou Guo**\*, Junyi Hou, Bingsheng He, Lixin Fan, Qiang Yang

_DIG-BUGS @ ICML 2025 (Long Paper)_

[[arXiv]](https://arxiv.org/abs/2410.10481)

- Proposed _Llamdex_, a novel framework that facilitates LLM customization as a service for domain-specific applications.
- Achieved substantial performance improvements in domain-specific tasks, **boosting accuracy by up to 26%** while preserving privacy and maintaining efficiency on par with the base LLM.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/elhsr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Reward Inside the Model: A Lightweight Hidden-State Reward Model for LLM's Best-of-N sampling**

**Jizhou Guo**, Zhaomin Wu, Philip S. Yu

_AI4Math @ ICML 2025_

[[paper]](https://openreview.net/forum?id=mCRC1ealFP)

- Proposed _ELHSR_, a highly parameter-efficient reward model leveraging the LLM hidden states, which **systematically outperforms baselines** with **less than 0.005% of the parameters** of baselines, resulting in orders-of-magnitude efficiency improvement.
- ELHSR also performs well with limited data, extends to logit-only training for certain closed-source LLMs, and can be combined with conventional reward models to yield further performance improvements.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/internal_consistency.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Calibrating Reasoning in Language Models with Internal Consistency**

Zhihui Xie, **Jizhou Guo**, Tong Yu, Shuai Li

_NeurIPS 2024_

[[arXiv]](https://arxiv.org/abs/2405.18711) [[poster]](https://neurips.cc/media/PosterPDFs/NeurIPS%202024/93260.png) [[code]](https://github.com/zhxieml/internal-consistency)

- Developed a novel "_internal consistency_" approach to calibrate reasoning in LLMs, **resulting in a significant boost in reasoning performance** without requiring additional training.
- Conducted in-depth analysis of Chain-of-Thought (CoT) reasoning in LLMs through the lens of internal representations. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMBC 2025</div><img src='images/dann.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

**Cross-Stimulus Transfer Learning: Enhancing Emotion Recognition from Visual-Auditory to Olfactory Perception**

Jiaqi Wang\*, Zhengting Chen\*, Keyan Huang, Yifan Wu, Dian Zhang, **Jizhou Guo**, Xinglan Liu, Dan Peng, Baoliang Lu, Weilong Zheng

_EMBC 2025_ (Full Contributed paper)

- Designed a cross-stimulus transfer learning task between olfactory and visual-auditory stimuli.
- Adopted Transformer-based Domain-Adversarial Neural Network (DANN) and outperformed conventional methods.

</div>
</div>

In addition, I have also completed several projects. Please refer to my [CV](assets/pdf/CV_Jizhou_Guo.pdf) for further details.


[//]: # (# 📚 Selected Projects)

[//]: # ()
[//]: # (<div class='paper-box'><div class='paper-box-image'><div><img src='images/2aRNN_model.png' alt="sym" width="100%"></div></div>)

[//]: # (<div class='paper-box-text' markdown="1">)

[//]: # ()
[//]: # (**Two-Area RNN: Representations for Context-Dependent Decisions**)

[//]: # ()
[//]: # (**Jizhou Guo**, Liting Pang, Zhaoyu Zhu, Ziyi Xu)

[//]: # ()
[//]: # ([[PDF]]&#40;assets/pdf/2aRNN_report.pdf&#41; [[code]]&#40;https://github.com/aster2024/2aRNN&#41;)

[//]: # ()
[//]: # (- Proposed a novel **Two-Area RNN** architecture for context-dependent decision-making tasks.)

[//]: # ()
[//]: # (</div>)

[//]: # (</div>)

[//]: # ()
[//]: # (Beyond this project, I have also completed work on SplitNN implementation, a review of AlphaGo, and validation of the Frequency Principle. Please refer to my [CV]&#40;assets/pdf/CV_Jizhou_Guo.pdf&#41; for further details.)

# 🌍 Services

Invited as reviewer: [EMBC 2025](https://embc.embs.org/2025/), [AI4MATH @ ICML 2025](https://sites.google.com/view/ai4mathworkshopicml2025)

<style>
.experience-box {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  overflow: hidden;
}
.experience-image {
  width: 100px;
  min-width: 100px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f5f5f5;
}
.experience-image img {
  max-width: 90%;
  max-height: 90%;
  object-fit: contain;
}
.experience-text {
  flex: 1;
  padding: 15px;
}
.experience-text h3 {
  margin-top: 0;
}
</style>

# 💼 Experience

<div class="experience-box">
  <div class="experience-image">
    <img src="images/uic_logo.png" alt="UIC logo">
  </div>
  <div class="experience-text" markdown="1">

### University of Illinois Chicago

2025.06 - 2025.08  
Research Assistant  
Advisor: [Prof. Philip S. Yu](https://cs.uic.edu/profiles/philip-yu/)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/nus_logo.jpeg" alt="NUS logo">
  </div>
  <div class="experience-text" markdown="1">

### National University of Singapore

2024.06 - 2024.08  
Research Assistant  
Advisor: [Prof. Bingsheng He](https://www.comp.nus.edu.sg/~hebs/)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/pku_logo.jpeg" alt="PKU logo">
  </div>
  <div class="experience-text" markdown="1">

### Peking University

2023.07  
Student Trainee  
Quantitative Biology Summer School of [Center for Life Sciences](http://www.cls.edu.cn/) (50 candidates nationwide)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/tencent_logo.jpeg" alt="Tencent logo">
  </div>
  <div class="experience-text" markdown="1">

### Tencent Corporation

2022.08  
Research Intern  
Spark Project (AI group) (50 high-school students with talents nationwide)

  </div>
</div>

<div class="experience-box">
  <div class="experience-image">
    <img src="images/sjtu_logo.jpeg" alt="SJTU logo">
  </div>
  <div class="experience-text" markdown="1">

### Shanghai Jiao Tong University

2022.09 - Present  
Bachelor of Science in Mathematics with <strong>Honors</strong>, [Zhiyuan College](https://zhiyuan.sjtu.edu.cn/)  
Research Advisors: [Prof. Shuai Li](https://shuaili8.github.io/), [Prof. Bao-Liang Lu](https://bcmi.sjtu.edu.cn/~blu/), and [Prof. Wei-Long Zheng](https://weilongzheng.github.io/)

  </div>
</div>

# 🎖 Selected Honors and Awards
_Click <a href="assets/pdf/certificates.pdf">here</a> to view all certificates_
- *2025.01* <strong> Gold Award🥇 </strong> and <strong> First Runner-up </strong> in the National College Students' Career Planning Contest (Shanghai Region).
- *2024.12* Zhiyuan Honors Scholarship.
- *2024.11* Zhiyuan <strong>First-Class</strong> Overseas Research Scholarship.
- *2024.09* Merit Student of SJTU.
- *2023.12* Second-Class Academic Scholarship, SJTU (Top 10%, ranked 2nd overall).
- *2023.12* Zhiyuan Honors Scholarship.
- *2023.12* Third Prize in Mathematics competition of Chinese College Students (Shanghai).
- *2023.09* <strong> First Prize </strong> in Shanghai Collegiate Programming Contest (Ranked 2nd in Shanghai).
- *2023.08* <strong> Gold Award🥇 </strong> in Astar Programming Contest (Shanghai Region) (Ranked 2nd in Shanghai).
- *2023.05* <strong> Gold Medal🥇 </strong> in 2023 China Collegiate Programming Contest (<strong>CCPC</strong>) National Invitational Contest (Hunan).  
- *2023.05* <strong> Gold Medal🥇 </strong> in 2023 International Collegiate Programming Contest (<strong>ICPC</strong>) Xi'an Invitational Contest.
- *2022.12* Zhiyuan Honors Scholarship.
- *2022.12* <strong> Gold Medal🥇 </strong> in 2022 International Collegiate Programming Contest (<strong>ICPC</strong>) Asia Hangzhou Regional Contest (Ranked 8th nationwide).
- *2022.09* <strong> Gold Medal🥇 </strong> in 2022 China Collegiate Programming Contest (<strong>CCPC</strong>) (Shanghai region).
- *2021.07* <strong> Silver Medal🥈 </strong> in National Olympiad in Informatics (<strong>NOI</strong>).
- *2021.03* <strong> Ranked 22nd nationwide </strong> in National Olympiad in Informatics (<strong>NOI</strong>) Online Senior Group.

# 🌈 Miscellaneous

Apart from academic studies and research, I have a wide range of interests, including piano and singing.

- I enjoy playing the piano🎹 and have passed <a href="https://www.abrsm.org/">ABRSM</a> Practical Grade 8 and <a href="https://kjzx.ccmusic.edu.cn/">CCM</a> Amateur Grade 10, both the highest levels. I've also won awards in several piano competitions.
- I am passionate about singing🎤 and have passed <a href="https://kjzx.ccmusic.edu.cn/">CCM</a> Amateur Grade 9 (highest level).
- I used to serve as the conductor of the choir in junior high school.
- I also have some experience in public speaking🗣️ and won Gold Award🥇 in the National College Students' Career Planning Contest (Shanghai Region).
- Regarding sports, I'm an amateur enthusiast of jogging🏃 and skiing⛷️.
- I have participated in various algorithm competitions🖥️ and earned Gold Medals🥇 in ICPC/CCPC and a Silver Medal🥈 in NOI.
