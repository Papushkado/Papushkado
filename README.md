<!-- ==================== TITRE NÉON (SVG) ==================== -->
<div align="center">
  <svg width="600" height="120" viewBox="0 0 600 120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <filter id="neon">
        <feGaussianBlur stdDeviation="4" result="glow"/>
        <feMerge>
          <feMergeNode in="glow"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#0ff"/>
        <stop offset="100%" stop-color="#ff00ff"/>
      </linearGradient>
    </defs>
    <text x="50%" y="60%" text-anchor="middle"
          font-family="Orbitron, sans-serif" font-size="48"
          fill="url(#grad)" filter="url(#neon)"
          style="animation: flicker 2s infinite;">
      Stephen Cohen <tspan fill="#ff2dfc">(Papushkado)</tspan>
    </text>
  </svg>
</div>

<p align="center">
  <a href="mailto:Stephen.cohen.pro@gmail.com">
    <img src="https://img.shields.io/badge/📧-Email-white?style=for-the-badge&logo=gmail&logoColor=red" alt="email"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/📍-Paris-white?style=for-the-badge&logo=google-maps&logoColor=0055FF" alt="location"/>
  </a>
  <a href="https://www.linkedin.com/in/stephen-cohen-491964163/">
    <img src="https://img.shields.io/badge/🔗-LinkedIn-white?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="linkedin"/>
  </a>
</p>

---

<!-- ==================== À PROPOS (fond animé SVG) ==================== -->
<div align="center">
  <svg width="100%" height="100" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="g2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#0ff"/>
        <stop offset="50%" stop-color="#ff00ff"/>
        <stop offset="100%" stop-color="#00f7ff"/>
      </linearGradient>
      <rect id="bg" x="0" y="0" width="100%" height="100" rx="12" ry="12"/>
    </defs>
    <use href="#bg" fill="url(#g2)">
      <animate attributeName="x" values="0;400;0" dur="15s" repeatCount="indefinite"/>
    </use>
    <text x="50%" y="55%" text-anchor="middle"
          fill="#111" font-family="Share Tech Mono, monospace" font-size="18">
      Étudiant en <tspan font-weight="bold">Cybersécurité</tspan> ／ 
      <tspan font-weight="bold">Actuariat</tspan> ／ <tspan font-weight="bold">IA & Cloud</tspan>
    </text>
  </svg>
</div>

---

## <svg width="200" height="40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="glitch">
      <feTurbulence type="fractalNoise" baseFrequency="0.02" numOctaves="3" result="noise"/>
      <feDisplacementMap in="SourceGraphic" in2="noise" scale="10"/>
    </filter>
  </defs>
  <text x="0" y="30" font-family="Share Tech Mono, monospace" font-size="24" fill="#fff" filter="url(#glitch)">
    DOMAINES D’EXPERTISE
  </text>
</svg>

<details>
  <summary style="color:#0ff; font-family:Orbitron, monospace; font-size:1.1rem; text-shadow:0 0 8px #0ff;">
    🛡️ Cybersécurité & Red Team
  </summary>
  <ul>
    <li><strong>Write-ups CTFs</strong> – exploitation de buffer overflows, forçage RSA sur-mesure, web-hacking (404CTF, UnitedCTF, MidnightCTF).</li>
    <li><strong>IMSI Catcher</strong> – simulateur et reverse-engineering de relais GSM, workshop detection/mitigation.</li>
    <li><strong>SSI Groupama</strong> – audit SWIFT, conformité DORA, méthode EBIOS RM pour cartographie des risques.</li>
  </ul>
</details>

<details>
  <summary style="color:#0ff; font-family:Orbitron, monospace; font-size:1.1rem; text-shadow:0 0 8px #0ff;">
    ☁️ Cloud & Infra DevOps
  </summary>
  <ul>
    <li><strong>DBCluster</strong> – cluster MySQL HA sur AWS, ProxySQL, Terraform & Ansible.</li>
    <li><strong>MapReduce Social</strong> – pipeline EMR pour analyser graphes Twitter (centralité, détection de communautés).</li>
    <li><strong>WiFi Mesh</strong> – OpenWrt & FreeRadius, WPA2-Enterprise, provisioning Docker/Shell.</li>
  </ul>
</details>

