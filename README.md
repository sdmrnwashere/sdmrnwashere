<p align="center">
  <svg viewBox="0 0 1000 280" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width: 900px; border-radius: 14px; display: block;">
    <defs>
      <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#0d0b1e"/>
        <stop offset="50%" stop-color="#2b1e4f"/>
        <stop offset="100%" stop-color="#3d2164"/>
      </linearGradient>
      <linearGradient id="sun" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#ffd76f"/>
        <stop offset="60%" stop-color="#ff7a59"/>
        <stop offset="100%" stop-color="#e5306b"/>
      </linearGradient>
      <linearGradient id="grid" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#ff2e63"/>
        <stop offset="100%" stop-color="#7a1fa2"/>
      </linearGradient>
      <clipPath id="sunclip">
        <circle cx="500" cy="168" r="82"/>
      </clipPath>
    </defs>

    <rect width="1000" height="280" fill="url(#sky)"/>

    <g fill="#ffffff">
      <circle cx="90" cy="40" r="1.5"><animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/></circle>
      <circle cx="240" cy="70" r="1.2"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="2.4s" repeatCount="indefinite"/></circle>
      <circle cx="760" cy="45" r="1.6"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.6s" repeatCount="indefinite"/></circle>
      <circle cx="900" cy="90" r="1.2"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2.8s" repeatCount="indefinite"/></circle>
      <circle cx="150" cy="110" r="1"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="4s" repeatCount="indefinite"/></circle>
      <circle cx="680" cy="120" r="1.3"><animate attributeName="opacity" values="0.25;1;0.25" dur="3.2s" repeatCount="indefinite"/></circle>
      <circle cx="420" cy="30" r="1.2"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="2.6s" repeatCount="indefinite"/></circle>
      <circle cx="560" cy="55" r="1"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.4s" repeatCount="indefinite"/></circle>
    </g>

    <g>
      <circle cx="500" cy="168" r="82" fill="url(#sun)"/>
      <g clip-path="url(#sunclip)">
        <rect x="418" y="196" width="164" height="7" fill="#0d0b1e" opacity="0.55"/>
        <rect x="418" y="208" width="164" height="7" fill="#0d0b1e" opacity="0.55"/>
        <rect x="418" y="220" width="164" height="8" fill="#0d0b1e" opacity="0.55"/>
        <rect x="418" y="233" width="164" height="9" fill="#0d0b1e" opacity="0.55"/>
        <rect x="418" y="247" width="164" height="3" fill="#0d0b1e" opacity="0.55"/>
      </g>
    </g>

    <g fill="#150f2b">
      <rect x="120" y="150" width="40" height="48"/>
      <rect x="160" y="170" width="34" height="28"/>
      <rect x="194" y="140" width="48" height="58"/>
      <rect x="242" y="168" width="30" height="30"/>
      <rect x="272" y="120" width="42" height="78"/>
      <rect x="314" y="152" width="36" height="46"/>
      <rect x="350" y="162" width="50" height="36"/>
      <rect x="400" y="128" width="60" height="70"/>
      <rect x="460" y="146" width="38" height="52"/>
      <rect x="498" y="158" width="46" height="40"/>
      <rect x="544" y="132" width="56" height="66"/>
      <rect x="600" y="156" width="34" height="42"/>
      <rect x="634" y="120" width="44" height="78"/>
      <rect x="678" y="150" width="38" height="48"/>
      <rect x="716" y="166" width="46" height="32"/>
      <rect x="762" y="138" width="52" height="60"/>
      <rect x="814" y="158" width="36" height="40"/>
      <rect x="850" y="146" width="42" height="52"/>
    </g>

    <g fill="#ffd166">
      <rect x="134" y="160" width="4" height="4"/>
      <rect x="204" y="152" width="4" height="4"/>
      <rect x="212" y="160" width="4" height="4"/>
      <rect x="282" y="132" width="4" height="4"/>
      <rect x="290" y="140" width="4" height="4"/>
      <rect x="418" y="140" width="4" height="4"/>
      <rect x="426" y="148" width="4" height="4"/>
      <rect x="434" y="140" width="4" height="4"/>
      <rect x="552" y="144" width="4" height="4"/>
      <rect x="560" y="152" width="4" height="4"/>
      <rect x="644" y="132" width="4" height="4"/>
      <rect x="652" y="140" width="4" height="4"/>
      <rect x="772" y="150" width="4" height="4"/>
      <rect x="780" y="158" width="4" height="4"/>
    </g>

    <rect x="0" y="198" width="1000" height="2" fill="#ff2e63">
      <animate attributeName="opacity" values="0.35;0.9;0.35" dur="4s" repeatCount="indefinite"/>
    </rect>

    <g>
      <line x1="500" y1="200" x2="90" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.55"/>
      <line x1="500" y1="200" x2="200" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.6"/>
      <line x1="500" y1="200" x2="330" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.65"/>
      <line x1="500" y1="200" x2="500" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.7"/>
      <line x1="500" y1="200" x2="670" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.65"/>
      <line x1="500" y1="200" x2="800" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.6"/>
      <line x1="500" y1="200" x2="910" y2="280" stroke="url(#grid)" stroke-width="1" opacity="0.55"/>

      <line x1="0" y1="206" x2="1000" y2="206" stroke="#ff2e63" stroke-width="1" opacity="0.4"/>
      <line x1="0" y1="214" x2="1000" y2="214" stroke="#ff2e63" stroke-width="1" opacity="0.45"/>
      <line x1="0" y1="224" x2="1000" y2="224" stroke="#ff2e63" stroke-width="1" opacity="0.5"/>
      <line x1="0" y1="236" x2="1000" y2="236" stroke="#ff2e63" stroke-width="1" opacity="0.55"/>
      <line x1="0" y1="251" x2="1000" y2="251" stroke="#ff2e63" stroke-width="1" opacity="0.6"/>
      <line x1="0" y1="268" x2="1000" y2="268" stroke="#ff2e63" stroke-width="1" opacity="0.7"/>
    </g>
  </svg>
