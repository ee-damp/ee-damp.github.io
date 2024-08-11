---
layout: page
title: EE DAMP TEAM
subtitle: 2023-25
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
        <img src="../../assets/img/team-images/Keshav Singhal.jpg">
      </div>
      <div class="content">
        <div class="contentBox">
          <h3>Keshav Singhal<br><span>EE DAMP Co-ordinator</span></h3>
        </div>
        <ul class="social">
          <li style="--i:1;"><a href="tel:9560823507"><i class="fas fa-phone f"></i></a></li>
          <li style="--i:2;"><a href="mailto:keshavsinghal2002@gmail.com"><i class="far fa-envelope i"></i></a></li>
          <li style="--i:3;"><a href="https://www.linkedin.com/in/keshav-singhal-/"><i class="fab fa-linkedin t"></i></a></li>
        </ul>
        <button class="flip-button">Flip</button>
      </div>
    <div class="flip-content">
      <p>This is the text revealed on flip.</p>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../assets/img/team-images/Mohit Kedia.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Mohit Kedia<br><span>EE DAMP Co-ordinator</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:6290613800"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:mohitkedia2015@gmail.com"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href=""><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

</div>

<h2 class="heading">Sub-group Heads</h2>
<div class="container">
<div class="card">
    <div class="imgBox">
      <img src="../../../assets/img/team-images/Raavi Gupta.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Raavi Gupta<br><span>Experiences Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:8079047813"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:raavi02g@gmail.com"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/raavi-gupta/"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../../assets/img/team-images/Samarth Agarwal.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Samarth Agarwal<br><span>Resources Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:07608000511"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:samarthagarwal909@gmail.com"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href=""><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="../../../assets/img/team-images/Srishti Sharma.jpg">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Srishti Sharma<br><span>Web Subgroup Head</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="tel:7424863981"><i class="fas fa-phone f"></i></a></li>
        <li style="--i:2;"><a href="mailto:srishtis0507@gmail.com"><i class="far fa-envelope i"></i></a></li>
        <li style="--i:3;"><a href="https://www.linkedin.com/in/srishtis19"><i class="fab fa-linkedin t"></i></a></li>
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
      <img src="../../../assets/img/team-images/{{member.Name}}.jpg" onerror="this.src='../../../assets/img/team-images/user.jpg'">
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

 <script>
  document.querySelectorAll('.flip-button').forEach(button => {
    button.addEventListener('click', function() {
      this.closest('.card').classList.toggle('flipped');
    });
  });
</script>