<details>
  <summary style="color:#0ff; font-family:Orbitron, monospace; font-size:1.1rem; text-shadow:0 0 8px #0ff;">
    📈 Actuariat & Risk Modelling
  </summary>
  <ul>
    <li><strong>SCOR Internal Model</strong> – ALM/DLM pour ouragans USA, simulation Monte-Carlo, back-tests NOAA.</li>
    <li><strong>Cyber CAT Models</strong> – scénarios sinistres cyber, calibrage pertes, dashboard Dash/Plotly.</li>
    <li><strong>Bayesian Statistics</strong> – MCMC (PyMC3) vs. ML classique pour durée de vie d’équipements.</li>
    <li><strong>Real-Estate Prediction</strong> – XGBoost + DVF, feature engineering géospatial, interface Streamlit.</li>
  </ul>
</details>

<details>
  <summary style="color:#0ff; font-family:Orbitron, monospace; font-size:1.1rem; text-shadow:0 0 8px #0ff;">
    🤖 IoT & Prototypage
  </summary>
  <ul>
    <li><strong>IoT_Telecom</strong> – MQTT, InfluxDB, Grafana en Docker, alerting via Webhooks.</li>
    <li><strong>Indoor Localisation</strong> – Bluetooth fingerprinting, K-NN/SVM, précision &lt; 2 m.</li>
    <li><strong>SMARTIES</strong> – soirées connectées: API WebSocket + capteurs pour show lumières/son.</li>
  </ul>
</details>

---

## <svg width="180" height="40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="glitch2">
      <feTurbulence type="turbulence" baseFrequency="0.05" numOctaves="2" result="n2"/>
      <feDisplacementMap in="SourceGraphic" in2="n2" scale="8"/>
    </filter>
  </defs>
  <text x="0" y="30" font-family="Share Tech Mono, monospace" font-size="24" fill="#fff" filter="url(#glitch2)">
    TECH STACK
  </text>
</svg>

```yaml
languages: [Python, C, Java, Kotlin, JavaScript, HTML/CSS, PHP]
cloud:     [AWS, Terraform, Docker, Ansible, Azure Databricks]
secops:    [EBIOS RM, Threat Modeling, Cryptography, CTFs]
ml/data:   [pandas, XGBoost, PyMC3, Dash/Plotly]
network:   [OpenWrt, FreeRadius, Linux, Bash]
```
<svg width="220" height="40" xmlns="http://www.w3.org/2000/svg">
<defs> <filter id="glitch3"> <feTurbulence type="fractalNoise" baseFrequency="0.03" numOctaves="4" result="n3"/> <feDisplacementMap in="SourceGraphic" in2="n3" scale="12"/> </filter> </defs> <text x="0" y="30" font-family="Share Tech Mono, monospace" font-size="24" fill="#fff" filter="url(#glitch3)"> VALEURS & PASSIONS </text> </svg> <div align="center"> <img src="https://img.icons8.com/ios-filled/60/00ffff/rocket.png" alt="rocket"/> <img src="https://img.icons8.com/ios-filled/60/ff00ff/book.png" alt="book"/> <img src="https://img.icons8.com/ios-filled/60/00f7ff/handshake.png" alt="handshake"/> </div> <p align="center" style="font-family:'Share Tech Mono', monospace; color:#0ff;"> Explorer l’inconnu | Simplifier le complexe | Bâtir l’inattendu </p>
<svg width="200" height="40" xmlns="http://www.w3.org/2000/svg">
<defs> <filter id="glitch4"> <feTurbulence type="turbulence" baseFrequency="0.04" numOctaves="3" result="n4"/> <feDisplacementMap in="SourceGraphic" in2="n4" scale="10"/> </filter> </defs> <text x="0" y="30" font-family="Share Tech Mono, monospace" font-size="24" fill="#fff" filter="url(#glitch4)"> PROJETS ANNEXES </text> </svg>

    🌿 IPPermaculture – guide open-source et ateliers pour étudiants en agroécologie.

    🧠 Philosophie x Manga – essai libre accès sur l’éthique dans la pop-culture japonaise.

    💼 Entrepreneurship Certificate – startup challenge de Polytechnique Paris, de l’idéation au pitch.

<div align="center"> <a href="mailto:Stephen.cohen.pro@gmail.com" style="text-decoration:none;"> <span style=" display:inline-block; padding:0.6rem 1.2rem; background:#0ff; color:#111; font-family:Orbitron, monospace; font-weight:bold; border-radius:0.6rem; box-shadow:0 0 12px #0ff; "> 🚀 Prêt à hacker une idée ? Contacte-moi ! </span> </a> </div>
