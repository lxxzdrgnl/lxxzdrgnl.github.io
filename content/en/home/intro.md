---
# Use the Intro widget of the Blog template
widget: about.avatar

# This file represents a page section.
headless: true

# Order that this section will appear in.
weight: 10

author: admin
#design:
#  background:
#    color: '#090a0b'
#    text_color_light: true
#    video:
#      path:  # enter filename of a video in /assets/media
#  css_class: fullscreen
---
<style>
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange; }
}

.typing-container {
  display: inline-block;
  position: relative;
  vertical-align: middle;
  margin-left: 10px;
}

.typing-text {
  display: inline-block;
  overflow: hidden; 
  border-right: .15em solid orange; 
  white-space: nowrap; 
  margin: 0 auto; 
  letter-spacing: .15em; 
  font-weight: bold;
  animation: 
    typing 2s steps(20, end),
    blink-caret .75s step-end infinite;
}

</style>
<div class="skill-badges">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" alt="Vue.js">
</div>
<br>

<div style="text-align: center;">
  <p style="font-size: 1.2rem;">👋 Hello, I'm Yongjae Lee, a developer who <span class="typing-container"><span class="typing-text">turns curiosity into action</span></span>.</p>
  <p style="font-size: 1rem;">I enjoy tackling challenges in various fields such as AI, backend, and frontend, and solving problems without technological boundaries.</p>
</div>

<div style="margin-top: 10px; padding: 10px; border-radius: 5px;">
<i class="fas fa-envelope"></i> <a href="mailto:pung4905@naver.com">pung4905@naver.com</a>
</div>

 Check out my <a href="/about/" style="color: #9c9c9cff; font-weight: bold;">resume</a>😍<br>
<a href="/uploads/resume.pdf" target="_blank" class="btn btn-primary"><i class="fas fa-download"></i> Download Resume</a>