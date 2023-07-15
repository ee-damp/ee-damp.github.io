---
layout: page
title: EE DAMP TEAM
subtitle: 2023-24
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
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Keshav Singhal<br><span>EE DAMP Co-ordinator</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="{{member.Phone}}"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="{{member.Email}}"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="{{member.Linkedin}}"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Mohit Kedia<br><span>EE DAMP Co-ordinator</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="{{member.Phone}}"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="{{member.Email}}"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="{{member.Linkedin}}"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

</div>

<h2 class="heading">Sub-group Heads</h2>
<div class="container">
<div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Raavi Gupta<br><span>Experiences Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="{{member.Phone}}"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="{{member.Email}}"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="{{member.Linkedin}}"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Samarth Agarwal<br><span>Resources Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="{{member.Phone}}"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="{{member.Email}}"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="{{member.Linkedin}}"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Srishti Sharma<br><span>Web Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="{{member.Phone}}"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="{{member.Email}}"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="{{member.Linkedin}}"><i class="fab fa-linkedin t"></i></a></li>
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
      <img src="../../../assets/img/team-images/{{member.Name}}.jpg">
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