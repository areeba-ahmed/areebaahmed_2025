---
layout: base
title: Areeba's Home
description: Home Page
hide: true
---

<style>
  /* Add custom animations and styles */
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap');

  @keyframes glow {
    0% { text-shadow: 0 0 5px #fff, 0 0 10px #ffb6c1, 0 0 20px #ffb6c1, 0 0 40px #ffb6c1; }
    50% { text-shadow: 0 0 10px #fff, 0 0 20px #ffb6c1, 0 0 30px #ffb6c1, 0 0 60px #ffb6c1; }
    100% { text-shadow: 0 0 5px #fff, 0 0 10px #ffb6c1, 0 0 20px #ffb6c1, 0 0 40px #ffb6c1; }
  }

  @keyframes slide-border {
    0% { border-color: #ffb6c1; }
    50% { border-color: #add8e6; }
    100% { border-color: #ffb6c1; }
  }

  body {
    background: radial-gradient(circle, #ffe4e1, #fffacd);
    font-family: 'Poppins', sans-serif;
    color: #333;
  }

  .glow-text {
    color: #ff69b4;
    animation: glow 2s infinite;
    font-size: 2.5em;
    text-align: center;
    margin-bottom: 10px;
  }

  .cool-button {
    background: linear-gradient(45deg, #ffb6c1, #add8e6);
    border: none;
    color: white;
    padding: 12px 24px;
    text-transform: uppercase;
    font-weight: bold;
    font-family: 'Poppins', sans-serif;
    border-radius: 10px;
    transition: background 0.5s ease;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .cool-button:hover {
    background: linear-gradient(45deg, #add8e6, #ffb6c1);
  }

  .moving-border {
    border: 3px solid;
    animation: slide-border 5s infinite;
    border-radius: 15px;
    padding: 25px;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
  }

  .moving-border:hover {
    transform: scale(1.02);
  }

  .hover-image img {
    transition: transform 0.4s;
    border-radius: 15px;
  }

  .hover-image img:hover {
    transform: scale(1.08);
  }

  h2 {
    color: #ff69b4;
    font-weight: 500;
  }

  a {
    color: #ff69b4;
    text-decoration: none;
    font-weight: bold;
  }

  a:hover {
    color: #add8e6;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }
  
  ul li {
    margin-bottom: 10px;
  }
</style>

<div style="padding: 20px;">
  <h1 class="glow-text">Areeba Ahmed ˚ʚ♡ɞ˚</h1>
  <p style="text-align: center; font-size: 1.2em;">Welcome to my home page!</p>

  <div style="text-align: center; margin-top: 20px;">
    <button class="cool-button"><a href="{{site.baserul}}/areebaahmed_2025/planning/">Planning Notebook</a></button>
  </div>

  <div class="moving-border" style="margin-top: 30px;">
    <h2>Sprint 1 Check ˚ʚ♡ɞ˚</h2>
    <button class="cool-button" style="margin-bottom: 10px;" onclick="window.location.href='{{site.baserul}}/areebaahmed_2025/sprint/'">Sprint 1</button>
  </div>

  <div class="moving-border" style="margin-top: 30px;">
    <h2>CSSE Projects ˚ʚ♡ɞ˚</h2>
    <p>These are some projects I worked on last year during CSSE.</p>
    <button class="cool-button" style="margin-bottom: 10px;" onclick="window.location.href='{{site.baserul}}/areebaahmed_2025/csse/'">View CSSE Projects</button>
  </div>

  <div class="moving-border hover-image" style="margin-top: 30px;">
    <h2>Snowboarding ˚ʚ♡ɞ˚</h2>
    <p>Some more info about me and snowboarding:</p>
    <button class="cool-button" style="margin-bottom: 10px;" onclick="window.location.href='{{site.baserul}}/areebaahmed_2025/snowboarding/'">View Snowboarding Info</button>
    <img src="images/snowboard.png" alt="Snowboarding" style="width: 100%; max-width: 400px; margin-top: 10px;">
  </div>

  <div class="moving-border" style="margin-top: 30px;">
    <h2>Useful Links ˚ʚ♡ɞ˚</h2>
    <ul>
      <li><a href="https://www.w3schools.com/html/default.asp">w3schools</a> - HTML, CSS, and JavaScript tutorials</li>
      <li><a href="https://github.com/areeba-ahmed/areeba_2025">GitHub Page</a> - Check out my projects on GitHub</li>
    </ul>
  </div>
</div>
