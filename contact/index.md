---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Contact Prof. Li Lin

- Address: Room 207 MED-X Research Institute, Shanghai Jiao Tong University, 1954 Huashan Road, Shanghai, P.R. China, 200030.
- Email: linli92@sjtu.edu.cn
- 
{%
  include button.html
  type="email"
  text="linli92@sjtu.edu.cn"
  link="linli92@sjtu.edu.cn"
%}

{%
  include button.html
  type="website"
  text="Google Scholar"
  link="https://bme.sjtu.edu.cn/Web/FacultyDetail/917"
%}

{%
  include button.html
  type="website"
  text="Researchgate"
  link="https://www.researchgate.net/profile/Li-Lin-71"
%}

Our team is in deep cooperation with Professor Jian Ye's group at SJTU. We jointly train graduate students and share cooperated projects. See their website for more details!
{%
  include button.html
  type="website"
  tooltip="Ye lab at SJTU"
  text="Ye lab website"
  link="http://www.yelab.sjtu.edu.cn/index.php"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}


{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
