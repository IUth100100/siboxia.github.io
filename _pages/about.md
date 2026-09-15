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

I am a Ph.D. student in the College of Software at Nankai University and a member of the AIOps@NKU group led by [Prof. Shenglin Zhang](https://nkcs.iops.ai/shenglinzhang/) and [Associate Prof. Yongqian Sun](https://nkcs.iops.ai/yongqiansun/). I received my B.E. degree from Nankai University. My Ph.D. research is supervised by [Prof. Shenglin Zhang](https://nkcs.iops.ai/shenglinzhang/), and my M.S. research was supervised by [Associate Prof. Yongqian Sun](https://nkcs.iops.ai/yongqiansun/).

---

My research focuses on AIOps for microservice systems, supercomputing, and intelligent computing, aiming to automate failure prediction, detection, and diagnosis for large-scale infrastructure. I have published 12 papers in leading international conferences and journals, including IEEE/ACM SC, IEEE/ACM ASE, ACM FSE, ACM WWW, ACM TOSEM, IEEE TSC, and IEEE IOTJ, and I have served as a reviewer for IEEE TR.


# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Our paper "Why Transformers?" is accepted by ACM TOSEM (CCF A).
- *2026.08*: &nbsp;🎉🎉 Our paper "FSLog" is accepted by IEEE IOTJ (JCR Q1).
- *2026.07*: &nbsp;🎉🎉 I start my internship as an Algorithm Engineer at Jingdong Digits Technology Holding Co., Ltd.
- *2026.06*: &nbsp;🎉🎉 Our paper "LagRCA" wins the Distinguished Paper Award in FSE 2026 Industry Track!
- *2026.03*: &nbsp;🎉🎉 Our paper "LagRCA" is accepted by FSE 2025 (CCF A).
- *2025.07*: &nbsp;🎉🎉 We get two posters accepted by APNet 2025 (CCF C).
- *2025.06*: &nbsp;🎉🎉 Our paper "NodeSentry" is accepted by SC 2025 (CCF A).
- *2025.01*: &nbsp;🎉🎉 Our paper "Failure Diagnosis Survey" is accepted by ACM TOSEM (CCF A).
- *2024.10*: &nbsp;🎉🎉 Our paper "UniDiag" is accepted by IEEE TSC (CCF A).
- *2024.08*: &nbsp;🎉🎉 I start my internship as a Technical Research Engineer at 2012 Laboratories, Huawei Technologies Co., Ltd.
- *2024.08*: &nbsp;🎉🎉 Our paper "ART" is accepted by ASE 2024 (CCF A).
- *2024.04*: &nbsp;🎉🎉 Our paper "Miner" is accepted by Journal of Computer Research and Development (CCF T1 in Chinese).
- *2023.06*: &nbsp;🎉🎉 Our paper "DiagFusion" is accepted by IEEE TSC (CCF A).
- *2023.02*: &nbsp;🎉🎉 I start my internship as a Research and Development Engineer at National Supercomputer Center in Tianjin.
- *2022.01*: &nbsp;🎉🎉 Our paper "OmniCluster" is accepted by WWW 2022 (CCF A).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">SC 2025</div><a href="https://dl.acm.org/doi/10.1145/3712285.3759794"><img src='images/nodesentry.png' alt="The overall framework of Nodesentry" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Effective Node-Level Anomaly Detection in HPC Systems via Coarse-Grained Clustering and Fine-Grained Model Sharing](https://dl.acm.org/doi/10.1145/3712285.3759794)

**Sibo Xia**, Yongqian Sun, Xijie Pan, et al.

- High-performance computing (HPC) systems are crucial for scientific advancement and engineering breakthroughs. Unexpected performance degradation or system failures can severely impact these endeavors. This paper introduces NodeSentry, a novel unsupervised anomaly detection framework tailored for compute nodes of large-scale HPC systems. NodeSentry leverages a combined approach of coarse-grained clustering and fine-grained model sharing to effectively address the challenges posed by the massive node scales, frequent job transitions, and complex patterns characteristic of modern HPC deployments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="transition: transform 0.3s ease; cursor: pointer; position: relative; z-index: 10;" onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'"><div><div class="badge">APNet 2025</div><a href="https://dl.acm.org/doi/full/10.1145/3735358.3737815"><img src='images/optprophet.png' alt="The overall framework of OptProphet" width="100%" style="width:100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Forewarned is Forearmed: Joint Prediction and Classification of Optical Transceiver Failures in Large-Scale LLM Training Clusters](https://dl.acm.org/doi/full/10.1145/3735358.3737815)

**Sibo Xia**, Long Ma, Junhua Kuang, et al.

- The reliable operation of Large Language Model (LLM) training clusters critically depends on optical transceivers, which face frequent failures with severe operational impacts. We propose OptProphet, a joint failure prediction and classification framework. By modeling temporal dependencies and physical couplings via feature aggregation and automatically addressing imbalanced data distributions, OptProphet significantly enhances prediction sensitivity and classification specificity.
</div>
</div>

# 🎖 Honors and Awards
- *2026.07* 🎓 FSE 2026 Industry Track Distinguished Paper Award (The Only Recipient)
- *2025.12* 🎓 Young Science and Technology Scientists Sponsorship Program by CAST - Doctoral Student Special Plan
- *2025.10* 🎓 National Scholarship
- *2025.10* 🎓 Shiing-Shen Chern Academic Newcomer Scholarship of Nankai University
- *2025.10* 🎓 First prize of the Gongneng Scholarship of Nankai University for Graduate Students
- *2024.10* 🎓 Third prize of the Gongneng Scholarship of Nankai University for Graduate Students 
- *2023.10* 🎓 First prize of the Gongneng Scholarship of Nankai University for Graduate Students
- *2023.09* 🎓 Outstanding Undergraduate Teaching Assistant
- *2022.10* 🎓 Second prize of the Gongneng Scholarship of Nankai University for Graduate Students
- *2022.10* 🎓 Scholarship of Nankai University for Postgraduate Recommendation

# 📖 Educations
- *2024.09 - Now*, Ph.D., Software Engineering, Nankai University, China, advisor [Shenglin Zhang](https://nkcs.iops.ai/shenglinzhang/)
- *2022.09 - 2024.06*, M.S. (Successive Postgraduate and Doctoral Programs), Software Engineering, Nankai University, China, advisor [Yongqian Sun](https://nkcs.iops.ai/yongqiansun/)
- *2018.09 - 2022.06*, B.E., Software Engineering, Nankai University, China

# 💻 Internships
- *2026.07 - Now*, Algorithm Engineer, Jingdong Digits Technology Holding Co., Ltd.
- *2024.08 - 2026.07*, Technical Research Engineer, Huawei Technologies Co., Ltd.
- *2023.02 - 2023.11*, Research and Development Engineer, National Supercomputer Center in Tianjin

# 💬 Invited Talks
- *2025.11*, Effective Node-Level Anomaly Detection in HPC Systems via Coarse-Grained Clustering and Fine-Grained Model Sharing, SC 2025, [Link](https://sc25.conference-program.com/presentation/?id=pap259&sess=sess178)
- *2025.08*, Delivered a speech at the Exchange Forum (Phase 2) organized by Huawei Technologies Co., Ltd.
