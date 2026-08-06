<p align="center">

<!-- =========================================================== -->
<!--  HERO - animated gradient banner + typewriter + particles    -->
<!-- =========================================================== -->
<svg width="100%" viewBox="0 0 1400 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="HAMZA - Python Developer and AI Engineer">
  <defs>
    <radialGradient id="hbg" cx="50%" cy="40%" r="80%">
      <stop offset="0%" stop-color="#0f1a2e"/>
      <stop offset="55%" stop-color="#0b1220"/>
      <stop offset="100%" stop-color="#05070f"/>
    </radialGradient>
    <linearGradient id="htxt" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee">
        <animate attributeName="stop-color" values="#22d3ee;#7c3aed;#f472b6;#22d3ee" dur="9s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#a78bfa">
        <animate attributeName="stop-color" values="#a78bfa;#ec4899;#22d3ee;#a78bfa" dur="9s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="hln" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
  </defs>

  <rect width="1400" height="320" fill="url(#hbg)"/>

  <!-- faint grid -->
  <g stroke="#2a3a5f" stroke-opacity="0.14" stroke-width="1">
    <path d="M0 64 H1400 M0 128 H1400 M0 192 H1400 M0 256 H1400"/>
    <path d="M200 0 V320 M400 0 V320 M600 0 V320 M800 0 V320 M1000 0 V320 M1200 0 V320"/>
  </g>

  <!-- floating particles -->
  <g>
    <circle cx="180" cy="90" r="3" fill="#22d3ee" opacity="0.7">
      <animateTransform attributeName="transform" type="translate" values="0,0;0,-46;0,0" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.1;0.7" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="640" cy="40" r="2.4" fill="#a78bfa" opacity="0.7">
      <animateTransform attributeName="transform" type="translate" values="0,0;18,-52;0,0" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.1;0.7" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1130" cy="110" r="3.2" fill="#f472b6" opacity="0.6">
      <animateTransform attributeName="transform" type="translate" values="0,0;-22,-40;0,0" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0.1;0.6" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1240" cy="230" r="2" fill="#22d3ee" opacity="0.7">
      <animateTransform attributeName="transform" type="translate" values="0,0;0,-38;0,0" dur="5.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.1;0.7" dur="5.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="520" cy="300" r="2.6" fill="#a78bfa" opacity="0.6">
      <animateTransform attributeName="transform" type="translate" values="0,0;24,-30;0,0" dur="6.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0.1;0.6" dur="6.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="980" cy="280" r="2" fill="#f472b6" opacity="0.7">
      <animateTransform attributeName="transform" type="translate" values="0,0;-14,-44;0,0" dur="7.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.1;0.7" dur="7.5s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- scanning beam -->
  <rect x="0" y="-80" width="1400" height="4" fill="#22d3ee" opacity="0" pointer-events="none">
    <animate attributeName="y" values="-80;320" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0.35;0" dur="6s" repeatCount="indefinite"/>
  </rect>

  <!-- main name -->
  <text x="700" y="138" text-anchor="middle" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="86" font-weight="800" letter-spacing="8" fill="url(#htxt)">HAMZA</text>

  <!-- animated underline -->
  <line x1="470" y1="158" x2="930" y2="158" stroke="url(#hln)" stroke-width="4" stroke-linecap="round">
    <animate attributeName="x1" values="470;930;470" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0.3" dur="5s" repeatCount="indefinite"/>
  </line>

  <!-- role typewriter -->
  <text x="700" y="208" text-anchor="middle" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="30" fill="#8b9fb4" opacity="0">
    <tspan fill="#22d3ee">&gt;</tspan> python developer
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.06;0.18;0.75;0.86;1" dur="15s" begin="0s" repeatCount="indefinite"/>
  </text>
  <text x="700" y="208" text-anchor="middle" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="30" fill="#c9d1d9" opacity="0">
    <tspan fill="#a78bfa">&gt;</tspan> ai engineer
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.06;0.18;0.75;0.86;1" dur="15s" begin="3s" repeatCount="indefinite"/>
  </text>
  <text x="700" y="208" text-anchor="middle" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="30" fill="#c9d1d9" opacity="0">
    <tspan fill="#f472b6">&gt;</tspan> machine learning &amp; deep learning
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.06;0.18;0.75;0.86;1" dur="15s" begin="6s" repeatCount="indefinite"/>
  </text>
  <text x="700" y="208" text-anchor="middle" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="30" fill="#c9d1d9" opacity="0">
    <tspan fill="#22d3ee">&gt;</tspan> rag &amp; multi-agent builder
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.06;0.18;0.75;0.86;1" dur="15s" begin="9s" repeatCount="indefinite"/>
  </text>
  <text x="700" y="208" text-anchor="middle" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="30" fill="#c9d1d9" opacity="0">
    <tspan fill="#a78bfa">&gt;</tspan> geospatial &amp; data systems
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.06;0.18;0.75;0.86;1" dur="15s" begin="12s" repeatCount="indefinite"/>
  </text>

  <!-- cursor -->
  <rect x="938" y="182" width="14" height="24" fill="#f472b6">
    <animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.5;0.5;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- profile-views counter -->
<img src="https://komarev.com/ghpvc/?username=hamza-0987&amp;label=PROFILE%20VISITS&amp;color=22d3ee&amp;style=for-the-badge" alt="profile views" width="240"/>

<br/>

---

