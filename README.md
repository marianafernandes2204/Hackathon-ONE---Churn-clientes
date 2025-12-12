# 🎧 Hackathon ONE II — Modelo de Churn (Spotify)

Este projeto desenvolve um modelo de Machine Learning para prever churn de usuários do Spotify, utilizando um pipeline completo de preparação de dados, treinamento, avaliação e exportação para produção nos formatos PKL e ONNX.

---

## 🚀 Tecnologias Utilizadas
- Python 3  
- Scikit-Learn  
- Pandas / NumPy  
- Imbalanced-Learn (SMOTE)  
- ONNX / ONNX Runtime  
- Joblib  
- skl2onnx  

---

## 📌 Objetivo
Criar um modelo capaz de prever se um usuário abandonará o serviço.  
O modelo é otimizado para ser integrado a um backend via inferência ONNX.

---

## 🧠 Pipeline de Treinamento
- Tratamento de dados nulos  
- Normalização de variáveis numéricas  
- One-Hot Encoding para variáveis categóricas  
- Balanceamento da base com SMOTE  
- Treinamento com Random Forest  
- Avaliação por Accuracy e F1-Score  

---

## 📂 Arquivos Gerados
| Arquivo | Finalidade |
|--------|------------|
| `modelo_churn.pkl` | Modelo no formato Sklearn |
| `modelo_hackathon.onnx` | Modelo convertido para produção |
| `metadata.json` | Metadados do modelo e schema de features |

---

## ▶️ Como Executar
Instale as dependências:
```bash
pip install -r requirements.txt
