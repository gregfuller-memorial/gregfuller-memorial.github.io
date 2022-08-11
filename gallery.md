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
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
  </div>
  <div class="column">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
  </div> 
  <div class="column">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
  </div>
  <div class="column">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Little.jpeg">
    <img src="assets/images/Greg and a cup of joe.jpeg">
  </div>
</div>

.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

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

@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}
