<!-- ==================== BANNIÈRE NÉON ==================== -->
<div align="center">
  <!-- SVG néon text inline pour un rendu futuriste -->
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
        <stop offset="0%" stop-color="#00F7FF"/>
        <stop offset="100%" stop-color="#FF00FF"/>
      </linearGradient>
    </defs>
    <text x="50%" y="60%" text-anchor="middle" fill="url(#grad)"
          font-family="Orbitron, sans-serif" font-size="48" filter="url(#neon)">
      Stephen Cohen (Papushkado)
    </text>
  </svg>
</div>

<!-- ==================== BADGES ANIMÉS ==================== -->
<p align="center">
  <a href="mailto:Stephen.cohen.pro@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/📧-Email-red?style=for-the-badge&logo=gmail&logoColor=white&animation=glow" />
  </a>
  <a href="#">
    <img alt="Paris" src="https://img.shields.io/badge/📍-Paris-0055FF?style=for-the-badge&logo=mapbox&logoColor=white&labelColor=000000" />
  </a>
  <a href="https://www.linkedin.com/in/stephen-cohen-491964163/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/🔗-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

<div align="center" style="background:#111; padding:1rem; border-radius:1rem; box-shadow:0 0 20px #00F7FF;">
  <p style="color:#0ff; font-family:monospace;">
    🎓 Étudiant en **Cybersécurité** ／ **Actuariat** ／ **IA & Cloud**<br/>
    🔍 Ponts entre technique, risques et innovation<br/>
    🚀 Toujours en quête de défis « hackables »
  </p>
</div>

---

## 👾 DOMAINES D’EXPERTISE

<details open>
  <summary style="font-size:1.1rem; font-weight:bold; cursor:pointer;">
    🛡️ Cybersécurité & Red Team
  </summary>

  - 🎯 **Write-ups CTFs**  
    Analyse et résolution de challenges (pwn, crypto, web) sur 404CTF, UnitedCTF et MidnightCTF. Exemples : exploitation de buffer overflow, déchiffrement RSA custom, et bypass d’UAC par DLL hijacking.
  - 🛰️ **IMSI Catcher**  
    Conception d’un simulateur d’IMSI-catcher, reverse-engineering de firmwares radio, et présentation technique de la détection et mitigation des faux relais cellulaires.
  - ⚖️ **SSI Groupama**  
    Audit de la plateforme SWIFT, revue de conformité DORA, application de la méthode EBIOS RM pour identification et réduction des risques critiques.
</details>

<details>
  <summary style="font-size:1.1rem; font-weight:bold; cursor:pointer;">
    ☁️ Cloud & Infra DevOps
  </summary>
  
  - 📡 **DBCluster**  
    Déploiement d’un cluster MySQL haute-disponibilité sur AWS (EC2 + RDS), configuration de ProxySQL et d’une API de gestion, avec scripts Terraform et playbooks Ansible.
  - 🔄 **MapReduce Social Graph**  
    Implémentation d’une pipeline MapReduce sur EMR pour analyser des datasets Twitter : détection de communautés, calcul de centralité, et visualisation réseau interactive.
  - 🌐 **WiFi Roaming Mesh**  
    Mise en place d’un réseau mesh OpenWrt + FreeRadius, configuration WPA2-Enterprise, automatisation du provisioning de nouveaux nœuds via Docker et scripts shell.
</details>

<details>
  <summary style="font-size:1.1rem; font-weight:bold; cursor:pointer;">
    📈 Actuariat & Risk Modelling
  </summary>
  
  - 🌪️ **SCOR Internal Model**  
    Développement d’un modèle hybride ALM/DLM pour estimation de pertes liées aux ouragans aux USA. Back-testing sur données NOAA, simulation Monte-Carlo, KPI Solvabilité II.
  - 🤖 **Cyber CAT Models**  
    Élaboration de scénarios de sinistres cyber : collecte de données breach, calibration de distributions de perte, et dashboard interactif en Dash/Plotly.
  - 🌐 **Bayesian Statistics**  
    Modélisation bayésienne de durée de vie d’équipements industriels, construction de priors adaptés, estimation par MCMC (PyMC3) et comparaison avec maximum de vraisemblance.
  - 🏘️ **Real-Estate Prediction**  
    Projet XGBoost sur base DVF pour prédire les prix immobiliers : feature engineering géospatial, validation croisée temporelle, et exposé des performances via Streamlit.
</details>

<details>
  <summary style="font-size:1.1rem; font-weight:bold; cursor:pointer;">
    🤖 IoT & Prototypage
  </summary>
  
  - 🌍 **IoT_Telecom**  
    Plateforme Dockerisée de collecte et traitement de données capteurs (MQTT + InfluxDB + Grafana), dashboard temps réel et alerting via Webhooks.
  - 🧭 **Indoor Localisation**  
    Solution Bluetooth fingerprinting : calibration de map de signaux, algorithme K-NN et SVM, précision <2 m en environnement de bureau.
  - 🎉 **SMARTIES**  
    Infrastructure API + capteurs pour soirées connectées : interactions mobiles via WebSocket, automatisation d’effets lumières et son synchronisés.
</details>

---

## 🛠️ TECH STACK

```yaml
languages: [Python, C, Java, Kotlin, JavaScript, HTML/CSS, PHP]
cloud:     [AWS, Terraform, Docker, Ansible, Azure Databricks]
secops:    [EBIOS RM, Threat Modeling, Cryptography, CTF]
ml/data:   [pandas, XGBoost, PyMC3, Dash/Plotly]
network:   [OpenWrt, FreeRadius, Linux, Bash]
```
