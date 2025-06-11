<!-- ======================= STYLE GÉNÉRAL ======================= -->
<style>
  /* Néon glow et flicker */
  @keyframes flicker {
    0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% { opacity: 1; }
    20%, 24%, 55% { opacity: 0.4; }
  }
  .neon-text {
    color: #0ff;
    text-shadow:
      0 0 2px #0ff,
      0 0 8px #0ff,
      0 0 16px #0ff,
      0 0 32px #ff2dfc;
    animation: flicker 2s infinite;
    font-family: 'Orbitron', sans-serif;
  }
  /* Fond animé par dégradé mouvant */
  .bg-gradient {
    background: linear-gradient(270deg, #0ff, #ff00ff, #00f7ff, #ff0055);
    background-size: 800% 800%;
    animation: gradientBG 15s ease infinite;
    padding: 1.5rem;
    border-radius: 1rem;
    box-shadow: 0 0 20px rgba(0,255,255,0.5);
  }
  @keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  /* Glitch effect pour titres */
  .glitch {
    position: relative;
    color: #fff;
    font-size: 2rem;
    font-family: 'Share Tech Mono', monospace;
  }
  .glitch::before,
  .glitch::after {
    content: attr(data-text);
    position: absolute;
    left: 0; top: 0;
    width: 100%; height: 100%;
    opacity: 0.8;
    clip: rect(0, 900px, 0, 0);
  }
  .glitch::before {
    animation: glitchTop 2s infinite linear alternate-reverse;
    color: #0ff;
    text-shadow: -2px -2px #ff00ff;
  }
  .glitch::after {
    animation: glitchBot 1.5s infinite linear alternate-reverse;
    color: #f0f;
    text-shadow: 2px 2px #00f7ff;
  }
  @keyframes glitchTop {
    0% { clip: rect(0, 900px, 10px, 0); }
    50% { clip: rect(20px, 900px, 30px, 0); transform: translate(-2px, -2px); }
    100% { clip: rect(5px, 900px, 15px, 0); }
  }
  @keyframes glitchBot {
    0% { clip: rect(85px, 900px, 120px, 0); }
    50% { clip: rect(60px, 900px, 80px, 0); transform: translate(2px, 2px); }
    100% { clip: rect(90px, 900px, 110px, 0); }
  }
</style>

<!-- ==================== TITRE PRINCIPAL ==================== -->
<div align="center">
  <h1 class="neon-text">Stephen Cohen <span style="color:#ff2dfc;">(Papushkado)</span></h1>
  <p class="neon-text" style="font-size:1.2rem;">
    🔒 Cybersécurité & Actuariat & IA ／ 🚀 Always Hacking Futures
  </p>
</div>

<!-- ==================== BADGES ==================== -->
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

<!-- ==================== À PROPOS ==================== -->
<div class="bg-gradient">
  <p style="color:#fff; font-family:'Share Tech Mono', monospace; font-size:1rem;">
    Étudiant à la croisée de la <strong>Cybersécurité</strong>, de l’<strong>Actuariat</strong> et de l’<strong>IA & Cloud</strong>.<br/>
    Mon credo : <em>« Apprendre. Prototyper. Sécuriser. »</em><br/>
    Toujours prêt à hacker le status quo.
  </p>
</div>

---

## <span class="glitch" data-text="DOMAINES D’EXPERTISE">DOMAINES D’EXPERTISE</span>

<details>
  <summary class="neon-text" style="font-size:1.1rem; cursor:pointer;">
    🛡️ Cybersécurité & Red Team
  </summary>
  <ul>
    <li><strong>Write-ups CTFs</strong> – exploitation de buffer overflows, forçage RSA maison, web-hacking, sur 404CTF, UnitedCTF, MidnightCTF.</li>
    <li><strong>IMSI Catcher</strong> – simulateur et reverse-engineering de faux relais GSM, atelier détection & mitigation.</li>
    <li><strong>SSI Groupama</strong> – audit SWIFT, mise en conformité DORA, méthode EBIOS RM pour cartographie des risques.</li>
  </ul>
</details>

<details>
  <summary class="neon-text" style="font-size:1.1rem; cursor:pointer;">
    ☁️ Cloud & Infra DevOps
  </summary>
  <ul>
    <li><strong>DBCluster</strong> – cluster MySQL HA sur AWS (EC2, RDS), ProxySQL, automations Terraform & Ansible.</li>
    <li><strong>MapReduce Social</strong> – pipeline EMR pour analyse de graphes Twitter : centralité, détection de communautés.</li>
    <li><strong>WiFi Mesh</strong> – OpenWrt & FreeRadius, WPA2-Enterprise, provisioning automatique Docker/Shell.</li>
  </ul>
</details>

<details>
  <summary class="neon-text" style="font-size:1.1rem; cursor:pointer;">
    📈 Actuariat & Risk Modelling
  </summary>
  <ul>
    <li><strong>SCOR Internal Model</strong> – ALM/DLM hybride pour ouragans USA, back-testing NOAA, simulation Monte-Carlo.</li>
    <li><strong>Cyber CAT Models</strong> – scénarios de sinistres cyber, calibrage de pertes, dashboard Dash/Plotly.</li>
    <li><strong>Bayesian Statistics</strong> – estimation bayésienne de durée de vie, MCMC PyMC3 vs ML classique.</li>
    <li><strong>Real-Estate Prediction</strong> – XGBoost + DVF, feature engineering géospatial, interface Streamlit.</li>
  </ul>
</details>

<details>
  <summary class="neon-text" style="font-size:1.1rem; cursor:pointer;">
    🤖 IoT & Prototypage
  </summary>
  <ul>
    <li><strong>IoT_Telecom</strong> – stack MQTT, InfluxDB, Grafana en Docker, alerting Webhooks.</li>
    <li><strong>Indoor Localisation</strong> – Bluetooth fingerprinting, K-NN/SVM, précision <2 m.</li>
    <li><strong>SMARTIES</strong> – soirées connectées: API WebSocket + capteurs pour show lumières/son.</li>
  </ul>
</details>

---

## <span class="glitch" data-text="TECH STACK">TECH STACK</span>

```yaml
languages: [Python, C, Java, Kotlin, JavaScript, HTML/CSS, PHP]
cloud:     [AWS, Terraform, Docker, Ansible, Azure Databricks]
secops:    [EBIOS RM, Threat Modeling, Cryptography, CTFs]
ml/data:   [pandas, XGBoost, PyMC3, Dash/Plotly]
network:   [OpenWrt, FreeRadius, Linux, Bash]
```

<span class="glitch" data-text="VALEURS & PASSIONS">VALEURS & PASSIONS</span>
<div style="display:flex; justify-content:space-around; margin:1rem 0;"> <div align="center"> <img width="60" src="https://img.icons8.com/ios-filled/50/00ffff/rocket.png" alt="rocket"/> <p style="color:#0ff;">Explorer l’inconnu</p> </div> <div align="center"> <img width="60" src="https://img.icons8.com/ios-filled/50/ff00ff/book.png" alt="book"/> <p style="color:#f0f;">Simplifier le complexe</p> </div> <div align="center"> <img width="60" src="https://img.icons8.com/ios-filled/50/00f7ff/handshake.png" alt="handshake"/> <p style="color:#0ff;">Bâtir l’inattendu</p> </div> </div>
<span class="glitch" data-text="PROJETS ANNEXES">PROJETS ANNEXES</span>

    🌿 IPPermaculture – association open-source d’agroécologie, ateliers et guides pratiques.

    🧠 Philosophie x Manga – essai libre accès sur les thèmes éthiques dans la pop-culture japonaise.

    💼 Entrepreneurship Certificate – startup challenge de Polytechnique Paris, de l’idéation au pitch final.

<div align="center" style="margin-top:2rem;"> <p class="neon-text">Prêt à hacker une idée ? <strong>Contacte-moi ! 🚀</strong></p> </div> ```