<!-- =========================================================== -->
<!--  ANIMATED PROFILE CARD                                       -->
<!-- =========================================================== -->
<svg width="100%" viewBox="0 0 520 560" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Profile card">
  <defs>
    <radialGradient id="pbg" cx="50%" cy="0%" r="100%">
      <stop offset="0%" stop-color="#141b2d"/>
      <stop offset="100%" stop-color="#0b1220"/>
    </radialGradient>
    <linearGradient id="brd" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#f472b6"/>
    </linearGradient>
    <clipPath id="aclip"><circle cx="260" cy="210" r="96"/></clipPath>
  </defs>

  <!-- card frame -->
  <rect x="20" y="20" width="480" height="524" rx="34" fill="url(#pbg)" stroke="url(#brd)" stroke-opacity="0.3"/>

  <!-- rotating dashed halo rings -->
  <circle cx="260" cy="210" r="116" fill="none" stroke="url(#brd)" stroke-width="3" stroke-dasharray="10 14" opacity="0.85">
    <animateTransform attributeName="transform" type="rotate" from="0 260 210" to="360 260 210" dur="18s" repeatCount="indefinite"/>
  </circle>
  <circle cx="260" cy="210" r="132" fill="none" stroke="#22d3ee" stroke-width="1.3" opacity="0.35">
    <animateTransform attributeName="transform" type="rotate" from="360 260 210" to="0 260 210" dur="30s" repeatCount="indefinite"/>
  </circle>

  <!-- pulsing glow -->
  <circle cx="260" cy="210" r="110" fill="#22d3ee" opacity="0.18">
    <animate attributeName="r" values="104;120;104" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.22;0.05;0.22" dur="3s" repeatCount="indefinite"/>
  </circle>

  <!-- avatar -->
  <image href="https://avatars.githubusercontent.com/u/59221443?v=4" x="164" y="114" width="192" height="192" clip-path="url(#aclip)" preserveAspectRatio="xMidYMid slice"/>
  <circle cx="260" cy="210" r="96" fill="none" stroke="#0b1220" stroke-width="4"/>

  <!-- name -->
  <text x="260" y="372" text-anchor="middle" font-size="42" font-weight="800" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" fill="#ffffff">HAMZA</text>
  <text x="260" y="400" text-anchor="middle" font-size="17" fill="#8b9fb4" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">Python Developer &#160;•&#160; AI Engineer</text>
  <text x="260" y="430" text-anchor="middle" font-size="16" fill="#5c7291" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">Karachi, Pakistan &#127479;&#127481;</text>

  <!-- open to work badge -->
  <g transform="translate(150,456)">
    <rect width="188" height="40" rx="20" fill="#22d3ee" opacity="0.12"/>
    <rect width="188" height="40" rx="20" fill="none" stroke="#22d3ee" stroke-opacity="0.5"/>
    <circle cx="24" cy="20" r="6" fill="#2dd4bf">
      <animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/>
    </circle>
    <text x="40" y="27" font-size="16" font-weight="600" fill="#a5f3fc" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">Open to Work</text>
  </g>

  <!-- footer stats strip -->
  <g>
    <text x="150" y="515" text-anchor="middle" font-size="24" font-weight="700" fill="#a5f3fc">56</text>
    <text x="150" y="535" text-anchor="middle" font-size="12" fill="#7689a6" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">repositories</text>
    <text x="260" y="515" text-anchor="middle" font-size="24" font-weight="700" fill="#d8b4fe">34</text>
    <text x="260" y="535" text-anchor="middle" font-size="12" fill="#8a86aa" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">contributions</text>
    <text x="376" y="515" text-anchor="middle" font-size="24" font-weight="700" fill="#f9a8d4">7</text>
    <text x="376" y="535" text-anchor="middle" font-size="12" fill="#9c86c4" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">followers</text>
  </g>
</svg>

</p>

<br>

<!-- =========================================================== -->
<!--  ABOUT                                                        -->
<!-- =========================================================== -->
<h2 align="center">🧑‍💻 &nbsp;About Me</h2>

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212750672-2f3f2b50-c84f-4ed8-a60a-849ae69ff9df.gif" width="230" align="left" alt="coding"/>
  <b>Python Developer &amp; AI Engineer</b> based in Karachi, Pakistan. I build <b>scalable applications</b> and <b>AI-driven solutions</b> — focused on <b>Machine Learning</b>, <b>Deep Learning</b>, and production-ready systems.
  <br/><br/>
  ☕ Fueled by coffee, driven by curiosity — I love turning messy data into meaningful intelligence.
</p>

<p align="center"><i>“Code is the canvas — algorithms are the brush.”</i></p>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/216120986-f2752ca9-fe82-4aa3-befe-0a58db010d85.png" width="46" alt="emoji">
  <img src="https://user-images.githubusercontent.com/74038190/216122028-c05b52fb-983e-4ee8-8811-6f30cd9ea5d5.png" width="46" alt="emoji">
  <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="46" alt="emoji">
</div>

<br>

<!-- =========================================================== -->
<!--  LIVE GITHUB STATS (always-loading animated SVG)            -->
<!-- =========================================================== -->
<h2 align="center">⚡ &nbsp;GitHub in Numbers</h2>

