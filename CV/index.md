---
title: CV
nav:
  order: 1
  tooltip: About Prof. Li Lin
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}CV

---
layout: default
---

{% capture floatcontent %}

{% include portrait.html lookup=page.slug %}

<div>
  {% for link in page.links %}
    {% assign key = link[0] %}
    {% assign value = link[1] %}
    {% include button.html type=key link=value style="bare" %}<br>
  {% endfor %}
</div>

{% endcapture %}

{% include float.html content=floatcontent %}

{{ content }}

{% assign aliases = page.aliases
  | default: page.name
  | default: page.title
  | join: ","
  | split: ","
  | array_filter
%}

{% capture search -%}
  research/?search={% for alias in aliases %}"{{ alias }}" {% endfor %}
{%- endcapture %}

<p class="center">
  <a href="{{ search | relative_url }}">
    Search for {{ page.name | default: page.title }}'s papers on the Research page
  </a>
</p>

{% capture search -%}
  blog/?search={{ page.name }}
{%- endcapture %}

<!--
<p class="center">
  <a href="{{ search | relative_url }}">
    See {{ page.name | default: page.title }}'s posts on the Blog page
  </a>
</p>
-->

Lin, Li 

Assistant Professor

Shanghai Chen-Guang Scholar 

School of Biomedical Engineering, Shanghai Jiao Tong University 

Room 207 Med-X Institute, 1954 Huashan Rd, Xuhui, Shanghai 200030

Email: linli92@sjtu.edu.cn

{% include section.html %}

### EDUCATION                                                                
- Ph.D., Biomedical Engineering, Shanghai Jiao Tong University, China, 2013-2018
Thesis Title: The Synthesis and Biomedical Applications of Gap Enhanced Raman Tags (GERTs)
Advisor: Prof. Hongchen Gu, Prof. Jian Ye
- B.S.	Biomedical Engineering, Shanghai Jiao Tong University, China, 2009-2013
- Visiting Student, Department of Biomedical Engineering, University of Minnesota, U.S., 2012 Summer

### PROFESSIONAL EMPLOYMENT 
- Assistant Professor, School of Biomedical Engineering, Shanghai Jiao Tong University, 2021-now
- Visiting Postdoctoral Fellow, Department of Bioengineering, University of Illinois at Urbana-Champaign (Advisor: Prof. Shuming Nie), 2018-2020
- Postdoctoral Fellow, School of Biomedical Engineering, Shanghai Jiao Tong University, 2018-2021

### HONORS AND AWARDS                                                                  
Shanghai Education Municipal “Chen-Guang” Young Scholar Program (2022)
Best Paper Award Nomination, IEEE 3M-Nano Conference (2021)
Best Paper Award, The 9th International Multidisciplinary Conference on Optofluidics (2019)
Shanghai Super Postdoctoral Fellowship (2018)
Shanghai Excellent Graduates City (2018)
Academic Rising Star in Shanghai Jiao Tong University (2017) (Top 10 students per year)
Best Poster Award, 2017 International Conference on SERS (2017)

### PUBLICATIONS
Over 20 journal papers, with an impact factor of over 200 and citations of more than 800. 

### JOURNAL PEER REVIEWER
- Analytical Chemistry
- Environmental Science & Technology
- Nature Communications
- Biosensors
- Journal of Innovative Optical Health Sciences
- IEEE Transactions on Biomedical Engineering

### INVITED TALKS
- Li Lin, In Vivo Surface-Enhanced Transmission Raman Spectroscopy: Advancing Toward Photosafe Non-invasive Detection of Deep-Seated Lesions, SciX, October 2023, Sparks, Nevada, US.
- Li Lin, Surface-Enhanced Transmission Raman Spectroscopy: Toward Photosafe Non-invasive Diagnosis, Photonix Conference, May 2023, Hangzhou, China.
- Li Lin, In Vivo Surface-Enhanced Transmission Raman Spectroscopy for Photosafe Non-invasive Diagnosis, Instrumental Website Online Webinar, June 2023.
- Li Lin, “Quantitative Direct Assessment of Raman Spectroscopic Tissue Penetration Depth in the NIR Window”, PIBM Conference, 2021, Haikou, Hainan, China. (Oral)
- Li Lin, “Tissue Optical Properties and Tissue Penetration: Implications for Surgical Navigation and Guidance,” BIOE498/598 class, University of Illinois at Urbana-Champaign, September 2020.
- Li Lin, “Biomedical Applications Based on Surface-Enhanced Raman Scattering,” Online Webinar, Horiba Inc., February 2020.

### TEACHING
- BME9001, Frontiers of Biomedical Engineering, Fall semester, From 2023
- GE7002, Ethics and Academic Norms of Medical Engineering, Fall semester, From 2023
- BME7006, Scientific Writing, Integrity and Ethics (English Class), Fall semester, From 2022
- BME8201, Spectroscopic Nanomaterials in Biomedical Application, Spring semester, From 2022
