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
# About Me
Jiye Qiu (邱 季野 / キュウ キヤ) is a graduate student studying nuclear science and energy engineering at Osaka University with a focus on radiation measurements in boron neutron capture therapy. Obtained bachelor of engineering degree in biomedical engineering from the University of Sydney with first class honours in 2021. 

日本語の履歴と業績は[Researchmap](https://researchmap.jp/jiye-qiu)にご参照してください。

# News
- *2024.01*: Made a oral presentation in [RD2024 (KEK)](https://www-conf.kek.jp/rdetconf/index.html). 
- *2023.07*: Made a oral presentation in [JSNCT-19](https://www.jsnct19.jp/). 
- *2022.11*: Made a poster presentation in [YBNCT-2022](https://isnct.net/ybnct2022/). 
- *2022.04*: Started building the homepage. 

# Educations
- **Master of Engineering, Sustainable Energy and Environmental Engineering, Osaka University, <em>2022 - 2024</em>**
  - Nuclear Science and Energy Engineering Course
  - Master's Thesis titled: "Development and Verification of a Real-time Epi-thermal Neutron Absolute Flux Intensity Measurement Technique for Boron Neutron Capture Therapy" (In Japanese)
- **Bachelor of Engineering (Honours Class I), Biomedical Engineering, The University of Sydney, <em>2017 - 2021</em>**
  - GPA: 3.55/4.00
  - Majored in Electrical Engineering
  - Achieved High Distinction in the Honours Thesis titled: "Volumetric CT Small Bowel Segmentation using Deep Learning" [[Code](https://github.com/KyuuKiya/Honours-Thesis-Project)]

# Experiences
- Research Student, <font color="#800000">School of Engineering, Osaka University</font>, *<font color="#808080">2021.10 - 2022.03</font>*

# Publications 
- Under Construction
<div style='display: none'>
<div class='paper-box'><div class='paper-box-image'><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
</div> 

# Presentations 
- **International Meetings**
  - **<u>J. Qiu</u>**, D. Hatano, S. Tamaki, S. Kusaka, I. Murata, "Design Study of Real‑time Absolute Epi‑thermal Neutron Flux Intensity Monitor using Scintillation Detectors", *Young Researchers’ BNCT Meeting 2022 (YBNCT‑2022)*, Virtual Meeting, November 2022. (Poster) [[Certificate](https://kyuukiya.github.io/images/Jiye_Qiu_PosterCertificate.png)]
- **Domestic Meetings**
  - **<u>J. Qiu</u>**, Y. Ge, N. Voulgaris, K. Sagara, D. Hatano, S. Tamaki, S. Kusaka, T. Takata, I. Murata, "Experimental Verification of a Real-time Epi-thermal Neutron Absolute Flux Intensity Measurement Technique using BNCT Therapeutic Neutron Field", *38th Workshop on Radiation Detectors and Their Uses*, Tsukuba Campus, High Energy Accelerator Research Organization (KEK), Japan, January 2024. (Oral) (In Japanese)
  - **<u>J. Qiu</u>**, Y. Ge, D. Hatano, Z. Qiao, S. Tamaki, S. Kusaka, I. Murata, "Experimental Study and Characterization of Neutron Scintillators containing Li-6 and B-10 for Neutron Detection in BNCT", *The 19th Congress on Neutron Capture Therapy*, Yokohama Symposia, Japan, July 2023. (Oral) (In Japanese)


# Projects
<div class='paper-box'><div class='paper-box-image'><img src='images/neutron_monitor.JPG' alt="sym" height="400" width="600"></div>
<div class='paper-box-text' markdown="1">
- **Development of Real-time Absolute Epi-thermal Neutron Flux Intensity Monitor for Boron Neutron Capture Therapy**
  - *2021.10 - 2024.03*
  - Division of Sustainable Energy and Environmental Engineering, Graduate School of Engineering, Osaka University
  - Description: In boron neutron capture therapy (BNCT), epi-thermal neutron irradiation is carried out to treat deep-seated cancers, as epi-thermal neutrons can be slowed down in a human body and converted into thermal neutrons before reaching the tumor. Since the number of irradiated epi-thermal neutrons determines the therapeutic effect, it is significantly required to measure the epi-thermal neutron intensity during the irradiation. Thus, we have been developing a novel monitor to measure the absolute epi-thermal neutron flux intensity on the body surface of a patient in real-time during BNCT treatment. 
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><img src='images/bowel_model.png' alt="sym" height="400" width="600"></div>
<div class='paper-box-text' markdown="1">
- **Automated CT-based Modelling for the Localization and Characterization of Obstruction in Small Bowel Obstruction**
  - *2020.08 - 2021.06*
  - School of Biomedical Engineering, Faculty of Engineering, The University of Sydney
  - Description: Small bowel obstruction is an abdominal disorder diagnosed using CT imaging. Image-based diagnosis is a complex task requiring a clinician to navigate through a stack of 2D slices representing the tortuous 3D small bowel. Our goal is to simplify this task by segmenting the bowel and generating high quality 3D models. 3D deep neural networks have the potential to perform segmentation efficiently and accurately. This research project focuses on investigating efficient ways to generate labelled segmentation data and developing a deep learning model based on 3D CNN to perform volumetric segmentation of small bowel from CT data. 
</div>
</div>

# Honors and Awards
- Faculty of Engineering Honours Recipient (Honours Class I), <font color="#800000">The University of Sydney</font>, *<font color="#808080">2021</font>* [[URL](https://www.sydney.edu.au/about-us/our-story/prizes-and-honour-roll.html)]

# Teaching Experience
- Exercise II in Energy Engineering (School of Engineering, Osaka University), Teaching Assistant, *<font color="#808080">2023</font>*

# Certifications and Licenses
- **Professional Qualifications**
  - Japanese-Language Proficiency Certificate N1, <font color="#800000">The Japan Foundation</font>, *<font color="#808080">2021.08</font>*, (Certification No. N1A430621A)
  - Japanese-Language Proficiency Certificate N2, <font color="#800000">The Japan Foundation</font>, *<font color="#808080">2019.08</font>*, (Certification No. N2A510830A)
- **Graduate Program for Advanced Interdisciplinary Studies (Osaka University)**
  - Co-creative Radiation Education Programme (CREPE), <font color="#800000">Institute for Radiation Sciences</font>, *<font color="#808080">2023.09</font>* [[URL](https://www.rcnp.osaka-u.ac.jp/crepe/course2/index.html)]
- **Training Certifications**
  - Geant4 Training Course in Medicine 2023, <font color="#800000">The High Energy Accelerator Research Organization (KEK)</font>, *<font color="#808080">2023.09</font>* [[Image](https://kyuukiya.github.io/images/geant4_med_certificate.jpg)]
  - International Training Course on Carbon-ion Radiotherapy, <font color="#800000">Association for Nuclear Technology in Medicine</font>, *<font color="#808080">2022.12</font>* [[Image](https://kyuukiya.github.io/images/itccir_certificate.jpg)]
  - 放射線防護のための管理・計測コース, <font color="#800000">National Institutes for Quantum Science and Technology</font>, *<font color="#808080">2022.09</font>* [[Image](https://kyuukiya.github.io/images/radiation_certificate_1.jpg)]
  - Coursera Online Courses: Programming in C++: A Hands-on Introduction [[URL](https://www.coursera.org/account/accomplishments/specialization/certificate/R9VTFRNZ9FL9)], Deep Learning [[URL](https://www.coursera.org/account/accomplishments/specialization/certificate/CGY9GT4HAF2L)]

# Professional Memberships
- **International Organizations**
  - Institute of Electrical and Electronics Engineers (Graduate Student Member), *<font color="#808080">2024 - Now</font>*
  - IEEE Engineering in Medicine and Biology Society (Graduate Student Member), *<font color="#808080">2024 - Now</font>*
  - IEEE Nuclear and Plasma Sciences Society (Graduate Student Member), *<font color="#808080">2024 - Now</font>*
  - European Federation of Organisations for Medical Physics (Individual Associate Member), *<font color="#808080">2024 - Now</font>*

# Skills
- **Languages**: Chinese (Native), Japanese (Native), English (Proficient)
- **Programming Languages**: Python, MATLAB, C++, Java
- **Research Software**: PHITS, Geant4, 3D Slicer, ITK, DppMCA
- **Laboratory Skills**: Oscilloscope, Radiation Detectors

# Access Information
Division of Sustainable Energy and Environmental Engineering, Graduate School of Engineering, Osaka University<br>
2-1 Yamadaoka, Suita, Osaka, Japan<br>