</p>

<h1 align="center">Sadman Rahman</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&color=E5306B&center=true&vCenter=true&width=560&lines=Co-Founder+%40+INSIA+Lab;Building+%26+scaling+foundational+AI+models;Signals+%26+TFRs+for+HCI;ML+%7C+DL+%7C+Signal+Processing;RAG+%7C+LangChain+%7C+LangGraph" alt="Typing SVG" />
</p>

<p align="center">
  Building and scaling foundational AI models, signals and Time-Frequency Representations (TFRs) for Human-Computer Interaction.
</p>

---

## Connect with Me

<p align="center">
  <a href="https://www.facebook.com/sadman.rahman.950583/">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook" />
  </a>
  <a href="https://www.linkedin.com/in/sdmrn/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

## Programming & Frameworks

<p align="center">
  <img src="https://skillicons.dev/icons?i=python" alt="Python" width="40" />
  <img src="https://skillicons.dev/icons?i=c" alt="C" width="40" />
  <img src="https://skillicons.dev/icons?i=pytorch" alt="PyTorch" width="40" />
  <img src="https://skillicons.dev/icons?i=tensorflow" alt="TensorFlow" width="40" />
  <img src="https://skillicons.dev/icons?i=docker" alt="Docker" width="40" />
  <img src="https://skillicons.dev/icons?i=sqlite" alt="SQL" width="40" />
</p>

<p align="center">MATLAB &nbsp;·&nbsp; Scikit-Learn &nbsp;·&nbsp; Notion</p>

## AI Stacks

<p align="center">
  Machine Learning &nbsp;·&nbsp; Deep Learning &nbsp;·&nbsp; Signal Processing & Classification &nbsp;·&nbsp; Time-Frequency Analysis &nbsp;·&nbsp; LangChain &nbsp;·&nbsp; LangGraph &nbsp;·&nbsp; RAG
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sdmrnwashere&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sdmrnwashere&layout=compact&theme=radical&hide_border=true" alt="Top Languages" height="165" />
</p>