<svg width="100%" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="GitHub statistics">
  <defs>
    <linearGradient id="sg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/><stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
  </defs>
  <rect width="900" height="220" rx="24" fill="#0d1117" stroke="#21262d"/>

  <!-- tile 1 : repositories -->
  <g>
    <rect x="60" y="55" width="180" height="120" rx="16" fill="#161b22" stroke="#21262d"/>
    <text x="150" y="98" text-anchor="middle" font-size="28">🗂️</text>
    <text x="150" y="138" text-anchor="middle" font-size="34" font-weight="800" fill="#a5f3fc">56</text>
    <text x="150" y="160" text-anchor="middle" font-size="13" fill="#7689a6">Repositories</text>
    <animate attributeName="opacity" values="0;1" dur="0.7s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,16;0,0" dur="0.7s" fill="freeze"/>
  </g>

  <!-- tile 2 : stars -->
  <g>
    <rect x="260" y="55" width="180" height="120" rx="16" fill="#161b22" stroke="#21262d"/>
    <text x="350" y="98" text-anchor="middle" font-size="28">⭐</text>
    <text x="350" y="138" text-anchor="middle" font-size="34" font-weight="800" fill="#fde68a">4</text>
    <text x="350" y="160" text-anchor="middle" font-size="13" fill="#7689a6">Total Stars</text>
    <animate attributeName="opacity" values="0;1" dur="0.7s" begin="0.15s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,16;0,0" dur="0.7s" begin="0.15s" fill="freeze"/>
  </g>

  <!-- tile 3 : contributions -->
  <g>
    <rect x="460" y="55" width="180" height="120" rx="16" fill="#161b22" stroke="#21262d"/>
    <text x="550" y="98" text-anchor="middle" font-size="28">📈</text>
    <text x="550" y="138" text-anchor="middle" font-size="34" font-weight="800" fill="#d8b4fe">34</text>
    <text x="550" y="160" text-anchor="middle" font-size="13" fill="#7689a6">Contributions</text>
    <animate attributeName="opacity" values="0;1" dur="0.7s" begin="0.3s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,16;0,0" dur="0.7s" begin="0.3s" fill="freeze"/>
  </g>

  <!-- tile 4 : followers -->
  <g>
    <rect x="660" y="55" width="180" height="120" rx="16" fill="#161b22" stroke="#21262d"/>
    <text x="750" y="98" text-anchor="middle" font-size="28">👥</text>
    <text x="750" y="138" text-anchor="middle" font-size="34" font-weight="800" fill="#f9a8d4">7</text>
    <text x="750" y="160" text-anchor="middle" font-size="13" fill="#7689a6">Followers</text>
    <animate attributeName="opacity" values="0;1" dur="0.7s" begin="0.45s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,16;0,0" dur="0.7s" begin="0.45s" fill="freeze"/>
  </g>

  <!-- streak line -->
  <rect x="60" y="192" width="780" height="6" rx="3" fill="#161b22"/>
  <rect x="60" y="192" width="0" height="6" rx="3" fill="url(#sg)">
    <animate attributeName="width" from="0" to="780" dur="2s" begin="0.6s" fill="freeze"/>
  </rect>
</svg>

<br>

<!-- =========================================================== -->
<!--  HIGHLIGHTS PILLS (replaces trophy service)                 -->
<!-- =========================================================== -->
<h2 align="center">🏆 &nbsp;Highlights</h2>

<svg width="100%" viewBox="0 0 900 110" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Highlights">
  <g>
    <rect x="25" y="30" width="130" height="46" rx="23" fill="#22d3ee" opacity="0.12"/>
    <text x="46" y="61" text-anchor="middle" font-size="20">🐍</text>
    <text x="72" y="60" font-size="14" font-weight="600" fill="#a5f3fc">Python</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="3s" repeatCount="indefinite"/>
  </g>
  <g>
    <rect x="169" y="30" width="150" height="46" rx="23" fill="#7c3aed" opacity="0.2"/>
    <text x="194" y="61" text-anchor="middle" font-size="20">🤖</text>
    <text x="220" y="60" font-size="14" font-weight="600" fill="#d8b4fe">AI Engineer</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="3.2s" begin="0.2s" repeatCount="indefinite"/>
  </g>
  <g>
    <rect x="333" y="30" width="130" height="46" rx="23" fill="#f472b6" opacity="0.15"/>
    <text x="354" y="61" text-anchor="middle" font-size="20">🧠</text>
    <text x="380" y="60" font-size="14" font-weight="600" fill="#f9a8d4">ML &amp; DL</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="3.4s" begin="0.4s" repeatCount="indefinite"/>
  </g>
  <g>
    <rect x="477" y="30" width="150" height="46" rx="23" fill="#10b981" opacity="0.15"/>
    <text x="502" y="61" text-anchor="middle" font-size="20">📚</text>
    <text x="528" y="60" font-size="14" font-weight="600" fill="#6ee7b7">Open Source</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="3.6s" begin="0.6s" repeatCount="indefinite"/>
  </g>
  <g>
    <rect x="641" y="30" width="130" height="46" rx="23" fill="#f59e0b" opacity="0.15"/>
    <text x="662" y="61" text-anchor="middle" font-size="20">🔎</text>
    <text x="688" y="60" font-size="14" font-weight="600" fill="#fcd34d">RAG &amp; NLP</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="3.8s" begin="0.8s" repeatCount="indefinite"/>
  </g>
  <g>
    <rect x="745" y="30" width="130" height="46" rx="23" fill="#38bdf8" opacity="0.15"/>
    <text x="766" y="61" text-anchor="middle" font-size="20">⚙️</text>
    <text x="792" y="60" font-size="14" font-weight="600" fill="#7dd3fc">Backend</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="3s" begin="1s" repeatCount="indefinite"/>
  </g>
