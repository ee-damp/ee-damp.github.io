---
layout: page
title: Course Reviews
subtitle: 
cover-img: assets/img/Cover_study.jpg
thumbnail-img: ""
share-img: ""
comments: true
tags: [Academic]
---

<style>
/*
  The grid itself needs only 4 CSS declarations:
*/

.myGallery {
  display: grid;
  grid-gap: 10px;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
}

.myGallery img {
  width: 100%;
}

/*
  And here are some declarations for the image caption.
  Just hover over one of the last 5 images to see it.
*/

.myGallery .item {
  position: relative;
  overflow: hidden;
}

.myGallery .item img {
  vertical-align: middle;
}

.myGallery .caption {
  margin: 0;
  padding: 1em;
  position: absolute;
  z-index: 1;
  bottom: 0;
  left: 0;
  width: 100%;
  max-height: 100%;
  overflow: auto;
  box-sizing: border-box;
  transition: transform 0.5s;
  transform: translateY(100%);
  background: rgba(0, 0, 0, 0.7);
  color: rgb(255, 255, 255);
}

.myGallery .item:hover .caption {
  transform: translateY(0%);
}

/*
  The rest is only styling for this example page
*/

@import url("https://fonts.googleapis.com/css2?family=Vollkorn:wght@400;900&display=swap");

body {
  font: 400 1.5em/1.58 Vollkorn, serif;
}

h1,
p {
  text-align: center;
}

.myGallery {
  font-size: 1rem;
}

<style>

<h1>Simple and Responsive CSS Image Grid</h1>
<p>And it works also for other content, not only images ✌😏</p>
<div class="myGallery">
  <img src="https://picsum.photos/190/190?1" />
  <img src="https://picsum.photos/190/190?2" />
  <img src="https://picsum.photos/190/190?3" />
  <img src="https://picsum.photos/190/190?4" />
  <img src="https://picsum.photos/190/190?5" />
  <img src="https://picsum.photos/190/190?6" />
  <img src="https://picsum.photos/190/190?7" />
  <img src="https://picsum.photos/190/190?8" />
  <img src="https://picsum.photos/190/190?9" />
  <img src="https://picsum.photos/190/190?10" />
  <div class="item">
    <img src="https://picsum.photos/190/190?11" />
    <span class="caption">This is an image caption for image 11</span>
  </div>
  <div class="item">
    <img src="https://picsum.photos/190/190?12" />
    <span class="caption">This is an image caption for image 12</span>
  </div>
  <div class="item">
    <img src="https://picsum.photos/190/190?13" />
    <span class="caption">This is an image caption for image 13</span>
  </div>
  <div class="item">
    <img src="https://picsum.photos/190/190?14" />
    <span class="caption">This is an image caption for image 14</span>
  </div>
  <div class="item">
    <img src="https://picsum.photos/190/190?15" />
    <span class="caption">This is an image caption for image 15</span>
  </div>
</div>
<p><em><small>If you need something fancier, just check out <a href="https://gridzy.gallery/" target="_blank">Gridzy.Gallery</a></small></em></p>
