---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-bottom: 60px;
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; 
    max-width: 100%;
  }

  hr {
    border: 1px solid #ebebeb;
    clear: both; 
  }

  dl dd {
    margin-top: 5px; 
    margin-bottom: 5px;
  }

  dl dd strong {
    font-weight: bold;
    color: black;
  }

  .co-first {
    color: red;
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 😊 About Me

Greetings!👋
I'm Jianshu Zhang (张鉴殊), a 4th year undergraduate student at the [School of Cyber Science and Engineering](http://cse.whu.edu.cn/index.htm), [Wuhan University](https://www.whu.edu.cn/).  
Prior to WHU, I spent three years studying at [Shenzhen Middle School (深圳中学)](https://www.shenzhong.net/). 

My research interests mainly focus on **Reliable (multimodal) LLMs, Data-centric AI, and Lifelong Learning**. 
Recently, I’ve started exploring **Reasoning**, focusing on key areas such as multimodal reasoning; longer reasoning and inference time scaling laws; and step-by-step reward mechanisms.

Currently, I'm actively seeking 🤗 25Fall Ph.D. positions 🤗 to further pursue my research goals. Feel free to connect and discuss exciting opportunities or collaborations!




# 🔥 News
- *2024.10*: &nbsp; I was selected as  Outstanding National Scholarship Student Representative!  
- *2024.10*: &nbsp; I won the **National Scholarship** 🥰  (Award Rate: 0.2% national-wide)!
- *2024.09*: &nbsp; One paper has been accepted by NeurIPS 2024 (D&B track). ✊ 
- *2024.09*: &nbsp; Two papers have been accepted by EMNLP 2024 (Main). 👏 
- *2024.07*: &nbsp; Attended CogSci 2024 in Rotterdam, Netherlands. The atmosphere is fantastic!
- *2024.03*: &nbsp; One paper has been accepted by Cogsci 2024 <strong><span style="color:red;">[Oral]</span></strong>.
- *2024.01*: 👽 Our work of [FuzzLLM](https://arxiv.org/abs/2309.05274) is invited to present at one of the top hacker conventions -- [*ShmooCon 2024*](https://www.shmoocon.org/speakers/#fuzzllm)!




# 📝 Publications 
<sup>&dagger;</sup> : equal contribution (names listed in no particular order), <sup>*</sup> : corresponding author

## Data-Centric AI
<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/it.png"></dt>
  <dd><a href="https://arxiv.org/pdf/2406.07502"><strong>Image Textualization: An Automatic Framework for Generating Rich and Detailed Image Descriptions</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Renjie Pi<sup>&dagger;</sup>, Jipeng Zhang, Rui Pan, Zhekai Chen, Tong Zhang<sup>*</sup></dd>
  <dd>The Thirty-Eighth Annual Conference on Neural Information Processing Systems [(NeurIPS 2024)](https://nips.cc/Conferences/2024)</dd>
  <dd>[[arXiv](https://arxiv.org/pdf/2406.07502)] [[code](https://github.com/sterzhang/image-textualization)]</dd>
</dl>

## Reliable (Multi-modal) LLMs
<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/mllm-protector.png"></dt>
  <dd><a href="https://arxiv.org/pdf/2401.02906"><strong>MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Renjie Pi<sup>&dagger;</sup>, Tianyang Han<sup>&dagger;</sup>, Yueqi XIE, Rui Pan, Qing LIAN, Hanze Dong, Jipeng Zhang, Tong Zhang<sup>*</sup></dd>
  <dd>The 2024 Conference on Empirical Methods in Natural Language Processing [(EMNLP 2024)](https://2024.emnlp.org/)</dd>
  <dd>[[arXiv](https://arxiv.org/pdf/2401.02906)] [[code](https://github.com/pipilurj/MLLM-protector)]</dd>
</dl>

<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/first.png"></dt>
  <dd><a href="https://arxiv.org/pdf/2408.12168"><strong>FIRST: Teach A Reliable Large Language Model Through Efficient Trustworthy Distillation</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, KaShun SHUM<sup>&dagger;</sup>, Minrui Xu<sup>&dagger;</sup>, Zixin CHEN, Shizhe Diao, Hanze Dong, Jipeng Zhang, Muhammad Omer Raza</dd>
  <dd>The 2024 Conference on Empirical Methods in Natural Language Processing [(EMNLP 2024)](https://2024.emnlp.org/)</dd>
  <dd>[[arXiv](https://arxiv.org/pdf/2408.12168)] [[code](https://github.com/sterzhang/FIRST)]</dd>
</dl>

<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/fuzzllm.png"></dt>
  <dd><a href="https://ieeexplore.ieee.org/document/10448041"><strong>FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Dongyu Yao<sup>&dagger;</sup>, Ian G. Harris<sup>*</sup>, Marcel Carlsson</dd>
  <dd>2024 IEEE International Conference on Acoustics, Speech and Signal Processing [(ICASSP 24)](https://cmsworkshops.com/ICASSP2024/papers/accepted_papers.php)</dd>
  <dd>[[arXiv](https://arxiv.org/abs/2309.05274)] [[code](https://github.com/sterzhang/FuzzLLM)]</dd>
</dl>

## Lifelong Learning
<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/core.png"></dt>
  <dd><a href="https://arxiv.org/abs/2402.01348"><strong>CORE: Mitigating Catastrophic Forgetting in Continual Learning through Cognitive Replay</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Yankai Fu<sup>&dagger;</sup>, Ziheng Peng<sup>&dagger;</sup>, Dongyu Yao, Kun He<sup>*</sup></dd>
  <dd>2024 Cognitive Science Society Annual Conference [(CogSci 2024)](https://cognitivesciencesociety.org/cogsci-2024/)</dd>
  <dd>[[arXiv](https://arxiv.org/abs/2402.01348)][[Code](https://github.com/sterzhang/CORE)]</dd>
</dl>

## ⌛️ In Submission & Preprint
<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/pvit.png"></dt>
  <dd><a href="https://arxiv.org/pdf/2410.07113"><strong>Personalized Visual Instruction Tuning</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Renjie Pi<sup>&dagger;</sup>, Tianyang Han, Jipeng Zhang, Rui Pan, Tong Zhang<sup>*</sup></dd>
  <dd>[[arXiv](https://arxiv.org/pdf/2410.07113)] [[code](https://github.com/sterzhang/PVIT)]</dd>
</dl>

<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/can.png"></dt>
  <dd><a href=""><strong>Client As Navigator: Emphasizing the Role of Clients in Federated Continual Learning</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Xuankun Rong<sup>&dagger;</sup>, Kun He, Mang Ye<sup>*</sup></dd>
  <dd>[[arXiv]()][[code]()]</dd>
</dl>

<dl>
  <dt><img align="left" width="400" hspace="10" wspace="20" src="../images/paper/bridge-coder.png"></dt>
  <dd><a href="https://arxiv.org/pdf/2410.18957"><strong>Bridge-Coder: Unlocking LLMs' Potential to Overcome Language Gaps in Low-Resource Code</strong></a></dd>
  <dd>**Jianshu Zhang**<sup>&dagger;</sup>, Jipeng Zhang<sup>&dagger;</sup>, Yuanzhe LI<sup>&dagger;</sup>, Renjie Pi, Rui Pan, Runtao Liu, Zheng Ziqiang, Tong Zhang<sup>*</sup></dd>
  <dd>[[arXiv]()] [[code]()]</dd>
</dl>

<!-- ## Data-Centric AI
- [**Image Textualization: An Automatic Framework for Generating Rich and Detailed Image Descriptions**](https://arxiv.org/pdf/2406.07502) 

  **Jianshu Zhang**<sup>&dagger;</sup>, Renjie Pi<sup>&dagger;</sup>, Jipeng Zhang, Rui Pan, Zhekai Chen, Tong Zhang<sup>*</sup> 

  The Thirty-Eighth Annual Conference on Neural Information Processing Systems [(NeurIPS 2024)](https://nips.cc/Conferences/2024)

  [[arXiv](https://arxiv.org/pdf/2406.07502)] [[code](https://github.com/sterzhang/image-textualization)]

## Reliable (Multi-modal) LLMs

- [**MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance**](https://arxiv.org/pdf/2401.02906) 

  **Jianshu Zhang**<sup>&dagger;</sup>, Renjie Pi<sup>&dagger;</sup>, Tianyang Han<sup>&dagger;</sup>, Yueqi XIE, Rui Pan, Qing LIAN, Hanze Dong, Jipeng Zhang, Tong Zhang<sup>*</sup> 

  The 2024 Conference on Empirical Methods in Natural Language Processing [(EMNLP 2024)](https://2024.emnlp.org/) 

  [[arXiv](https://arxiv.org/pdf/2401.02906)] [[code](https://github.com/pipilurj/MLLM-protector)]

- [**FIRST: Teach A Reliable Large Language Model Through Efficient Trustworthy Distillation**]()

  **Jianshu Zhang**<sup>&dagger;</sup>, KaShun SHUM<sup>&dagger;</sup>, Minrui Xu<sup>&dagger;</sup>, Zixin CHEN, Shizhe Diao, Hanze Dong, Jipeng Zhang, Muhammad Omer Raza 

  The 2024 Conference on Empirical Methods in Natural Language Processing [(EMNLP 2024)](https://2024.emnlp.org/)  

  [[arXiv](https://arxiv.org/pdf/2408.12168)] [[code](https://github.com/sterzhang/FIRST)]

- [**FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models**](https://ieeexplore.ieee.org/document/10448041)

  **Jianshu Zhang**<sup>&dagger;</sup>, Dongyu Yao<sup>&dagger;</sup>, Ian G. Harris<sup>*</sup> , Marcel Carlsson

  
  2024 IEEE International Conference on Acoustics, Speech and Signal Processing [(ICASSP 24)](https://cmsworkshops.com/ICASSP2024/papers/accepted_papers.php) 
  
  [[arXiv](https://arxiv.org/abs/2309.05274)] [[code](https://github.com/sterzhang/FuzzLLM)]

## Lifelong Learning
- [**CORE: Mitigating Catastrophic Forgetting in Continual Learning through Cognitive Replay**](https://arxiv.org/abs/2402.01348) 

  **Jianshu Zhang**<sup>&dagger;</sup>, Yankai Fu<sup>&dagger;</sup>, Ziheng Peng<sup>&dagger;</sup>, Dongyu Yao, Kun He<sup>*</sup>

  2024 Cognitive Science Society Annual Conference [(CogSci 2024)](https://cognitivesciencesociety.org/cogsci-2024/)  <strong><span style="color:red;">[Oral]</span></strong>
  
  [[arXiv](https://arxiv.org/abs/2402.01348)][[Code](https://github.com/sterzhang/CORE)]



## ⌛️ In Submission & Preprint

  - [**Personalized Visual Instruction Tuning**](https://arxiv.org/pdf/2410.07113) 

    **Jianshu Zhang**<sup>&dagger;</sup>, Renjie Pi<sup>&dagger;</sup>, Tianyang Han, Jipeng Zhang, Rui Pan, Tong Zhang<sup>*</sup> 

    [[arXiv](https://arxiv.org/pdf/2410.07113)] [[code](https://github.com/sterzhang/PVIT)] 

  
  - [**Client As Navigator: Emphasizing the Role of Clients in Federated Continual Learning**]() 

    **Jianshu Zhang**<sup>&dagger;</sup>, Xuankun Rong<sup>&dagger;</sup>, Kun He, Mang Ye<sup>*</sup> 

    [[arXiv]()] [[code]()]
  
  - [**Bridge-Coder: Unlocking LLMs' Potential to Overcome Language Gaps in Low-Resource Code**](https://arxiv.org/pdf/2410.18957) 

    **Jianshu Zhang**<sup>&dagger;</sup>, Jipeng Zhang<sup>&dagger;</sup>, Yuanzhe LI<sup>&dagger;</sup>, Renjie Pi, Rui Pan, Runtao Liu, Zheng Ziqiang, Tong Zhang*

    [[arXiv]()] [[code]()]



 
 -->

# 🏆 Honors and Awards
- *2024.10*: &nbsp; Outstanding National Scholarship Student Representative (the Only One from the department)
- *2024.10*: &nbsp; National Scholarship (Award Rate: 0.2% national-wide) *Ministry of Education, China*
- *2024.10*: &nbsp; First Class Scholarship (Award Rate: 5% school-wide) *Wuhan University*
- *2024.05*: &nbsp; First Prize in the 17th China Undergraduate Computer Design Competition of Middle South Division (Award Rate: 3% division-wide)
- *2023.12*: &nbsp; Advanced Individual in Scientific Innovation *Wuhan University*
- *2023.10*: &nbsp; 2022-2023 Merit Student *Wuhan University*
- *2023.05*: &nbsp; First Prize (*4.5% nationwide*), Huazhong Contest in Mathematical Modeling
- *2022.10*: &nbsp; 2021-2022 Merit Student *Wuhan University*



# 📖 Educations
- *2021.09 - now*, Undergraduate, [School of Cyber Science and Engineering](http://cse.whu.edu.cn/index.htm), [Wuhan University](https://www.whu.edu.cn/), China. 
- *2018.09 - 2021.07*, Senior Middle School, [Shenzhen Middle School](https://www.shenzhong.net/), China.



# 💻 Internships
- *2024.10 - now,* Research Intern in [MIT](https://www.mit.edu/), under the supervision of Prof. [Paul Liang](https://pliang279.github.io/) and Dr. [Yi R. (May) Fung](https://yrf1.github.io/).
- *2024.02 - now,* Research Assistant in [University of Illinois Urbana-Champaign (UIUC)](https://illinois.edu/), supervised by Prof. [Tong Zhang](https://tongzhang-ml.org/)
- *2023.09 - 2024.5,* Research Assistant at [Data Security Lab, Wuhan University](https://datasec.whu.edu.cn/), supervised by Prof. [Kun He](https://cse.whu.edu.cn/info/1262/3298.htm)
- *2023.07 - 2023.09*, UCInspire Summer Research Program (University of California Irvine), supervised by Prof. [Ian G. Harris](https://www.ics.uci.edu/~harris/index.html)
- *2023.06 - 2023.09*, [Tencent](https://www.tencent.com/zh-cn/index.html), IEG (Interactive Entertainment Group), Shenzhen, China.



