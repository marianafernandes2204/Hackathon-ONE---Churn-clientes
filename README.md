<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Spotify_logo_with_text.svg" width="250">
</p>
<h1 align="center">Projeto ChurnInsight – Spotify Dataset</h1>
<h2 font color=gree, align="center">🌟 Hackathon ONE II </h2>

## 📌 Visão Geral

O **Churn Insight** é um projeto desenvolvido no contexto do **Hackathon ONE II**, com o objetivo de criar uma solução baseada em **Data Science e Machine Learning** para **prever a probabilidade de cancelamento (churn)** de clientes em serviços por assinatura.

O projeto simula um cenário real de negócio aplicado a plataformas de streaming, como o **Spotify**, permitindo que empresas atuem de forma **proativa na retenção de clientes**, reduzindo perdas financeiras e aumentando o **Customer Lifetime Value (CLV)**.

---

## 🎯 Problema de Negócio

Empresas que operam sob o modelo de assinatura enfrentam desafios constantes relacionados ao churn, impactando diretamente receita, crescimento e sustentabilidade do negócio.

Antecipar clientes com maior risco de cancelamento possibilita:

- Priorizar ações estratégicas de retenção  
- Criar campanhas personalizadas e direcionadas  
- Reduzir custos com aquisição de novos clientes  

---

## 💡 Solução Proposta

Foi desenvolvido um **modelo preditivo de classificação binária**, capaz de indicar se um cliente possui **alta ou baixa probabilidade de cancelar** o serviço.

A solução contempla um pipeline completo de Data Science:

- Análise exploratória dos dados (EDA)  
- Engenharia de atributos (*feature engineering*)  
- Treinamento de modelos supervisionados  
- Avaliação com métricas adequadas ao problema de churn  
- Serialização e preparação do modelo para integração com backend  

---

## 📊 Dataset Utilizado

- **Fonte:** Kaggle  
- **Nome:** Spotify Dataset for Churn Analysis  
- **Variável alvo:** `is_churned`  
  - `0` → Cliente ativo  
  - `1` → Cliente cancelou  

🔗 [Acessar Dataset CSV](https://github.com/aluizr/Hackathon-ONE---Churn-clientes/blob/main/spotify_churn_dataset.csv)

---

## 🧠 Modelagem e Avaliação

Os modelos de Machine Learning foram implementados utilizando **scikit-learn**, incluindo:

- Regressão Logística  
- Random Forest  
- *(Arquitetura preparada para inclusão de novos modelos)*  

O **Random Forest** foi selecionado como modelo final por apresentar o melhor equilíbrio entre **accuracy**, **precision**, **recall** e **F1-score**, métricas críticas em cenários de churn, onde a redução de falsos negativos é essencial.

---

## 🛠️ Stack Tecnológico

### Linguagens & Ambiente
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="36"/>&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg" width="36"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kaggle/kaggle-original.svg" width="36"/>
</p>

### Data Science & Machine Learning
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="36"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="36"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="36"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="36"/>&nbsp;
  <img src="https://raw.githubusercontent.com/mwaskom/seaborn/master/doc/_static/logo-wide-lightbg.svg" width="60"/>&nbsp;
  <img src="https://joblib.readthedocs.io/en/latest/_static/joblib_logo.svg" width="36"/>&nbsp;
  <img src="https://cdn.simpleicons.org/onnx" width="36"/>&nbsp;
  <img src="https://raw.githubusercontent.com/microsoft/onnxruntime/main/docs/images/ONNX_Runtime_icon.png" width="36"/>
</p>

### Backend
<p align="left">
  <img src="https://cdn.simpleicons.org/springboot" width="36"/>&nbsp;
  <img src="https://cdn.simpleicons.org/springsecurity" width="36"/>&nbsp;
  <img src="https://cdn.simpleicons.org/spring" width="36"/>&nbsp;
  <img src="https://cdn.simpleicons.org/flyway" width="36"/>&nbsp;
  <img src="https://img.shields.io/badge/Java-Lombok-EA1E2D?style=flat-square&logo=java&logoColor=white"/>
</p>

### Banco de Dados
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="36"/>
</p>

### Testes
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/junit/junit-original.svg" width="36"/>
</p>

### Versionamento
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="36"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="36"/>
</p>

---

##  ⚠️ Limitações do Estudo
- Dataset sintético
- Ausência de histórico temporal
- Variáveis comportamentais agregadas

---

## 📦 Próximos Passos

- Integração completa com API REST  
- Implementação do endpoint `/predict`  
- Persistência das previsões no banco de dados  
- Desenvolvimento de dashboard para visualização do risco de churn  

---

## 👥 Equipe do Projeto – Hackathon ONE II

### **Time Bank-End**
- Ezandro Bueno  &nbsp;<a href="https://github.com/ezbueno"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
&nbsp; | &nbsp;<a href="https://www.linkedin.com/in/ezandro-bueno-776aab192/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

- Jorge Filipi Dias  &nbsp;<a href="https://github.com/JorgeFilipi"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/jfdias/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

- Wanderson Souza  &nbsp;<a href="https://github.com/wandersonjafe"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/wandersonjafe/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

- Wendell Dorta  &nbsp;<a href="https://github.com/Wendell-Dorta"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/wendell-dorta/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

### **TIme Data Science**
- André Ribeiro  &nbsp;<a href="https://github.com/aluizr"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/andreluizr/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

- Kelly Muehlmann  &nbsp;<a href="https://github.com/KellyMuehlmann"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/kelly-muehlmann-43b9962b3/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

- Luiz Alves  &nbsp;<a href="https://github.com/marianafernandes2204"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/lfall/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>
  
- Mariana Fernandes  &nbsp;<a href="https://github.com/marianafernandes2204"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="18"/></a>
  &nbsp; | &nbsp;<a href="https://www.linkedin.com/in/mariana-fernandes-0a93a71b5/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="18"/></a>

---

## 🔄 Status do Projeto

🚧 **MVP funcional em desenvolvimento**, evoluído durante o Hackathon ONE II.

---

