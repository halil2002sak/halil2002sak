<div align="center">

<!-- Custom Animated Header -->
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1">
        <animate attributeName="stop-color" values="#667eea;#764ba2;#f093fb;#667eea" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:1">
        <animate attributeName="stop-color" values="#764ba2;#f093fb;#667eea;#764ba2" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <rect width="100%" height="200" fill="url(#grad1)" rx="15"/>
  
  <text x="50%" y="45%" font-family="'Courier New', monospace" font-size="48" font-weight="bold" 
        fill="#ffffff" text-anchor="middle" filter="url(#glow)">
    HALIL SAK
  </text>
  
  <text x="50%" y="65%" font-family="'Arial', sans-serif" font-size="20" 
        fill="#ffffff" text-anchor="middle" opacity="0.9">
    Full Stack Developer & Digital Craftsman
  </text>
  
  <!-- Animated Stars -->
  <circle cx="10%" cy="20%" r="2" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="90%" cy="30%" r="2" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="15%" cy="80%" r="2" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="85%" cy="75%" r="2" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

<!-- Custom Badges with SVG icons -->
<a href="https://web.synthjob.com">
  <svg width="180" height="35" xmlns="http://www.w3.org/2000/svg">
    <rect width="180" height="35" rx="5" fill="#667eea"/>
    <text x="90" y="22" font-family="Arial" font-size="14" fill="white" text-anchor="middle" font-weight="bold">
      🌐 web.synthjob.com
    </text>
  </svg>
</a>

<br/><br/>

<!-- Animated Divider -->
<svg width="100%" height="20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="100%" y2="10" stroke="#667eea" stroke-width="2" opacity="0.3"/>
  <circle cx="50%" cy="10" r="5" fill="#667eea">
    <animate attributeName="r" values="5;8;5" dur="1.5s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

## 👨‍💻 Code Philosopher

<svg width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="codeGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:0.1"/>
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#667eea;stop-opacity:0.1"/>
    </linearGradient>
  </defs>
  
  <rect width="100%" height="120" fill="url(#codeGrad)" rx="10"/>
  
  <text x="20" y="30" font-family="'Courier New', monospace" font-size="14" fill="#667eea" opacity="0.8">
    <tspan x="20" dy="0">const developer = {</tspan>
    <tspan x="40" dy="20">name: "Halil Sak",</tspan>
    <tspan x="40" dy="20">location: "Bursa, Turkey 🇹🇷",</tspan>
    <tspan x="40" dy="20">passion: "Building the future, one commit at a time"</tspan>
    <tspan x="20" dy="20">};</tspan>
  </text>
</svg>

<br/>

## 🛠️ Tech Arsenal

<div align="center">

