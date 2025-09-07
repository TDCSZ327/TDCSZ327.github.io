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

Hi, I'm Tianyu. I am a Ph.D. student at Dartmouth College. I have the great honor of being advised by [Prof. Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/).

I am passionate about model diagnostics and mechanistic interpretability . My  current research is focused on

- understanding the mechanisms, dynamics and generalization of LLMs  from the perspective of random matrix theory, high-dimensional statistics and loss landscape;
- leveraging  model/data diagnostics and interpretability insights to improve the transparency, robustness and efficiency  of (scientific) machine learning.

# 📖 Educations

- *2025.09 - present*, Ph.D. in Machine Learning, Department of Computer Science, Dartmouth College.
- *2022.09 - 2025.06*, M.S. in Mathematics, Department of Mathematics, Nanjing University. 
- *2018.09 - 2022.06*, B.S. in Statistics, Kuang Yaming Honors School, Nanjing University. 


# 🔥 News
- *2025.07*: 🎉🎉Excited to share that our work“From Spikes to Heavy Tails: Unveiling the Spectral Evolution of Neural Networks”  is accepted by [TMLR](https://openreview.net/forum?id=DJHB8eBUnt&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DTMLR%2FAuthors%23your-submissions)).
- *2025.05*: 🎉🎉 Excited to share that our work “LIFT the Veil for the Truth: Principal Weights Emerge after Rank Reduction for Reasoning-Focused Supervised Fine-Tuning” is accepted by [ICML 2025](https://icml.cc/) as **Poster**!
- *2024.10*: &nbsp;😁 Completing a wonderful three-month visiting at Dartmouth College.
- *2024.09*: &nbsp;🎉🎉 Excited to share that our work “Model Balancing Helps Low-data Training and Fine-tuning” is accepted by [EMNLP 2024](https://2024.emnlp.org) as **Oral Presentation**!
- *2023.09*: &nbsp;🎉🎉 Excited to share that our work “Temperature Balancing, Layer-wise Weight Analysis, and Neural Network Training” is accepted by [NeurIPS 2023](https://neurips.cc/Conferences/2023) as **Spotlight**!

# 📝 Publications 

（# denotes equal contribution）



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2025</div><img src='images/ICLR_2025_1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">



**From Spikes to Heavy Tails: Unveiling the Spectral Evolution of Neural Networks** 

[Vignesh Kothapalli](https://kvignesh1420.github.io), **Tianyu Pang**, [Shenyang Deng](https://scholar.google.com/citations?user=TvUZLD8AAAAJ&hl=en&oi=ao), [Zongmin Liu](https://www.linkedin.com/in/zongmin-dylan-liu-73438a242/details/education/), [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/)

[Code](https://github.com/kvignesh1420/single-index-ht)\|[Paper](https://arxiv.org/pdf/2406.04657)

**TMLR 2025** 

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/ICML_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LIFT the Veil for the Truth: Principal Weights Emerge after Rank Reduction for Reasoning-Focused Supervised Fine-Tuning**

[Zihang Liu](https://zihanghliu.github.io), **Tianyu Pang**, [Oleg Balabanov](https://scholar.google.com/citations?user=N-Rm3SIAAAAJ&hl=en), Chaoqun Yang, [Tianjin Huang](https://tianjinyellow.github.io/), [Lu Yin](https://luuyin.com/), [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/), [Shiwei Liu](https://shiweiliuiiiiiii.github.io/)

[Code]( https://github.com/zihanghliu/LIFT)\|[Paper](https://arxiv.org/pdf/2506.00772)

**ICML 2025**

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/EMNLP_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">




**Why LLM Safety Guardrails Collapse After Fine-tuning: A Similarity Analysis Between Alignment and Fine-tuning Datasets** 

[Lei Hsiung](https://hsiung.cc/), **Tianyu Pang**, [Yung-Chen Tang](https://sites.google.com/view/yungchentang), [Linyue Song](https://www.linkedin.com/in/linyue-song), [Tsung-Yi Ho](https://www.cse.cuhk.edu.hk/people/faculty/tsung-yi-ho/), [Pin-yu Chen](https://sites.google.com/site/pinyuchenpage) , [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/)

[Paper](https://arxiv.org/abs/2506.05346)\|[Demo](https://hsiung.cc/llm-similarity-risk/)

**ICML 2025 Workshop DIG-BUG <span style="color: red;">Oral</span>**

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/EMNLP_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Model Balancing Helps Low-data Training and Fine-tuning**

[Zihang Liu](https://zihanghliu.github.io)#, [Yuanzhe Hu](https://github.com/HUST-AI-HYZ)#, **Tianyu Pang**, [Yefan Zhou](https://yefanzhou.github.io), [Pu Ren](https://paulpuren.github.io), [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/)

[Code](https://github.com/ZihangHLiu/ModelBalancing)\|[Paper](https://arxiv.org/abs/2410.12178)\|[Video](https://us06web.zoom.us/rec/play/5RHeJiEVuG-yw_Ytt9cHPMzqEIm2xWenwjhHjJ4yt7camtmQObTndJ56YgBBw0A1TlNRGiwZ2MAw5klz.7Xm2WgzcHdxPjGqm?autoplay=true)

**EMNLP 2024 <span style="color: red;">Oral</span>**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/NeurIPS_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Temperature Balancing, Layer-wise Weight Analysis, and Neural Network Training** 

[Yefan Zhou](https://yefanzhou.github.io)#, **Tianyu Pang**#, [Keqin Liu](https://scholar.xjtlu.edu.cn/en/persons/kevin-liu), [Charles H. Martin](https://www.linkedin.com/in/charlesmartin14/), [Michael Mahoney](https://www.stat.berkeley.edu/~mmahoney/), [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/)

[Code](https://github.com/YefanZhou/TempBalance)\|[Paper](https://arxiv.org/abs/2312.00359)\|[Video](https://recorder-v3.slideslive.com/?share=87192&s=14ff4069-14ea-4f19-bf8b-368a2db26dfd)

**NeurIPS 2023 <span style="color: red;">Spotlight</span>**

</div>
</div>
