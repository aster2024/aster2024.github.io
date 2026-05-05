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

Currently I am at **Xiaohongshu (Rednote) HI Lab** through the **REDstar Talent Program**, focusing on the R&D of LLM Foundation Models. Throughout my undergraduate journey at SJTU Zhiyuan College (Honor Program, Top 10%), I have been fortunate to collaborate with and be mentored by esteemed researchers, including [Prof. Philip S. Yu](https://cs.uic.edu/profiles/philip-yu/), [Prof. Bingsheng He](https://www.comp.nus.edu.sg/~hebs/), [Prof. Shuai Li](https://shuaili8.github.io/), [Prof. Bao-Liang Lu](https://bcmi.sjtu.edu.cn/~blu/), and [Prof. Wei-Long Zheng](https://weilongzheng.github.io/).

My research has been published in top-tier venues such as KDD, EMNLP (main), NeurIPS, and **ICLR (Oral)**. I also serve as a reviewer for conferences like **ICLR 2026**. Beyond research, I am a competitive programmer with multiple Gold Medals in **ICPC** and **CCPC**, mentored by [Prof. Yong Yu](https://apex.sjtu.edu.cn/members/yyu).

My research interests include **LLMs, Agentic Systems, Privacy and Safety, and Efficient ML**. Feel free to reach out if you'd like to chat!


<p style="text-align: center;">
<a href="mailto:sjtu18640985163@sjtu.edu.cn">Email</a> / 
<a href="https://www.linkedin.com/in/jizhou-guo-6971b6277">LinkedIn</a> / 
<a href="images/wechat.jpg">WeChat</a> /
<a href="images/qq.jpg">QQ</a> /
<a href="images/xiaohongshu.jpg">Xiaohongshu (RedNote)</a> /
<a href="assets/pdf/CV_Jizhou_Guo.pdf">CV</a>
</p>

# 🔥 News
- *2026.04*: &nbsp; <a href="https://arxiv.org/abs/2510.10994">DeepResearchGuard</a> and _LLM-HAS Survey_ are accepted to ACL 2026! 🎉
- *2026.03*: &nbsp; _Self-Supervised EEG-based Emotion Recognition_ is selected as ICASSP 2026 <span style="color: #8B0000;">Oral</span>!
- *2026.02*: &nbsp; <a href="https://arxiv.org/abs/2509.24496">LLM DNA</a> is selected as ICLR 2026 <span style="color: #8B0000;">Oral</span> (Top 1%)!
- *2026.01*：&nbsp; <a href="https://arxiv.org/abs/2505.12225">SWIFT</a> is featured by <a href="https://mp.weixin.qq.com/s/ka5bndnjGxux3qyOnz6Yeg">AI Era (新智元)</a>.
- *2026.01*: &nbsp; <a href="https://arxiv.org/abs/2510.06186">RECODE-H</a> and <a href="https://arxiv.org/abs/2509.24496">LLM DNA</a> are accepted to ICLR 2026! 🎉
- *2026.01*: &nbsp; _Self-Supervised EEG-based Emotion Recognition_ is accepted to ICASSP 2026! 🎉
- *2025.11*: &nbsp; 🎉<a href="https://arxiv.org/abs/2505.12225">SWIFT</a> is accepted to KDD 2026! 🎉
- *2025.09*: &nbsp; <a href="https://arxiv.org/abs/2509.23614">PSG-Agent</a> is on arXiv!
- *2025.08*: &nbsp; 🎉<a href="https://arxiv.org/abs/2410.10481">Llamdex</a> is accepted to EMNLP 2025 main conference! 🎉
- *2025.04*: &nbsp; <a href="https://pubmed.ncbi.nlm.nih.gov/41335954/">EEG Cross-Stimulus Transfer Learning</a> is accepted to EMBC 2025! 🎉
- *2024.09*: &nbsp; <a href="https://arxiv.org/abs/2405.18711">Internal Consistency</a> is accepted to NeurIPS 2024! 🎉

# 📝 Selected Publications 
_<sup>*</sup> denotes equal contribution_

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src='images/swift.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Mining Intrinsic Rewards from LLM Hidden States for Efficient Best-of-N Sampling**

**Jizhou Guo**, Zhaomin Wu, Hanchen Yang, Philip S. Yu

_KDD 2026_

[[arXiv]](https://arxiv.org/abs/2505.12225) [[code]](https://github.com/aster2024/SWIFT) [[HF Daily]](https://huggingface.co/papers/2505.12225) [[AI Era (新智元)]](https://mp.weixin.qq.com/s/ka5bndnjGxux3qyOnz6Yeg)

<small>Proposed SWIFT, a lightweight reward model based on the LLM hidden states, which systematically outperforms baselines with less than 0.005% of the parameters of baselines.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 main</div><img src='images/llamdex.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

**Model-based Large Language Model Customization as Service**

Zhaomin Wu\*, **Jizhou Guo**\*, Junyi Hou, Bingsheng He, Lixin Fan, Qiang Yang

_EMNLP 2025 main_

[[arXiv]](https://arxiv.org/abs/2410.10481) [[code]](https://github.com/Xtra-Computing/Llamdex)

<small>Proposed Llamdex, a novel framework that facilitates LLM customization as a service for domain-specific applications. It boosted accuracy by up to 26% while preserving privacy.</small>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/psg_agent.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

**PSG-Agent: Personality-Aware Safety Guardrail for LLM-based Agents**

Yaozu Wu\*,  **Jizhou Guo**\*, Dongyuan Li\*, Henry Peng Zou, Wei-Chieh Huang, Yankai Chen, Zhen Wang, Weizhi Zhang, Yangning Li, Meng Zhang, Renhe Jiang, Philip S. Yu

_Under review_

[[arXiv]](https://arxiv.org/abs/2509.23614)

<small>Introduces PSG-Agent, a training-free system that provides personalized safety guardrails for LLM-based agents.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Oral</div><img src='images/llm_dna.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LLM DNA: Tracing Model Evolution via Functional Representations**

Zhaomin Wu, Haodong Zhao, Ziyang Wang, **Jizhou Guo**, Qian Wang, Bingsheng He

_ICLR 2026 <span style="color: #8B0000;">Oral</span> (Top 1%)_

[[arXiv]](https://arxiv.org/abs/2509.24496)

<small>Introduced LLM DNA, a mathematically grounded, low-dimensional functional representation for LLMs. We developed RepTrace, a training-free pipeline that extracts DNA signatures to trace the evolutionary lineage of 305+ models.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/internal_consistency.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Calibrating Reasoning in Language Models with Internal Consistency**

Zhihui Xie, **Jizhou Guo**, Tong Yu, Shuai Li

_NeurIPS 2024_

[[arXiv]](https://arxiv.org/abs/2405.18711) [[poster]](https://neurips.cc/media/PosterPDFs/NeurIPS%202024/93260.png) [[code]](https://github.com/zhxieml/internal-consistency)

<small>Proposed "internal consistency" approach to calibrate reasoning in LLMs, resulting in a significant boost in reasoning performance without requiring additional training.</small>
</div>
</div>

[//]: # (<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMBC 2025</div><img src='images/dann.png' alt="sym" width="60%"></div></div>)

[//]: # (<div class='paper-box-text' markdown="1">)

[//]: # (**Cross-Stimulus Transfer Learning: Enhancing Emotion Recognition from Visual-Auditory to Olfactory Perception**)

[//]: # ()
[//]: # (Jiaqi Wang\*, Zhengting Chen\*, Keyan Huang, Yifan Wu, Dian Zhang, **Jizhou Guo**, Xinglan Liu, Dan Peng, Baoliang Lu, Weilong Zheng)

[//]: # ()
[//]: # (_EMBC 2025_)

[//]: # ()
[//]: # (<small>Adopted Transformer-based Domain-Adversarial Neural Network &#40;DANN&#41; for cross-stimulus transfer learning task between olfactory and visual-auditory stimuli and outperformed conventional methods.</small>)

[//]: # (</div>)

[//]: # (</div>)

[//]: # ()
[//]: # (In addition, I have also completed several projects. Please refer to my [CV]&#40;assets/pdf/CV_Jizhou_Guo.pdf&#41; for further details.)


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

Invited as reviewer: [ICLR 2026](https://iclr.cc/Conferences/2026), [EMBC 2025](https://embc.embs.org/2025/), [AI4MATH @ ICML 2025](https://sites.google.com/view/ai4mathworkshopicml2025)

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

<!-- # 💼 Experience

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
</div> -->

# 🎖 Selected Honors and Awards
_Click <a href="assets/pdf/certificates.pdf">here</a> to view all certificates_

- *2025.12* Zhiyuan Honors Scholarship.
- *2025.12* Academic Excellence Scholarship, SJTU (Top 10%, ranked 2nd overall).
- *2025.10* Zhiyuan Overseas Research Scholarship.
- *2025.09* Merit Student of SJTU.
- *2025.01* <strong> Gold Award🥇 </strong> and <strong> First Runner-up </strong> in the National College Students' Career Planning Contest (Shanghai Region).
- *2024.12* Zhiyuan Honors Scholarship.
- *2024.11* Zhiyuan <strong>First-Class</strong> Overseas Research Scholarship.
- *2024.09* Merit Student of SJTU.
- *2023.12* Academic Excellence Scholarship, SJTU (Top 10%, ranked 2nd overall).
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