</svg>

<br>

<!-- streak (reliable external service) -->
<p align="center">
  <img width="520" src="https://streak-stats.demolab.com?user=hamza-0987&hide_border=true&background=0d1117&ring=22d3ee&fire=f472b6&sideLabels=c9d1d9&currStreakLabel=a78bfa&stroke=a78bfa" alt="streak"/>
</p>

<p align="center">
  🔭 <b>Currently building:</b> RAG engines, multi-agent AI systems &amp; MCP tooling
  <br/>
  🌱 <b>Learning:</b> Agentic AI, advanced LLM orchestration &amp; distributed systems
</p>

<br>

<!-- =========================================================== -->
<!--  ANIMATED LANGUAGE BARS                                      -->
<!-- =========================================================== -->
<h2 align="center">🛠️ &nbsp;Languages</h2>

<svg width="100%" viewBox="0 0 900 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Language proficiency bars">
  <defs>
    <linearGradient id="lg1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/><stop offset="100%" stop-color="#0891b2"/>
    </linearGradient>
    <linearGradient id="lg2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed"/><stop offset="100%" stop-color="#c084fc"/>
    </linearGradient>
    <linearGradient id="lg3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#f472b6"/><stop offset="100%" stop-color="#fb7185"/>
    </linearGradient>
    <linearGradient id="lg4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#10b981"/><stop offset="100%" stop-color="#0d9488"/>
    </linearGradient>
  </defs>
  <rect width="900" height="400" rx="24" fill="#0d1117" stroke="#21262d"/>

  <text x="40" y="46" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="16" fill="#8b9fb4">Python</text>
  <rect x="40" y="60" width="820" height="22" rx="11" fill="#161b22"/>
  <rect x="40" y="60" width="0" height="22" rx="11" fill="url(#lg1)">
    <animate attributeName="width" from="0" to="614" dur="1.4s" fill="freeze"/>
  </rect>
  <text x="838" y="78" text-anchor="end" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="14" fill="#c9d1d9" font-weight="700">75%</text>

  <text x="40" y="112" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="16" fill="#94a9ff">JavaScript</text>
  <rect x="40" y="126" width="820" height="22" rx="11" fill="#161b22"/>
  <rect x="40" y="126" width="0" height="22" rx="11" fill="url(#lg2)">
    <animate attributeName="width" from="0" to="565" dur="1.4s" begin="0.15s" fill="freeze"/>
  </rect>
  <text x="838" y="144" text-anchor="end" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="14" fill="#c9d1d9" font-weight="700">69%</text>

  <text x="40" y="178" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="16" fill="#94a9ff">TypeScript</text>
  <rect x="40" y="192" width="820" height="22" rx="11" fill="#161b22"/>
  <rect x="40" y="192" width="0" height="22" rx="11" fill="url(#lg3)">
    <animate attributeName="width" from="0" to="531" dur="2s" begin="0.3s" fill="freeze"/>
  </rect>
  <text x="838" y="210" text-anchor="end" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="14" fill="#c9d1d9" font-weight="700">65%</text>

  <text x="40" y="244" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="16" fill="#94b9db">CSS / HTML</text>
  <rect x="40" y="258" width="820" height="22" rx="11" fill="#161b22"/>
  <rect x="40" y="258" width="0" height="22" rx="11" fill="url(#lg4)">
    <animate attributeName="width" from="0" to="492" dur="2s" begin="0.45s" fill="freeze"/>
  </rect>
  <text x="838" y="276" text-anchor="end" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="14" fill="#c9d1d9" font-weight="700">60%</text>

  <text x="40" y="310" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="16" fill="#c9d1d9">Java</text>
  <rect x="40" y="324" width="820" height="22" rx="11" fill="#161b22"/>
  <rect x="40" y="324" width="0" height="22" rx="11" fill="url(#lg1)">
    <animate attributeName="width" from="0" to="344" dur="2s" begin="0.6s" fill="freeze"/>
  </rect>
  <text x="838" y="342" text-anchor="end" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="14" fill="#c9d1d9" font-weight="700">42%</text>

  <text x="40" y="376" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="16" fill="#c9d1d9">Jupyter / Shell</text>
  <rect x="40" y="390" width="820" height="22" rx="11" fill="#161b22"/>
  <rect x="40" y="390" width="0" height="22" rx="11" fill="url(#lg4)">
    <animate attributeName="width" from="0" to="369" dur="2s" begin="0.75s" fill="freeze"/>
  </rect>
  <text x="838" y="408" text-anchor="end" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif" font-size="14" fill="#c9d1d9" font-weight="700">45%</text>
</svg>

<br>

<!-- animated tech-stack logos -->
<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="52" title="Python"/>
  <img src="https://user-images.githubusercontent.com/74038190/212257454-16e3712e-945a-4ca2-b238-408ad0bf87e6.gif" width="52" title="JavaScript"/>
  <img src="https://user-images.githubusercontent.com/74038190/212281775-b468df30-4edc-4bf8-a4ee-f52e1aaddc86.gif" width="52" title="TypeScript"/>
  <img src="https://user-images.githubusercontent.com/74038190/212257465-7ce8d493-cac5-494e-982a-5a9deb852c4b.gif" width="52" title="HTML"/>
  <img src="https://user-images.githubusercontent.com/74038190/212280805-9bcb336b-8c55-46a8-abf8-ff286ab55472.gif" width="52" title="CSS"/>
  <img src="https://user-images.githubusercontent.com/74038190/212257467-871d32b7-e401-42e8-a166-fcfd7baa4c6b.gif" width="52" title="React"/>
  <img src="https://user-images.githubusercontent.com/74038190/212281780-0afd9616-8310-46e9-a898-c4f5269f1387.gif" width="52" title="Node"/>
  <img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="52" title="GitHub"/>
  <img src="https://user-images.githubusercontent.com/74038190/212281756-450d3ffa-9335-4b98-a965-db8a18fee927.gif" width="52" title="Terminal"/>
  <img src="https://user-images.githubusercontent.com/74038190/212281763-e6ecd7ef-c4aa-45b6-a97c-f33f6bb592bd.gif" width="52" title="Java"/>
