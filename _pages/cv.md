---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<style>

td, th {
   border: none!important;
}
</style>
{% include base_path %}

<h1 id="education"> Education</h1>
<table style="border: none;rules:none;cellspacing:0;font-size:16px;">
<tbody><tr>
    <td><b>08/2023 - present</b> &nbsp;&nbsp;&nbsp;</td>
    <td><b>The Hong Kong University of Science and Technology</b>, Hong Kong, China</td>
</tr>
<tr>
    <td></td>
    <td><font color="grey">PhD in Computer Science and Engineering</font></td>
</tr>
<tr>
    <td><b>09/2019 - 06/2022</b> &nbsp;&nbsp;&nbsp;</td>
    <td><b>Dalian University of Technology</b>, Dalian, China</td>
</tr>
<tr>
    <td></td>
    <td><font color="grey">Master in Information and Communication Engineering </font></td>
</tr>
<tr>
    <td><b>09/2015 - 06/2019</b> &nbsp;&nbsp;&nbsp;</td>
    <td><b>Dalian University of Technology</b>, Dalian, China</td>
</tr>
<tr>
    <td></td>
    <td><font color="grey">Bachelor in Computer Science and Technology</font></td>
</tr>
</tbody></table>

<h1 id="experience"> Experience</h1>
<table style="border: none;rules:none;cellspacing:0;font-size:16px;">
<tbody>
<tr>
    <td><b>03/2021 - 03/2022</b> &nbsp;&nbsp;&nbsp;</td>
    <td><b>Meituan</b>, Beijing, China</td>
</tr>
<tr>
    <td></td>
    <td><font color="grey">Intern researcher on Computer Vision, Segmentation</font></td>
</tr>
<tr>
    <td><b>03/2022 - 05/2023</b> &nbsp;&nbsp;&nbsp;</td>
    <td><b>Alibaba AMap</b>, Beijing, China</td>
</tr>
<tr>
    <td></td>
    <td><font color="grey">Full-time researcher on Computer Vision, Autonomous driving/BEV perception</font></td>
</tr>
</tbody></table>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
