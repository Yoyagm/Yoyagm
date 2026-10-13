# Johan David Rodriguez Castro

Final-semester Systems & Software Engineering student (UPB, Colombia) · ML model training & evaluation · cybersecurity · C2 English · open to remote roles

[Portfolio](https://johanrodriguez.is-a.dev) · [LinkedIn](https://www.linkedin.com/in/johan-rodriguez-97bb29323/) · [Email](mailto:johan.rc2020@gmail.com)

Estudiante de último semestre de Ingeniería de Sistemas y Software (UPB Bucaramanga; fin de carrera previsto en 2026) · [Portafolio en español](https://johanrodriguez.is-a.dev/es)

## What I build and measure

| Project | What it is | Measured result | Links |
|---|---|---|---|
| **[Phishing URL Detector](https://github.com/Yoyagm/phishing-url-detector)** | Explainable phishing detection that first measures how broken the benchmark is: two label leaks in PhiUSIIL, an honest baseline and exact TreeSHAP in the browser. | **70.5 %** recall at a 1 % false-positive rate against phishing submitted two years after the training data | [Demo](https://yoyagm.github.io/phishing-url-detector/) · [Report](https://github.com/Yoyagm/phishing-url-detector/blob/main/paper/report.pdf) |
| **[Small Neural Models vs LightGBM (phishing)](https://github.com/Yoyagm/phishing-url-small-models)** | Do small neural models beat LightGBM at detecting phishing from a host name when the evaluation cannot be gamed? Same leak-free protocol, three seeds, confidence intervals and the result as it came out. | **71.1 % vs 70.5 %** recall at a 1 % false-positive rate out-of-distribution and temporal: fine-tuned DistilBERT ties LightGBM; the char-CNN (59.9 %) loses and the BiGRU (68.3 %) does not beat it | — |
| **[Vulnerability Prioritization Dashboard](https://github.com/Yoyagm/vuln-prioritization-dashboard)** | Which vulnerability do you patch first? CISA KEV + EPSS + NVD, and a measurement showing that the EPSS advantage everyone quotes is mostly evaluation artefact. | **6.1× → 0.5–0.7×** the EPSS advantage over CVSS as usually measured (80 % coverage with 22,736 CVEs instead of 137,952) versus measured with frozen scores and only later exploitation counted | — |
| **[SlopGuard](https://github.com/Yoyagm/slopguard)** | Pre-install supply-chain guard that catches hallucinated, typosquatted and known-malicious dependencies before any code runs, with zero runtime dependencies. | **5** detection layers (existence and age, typosquatting, metadata, OSV.dev threat intel and an opt-in language-model layer that can never block on its own) | — |
| **[GOATGuard](https://github.com/Yoyagm/goatguard-app)** | Flutter mobile client for a team-built network-monitoring platform (Integrative Project III, UPB), with full TOTP 2FA. | **19 of 25** of the client repository's commits are Johan's (the backend and agent were written by a teammate) | — |
| **[AWS High-Availability Infrastructure](https://github.com/Yoyagm/eval-final-dgiti)** | Three-tier architecture across two availability zones, codified in Terraform and deployed with GitHub Actions; final assessment for a UPB course. | **2** availability zones; the Auto Scaling Group keeps at least 2 instances | — |
| **[Portafolio](https://github.com/Yoyagm/portafolio)** | Bilingual portfolio (Next.js) with six security and applied-ML case studies, each with its evidence. | **6** case studies with each feature's status declared (implemented, demo or simulated) | [Demo](https://johanrodriguez.is-a.dev) |

## Currently (Oct 2026)

- Endpoint Security (Cisco Networking Academy)
- Network Defense (Cisco Networking Academy)
- Cyber Threat Management (Cisco Networking Academy)

## Credentials

18 credentials, listed with their issuers in [the portfolio](https://johanrodriguez.is-a.dev/en#experience).

## Stack (backed by the repos above)

- **Security:** Cybersecurity
- **ML & AI:** Machine learning, Model training and evaluation, TensorFlow / Keras, AI agents (smolagents, CrewAI) and MCP, scikit-learn
- **Languages:** Python, SQL, TypeScript / JavaScript, Dart / Flutter
- **Backend & data:** pandas and NumPy
- **DevSecOps:** Git and GitHub
- **Frontend:** Next.js and React

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Yoyagm/Yoyagm/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Yoyagm/Yoyagm/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/Yoyagm/Yoyagm/output/github-snake-dark.svg" />
</picture>