</div>

<br>

<!-- =========================================================== -->
<!--  ANIMATED EXPERTISE CARDS                                   -->
<!-- =========================================================== -->
<h2 align="center">🧠 &nbsp;Expertise</h2>

<svg viewBox="0 0 900 360" width="100%" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Expertise grid">
  <!-- row 1 -->
  <g>
    <rect x="20" y="20" width="200" height="160" rx="18" fill="#161b22" stroke="#21262d"/>
    <text x="120" y="58" text-anchor="middle" font-size="22">☁️</text>
    <text x="120" y="82" text-anchor="middle" font-size="15" font-weight="600" fill="#e6edf3">Cloud &amp; DevOps</text>
    <line x1="32" y1="96" x2="208" y2="96" stroke="#21262d"/>
    <text x="120" y="118" text-anchor="middle" font-size="11" fill="#8b9fb4">AWS EC2 · Lambda · S3 · IAM</text>
    <text x="120" y="136" text-anchor="middle" font-size="11" fill="#8b9fb4">SQS · SNS · Athena · Serverless</text>
    <text x="120" y="154" text-anchor="middle" font-size="11" fill="#8b9fb4">Terraform · CloudFormation</text>
    <text x="120" y="172" text-anchor="middle" font-size="11" fill="#8b9fb4">Step Functions · Azure · GCP</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="3s" repeatCount="indefinite"/>
  </g>
  <g transform="translate(280,0)">
    <rect x="20" y="20" width="200" height="160" rx="18" fill="#161b22" stroke="#21262d"/>
    <text x="120" y="58" text-anchor="middle" font-size="22">📡</text>
    <text x="120" y="82" text-anchor="middle" font-size="14" font-weight="600" fill="#e6edf3">Observability &amp; Monitoring</text>
    <line x1="32" y1="96" x2="208" y2="96" stroke="#21262d"/>
    <text x="120" y="118" text-anchor="middle" font-size="11" fill="#8b9fb4">End-to-end Observability layer</text>
    <text x="120" y="136" text-anchor="middle" font-size="11" fill="#8b9fb4">Traceability layer</text>
    <text x="120" y="154" text-anchor="middle" font-size="11" fill="#8b9fb4">Cost &amp; Health Monitoring app</text>
    <text x="120" y="172" text-anchor="middle" font-size="11" fill="#8b9fb4">Operations Management Portal</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="3.4s" repeatCount="indefinite"/>
  </g>
  <g transform="translate(560,0)">
    <rect x="20" y="20" width="200" height="160" rx="18" fill="#161b22" stroke="#21262d"/>
    <text x="120" y="58" text-anchor="middle" font-size="22">🧠</text>
    <text x="120" y="82" text-anchor="middle" font-size="15" font-weight="600" fill="#e6edf3">Computer Vision &amp; DL</text>
    <line x1="32" y1="96" x2="208" y2="96" stroke="#21262d"/>
    <text x="120" y="118" text-anchor="middle" font-size="11" fill="#8b9fb4">SAM · Mobile SAM</text>
    <text x="120" y="136" text-anchor="middle" font-size="11" fill="#8b9fb4">Grounding DINO · OpenCV · CNN</text>
    <text x="120" y="154" text-anchor="middle" font-size="11" fill="#8b9fb4">GAN · Super-Resolution</text>
    <text x="120" y="172" text-anchor="middle" font-size="11" fill="#8b9fb4">Automated Labelling Tool</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="3.8s" repeatCount="indefinite"/>
  </g>
  <!-- row 2 -->
  <g transform="translate(0,200)">
    <rect x="20" y="20" width="200" height="140" rx="18" fill="#161b22" stroke="#21262d"/>
    <text x="120" y="58" text-anchor="middle" font-size="22">🗄️</text>
    <text x="120" y="82" text-anchor="middle" font-size="15" font-weight="600" fill="#e6edf3">Backend &amp; Databases</text>
    <line x1="32" y1="96" x2="208" y2="96" stroke="#21262d"/>
    <text x="120" y="118" text-anchor="middle" font-size="11" fill="#8b9fb4">PostgreSQL · MySQL</text>
    <text x="120" y="136" text-anchor="middle" font-size="11" fill="#8b9fb4">Hasura · GraphQL</text>
    <text x="120" y="154" text-anchor="middle" font-size="11" fill="#8b9fb4">Athena · Data querying</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="2.9s" repeatCount="indefinite"/>
  </g>
  <g transform="translate(280,200)">
    <rect x="20" y="20" width="200" height="140" rx="18" fill="#161b22" stroke="#21262d"/>
    <text x="120" y="58" text-anchor="middle" font-size="22">🎨</text>
    <text x="120" y="82" text-anchor="middle" font-size="15" font-weight="600" fill="#e6edf3">Full-Stack &amp; Frontend</text>
    <line x1="32" y1="96" x2="208" y2="96" stroke="#21262d"/>
    <text x="120" y="118" text-anchor="middle" font-size="11" fill="#8b9fb4">React · Next.js</text>
    <text x="120" y="136" text-anchor="middle" font-size="11" fill="#8b9fb4">Shadcn · Magic UI · Hero UI</text>
    <text x="120" y="154" text-anchor="middle" font-size="11" fill="#8b9fb4">React Native · Expo</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="3.2s" repeatCount="indefinite"/>
  </g>
  <g transform="translate(560,200)">
    <rect x="20" y="20" width="200" height="140" rx="18" fill="#161b22" stroke="#21262d"/>
    <text x="120" y="58" text-anchor="middle" font-size="22">🌍</text>
    <text x="120" y="82" text-anchor="middle" font-size="15" font-weight="600" fill="#e6edf3">Geospatial &amp; Agri-AI</text>
    <line x1="32" y1="96" x2="208" y2="96" stroke="#21262d"/>
    <text x="120" y="118" text-anchor="middle" font-size="11" fill="#8b9fb4">GPS Acres</text>
    <text x="120" y="136" text-anchor="middle" font-size="11" fill="#8b9fb4">Anomaly Detection pipeline</text>
    <text x="120" y="154" text-anchor="middle" font-size="11" fill="#8b9fb4">Plant Count classifier</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="3.6s" repeatCount="indefinite"/>
  </g>
