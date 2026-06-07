**`Developer`** 

<div>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 300" width="900" height="300" style="font-family: 'JetBrains Mono', monospace;">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&amp;family=Outfit:wght@300;400;600;700&amp;display=swap');
    </style>
    <pattern id="grid" width="28" height="28" patternUnits="userSpaceOnUse">
      <path d="M 28 0 L 0 0 0 28" fill="none" stroke="#569cd6" stroke-width="0.4" opacity="0.12"/>
    </pattern>
    <clipPath id="clip">
      <rect width="900" height="300" rx="12"/>
    </clipPath>
  </defs>

  <g clip-path="url(#clip)">

    <!-- Background -->
    <rect width="900" height="300" fill="#1e1e1e"/>

    <!-- Grid overlay -->
    <rect width="900" height="300" fill="url(#grid)"/>

    <!-- Top bar -->
    <rect width="900" height="38" fill="#2d2d2d"/>
    <rect y="37" width="900" height="1" fill="#3c3c3c"/>

    <!-- Traffic lights -->
    <circle cx="20" cy="19" r="6" fill="#ff5f57"/>
    <circle cx="40" cy="19" r="6" fill="#febc2e"/>
    <circle cx="60" cy="19" r="6" fill="#28c840"/>

    <!-- Active tab -->
    <rect x="80" y="0" width="130" height="38" fill="#1e1e1e"/>
    <rect x="80" y="0" width="130" height="2" fill="#569cd6"/>
    <circle cx="96" cy="19" r="4" fill="#e2c08d"/>
    <text x="106" y="23" fill="#cccccc" font-family="'JetBrains Mono', monospace" font-size="12">README.md</text>

    <!-- Sidebar -->
    <rect x="0" y="38" width="52" height="262" fill="#252526"/>
    <rect x="51" y="38" width="1" height="262" fill="#3c3c3c"/>

    <!-- Active sidebar indicator -->
    <rect x="0" y="58" width="2" height="28" fill="#569cd6"/>

    <!-- Sidebar icons (simple geometric) -->
    <!-- Files icon -->
    <rect x="17" y="62" width="18" height="20" rx="2" fill="none" stroke="#cccccc" stroke-width="1.2"/>
    <line x1="21" y1="68" x2="31" y2="68" stroke="#cccccc" stroke-width="1"/>
    <line x1="21" y1="72" x2="31" y2="72" stroke="#cccccc" stroke-width="1"/>
    <line x1="21" y1="76" x2="27" y2="76" stroke="#cccccc" stroke-width="1"/>

    <!-- Search icon -->
    <circle cx="26" cy="112" r="7" fill="none" stroke="#666" stroke-width="1.2"/>
    <line x1="31" y1="117" x2="36" y2="122" stroke="#666" stroke-width="1.2" stroke-linecap="round"/>

    <!-- Git icon -->
    <circle cx="22" cy="148" r="4" fill="none" stroke="#666" stroke-width="1.2"/>
    <circle cx="22" cy="162" r="4" fill="none" stroke="#666" stroke-width="1.2"/>
    <circle cx="34" cy="148" r="4" fill="none" stroke="#666" stroke-width="1.2"/>
    <path d="M22 152 Q22 158 26 158 Q34 158 34 152" fill="none" stroke="#666" stroke-width="1.2"/>

    <!-- Line numbers -->
    <text x="68" y="88" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">1</text>
    <text x="68" y="104" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">2</text>
    <text x="68" y="120" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">3</text>
    <text x="68" y="136" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">4</text>
    <text x="68" y="152" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">5</text>
    <text x="68" y="168" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">6</text>
    <text x="68" y="184" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">7</text>
    <text x="68" y="200" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">8</text>
    <text x="68" y="216" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">9</text>
    <text x="68" y="232" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">10</text>
    <text x="68" y="248" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">11</text>
    <text x="68" y="264" fill="#4a4a4a" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">12</text>

    <!-- Main content area -->

    <!-- Line 1: comment -->
    <text x="88" y="88" fill="#6a9955" font-family="'JetBrains Mono', monospace" font-size="13">// Software Engineer · Architect mindset</text>

    <!-- Line 2: const dev = { -->
    <text x="88" y="108" fill="#569cd6" font-family="'JetBrains Mono', monospace" font-size="13">const </text>
    <text x="140" y="108" fill="#9cdcfe" font-family="'JetBrains Mono', monospace" font-size="13">dev</text>
    <text x="167" y="108" fill="#cccccc" font-family="'JetBrains Mono', monospace" font-size="13"> = {</text>

    <!-- Line 3: name: "Ikaro de Castro" -->
    <text x="106" y="130" fill="#9cdcfe" font-family="'JetBrains Mono', monospace" font-size="13">name:</text>
    <text x="160" y="138" fill="#dcdcaa" font-family="'Outfit', sans-serif" font-size="40" font-weight="700" letter-spacing="-0.5">"Ikaro de Castro"</text>

    <!-- Line 5: role -->
    <text x="106" y="176" fill="#9cdcfe" font-family="'JetBrains Mono', monospace" font-size="13">role:</text>
    <text x="160" y="176" fill="#4ec9b0" font-family="'JetBrains Mono', monospace" font-size="13">"Software Engineer · @IkadoDev"</text>

    <!-- Tags / badges -->
    <!-- Junior Developer -->
    <rect x="106" y="188" width="136" height="22" rx="4" fill="#3a2a1a" stroke="#5a3a1a" stroke-width="1"/>
    <text x="174" y="203" fill="#e2c08d" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">Junior Developer</text>

    <!-- Java -->
    <rect x="250" y="188" width="52" height="22" rx="4" fill="#2a3a2a" stroke="#2a4a2a" stroke-width="1"/>
    <text x="276" y="203" fill="#4ec9b0" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">Java</text>

    <!-- C++ -->
    <rect x="310" y="188" width="44" height="22" rx="4" fill="#1a2a3a" stroke="#1a3050" stroke-width="1"/>
    <text x="332" y="203" fill="#569cd6" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">C++</text>

    <!-- Arquitetura de Software -->
    <rect x="362" y="188" width="176" height="22" rx="4" fill="#2e1e3a" stroke="#4a2a5a" stroke-width="1"/>
    <text x="450" y="203" fill="#c586c0" font-family="'JetBrains Mono', monospace" font-size="11" text-anchor="middle">Arquitetura de Software</text>

    <!-- Bio lines (as comments) -->
    <rect x="104" y="218" width="4" height="52" rx="2" fill="#2d4a2d"/>
    <text x="116" y="232" fill="#6a9955" font-family="'JetBrains Mono', monospace" font-size="11">// Desenvolvo soluções com foco em arquitetura limpa, SOLID e boas práticas.</text>
    <text x="116" y="248" fill="#6a9955" font-family="'JetBrains Mono', monospace" font-size="11">// Cada linha de código reflete responsabilidade única e baixo acoplamento.</text>
    <text x="116" y="264" fill="#6a9955" font-family="'JetBrains Mono', monospace" font-size="11">// Comprometido com sistemas escaláveis, legíveis e fáceis de manter.</text>

    <!-- Status bar -->
    <rect y="278" width="900" height="22" fill="#007acc"/>

    <!-- Branch -->
    <text x="12" y="293" fill="#ffffff" font-family="'JetBrains Mono', monospace" font-size="11" opacity="0.9">⎇ main</text>

    <!-- 0 errors -->
    <text x="76" y="293" fill="#ffffff" font-family="'JetBrains Mono', monospace" font-size="11" opacity="0.9">✓ 0 errors</text>

    <!-- Right side -->
    <text x="650" y="293" fill="#ffffff" font-family="'JetBrains Mono', monospace" font-size="11" opacity="0.9">Java · C++</text>
    <text x="740" y="293" fill="#ffffff" font-family="'JetBrains Mono', monospace" font-size="11" opacity="0.9">UTF-8</text>
    <text x="800" y="293" fill="#ffffff" font-family="'JetBrains Mono', monospace" font-size="11" opacity="0.9">Ln 12, Col 1</text>

  </g>
</svg>  
</div>

<li>💻Full-Stack Developer</li>
<li>⌨️Dev Junior Java/C++ Dominantes</li>
<li>⚒️Cursando Engenharia de Software</li>
<li>📩 Aberto a oportunidades de Estagio e Emprego</li>
<br>
<p>Desenvolvedor Back-End com experiência em Java e C++, buscando oportunidades para aplicar meus conhecimentos em desenvolvimento de sistemas robustos e eficientes, contribuindo com soluções de qualidade e continuando meu crescimento técnico na área.</p>

  <div>
  <h1>Linguagens 🤖</h1>

  <table>
    <tr>
      <td><img alt="C" height="30" width="30" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg"></td>
      <td><img alt= "C++" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg"></td>
      <td><img alt="Java" height="40" width="35" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg"></td>
      <td><img alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg"></td>
      <td><img alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg"></td>
      <td><img alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg"></td>
    </tr>
  </table>
</div>

<div>
  <h1>Ferramentas/Frameworks ⚒️</h1>

  <table>
    <tr>
      <td><img alt="Docker" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg"></td>
      <td><img alt="React" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg"></td>
      <td><img alt="VSCode" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"></td>
      <td><img alt="Git" height="30" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"></td>
      <td><img alt="AWS" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg"></td>
    </tr>
  </table>
</div>

<div>
  <h1>Data Bases💾</h1>
      <table>
            <tr>
              <td><img alt="Postgree" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg"></td>
            </tr>
      </table>
</div>
  
  <picture align="center">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ikarocastro/ikarocastro/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ikarocastro/ikarocastro/output/github-contribution-grid-snake-dark.svg">
  <img align="center" alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/ikarocastro/ikarocastro/output/github-contribution-grid-snake.svg">
</picture>
</div>

<p>📈Estatísticas</p>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Felix-Unit&locale=en&mode=daily&theme=tokyonight&hide_border=false&border_radius=5" height="150" alt="streak graph" />
</div>
