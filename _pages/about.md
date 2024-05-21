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

I’m currently a second year Ph.D. candidate at [IIoT Research Center](https://iiot.sjtu.edu.cn/#/), [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), where I have the honor to be supervised by [Prof. Xinbing Wang](https://www.cs.sjtu.edu.cn/~wang-xb/) and [Prof. Guanjie Zheng](https://jhc.sjtu.edu.cn/~gjzheng/).

I received my bachelor's degree from Chongxin College at [Shandong University](https://www.sdu.edu.cn) in 2022, surpervised by [Prof. Hongchao Zhou](https://faculty.sdu.edu.cn/zhouhongchao/zh_CN/) and [Prof. Hailiang Xiong](https://faculty.sdu.edu.cn/xionghailiang).

My research interests include **data mining**, **knowledge graph** and **AI for science**.
I’m currently devoted to research on **time series analysis**, machine learning problems with **missing data**. What's more, I'm learning how to train a time series or spatio-temporal foundation model.

I am looking for collaborations and am also open to **interested undergraduate interns**. Please feel free to contact me!

<!-- My research interest includes neural machine translation and computer vision.  -->

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- # 🔥 News

- _2022.02_: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2022.02_: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications

- <span class='paper-badge'>ICASSP 2024</span> **Towards Controlled Table-to-Text Generation with Scientific Reasoning**<br>
  _Zhixin Guo, <u><b>Jianping Zhou</b></u>, Jiexing Qi, Mingxuan Yan, Ziwei He, Guanjie Zheng, Zhouhan Lin, Xinbing Wang, Chenghu Zhou_<br>
  _IEEE International Conference on Acoustics, Speech and Signal Processing_, 2024 (CCF-B)<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2312.05402">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2312.05402.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/CTRLSciTab">Code</a></span>

- <span class='paper-prebadge'>arXiv 2024</span> **GeoViz: A Multi-View Visualization Platform for Spatio-temporal Knowledge Graph**<br>
  _<u><b>Jianping Zhou</b></u>, Junhao Li, Guanjie Zheng, Yunqiang Zhu, Xinbing Wang, Chenghu Zhou_<br>
  _arXiv (preprint)_, 2024<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2405.03697">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2405.03697">PDF</a></span> <span class='paper-asset'><a href="https://www.youtube.com/watch?v=o31xlMEmcl4">Video</a></span>

- <span class='paper-prebadge'>arXiv 2024</span> **AceMap: Knowledge Discovery through Academic Graph**<br>
  Xinbing Wang, _<u><b>Jianping Zhou</b></u>, et al._<br>
  _arXiv (preprint)_, 2024<br>
  <span class='paper-asset'><a href="https://www.acemap.info/">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2403.02576">PDF</a></span>

- <span class='paper-prebadge'>arXiv 2023</span> **Adapting Prompt for Few-shot Table-to-Text Generation**<br>
  Zhixin Guo, Minyxuan Yan, Jiexing Qi, _<u><b>Jianping Zhou</b></u>, Ziwei He, Zhouhan Lin, Guanjie Zheng, Xinbing Wang_<br>
  _arXiv (preprint)_, 2023<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2302.12468">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2302.12468.pdf">PDF</a></span>

# 🚀 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">beta</div><img src='images/geoknowledgefusion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Knowledge Fusion: An Advanced Platform for Efficient Multimodal Data Integration from Geoscience Literature](https://knowledgefusion.acemap.info/#/index)

- DDE Knowledge Fusion is a one-stop multimodal knowledge fusion system for geoscientific literature, supporting the table extraction and table fusion from geoscience literature, as well as the extraction of knowledge tuples from text to construct knowledge graphs. We have completed the fusion of global Sm-Nd isotope tabular data and the construction of a global knowledge graph of debris flow. This project is supported by [Deep-time Digital Earth (DDE) International Big Science Program](https://deep-time.org/).

- <span class='paper-badge'>Remote Sensing 2024</span> **GeoKnowledgeFusion: A Platform for Multimodal Data Compilation from Geoscience Literature**<br>
  <span class='paper-asset'><a href="https://www.mdpi.com/2072-4292/16/9/1484">Page</a></span> <span class='paper-asset'><a href="https://www.mdpi.com/2072-4292/16/9/1484/pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/GeoKnowledgeFusion">Code</a></span>

- <span class='paper-badge'>EGU 2024</span> **Accelerating Geoscience Research: An Advanced Platform for Efficient Multimodal Data Integration from Geoscience Literature**<br>
  <span class='paper-asset'><a href="https://meetingorganizer.copernicus.org/EGU24/EGU24-13715.html">Page</a></span>

- <span class='paper-prebadge'>arXiv 2024</span> **Sm-Nd Isotope Data Compilation from Geoscientific Literature Using an Automated Tabular Extraction Method**<br>
Zhixin Guo, Tao Wang, Chaoyang Wang, _<u><b>Jianping Zhou</b></u>, Guanjie Zheng, Xinbing Wang, Chenghu Zhou_<br>
_arXiv (preprint)_, 2024<br>
<span class='paper-asset'><a href="https://arxiv.org/abs/2403.18306">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2403.18306">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/tabularDataCollection">Code</a></span>
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">beta</div><img src='images/geoviz.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Geoviz: Spatio-temporal knowledge graph visualizations platform](https://mdkg.acemap.cn/#/index)

- GeoViz is a one-stop Spatio-temporal knowledge graph (STKG) visualization platform. We developed three customized visualization views for STKG: **knowledge tree**, **knowledge network** and **knowledge map**. This project is supported by the [National key research and development plan](http://www.igsnrr.cas.cn/news/zhxw/202303/t20230303_6688038.html) and [Deep-time Digital Earth (DDE) International Big Science Program](https://deep-time.org/).

</div>
</div> -->

<!-- **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

# 💻 Internships

- _2020.06 - 2020.09_, Hardware Engineer Intern, [Xilinx](https://xupsh.github.io/camp/), China.
- _2021.09 - 2021.12_, MindSpore Excellent Developer, [Huawei MindSpore](https://www.mindspore.cn/), China. [\[Certificate\]](https://www.mindspore.cn/community/developer)

# 📖 Teaching

- Teaching Assistant, Communication Theory (EST3306), Shanghai Jiao Tong University. (Fall 2023)

# 🎖 Honors and Awards

- _2020.12_, _2021.12_ National Scholarship in China (top 1%)
- _2021.12_ President's Award of Shandong University (top 1%) [\[news\]](https://mp.weixin.qq.com/s/kg9RxqXPaxizK5F9qemySg)
- _2021.12_ Outstanding Student of Shandong Province (top 2%)
- _2020.12_ Outstanding Student Leader of Shandong Province (top 2%)
- _2019.10_ First Prize of the 11th College Student Mathematics Competition
- _2020.12_ First Prize of the 14th International Contest of innovAtionN [\[news\]](https://www.view.sdu.edu.cn/info/1003/144886.htm)

<!-- # 📖 Educations


- _2019.06 - 2022.04 (now)_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2015.09 - 2019.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

<!-- # 💬 Invited Talks

- _2021.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2021.03_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. \| [\[video\]](https://github.com/) -->

# 📫 Contact

Location: Room 441, Building 1, No. 800 Dongchuan Road, Minhang District, Shanghai, China, 200240

Email: jianpingzhou0927@gmail.com

<div>

<a href='https://clustrmaps.com/site/1bxrr'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=600&t=tt&d=0M8kPkKxBLYWYMx2sN62-gal633opUGy56vm6VlWAz8&co=2d78ad&ct=ffffff'/></a>

</div>
