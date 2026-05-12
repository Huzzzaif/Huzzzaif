<div align="center">

<!-- Custom Animated SVG Header -->
<svg xmlns="http://www.w3.org/2000/svg" width="900" height="260" viewBox="0 0 900 260">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="50%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#0a0a0a"/>
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d2ff"/>
      <stop offset="50%" style="stop-color:#7b2ff7"/>
      <stop offset="100%" style="stop-color:#ff0080"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d2ff">
        <animate attributeName="stop-color" values="#00d2ff;#7b2ff7;#ff0080;#00d2ff" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#7b2ff7">
        <animate attributeName="stop-color" values="#7b2ff7;#ff0080;#00d2ff;#7b2ff7" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="260" fill="url(#bg)" rx="0"/>

  <!-- Animated grid lines -->
  <g opacity="0.06">
    <line x1="0" y1="40" x2="900" y2="40" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="0" y1="80" x2="900" y2="80" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="0" y1="120" x2="900" y2="120" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="0" y1="160" x2="900" y2="160" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="0" y1="200" x2="900" y2="200" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="100" y1="0" x2="100" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="200" y1="0" x2="200" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="300" y1="0" x2="300" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="400" y1="0" x2="400" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="500" y1="0" x2="500" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="600" y1="0" x2="600" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="700" y1="0" x2="700" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
    <line x1="800" y1="0" x2="800" y2="260" stroke="#58a6ff" stroke-width="0.5"/>
  </g>

  <!-- Floating particles -->
  <circle cx="120" cy="60" r="2" fill="#00d2ff" opacity="0.6">
    <animate attributeName="cy" values="60;40;60" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="780" cy="180" r="1.5" fill="#ff0080" opacity="0.5">
    <animate attributeName="cy" values="180;200;180" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="50" r="1.8" fill="#7b2ff7" opacity="0.4">
    <animate attributeName="cy" values="50;70;50" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="200" r="1.2" fill="#00d2ff" opacity="0.3">
    <animate attributeName="cy" values="200;180;200" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="30" r="2.5" fill="#ff0080" opacity="0.2">
    <animate attributeName="cy" values="30;50;30" dur="6s" repeatCount="indefinite"/>
  </circle>

  <!-- Accent line -->
  <rect x="300" y="100" width="300" height="2" fill="url(#accent)" rx="1" opacity="0.8">
    <animate attributeName="width" values="0;300" dur="1.5s" fill="freeze"/>
  </rect>

  <!-- Name -->
  <text x="450" y="85" text-anchor="middle" font-family="'Segoe UI', system-ui, sans-serif" font-size="40" font-weight="700" fill="url(#textGrad)" filter="url(#glow)">
    HUZAIF KHAN
  </text>

  <!-- Terminal-style subtitle -->
  <text x="450" y="140" text-anchor="middle" font-family="'Courier New', monospace" font-size="15" fill="#8b949e" letter-spacing="2">
    <tspan fill="#00d2ff">$</tspan> full_stack_dev <tspan fill="#484f58">&&</tspan> ai_ml_engineer
  </text>

  <!-- Tagline -->
  <text x="450" y="175" text-anchor="middle" font-family="'Segoe UI', system-ui, sans-serif" font-size="13" fill="#6e7681" letter-spacing="1">
    BUILDING INTELLIGENT SOFTWARE — FROM MODEL TO PIXEL
  </text>

  <!-- Bottom accent -->
  <rect x="0" y="256" width="900" height="4" fill="url(#accent)" opacity="0.7"/>
</svg>

<br>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=false&width=600&height=45&lines=shipping+ml+models+into+production+%F0%9F%9A%80;building+full-stack+ai+applications+%F0%9F%A7%AC;turning+data+into+decisions+%F0%9F%93%8A;open+to+new+opportunities+%F0%9F%92%BC" alt="Typing SVG" /></a>

<br>

