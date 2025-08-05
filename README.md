# 📊 Projeto Telecom X – Previsão de Evasão de Clientes

Bem-vindo ao projeto **Algar Telecom X – Parte 2**, onde aplicamos técnicas de ciência de dados e machine learning para prever a evasão de clientes (churn) em uma empresa de telecomunicações fictícia. 🚀

---

## 🎯 Objetivo

Antecipar a evasão de clientes por meio de modelos preditivos, ajudando a empresa a tomar decisões estratégicas e implementar ações de retenção.

---

## 🧪 Etapas do Projeto

### ✅ 1. Pré-processamento dos Dados
- Remoção de colunas irrelevantes
- Exclusão de valores nulos
- Encoding de variáveis categóricas com `pd.get_dummies()`
- Aplicação de balanceamento com `class_weight='balanced'` e `SMOTE`

### ✅ 2. Análise Exploratória de Dados (EDA)
- Análise de distribuição da variável alvo
- Visualizações em português 🇧🇷
- Matriz de correlação
- Gráficos de boxplot e dispersão para variáveis como tempo de contrato e total gasto

### ✅ 3. Modelagem

Foram aplicados dois modelos de machine learning:

| Modelo               | Normalização | Recall (Churn) | F1-score (Churn) |
|----------------------|--------------|----------------|------------------|
| 🌳 Árvore de Decisão    | ❌ Não        | 49%            | 49%              |
| 📈 Regressão Logística  | ✅ Sim        | **80%**        | **62%**          |

✔️ A Regressão Logística teve melhor desempenho na detecção de churn, mesmo com mais falsos positivos.

### ✅ 4. Interpretação dos Resultados
- Análise de importância das variáveis (Feature Importance)
- Variáveis mais relevantes: tempo de contrato, mensalidade, total gasto, tipo de contrato e internet fibra óptica

---

## 📌 Justificativa Técnica

> “O modelo de Regressão Logística conseguiu identificar 80% dos clientes que realmente evadem, com um custo de 49% de falsos positivos. Considerando o objetivo do negócio — prevenir a evasão —, essa troca pode ser aceitável dependendo da capacidade de atendimento da equipe de retenção.”

---

## 💡 Conclusão Estratégica

A solução desenvolvida permite à empresa agir de forma preventiva, com foco nos clientes que apresentam maior risco de evasão.  
Isso potencializa os esforços da equipe de retenção e contribui para a sustentabilidade do negócio.

---

## 🧰 Tecnologias Utilizadas

- Python 🐍  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter / Google Colab  

---

## 🙏 Agradecimentos

Obrigada por acompanhar este projeto!  
Foi uma jornada de muito aprendizado e evolução. Que este trabalho possa inspirar novas ideias e soluções dentro e fora da área de dados.

---

**Desenvolvido com 💙 por Vitoria**