</svg>

<br>

<h3 align="center">🛰️ &nbsp;Notable Builds</h3>
<p align="center">
  📈 End-to-End Observability &amp; Traceability layer<br/>
  💸 Cloud Cost &amp; Health Monitoring &amp; Tracking application<br/>
  🧭 Complete Operations Management &amp; Monitoring Portal<br/>
  📍 GPS Acres<br/>
  🏷️ Automated Labelling Tool with cloud connectivity<br/>
  🚨 Anomaly Detection end-to-end pipeline<br/>
  🌾 Plant Count Report Classifier
</p>

<br>

<!-- =========================================================== -->
<!--  CONTRIBUTION ACTIVITY GRAPH                                -->
<!-- =========================================================== -->
<h2 align="center">📈 &nbsp;Contribution Graph</h2>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=hamza-0987&bg_color=0d1117&color=22d3ee&line=7c3aed&point=f472b6&area=true&hide_border=true" />
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=hamza-0987&bg_color=ffffff&color=7c3aed&line=22d3ee&point=f472b6&area=true&hide_border=true" width="100%" alt="Contribution graph"/>
  </picture>
</p>

<br>

<!-- =========================================================== -->
<!--  FEATURED PROJECTS (always-loading animated SVG grid)       -->
<!-- =========================================================== -->
<h2 align="center">🗂️ &nbsp;Featured Projects</h2>

<pre align="center">
 ●───────●───────●───────●───────●
 │                          │
 │                          ●───────●───────●
 │                                  │
 │                                  ●───────●
 │
 ●───────●───────●
</pre>