<!-- Social Links - Minimal style -->
[![LinkedIn](https://img.shields.io/badge/-huzaif-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/-huzaiffkhhan@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:huzaiffkhhan@gmail.com)
&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/-Huzzzaif-181717?style=flat&logo=github&logoColor=white)](https://github.com/Huzzzaif)

</div>

<br>

<!-- ABOUT SECTION -->
## `> whoami`

```python
class HuzaifKhan:
    role       = "Full-Stack Developer × AI/ML Engineer"
    location   = "Los Angeles, CA"
    education  = "Computer Science"
    
    languages  = ["Python", "JavaScript", "C", "SQL"]
    ml_stack   = ["TensorFlow", "PyTorch", "Scikit-learn", "OpenCV", "NLP"]
    web_stack  = ["React", "Node.js", "REST APIs", "HTML/CSS"]
    devops     = ["Docker", "Git", "Linux"]
    interests  = ["Reinforcement Learning", "LLMs", "Blockchain (ZKP)"]
    
    currently  = "building AI-powered apps & looking for my next role"
```

<br>

<!-- TECH STACK - Visual Grid -->
## `> tech_stack --verbose`

<div align="center">
<table>
<tr>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
<br><sub><b>Python</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript" />
<br><sub><b>JavaScript</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=c" width="48" height="48" alt="C" />
<br><sub><b>C</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=tensorflow" width="48" height="48" alt="TensorFlow" />
<br><sub><b>TensorFlow</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=pytorch" width="48" height="48" alt="PyTorch" />
<br><sub><b>PyTorch</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=sklearn" width="48" height="48" alt="Scikit-learn" />
<br><sub><b>Scikit-learn</b></sub>
</td>
</tr>
<tr>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React" />
<br><sub><b>React</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" />
<br><sub><b>Node.js</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
<br><sub><b>Docker</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
<br><sub><b>Git</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" />
<br><sub><b>Linux</b></sub>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=opencv" width="48" height="48" alt="OpenCV" />
<br><sub><b>OpenCV</b></sub>
</td>
</tr>
</table>
</div>

<br>

<!-- PROJECTS -->
## `> ls ./projects --featured`

<div align="center">
<table>
<tr>
<td width="50%">
<h3 align="center">🧬 NLP Cancer Prediction</h3>
<p align="center">
<a href="https://github.com/Huzzzaif/nlp-cancer-prediction">
<img src="https://img.shields.io/badge/VIEW_REPO-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>
<p align="center">NLP pipeline that predicts cancer from clinical text data using deep learning models</p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NLP-blueviolet?style=flat-square"/>
<img src="https://img.shields.io/badge/Deep_Learning-FF6F00?style=flat-square"/>
</p>
</td>
<td width="50%">
<h3 align="center">🏥 Medical Prediction App</h3>
<p align="center">
<a href="https://github.com/Huzzzaif/medical_pred_frontend">
<img src="https://img.shields.io/badge/VIEW_REPO-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>
<p align="center">Full-stack app with React frontend serving a trained ML model for medical predictions</p>
<p align="center">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/ML-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/Full_Stack-339933?style=flat-square"/>
</p>
</td>
</tr>
<tr>
<td width="50%">
<h3 align="center">💰 Finance Bot</h3>
<p align="center">
<a href="https://github.com/Huzzzaif/finance_bot">
<img src="https://img.shields.io/badge/VIEW_REPO-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>
<p align="center">AI-powered financial assistant that provides intelligent insights and analysis</p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/AI-red?style=flat-square"/>
<img src="https://img.shields.io/badge/FinTech-00d2ff?style=flat-square"/>
</p>
</td>
<td width="50%">
<h3 align="center">🔐 ZKP Blockchain × LLM</h3>
<p align="center">
<a href="https://github.com/Huzzzaif/zkp-blockchain-llm-sim">
<img src="https://img.shields.io/badge/VIEW_REPO-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>
<p align="center">Zero-knowledge proof blockchain simulation integrated with large language models</p>
<p align="center">
<img src="https://img.shields.io/badge/Blockchain-121D33?style=flat-square"/>
<img src="https://img.shields.io/badge/ZKP-7b2ff7?style=flat-square"/>
<img src="https://img.shields.io/badge/LLM-ff0080?style=flat-square"/>
</p>
</td>
</tr>
<tr>
<td width="50%">
<h3 align="center">🎭 See The Tone</h3>
<p align="center">
<a href="https://github.com/Huzzzaif/see_the_tone">
<img src="https://img.shields.io/badge/VIEW_REPO-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>
<p align="center">Real-time sentiment & tone analysis tool powered by NLP</p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NLP-blueviolet?style=flat-square"/>
<img src="https://img.shields.io/badge/Sentiment-00d2ff?style=flat-square"/>
</p>
</td>
</tr>
</table>
</div>

<br>

<!-- STATS -->
## `> git stats --all`

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Huzzzaif&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=00000000&title_color=58a6ff&icon_color=00d2ff&text_color=c9d1d9" height="180" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Huzzzaif&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="180" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Huzzzaif&theme=github-dark-blue&hide_border=true&background=00000000&stroke=1f6feb&ring=00d2ff&fire=ff0080&currStreakLabel=58a6ff" width="55%" />
</div>

<br>

<!-- Contribution Snake -->
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Huzzzaif/Huzzzaif/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Huzzzaif/Huzzzaif/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/Huzzzaif/Huzzzaif/output/github-snake.svg" width="95%" />
</picture>

<sub>⬆️ Set up with <a href="https://github.com/Platane/snk">Platane/snk</a> GitHub Action — see instructions below</sub>
</div>

<br>

<br>

<!-- Profile Views Counter -->
<div align="center">

![](https://komarev.com/ghpvc/?username=Huzzzaif&color=00d2ff&style=flat-square&label=PROFILE+VIEWS)

<br>

<sub>💼 Open to full-time roles — <a href="mailto:huzaiffkhhan@gmail.com">let's talk</a></sub>

</div>

<!-- Footer wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,30:0d1117,60:1f6feb,100:00d2ff&height=80&section=footer" width="100%" />
