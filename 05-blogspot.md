---
title: Blogposts
layout: landing
description: Insights drawn from news articles
image: assets/images/news.jpg
nav-menu: true
bannerStyle: style5
permalink: blogposts
---
<style>
  .image {
    position: relative;
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
  .image .base {
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: .5s ease;
    background-color: #e7b788;
    border-radius: 50%;
  }
  .image:hover .overlay {
    opacity: 0.8;
  }
  .align {
    text-align: center;
    margin: 0 auto;
  }
  .divider {
		margin: 0 auto;
		padding: 0 0 2em 0;
  }
  .overlay .text {
    color: #242943;
		font-family: 'Source Sans Pro', Helvetica, sans-serif;
    font-size: 1em;
    font-weight: 600;
    opacity: 1;
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    text-align: center;
  }
</style>

<!-- Countries -->
<section id="countries">
	<div class="inner">
		<header class="major">
			<h3>Articles by Country</h3>
		</header>
	</div>
  <div class="box alt">
    <div class="row 50% uniform">
      <div class="3u align">
        <div class="image" onclick="location.href='/nyc-blogs';">
          <img src="assets/images/nyc.jpg" alt="New York City" class="base">
          <div class="overlay">
            <div class="text">NYC</div>
          </div>
        </div>
      </div>
      <div class="3u align">
        <div class="image" onclick="location.href='/seoul-blogs';">
          <img src="assets/images/seoul.jpg" alt="Seoul" class="base">
          <div class="overlay">
            <div class="text">Seoul</div>
          </div>
        </div>
      </div>
      <div class="3u align">
        <div class="image" onclick="location.href='/singapore-blogs';">
          <img src="assets/images/singapore-2.jpg" alt="Singapore" class="base">
          <div class="overlay">
            <div class="text">Singapore</div>
          </div>
        </div>
      </div>
      <div class="3u$ align">
        <div class="image" onclick="location.href='/honolulu-blogs';">
          <img src="assets/images/honolulu.jpg" alt="Honolulu" class="base">
          <div class="overlay">
            <div class="text">Honolulu</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="divider"></div>
</section>