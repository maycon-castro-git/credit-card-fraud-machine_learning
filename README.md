# 💳 Credit Card Fraud Detection (Detecção de Fraude / Detección de Fraude)

<p align="center">
  <a href="#português">🇧🇷 Português</a> • 
  <a href="#english">🇺🇸 English</a> • 
  <a href="#español">🇪🇸 Español</a>
</p>

---

## <a name="português"></a>🇧🇷 Português
Projeto de Data Science focado na detecção de transações fraudulentas em cartões de crédito. O objetivo é desenvolver um classificador capaz de identificar atividades fraudulentas em um conjunto de dados altamente desbalanceado, otimizando o equilíbrio entre segurança (Recall) e experiência do usuário (Precisão).

## <a name="english"></a>🇺🇸 English
Data Science project focused on detecting fraudulent credit card transactions. The goal is to develop a classifier to identify fraudulent activities within a highly imbalanced dataset, optimizing the balance between security (Recall) and user experience (Precision).

## <a name="español"></a>🇪🇸 Español
Proyecto de Data Science enfocado en la detección de transacciones fraudulentas en tarjetas de crédito. El objetivo es desarrollar un clasificador capaz de identificar actividades fraudulentas dentro de un conjunto de datos altamente desequilibrado, optimizando el equilibrio entre seguridad (Recall) y experiencia del usuario (Precisión).

---

## 🚀 Tecnologias Utilizadas / Tech Stack
* **Python** (Pandas, Numpy, Scikit-Learn)
* **Imbalanced-learn** (SMOTE)
* **Visualização:** Matplotlib, Seaborn
* **Modelagem:** Logistic Regression, GridSearchCV

## 📊 Principais Desafios / Key Challenges
* **Desbalanceamento Severo:** Apenas 0.17% das transações são fraudes.[cite: 1]
* **Prevenção de Data Leakage:** Implementação de pipelines para assegurar que o SMOTE fosse aplicado corretamente apenas nos dados de treino.[cite: 1]
* **Métricas de Negócio:** Equilíbrio entre a captura de fraudes e a redução de bloqueios indevidos de clientes legítimos.[cite: 1]

## 📈 Resultados / Results
| Métrica | Valor Final |
| :--- | :--- |
| **Recall (Classe 1)** | 91% |
| **Precisão (Classe 1)** | 23% |
| **Acurácia Geral** | 99% |

## 🧠 Lições Aprendidas / Lessons Learned
**PT:** Aprendi que, em detecção de fraude, a acurácia pode ser uma métrica enganosa ("norte falso"). O valor real está em ajustar o modelo para encontrar o equilíbrio ideal entre segurança e usabilidade.
**EN:** I learned that in fraud detection, accuracy can be a misleading metric ("false north"). The real value lies in tuning the model to find the ideal balance between security and usability.
**ES:** Aprendí que, en la detección de fraudes, la precisión puede ser una métrica engañosa ("norte falso"). El valor real radica en ajustar el modelo para encontrar el equilibrio ideal entre seguridad y usabilidad.

---

## 📂 Como executar / How to run
1. Clone este repositório.
2. Abra o arquivo `Analise_de_Fraude_de_Cartao_de_Credito.ipynb` no Google Colab.
3. Carregue o arquivo `creditcard.csv` no ambiente.

---
**Analista:** Maycon Castro  
[www.linkedin.com/in/maycon-castro] | [(https://maycon-castro-git.github.io/portfolio-maycon-castro/)]
