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

[//]: # (Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.)

[//]: # ()
[//]: # (My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> &#40;You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>&#41;.)
# About me
Hello, my name is **Luyang Cao**. I am currently a Ph.D. candidate at Nanjing University, also a member of the Reasoning & Learning Group, conducting research under the guidance of Professor Yinghuan Shi. My academic work primarily focuses on medical image computing, with specific interests in three interrelated areas: **medical image restoration** (enhancing low-quality clinical data), **medical image analysis** (developing diagnostic algorithms for disease detection), and **semi-supervised learning** (leveraging limited labeled data for robust model training).

# 💬 Current Research Topics
- Large-Scale Models for Medical Image Restoration
- Semi-supervised Medical Image Segmentation
- Medical Image Analysis

# 📖 Educations
- *2024.09 - now*, The State Key Laboratory for Novel Software Technology, Nanjing University, Nanjing, Jiangsu, China
- *2021.09 - 2024.06*, The College of Physics and Information Engineering, Fuzhou University, Fuzhou, Fujian, China
- *2017.09 - 2021.06*, The College of Physics and Information Engineering, Fuzhou University, Fuzhou, Fujian, China

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper is accepted by IEEE Transactions on Image Processing (TIP)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2025</div><img src='images/CVBM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Background Matters: A Cross-view Bidirectional
Modeling Framework for Semi-supervised
Medical Image Segmentation](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Luyang Cao**, Jianwei Li, Yinghuan Shi

[//]: # ([**Project**]&#40;https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC&#41; <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>)

[//]: # (- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )
[**Code**](at https://github.com/caoluyang0830/CVBM.git)
- Current semi-supervised medical image segmentation methods primarily focus on foreground modeling while overlooking the potential of background modeling. We demonstrate that reliable background modeling predictions enhance the confidence of foreground modeling. Building on this insight, we propose a Cross-view Bidirectional Modeling (CVBM) framework for semi-supervised medical image segmentation—the first work to integrate background modeling as an auxiliary view to enhance foreground modeling. 
</div>
</div>


# 🎖 Honors and Awards
- *2022.12* National Scholarship for Master's Students.

[//]: # (- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # ()
[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)
[//]: # ()
[//]: # (# 💻 Internships)

[//]: # (- *2019.05 - 2020.02*, [Lorem]&#40;https://github.com/&#41;, China.)