<h2 align="center">👋 Olá, eu sou o João!</h2>

<p align="center">
  💼 Analista de TI Júnior &nbsp;|&nbsp; ☁️ Cloud & Automação &nbsp;|&nbsp; 🤖 IA & Machine Learning
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=9B59F7&center=true&vCenter=true&width=500&lines=Analista+de+TI+%7C+MLOps+%7C+Cloud;Python+%2B+Azure+%2B+Machine+Learning;Do+dado+bruto+ao+modelo+em+produ%C3%A7%C3%A3o+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

---

### 📌 Sobre mim

Atuo como **Analista de TI Júnior na Brainvest Wealth Management**, com foco em automação de processos, segurança, cloud e desenvolvimento. Tenho experiência com soluções Microsoft, Python e Azure, além de ferramentas voltadas à integração e infraestrutura como código.

Atualmente cursando **Pós-graduação em Engenharia de Machine Learning (FIAP)**, onde desenvolvo soluções de ML end-to-end — da análise exploratória ao deploy em produção.

🎯 Meu objetivo é evoluir continuamente, aplicando tecnologia de forma estratégica, escalável e orientada a resultados.

📩 Contato: **jvbelletati@gmail.com**

---

### 🚀 Projetos em Destaque

#### 🤖 [Pipeline ML — Previsão de Churn em Telecomunicações](https://github.com/ML-PosTechFiap/ML-Fiap-Step1)
> Tech Challenge · Pós-graduação em Machine Learning Engineering (FIAP)

Pipeline completo de Machine Learning para prever cancelamento de clientes em uma operadora de telecomunicações, cobrindo todas as etapas do ciclo de vida do modelo.

**Principais entregas:**
- Análise exploratória e pré-processamento do dataset Telco Customer Churn (IBM)
- Treinamento e comparação de **12 modelos** (11 Scikit-Learn + Rede Neural MLP com PyTorch), avaliados por 5 métricas simultâneas: ROC-AUC, PR-AUC, Recall, F1 e custo de negócio
- Modelo vencedor: **Gradient Boosting** (ROC-AUC: 0,843 · Accuracy: 0,810)
- Análise de threshold ótimo via custo de negócio — a Regressão Logística minimizou perdas reais em **R$ 48.880**, superando o melhor modelo estatístico em valor de negócio
- **API REST em produção** no Railway com monitoramento via Prometheus + Grafana e detecção de drift ativa
- Model Card completo com limitações, vieses e critérios de retreinamento

`Python` `PyTorch` `Scikit-Learn` `Docker` `Railway` `MLflow` `Prometheus` `Grafana` `pytest`

#### 🏦 [Fintech MLOps — Pipeline de Predição de Churn](https://github.com/JvBelletati/fintech-mlops)
> Projeto de Portfólio · Pós-graduação em Machine Learning Engineering (FIAP)

[![CI/CD](https://github.com/jvbelletati/fintech-mlops/actions/workflows/ci.yml/badge.svg)](https://github.com/jvbelletati/fintech-mlops/actions/workflows/ci.yml) [![Drift Check](https://github.com/jvbelletati/fintech-mlops/actions/workflows/drift-check.yml/badge.svg)](https://github.com/jvbelletati/fintech-mlops/actions/workflows/drift-check.yml)

Pipeline MLOps **end-to-end** para prever evasão de clientes de uma fintech fictícia, atendendo a requisitos reais de governança, performance e excelência operacional.

**Principais entregas:**
- Pipeline de treino com **scikit-learn + MLflow tracking**, versionamento de dados com **DVC**
- **Governança com Fairlearn**: auditoria de fairness por gênero e UF — gate bloqueia registro do modelo se disparidades excederem threshold
- **Model Card** auto-gerado com métricas por grupo demográfico, limitações e critérios de retreinamento
- **API FastAPI** containerizada com Docker multi-stage (~400MB), com logging assíncrono via `BackgroundTask`
- **CI/CD com GitHub Actions**: lint + 43 testes unitários + treino + gate de governança em cada push
- Detecção de drift com **KS test + chi-square** e workflow diário com retreino automático em cascata

`Python` `FastAPI` `Scikit-Learn` `MLflow` `DVC` `Fairlearn` `Docker` `GitHub Actions` `pytest`

---

### 🏅 Certificações

📚 **Microsoft Certified: Azure AI Fundamentals (AI-900)**

<p align="center">
  <a href="https://www.credly.com/badges/007b579a-eed9-4cb1-9feb-f09370eb3ee6/public_url" target="_blank">
    <img width="120" src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" alt="AI-900 Badge"/>
  </a>
</p>

---

### 🐍 Contribuições devorando o histórico

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JvBelletati/JvBelletati/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JvBelletati/JvBelletati/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/JvBelletati/JvBelletati/output/github-snake.svg" />
</picture>

---

### 📊 Estatísticas do GitHub

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=JvBelletati&theme=radical&show_icons=true&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JvBelletati&layout=compact&theme=radical&hide_border=true&langs_count=8" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=JvBelletati&theme=radical&hide_border=true&locale=pt_BR&date_format=j%20M%5B%20Y%5D" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=JvBelletati&color=blueviolet&style=for-the-badge&label=VISITAS+AO+PERFIL" alt="Profile views" />
</div>

---

### 🧠 Tecnologias e Ferramentas

<p align="center">
  <img title="Python" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  <img title="PyTorch" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" />
  <img title="JavaScript" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
  <img title="React" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  <img title="HTML5" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
  <img title="CSS3" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" />
  <img title="Microsoft Azure" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" />
  <img title="Docker" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
  <img title="Terraform" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" />
  <img title="PowerShell" height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/powershell/powershell-original.svg" />
  <img title="n8n" height="36" alt="n8n" src="https://github.com/n8n-io/n8n/raw/master/assets/n8n-logo.png" />
</p>

---

### 🌐 Conecte-se comigo

<p align="center">
  <a href="https://www.linkedin.com/in/JvBelletati" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://instagram.com/jvbelletati" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>
  <a href="mailto:jvbelletati@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>
