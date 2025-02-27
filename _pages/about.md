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
    margin-top: 1px;
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🧑‍💻 About Me

Greetings!👋
I'm Jianshu Zhang (张鉴殊), a 4th year undergraduate at the [Wuhan University](https://www.whu.edu.cn/) and an incoming CS PhD at the [Northwestern University](https://www.northwestern.edu/), co-supervised by Professor [Liu Han](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/liu-han.html) and Professor [Manling Li](https://limanling.github.io/). 

My long-term goal is to enhance the interaction between humans and AI by focusing on three key attributes: (i) reliability, (ii) multimodality, and (iii) adaptability. Specifically, my primary focus will be on bridging the gap between a model’s linguistic capabilities and its proficiency in other domains (especially in vision/action).
Feel free to connect and discuss exciting opportunities or collaborations! ([wechat](https://sterzhang.github.io/images/wechat.jpg))



# 🔥 News
- *2025.01*: &nbsp; 1 paper (PVIT) has been accepted by **ICLR 2025**. ✊
- *2024.11*: &nbsp; Dataset of [PVIT-3M](https://huggingface.co/datasets/Sterzhang/PVIT-3M) made it to the **Top 3 Dataset downloads** [November 2024] at HuggingFace🤗! [（Post from X）](https://x.com/mvaloatto/status/1865102836092277077)
- *2024.10*: &nbsp; I won the **National Scholarship**  (Award Rate: 0.2% national-wide)!
- *2024.09*: &nbsp; 1 paper (Image Textualization) has been accepted by **NeurIPS 2024** (D&B track). 
- *2024.09*: &nbsp; 2 papers (MLLM-Protector, FIRST) have been accepted by **EMNLP 2024** (Main). 
- *2024.03*: &nbsp; 1 paper (CORE) has been accepted by **Cogsci 2024** <strong><span style="color:red;">[Oral]</span></strong>.
- *2024.01*: &nbsp; [FuzzLLM](https://arxiv.org/abs/2309.05274) has been invited to present at one of the top hacker conventions -- ShmooCon 2024!
- *2023.12*: &nbsp; 1 paper (FuzzLLM) has been accepted by **ICASSP 2024**.


<br/>

# 📝 Publications 
<sup>&dagger;</sup> : equal contribution (names listed in no particular order), <sup>*</sup> : corresponding author


<dl>
  <dt><img align="left" width="400" src="../images/paper/vlm2-bench.png" alt="VLM$^2$-Bench: A Closer Look at How Well VLMs Implicitly Link Explicit Matching Visual Cues"></dt>
  <dd><a href="https://arxiv.org/pdf/2502.12084" class="publication-title">VLM$^2$-Bench: A Closer Look at How Well VLMs Implicitly Link Explicit Matching Visual Cues</a></dd>
  <dd><strong>Jianshu Zhang&dagger; </strong>, Dongyu Yao<sup>&dagger;</sup>, Renjie Pi, Paul Pu Liang, Yi R. (May) Fung<sup>*</sup></dd>
  <dd>Under Review</dd>
  <dd><a href="https://arxiv.org/pdf/2502.12084">[arXiv]</a> <a href="https://vlm2-bench.github.io/">[project page]</a></dd>
</dl>

<br/>
<dl>
  <dt><img align="left" width="400" src="../images/paper/it.png" alt="Image Textualization"></dt>
  <dd><a href="https://arxiv.org/pdf/2406.07502" class="publication-title">Image Textualization: An Automatic Framework for Generating Rich and Detailed Image Descriptions</a></dd>
  <dd>Renjie Pi<sup>&dagger;</sup>, <strong>Jianshu Zhang&dagger; </strong>, Jipeng Zhang, Rui Pan, Zhekai Chen, Tong Zhang<sup>*</sup></dd>
  <dd>The Thirty-Eighth Annual Conference on Neural Information Processing Systems (<strong>NeurIPS 2024</strong>)</dd>
  <dd><a href="https://arxiv.org/pdf/2406.07502">[arXiv]</a> <a href="https://github.com/sterzhang/image-textualization">[code]</a></dd>
</dl>

<dl>
  <dt><img align="left" width="400" src="../images/paper/pvit.png" alt="Personalized Visual Instruction Tuning"></dt>
  <dd><a href="https://arxiv.org/pdf/2410.07113" class="publication-title">Personalized Visual Instruction Tuning</a></dd>
  <dd>Renjie Pi<sup>&dagger;</sup>, <strong>Jianshu Zhang&dagger; </strong>, Tianyang Han, Jipeng Zhang, Rui Pan, Tong Zhang<sup>*</sup></dd>
  <dd>The Thirteenth International Conference on Learning Representations (<strong>ICLR 2025</strong>)</dd>
  <dd><a href="https://arxiv.org/pdf/2410.07113">[arXiv]</a> <a href="https://github.com/sterzhang/PVIT">[code]</a></dd>
</dl>
<br/>

<br/>

<dl>
  <dt><img align="left" width="400" src="../images/paper/mllm-protector.png" alt="MLLM-Protector"></dt>
  <dd><a href="https://arxiv.org/pdf/2401.02906" class="publication-title">MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance</a></dd>
  <dd>Renjie Pi<sup>&dagger;</sup>, Tianyang Han<sup>&dagger;</sup>, <strong>Jianshu Zhang&dagger; </strong>, Yueqi XIE, Rui Pan, Qing LIAN, Hanze Dong, Jipeng Zhang, Tong Zhang<sup>*</sup></dd>
  <dd>The 2024 Conference on Empirical Methods in Natural Language Processing (<strong>EMNLP 2024</strong>)</dd>
  <dd><a href="https://arxiv.org/pdf/2401.02906">[arXiv]</a> <a href="https://github.com/pipilurj/MLLM-protector">[code]</a></dd>
</dl>

<dl>
  <dt><img align="left" width="400" src="../images/paper/first.png" alt="FIRST"></dt>
  <dd><a href="https://arxiv.org/pdf/2408.12168" class="publication-title">FIRST: Teach A Reliable Large Language Model Through Efficient Trustworthy Distillation</a></dd>
  <dd>KaShun SHUM<sup>&dagger;</sup>, Minrui Xu<sup>&dagger;</sup>, <strong>Jianshu Zhang&dagger; </strong>, Zixin CHEN, Shizhe Diao, Hanze Dong, Jipeng Zhang, Muhammad Omer Raza</dd>
  <dd>The 2024 Conference on Empirical Methods in Natural Language Processing (<strong>EMNLP 2024</strong>)</dd>
  <dd><a href="https://arxiv.org/pdf/2408.12168">[arXiv]</a> <a href="https://github.com/sterzhang/FIRST">[code]</a></dd>
</dl>

<dl>
  <dt><img align="left" width="400" src="../images/paper/fuzzllm.png" alt="FuzzLLM"></dt>
  <dd><a href="https://ieeexplore.ieee.org/document/10448041" class="publication-title">FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models</a></dd>
  <dd>Dongyu Yao<sup>&dagger;</sup>, <strong>Jianshu Zhang&dagger; </strong>, Ian G. Harris<sup>*</sup>, Marcel Carlsson</dd>
  <dd>2024 IEEE International Conference on Acoustics, Speech and Signal Processing (<strong>ICASSP 2024</strong>)</dd>
  <dd><a href="https://arxiv.org/abs/2309.05274">[arXiv]</a> <a href="https://github.com/sterzhang/FuzzLLM">[code]</a></dd>
</dl>

<br/>

<dl>
  <dt><img align="left" width="400" src="../images/paper/core.png" alt="CORE"></dt>
  <dd><a href="https://arxiv.org/abs/2402.01348" class="publication-title">CORE: Mitigating Catastrophic Forgetting in Continual Learning through Cognitive Replay</a></dd>
  <dd><strong>Jianshu Zhang&dagger; </strong>, Yankai Fu<sup>&dagger;</sup>, Ziheng Peng<sup>&dagger;</sup>, Dongyu Yao, Kun He<sup>*</sup></dd>
  <dd>2024 Cognitive Science Society Annual Conference (<strong>Cogsci 2024</strong>) <strong><span style="color:red;">[Oral]</span></strong> </dd> 
  <dd><a href="https://arxiv.org/abs/2402.01348">[arXiv]</a> <a href="https://github.com/sterzhang/CORE">[code]</a></dd>
</dl>



<dl>
  <dt><img align="left" width="400" src="../images/paper/can.png" alt="Client As Navigator"></dt>
  <dd><a href="" class="publication-title">CAN: Injecting More "Federation" into Federated Continual Learning by Positioning Clients as Navigators</a></dd>
  <dd><strong>Jianshu Zhang&dagger; </strong>, Xuankun Rong<sup>&dagger;</sup>, Kun He, Mang Ye<sup>*</sup></dd>
  <dd>Under Review</dd>
  <dd><a href="#">[arXiv]</a> <a href="#">[code]</a></dd>
</dl>

<dl>
  <dt><img align="left" width="400" src="../images/paper/bridge-coder.png" alt="Bridge-Coder"></dt>
  <dd><a href="https://arxiv.org/pdf/2410.18957" class="publication-title">Bridge-Coder: Unlocking LLMs' Potential to Overcome Language Gaps in Low-Resource Code</a></dd>
  <dd>Jipeng Zhang<sup>&dagger;</sup>, <strong>Jianshu Zhang&dagger; </strong>, Yuanzhe LI<sup>&dagger;</sup>, Renjie Pi, Rui Pan, Runtao Liu, Zheng Ziqiang, Tong Zhang<sup>*</sup></dd>
  <dd>Under Review</dd>
  <dd><a href="https://arxiv.org/pdf/2410.18957">[arXiv]</a> <a href="#">[code]</a></dd>
</dl>
<br/>

<br/>

<br/>

# 🏆 Awards

- **National Scholarship** 
- Merit Student
- First Class Scholarship




# 📖 Educations
- *2021.09 - now*, Undergraduate, [Wuhan University](https://www.whu.edu.cn/), China. 
- *2018.09 - 2021.07*, Senior Middle School, [Shenzhen Middle School](https://www.shenzhong.net/), China.



# 💻 Internships
- *2024.10 - 2025.03,* Research Intern in [MIT](https://www.mit.edu/), under the supervision of Prof. [Paul Liang](https://pliang279.github.io/) and Dr. [Yi R. (May) Fung](https://yrf1.github.io/).
- *2024.02 - 2024.12,* Research Assistant in [University of Illinois Urbana-Champaign (UIUC)](https://illinois.edu/), supervised by Prof. [Tong Zhang](https://tongzhang-ml.org/).
- *2023.09 - 2024.5,* Research Assistant at [Data Security Lab, Wuhan University](https://datasec.whu.edu.cn/), supervised by Prof. [Kun He](https://cse.whu.edu.cn/info/1262/3298.htm).
- *2023.07 - 2023.09*, UCInspire Summer Research Program (University of California Irvine), supervised by Prof. [Ian G. Harris](https://www.ics.uci.edu/~harris/index.html)
- *2023.06 - 2023.09*, [Tencent](https://www.tencent.com/zh-cn/index.html), IEG (Interactive Entertainment Group), Shenzhen, China.