<svg viewBox="0 0 900 540" width="100%" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Featured projects terminal">
  <defs>
    <linearGradient id="fp" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/><stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
  </defs>

  <!-- frame -->
  <rect x="0" y="0" width="900" height="540" rx="20" fill="#0d1117" stroke="#21262d"/>

  <!-- title bar -->
  <rect x="0" y="0" width="900" height="42" rx="20" fill="#161b22"/>
  <rect x="0" y="20" width="900" height="22" fill="#161b22"/>
  <circle cx="26" cy="21" r="6" fill="#ff5f57"/>
  <circle cx="46" cy="21" r="6" fill="#febc2e"/>
  <circle cx="66" cy="21" r="6" fill="#28c840"/>
  <text x="450" y="27" text-anchor="middle" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#7689a6">hamza@hamza-0987: ~/featured</text>

  <!-- command line -->
  <text x="28" y="72" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="15" fill="#8b9fb4">$</text>
  <text x="46" y="72" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="15" fill="#c9d1d9">ls -la --top 9</text>
  <rect x="212" y="58" width="9" height="16" fill="#22d3ee">
    <animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.49;0.5;1" dur="1.1s" repeatCount="indefinite"/>
  </rect>

  <!-- scan sweep on load -->
  <rect x="0" y="42" width="900" height="2" fill="url(#fp)" opacity="0">
    <animate attributeName="y" values="42;538" dur="2.2s" begin="0.3s" fill="freeze"/>
    <animate attributeName="opacity" values="0;0.45;0" dur="2.2s" begin="0.3s" fill="freeze"/>
  </rect>

  <!-- column headers -->
  <circle cx="42" cy="96" r="4" fill="#28c840">
    <animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  <text x="58" y="100" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="11" fill="#4b5a72" letter-spacing="1.5">PROJECT</text>
  <text x="788" y="100" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="11" fill="#4b5a72" letter-spacing="1.5">STARS</text>

  <!-- ============ project rows ============ -->

  <!-- row 0 -->
  <g>
    <rect x="24" y="114" width="852" height="36" rx="9" fill="#0f1420"/>
    <a href="https://github.com/hamza-0987/multi-agent-system" target="_blank">
      <rect x="42" y="123" width="18" height="18" rx="5" fill="#3572A5">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.8s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="136" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">multi-agent-system</text>
      <text x="70" y="148" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">AutoGen Studio, Groq LLM and MCP integration</text>
      <text x="788" y="136" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#fde68a">★ 1</text>
      <text x="868" y="136" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.15s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.15s" fill="freeze"/>
  </g>

  <!-- row 1 -->
  <g>
    <rect x="24" y="156" width="852" height="36" rx="9" fill="#121a29"/>
    <a href="https://github.com/hamza-0987/text2sql" target="_blank">
      <rect x="42" y="165" width="18" height="18" rx="5" fill="#3572A5">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.9s" begin="0.2s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="178" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">text2sql</text>
      <text x="70" y="190" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Natural language questions to SQL queries</text>
      <text x="788" y="178" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="178" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.24s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.24s" fill="freeze"/>
  </g>

  <!-- row 2 -->
  <g>
    <rect x="24" y="198" width="852" height="36" rx="9" fill="#0f1420"/>
    <a href="https://github.com/hamza-0987/easy-rag" target="_blank">
      <rect x="42" y="207" width="18" height="18" rx="5" fill="#3572A5">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="3s" begin="0.4s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="220" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">easy-rag</text>
      <text x="70" y="232" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Lightweight and flexible RAG framework</text>
      <text x="788" y="220" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="220" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.33s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.33s" fill="freeze"/>
  </g>

  <!-- row 3 -->
  <g>
    <rect x="24" y="240" width="852" height="36" rx="9" fill="#121a29"/>
    <a href="https://github.com/hamza-0987/neo4j-rag-example" target="_blank">
      <rect x="42" y="249" width="18" height="18" rx="5" fill="#DA5B0B">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.7s" begin="0.6s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="262" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">neo4j-rag-example</text>
      <text x="70" y="274" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Graph-powered retrieval with Neo4j</text>
      <text x="788" y="262" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="262" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.42s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.42s" fill="freeze"/>
  </g>

  <!-- row 4 -->
  <g>
    <rect x="24" y="282" width="852" height="36" rx="9" fill="#0f1420"/>
    <a href="https://github.com/hamza-0987/unified-arhitecture-thesis-app" target="_blank">
      <rect x="42" y="291" width="18" height="18" rx="5" fill="#3178c6">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.8s" begin="0.8s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="304" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">unified-architecture-thesis-app</text>
      <text x="70" y="316" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Full-stack unified architecture thesis app</text>
      <text x="788" y="304" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="304" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.51s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.51s" fill="freeze"/>
  </g>

  <!-- row 5 -->
  <g>
    <rect x="24" y="324" width="852" height="36" rx="9" fill="#121a29"/>
    <a href="https://github.com/hamza-0987/github2diagram" target="_blank">
      <rect x="42" y="333" width="18" height="18" rx="5" fill="#e34c26">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.9s" begin="1s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="346" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">github2diagram</text>
      <text x="70" y="358" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Turn GitHub data into diagrams</text>
      <text x="788" y="346" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="346" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.6s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.6s" fill="freeze"/>
  </g>

  <!-- row 6 -->
  <g>
    <rect x="24" y="366" width="852" height="36" rx="9" fill="#0f1420"/>
    <a href="https://github.com/hamza-0987/shaheenviz" target="_blank">
      <rect x="42" y="375" width="18" height="18" rx="5" fill="#3572A5">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.6s" begin="1.2s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="388" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">shaheenviz</text>
      <text x="70" y="400" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Geospatial data visualization</text>
      <text x="788" y="388" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="388" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.69s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.69s" fill="freeze"/>
  </g>

  <!-- row 7 -->
  <g>
    <rect x="24" y="408" width="852" height="36" rx="9" fill="#121a29"/>
    <a href="https://github.com/hamza-0987/stocksage" target="_blank">
      <rect x="42" y="417" width="18" height="18" rx="5" fill="#3572A5">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="3.1s" begin="1.4s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="430" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">stocksage</text>
      <text x="70" y="442" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Stock market insights and analysis</text>
      <text x="788" y="430" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#4b5a72">★ 0</text>
      <text x="868" y="430" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.78s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.78s" fill="freeze"/>
  </g>

  <!-- row 8 -->
  <g>
    <rect x="24" y="450" width="852" height="36" rx="9" fill="#0f1420"/>
    <a href="https://github.com/hamza-0987/Rolex-watch" target="_blank">
      <rect x="42" y="459" width="18" height="18" rx="5" fill="#663399">
        <animate attributeName="opacity" values="0.55;1;0.55" dur="2.7s" begin="1.6s" repeatCount="indefinite"/>
      </rect>
      <text x="70" y="472" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="14.5" font-weight="700" fill="#e6edf3">Rolex-watch</text>
      <text x="70" y="484" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="10.5" fill="#7689a6">Luxury watch crafted in pure CSS</text>
      <text x="788" y="472" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#fde68a">★ 1</text>
      <text x="868" y="472" text-anchor="end" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.45s" begin="0.87s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,10;0,0" dur="0.45s" begin="0.87s" fill="freeze"/>
  </g>

  <!-- footer -->
  <rect x="24" y="498" width="852" height="1.5" fill="#1c2333"/>
  <rect x="24" y="498" width="0" height="1.5" fill="url(#fp)">
    <animate attributeName="width" from="0" to="852" dur="1.2s" begin="1s" fill="freeze"/>
  </rect>
  <text x="28" y="521" font-family="ui-monospace,SFMono-Regular,Consolas,monospace" font-size="13" fill="#22d3ee">
    <tspan fill="#8b9fb4">❯</tspan> <a href="https://github.com/hamza-0987?tab=repositories" target="_blank">browse all 56 repositories</a>
    <animate attributeName="opacity" values="1;1;0.4;1" dur="2.4s" repeatCount="indefinite"/>
  </text>