<!-- Custom Tech Stack Cards -->
<svg width="100%" height="180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="jsGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#f7df1e;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#f7df1e;stop-opacity:0.05"/>
    </linearGradient>
    <linearGradient id="reactGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#61dafb;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#61dafb;stop-opacity:0.05"/>
    </linearGradient>
    <linearGradient id="nodeGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#339933;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#339933;stop-opacity:0.05"/>
    </linearGradient>
    <linearGradient id="pythonGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#3776ab;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#3776ab;stop-opacity:0.05"/>
    </linearGradient>
  </defs>
  
  <!-- JavaScript Card -->
  <g>
    <rect x="5%" y="10" width="20%" height="70" rx="8" fill="url(#jsGrad)" stroke="#f7df1e" stroke-width="2"/>
    <text x="15%" y="50" font-family="Arial" font-size="16" fill="#f7df1e" text-anchor="middle" font-weight="bold">JavaScript</text>
  </g>
  
  <!-- React Card -->
  <g>
    <rect x="28%" y="10" width="20%" height="70" rx="8" fill="url(#reactGrad)" stroke="#61dafb" stroke-width="2"/>
    <text x="38%" y="50" font-family="Arial" font-size="16" fill="#61dafb" text-anchor="middle" font-weight="bold">React</text>
  </g>
  
  <!-- Node.js Card -->
  <g>
    <rect x="51%" y="10" width="20%" height="70" rx="8" fill="url(#nodeGrad)" stroke="#339933" stroke-width="2"/>
    <text x="61%" y="50" font-family="Arial" font-size="16" fill="#339933" text-anchor="middle" font-weight="bold">Node.js</text>
  </g>
  
  <!-- Python Card -->
  <g>
    <rect x="74%" y="10" width="20%" height="70" rx="8" fill="url(#pythonGrad)" stroke="#3776ab" stroke-width="2"/>
    <text x="84%" y="50" font-family="Arial" font-size="16" fill="#3776ab" text-anchor="middle" font-weight="bold">Python</text>
  </g>
  
  <!-- Animated Progress Bars -->
  <rect x="5%" y="90" width="20%" height="4" rx="2" fill="#f7df1e" opacity="0.3"/>
  <rect x="5%" y="90" width="18%" height="4" rx="2" fill="#f7df1e">
    <animate attributeName="width" from="0%" to="18%" dur="1.5s" fill="freeze"/>
  </rect>
  
  <rect x="28%" y="90" width="20%" height="4" rx="2" fill="#61dafb" opacity="0.3"/>
  <rect x="28%" y="90" width="17%" height="4" rx="2" fill="#61dafb">
    <animate attributeName="width" from="0%" to="17%" dur="1.5s" fill="freeze"/>
  </rect>
  
  <rect x="51%" y="90" width="20%" height="4" rx="2" fill="#339933" opacity="0.3"/>
  <rect x="51%" y="90" width="16%" height="4" rx="2" fill="#339933">
    <animate attributeName="width" from="0%" to="16%" dur="1.5s" fill="freeze"/>
  </rect>
  
  <rect x="74%" y="90" width="20%" height="4" rx="2" fill="#3776ab" opacity="0.3"/>
  <rect x="74%" y="90" width="15%" height="4" rx="2" fill="#3776ab">
    <animate attributeName="width" from="0%" to="15%" dur="1.5s" fill="freeze"/>
  </rect>
  
  <!-- Labels -->
  <text x="15%" y="110" font-family="Arial" font-size="12" fill="#888" text-anchor="middle">Expert</text>
  <text x="38%" y="110" font-family="Arial" font-size="12" fill="#888" text-anchor="middle">Advanced</text>
  <text x="61%" y="110" font-family="Arial" font-size="12" fill="#888" text-anchor="middle">Advanced</text>
  <text x="84%" y="110" font-family="Arial" font-size="12" fill="#888" text-anchor="middle">Proficient</text>
</svg>

</div>

<br/>

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/halil2002sak">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=halil2002sak&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=667eea&icon_color=764ba2&text_color=ffffff"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=halil2002sak&layout=compact&langs_count=8&theme=radical&hide_border=true&bg_color=0D1117&title_color=667eea&text_color=ffffff"/>
</a>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=halil2002sak&bg_color=0D1117&color=667eea&line=764ba2&point=ffffff&area=true&hide_border=true" width="100%"/>

</div>

<br/>

## 🎯 Current Focus

<svg width="100%" height="150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="focusGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:0.1"/>
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:0.1"/>
    </linearGradient>
  </defs>
  
  <rect width="100%" height="150" fill="url(#focusGrad)" rx="10"/>
  
  <text x="3%" y="30" font-family="Arial" font-size="16" fill="#667eea">
    <tspan x="3%" dy="0">🔭 Building innovative web applications</tspan>
    <tspan x="3%" dy="30">🌱 Learning cutting-edge technologies</tspan>
    <tspan x="3%" dy="30">💡 Contributing to open source</tspan>
    <tspan x="3%" dy="30">🎨 Crafting beautiful user experiences</tspan>
  </text>
</svg>

<br/><br/>

<!-- Custom Footer -->
<div align="center">

<svg width="100%" height="100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:1"/>
    </linearGradient>
  </defs>
  
  <rect width="100%" height="100" fill="url(#footerGrad)" rx="15"/>
  
  <text x="50%" y="35" font-family="'Courier New', monospace" font-size="20" 
        fill="white" text-anchor="middle" font-weight="bold">
    "Code is poetry, make it beautiful"
  </text>
  
  <text x="50%" y="60" font-family="Arial" font-size="14" 
        fill="white" text-anchor="middle" opacity="0.8">
    ⭐ from halil2002sak | Made with 💜 and SVG
  </text>
  
  <!-- Animated Circle -->
  <circle cx="50%" cy="85" r="3" fill="white">
    <animate attributeName="r" values="3;5;3" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.5;1" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=halil2002sak&color=blueviolet&style=for-the-badge)

</div>