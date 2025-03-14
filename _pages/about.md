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

I am a forth-year Ph.D. student in the School of Computer Science, Peking University, advised by Prof. Guojie Luo at PKU-DASYS Group (Design Automation for Next-generation Computing Systems). My current research area is Computer Architecture and I mainly focus on reconfigurable computing (e.g. FPGA, CGRA, and etc.). I hope to combine the advanced compilation and synthesis techniques with the reconfigurable architectures to build the next generation of efficient domain-specific computing systems. And I also have broad research interests including LLM, MLSys, and neuromorphic computing. I have published more than 15 peer-reviewed papers with total google scholar citations <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

I obtained my B.S. in Computer Science from the School of EECS at Peking University in 2021. During the undergraduate studies, I mainly worked on the design of FPGA accelerators using High-level Synthesis (HLS). And I also worked as a research intern at Computing Technology Lab, DAMO Academy, Alibaba Group, where I had the priviledge of working with Dr. Yen-kuang Chen and Dr. Yuan Xie. 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.08*: &nbsp;🎉🎉 Our paper *Adaptive Spatiotemporal Neural Networks through Complementary Hybridization* has been accepted by **Nature Communications** and selected as Editors' Highlights. Codes and Datasets are available [here](https://github.com/shibizhao/hstnn-demo).
- *2024.05*: &nbsp;🎉🎉 Our paper *ImageMap: Enabling Efficient Mapping from Image Processing DSL to CGRA* has been accepted by **30th International European Conference on Parallel and Distributed Computing (EuroPAR-24)**.
- *2024.02*: &nbsp;🎉🎉 Our paper *PT-Map: Efficient Program Transformation Optimization for CGRA* has been accepted by **61st Design Automation Conference (DAC-24)**.
 

# 📝 Publications

## Journals

