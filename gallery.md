---
layout: page
title: Gallery
landing-title: 'Gallery'
nav-menu: true
description: null
image: null
author: null
show_tile: false
---

<div class="row"> 
  <div class="column">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
  </div>
  <div class="column">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
  </div> 
  <div class="column">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
  </div>
  <div class="column">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Little.jpg">
    <img src="assets/images/Greg and a cup of joe.jpg">
  </div>
</div>

.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}