</svg>

<details align="center">
  <summary><b>🧭 Explore more repositories</b></summary>
  <br>
  <p align="center">
    <a href="https://github.com/hamza-0987/shaheenai-github">shaheenai-github</a> •
    <a href="https://github.com/hamza-0987/local_lambda_test">local_lambda_test</a> •
    <a href="https://github.com/hamza-0987/gemini-flask">gemini-flask</a> •
    <a href="https://github.com/hamza-0987/crud_django">crud_django</a> •
    <a href="https://github.com/hamza-0987/firecrawle-semantic-search">firecrawl-semantic-search</a> •
    <a href="https://github.com/hamza-0987/prompt-pack-for-3d-web-pages">3d-prompt-pack</a> •
    <a href="https://github.com/hamza-0987/diabetes-prediction-model">diabetes-model</a> •
    <a href="https://github.com/hamza-0987/pychat">pychat</a>
  </p>
</details>

<br>

<!-- =========================================================== -->
<!--  CONNECT (real platforms only: GitHub, LinkedIn)            -->
<!-- =========================================================== -->
<h2 align="center">🤝 &nbsp;Let&apos;s Connect</h2>

<svg viewBox="0 0 900 320" width="100%" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Connect links">
  <rect width="900" height="320" rx="24" fill="#0d1117" stroke="#21262d"/>
  <text x="450" y="52" text-anchor="middle" font-size="22" font-weight="700" fill="#e6edf3">Where to find me</text>

  <!-- GitHub -->
  <g>
    <a href="https://github.com/hamza-0987" target="_blank">
      <rect x="150" y="90" width="600" height="80" rx="16" fill="#161b22" stroke="#21262d"/>
      <image href="https://user-images.githubusercontent.com/74038190/235294002-8aafea24-3179-45af-91d9-412ad7ff5359.gif" x="172" y="102" width="56" height="56" preserveAspectRatio="xMidYMid slice"/>
      <text x="250" y="130" font-size="19" font-weight="700" fill="#ffffff">GitHub</text>
      <text x="250" y="152" font-size="14" fill="#8b9fb4">github.com/hamza-0987 — code, experiments &amp; OSS</text>
      <text x="726" y="132" text-anchor="end" font-size="22" fill="#22d3ee">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.6s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,16;0,0" dur="0.6s" fill="freeze"/>
  </g>

  <!-- LinkedIn -->
  <g>
    <a href="https://www.linkedin.com/in/hamza-075864228" target="_blank">
      <rect x="150" y="185" width="600" height="80" rx="16" fill="#161b22" stroke="#21262d"/>
      <image href="https://user-images.githubusercontent.com/74038190/235294010-ec412ef5-e3da-4efa-b1d4-0ab4d4638755.gif" x="172" y="197" width="56" height="56" preserveAspectRatio="xMidYMid slice"/>
      <text x="250" y="225" font-size="19" font-weight="700" fill="#ffffff">LinkedIn</text>
      <text x="250" y="247" font-size="14" fill="#8b9fb4">linkedin.com/in/hamza-075864228 — let&apos;s network</text>
      <text x="726" y="227" text-anchor="end" font-size="22" fill="#7c3aed">→</text>
    </a>
    <animate attributeName="opacity" values="0;1" dur="0.6s" begin="0.2s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,16;0,0" dur="0.6s" begin="0.2s" fill="freeze"/>
  </g>

  <!-- note -->
  <text x="450" y="292" text-anchor="middle" font-size="14" fill="#5c7291">💬 Open to collaborations in AI/ML, RAG &amp; geospatial projects — I reply fast.</text>
</svg>

<br>

<!-- animated footer wave -->
<svg width="100%" viewBox="0 0 1440 120" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <path d="M0,64 C240,96 480,32 720,64 C960,96 1200,32 1440,64 L1440,120 L0,120 Z" fill="#7c3aed" opacity="0.35">
    <animate attributeName="d" values="M0,64 C240,96 480,32 720,64 C960,96 1200,32 1440,64 L1440,120 L0,120 Z;M0,64 C240,32 480,96 720,64 C960,32 1200,96 1440,64 L1440,120 L0,120 Z;M0,64 C240,96 480,32 720,64 C960,96 1200,32 1440,64 L1440,120 L0,120 Z" dur="6s" repeatCount="indefinite"/>
  </path>
  <path d="M0,80 C240,110 480,50 720,80 C960,110 1200,50 1440,80 L1440,120 L0,120 Z" fill="#22d3ee" opacity="0.4">
    <animate attributeName="d" values="M0,80 C240,110 480,50 720,80 C960,110 1200,50 1440,80 L1440,120 L0,120 Z;M0,80 C240,50 480,110 720,80 C960,50 1200,110 1440,80 L1440,120 L0,120 Z;M0,80 C240,110 480,50 720,80 C960,110 1200,50 1440,80 L1440,120 L0,120 Z" dur="7s" repeatCount="indefinite"/>
  </path>
</svg>

<p align="center">
  <i>Made with ❤️ &amp; far too much coffee</i> &nbsp;•&nbsp; <b>@hamza-0987</b> &nbsp;•&nbsp; <b>2026</b>
  <br>
  <sub>Profile auto-enhanced with live GitHub GraphQL data — always current.</sub>
</p>