\[J4\] [Adaptive Spatiotemporal Neural Networks through Complementary Hybridization](https://www.nature.com/articles/s41467-024-51641-x), Yujie Wu#, **Bizhao Shi**# (# denotes Equal Contributions), Zhong Zheng, Hanle Zheng, Fangwen Yu, Xue Liu, Guojie Luo, and Lei Deng. in the Nature Communications (**NatComm**), 2024.

\[J3\] [PowerSyn: A Logic Synthesis Framework with Early Power Optimization](https://ieeexplore.ieee.org/document/10186351), Sunan Zou, Jiaxi Zhang, **Bizhao Shi**, and Guojie Luo. in the IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (**TCAD**), Early Access.

\[J2\] [Weave: Abstraction and Integration Flow for Accelerators of Generated Modules](https://ieeexplore.ieee.org/document/10288134), Tuo Dai, **Bizhao Shi**, and Guojie Luo. in the IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (**TCAD**), Early Access.

\[J1\] [Efficient Super-Resolution System With Block-Wise Hybridization and Quantized Winograd on FPGA](https://ieeexplore.ieee.org/document/10049639), **Bizhao Shi**, Jiaxi Zhang, Zhuolun He, Xuechao Wei, Sicheng Li, Guojie Luo, Hongzhong Zheng, and Yuan Xie. in the IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (**TCAD**), Vol: 42: Issue: 11, November 2023, pp. 3910-3924.

## Conferences

\[C13\] [MuSA: Multi-Sketch Accelerator with Hybrid Parallelism and Coalesced Memory Organization](https://ieeexplore.ieee.org/document/10817985), Sunan Zou, **Bizhao Shi**, Ziyun Zhang, and Guojie Luo. to appear in the Proceedings of the 42nd International Conference on Computer Design (**ICCD**), Nov, 2024.

\[C12\] [ImageMap: Enabling Efficient Mapping from Image Processing DSL to CGRA](https://link.springer.com/chapter/10.1007/978-3-031-69577-3_5), **Bizhao Shi**, Tuo Dai, Sunan Zou, Ximing Wei, and Guojie Luo. in the Proceedings of the 30th International European Conference on Parallel and Distributed Computing (**Euro-Par**), Aug, 2024.

\[C11\] [G^2PM: Performance Modeling for ACAP Architecture with Dual-Tiered Graph Representation Learning](https://dl.acm.org/doi/10.1145/3649329.3655898), Tuo Dai, **Bizhao Shi**, and Guojie Luo. in the Proceedings of 2024 Design Automation Conference (**DAC**), Jun, 2024.

\[C10\] [PT-Map: Efficient Program Transformation Optimization for CGRA Mapping](https://dl.acm.org/doi/10.1145/3649329.3656257), **Bizhao Shi**, Tuo Dai, Jiaxi Zhang, Xuechao Wei, and Guojie Luo. in the Proceedings of 2024 Design Automation Conference (**DAC**), Jun, 2024.

\[C9\] [BESWAC: Boosting Exact Synthesis via Wiser SAT Solver Call](https://ieeexplore.ieee.org/document/10546591/), Sunan Zou, Jiaxi Zhang, **Bizhao Shi**, and Guojie Luo. in the Proceedings of 2024 Design Automation and Test in Europe (**DATE**), Mar, 2024.

\[C8\] [WideSA: A High Array Utilization Mapping Scheme for Uniform Recurrences on the Versal ACAP Architecture](https://ieeexplore.ieee.org/document/10546896), Tuo Dai, **Bizhao Shi**, and Guojie Luo. in the Proceedings of 2024 Design Automation and Test in Europe (**DATE**), Mar, 2024.

\[C7\] [F-TFM: Accelerating Total Focusing Method for Ultrasonic Array Imaging on FPGA](https://ieeexplore.ieee.org/document/10416104), **Bizhao Shi**, Jieran Zhang, and Guojie Luo. in the Proceedings of 2023 International Conference on Field-Programmable Technology (**FPT**), Dec, 2023.

\[C6\] [RF-SIFTER: Sifting Signals at Layer-0.5 to Mitigate Wideband Cross-Technology Interference for IoT](https://dl.acm.org/doi/10.1145/3570361.3592513), Xiong Wang, Jun Huang, **Bizhao Shi**, Zhe Ou, Guojie Luo, Linghe Kong, Daqing Zhang, and Chenren Xu. in the Proceedings of the 29th Annual International Conference on Mobile Computing and Networking (**MobiCom**), Jul, 2023.

\[C5\] [Weave: Abstraction for Accelerator Integration of Generated Modules](https://dl.acm.org/doi/abs/10.1145/3543622.3573176), Tuo Dai, Bizhao Shi, and Guojie Luo. in International Symposium on Field Programmable Gate Arrays (**FPGA**), Feb, 2023.

\[C4\] [2022 ICCAD CAD Contest Problem C: Microarchitecture Design Space Exploration](https://ieeexplore.ieee.org/document/10069474), Sicheng Li, Chen Bai, Xuechao Wei, **Bizhao Shi**, Yen-Kuang Chen, and Yuan Xie. in the Proceedings of the 41st IEEE/ACM International Conference on Computer-Aided Design (**ICCAD**), Oct, 2022.

\[C3\] [EasyMAC: Design Exploration-Enabled Multiplier-Accumulator Generator Using a Canonical Architectural Representation](https://ieeexplore.ieee.org/document/9712519), Jiaxi Zhang, Qiuyang Gao, Yijiang Guo, **Bizhao Shi**, Guojie Luo. in the Proceedings of the 27th Asia and South Pacific Design Automation Conference (**ASP-DAC**), Jan, 2022. (Invited)

\[C2\] [BlockGNN: Towards Efficient GNN Acceleration Using Block-Circulant Weight Matrices](https://ieeexplore.ieee.org/document/9586181), Zhe Zhou, **Bizhao Shi**, Zhe Zhang, Yijin Guan, Guangyu Sun, and Guojie Luo. in the Proceedings of the 58th ACM/IEEE Design Automation Conference (**DAC**), Dec, 2021.

\[C1\] [Winograd-Based Real-Time Super-Resolution System on FPGA](https://ieeexplore.ieee.org/document/8977840/), **Bizhao Shi**, Zhucheng Tang, Guojie Luo, and Ming Jiang. in the Proceedings of 2019 International Conference on Field-Programmable Technology (**FPT**), Dec, 2019.



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- **2024.12** - Qingyun Shi Outstanding Paper Award (**石青云院士优秀论文奖**), Peking University
- **2024.12** - Xiaomi Top Ten Academic Awards (**小米杯“学术十杰”称号**), Peking University
- **2024.10** - Young Elite Scientist Sponsorship (YESS) Doctoral Special Program (**中国科协青年人才托举工程博士生专项**), China Association for Science and Technology (CAST) 
- **2024.09** - National Scholarship (**国家奖学金**), Peking University
- **2024.09** - Honors for Academic Innovation (**学术创新奖**), Peking University
- **2024.09** - President Scholarship (**校长奖学金**), Peking University
- **2024.09** - Honors for Outstanding Academic Performance (**优秀科研奖**), Peking University
- **2023.09** - Honors for Merit Student (**三好学生**), Peking University
- **2023.09** - Huatai Securities Technology Scholarship (**华泰证券奖学金**), Peking University
- **2021.07** - Honors for Outstanding Undergraduate Graduates in Beijing (**北京市优秀毕业生**)
- **2021.07** - Honors for Outstanding Undergraduate Graduates in Peking University (**北京大学优秀毕业生**)
- **2020.10** - The Second Class Scholarship (**北京大学二等奖学金**), Peking University
- **2020.10** - Honors for Merit Student (**三好学生**), Peking University
- **2018.10** - The May 4th Scholarship (**五四奖学金**), Peking University

# 📖 Educations
- *2021.09 - Present*, PhD Student, School of Computer Science, Peking University. 
- *2017.09 - 2021.07*, Undergraduate Student, School of Electronics Engineering and Computer Science, Peking University. 

# 💬 Invited Talks
- *2024.01*, Invited talk about the FPGA acceleration of ultrasonic array imaging at AMD Winter Camp.


# 💻 Internships
- *2020.07 - 2024.02*, Computing Technology Lab, Alibaba DAMO Academy, Beijing, China.