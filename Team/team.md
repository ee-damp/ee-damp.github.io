---
layout: page
title: EE DAMP TEAM
subtitle: 2024-25
cover-img: assets/img/Home.jpg
full-width: true
css: Team/team.css
thumbnail-img: ""
share-img: ""
comments: true
tags: [Academic]
---

<h2 class="heading">DAMP Co-ordinators</h2>
<div class="container">
<div class="card">
    <div class="imgBox">
      <img src="../../assets/img/Aryan.jpeg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Aryan Bhaskar<br><span>EE DAMP Co-ordinator</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:9993220571"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:21d070017@iitb.ac.in"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/aryan-bhaskar-7a1391228?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../assets/img/Pradyuman.jpeg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Pradyuman Agarwal<br><span>EE DAMP Co-ordinator</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:8777015253"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:210020090@iitb.ac.in"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/pradyuman-agarwal-625991223?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

</div>

<h2 class="heading">Sub-group Heads</h2>
<div class="container">
<div class="card">
    <div class="imgBox">
      <img src="../../assets/img/team_img_2024-25/Maalavika Chitoor.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Maalavika Chitoor<br><span>Experiences Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:9884902512"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:210070050@iitb.ac.in"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/maalavika-chitoor-874523227?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../assets/img/team_img_2024-25/Arya Vishe.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Arya Vishe<br><span>Resources and Outreach Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:8291466413"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:aryavishe@iitb.ac.in"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://in.linkedin.com/in/aryavishe"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../assets/img/team_img_2024-25/Sarvadnya Desai.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Sarvadnya Desai<br><span>Resources and Outreach Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:8655919703"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:210040138@iitb.ac.in"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/sarvadnya-desai-a31965250/"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../assets/img/team_img_2024-25/Siddharth Kaushik.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Siddharth Kaushik<br><span>Web Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:8691863295"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:210070086@iitb.ac.in"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/siddharth-kaushik-71152120a/"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>
  
</div>

<h2 class="heading">Mentors</h2>
<div class="container">
{% assign teamData = site.data.team | csv %}
{% for member in teamData %}
  <div class="card">
    <div class="imgBox">
      <img src="../../assets/img/team_img_2024-25/{{member.Name}}.jpg" onerror="this.src='../../../assets/img/team-images/user.jpg'">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>{{member.Name}}<br><span>{{member.Year}} Year DAMP Mentor</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:{{member.Phone}}"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:{{member.Email}}"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="{{member.Linkedin}}"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>
 {% endfor %}

 </div>
