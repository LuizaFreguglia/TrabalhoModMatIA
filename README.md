# TrabalhoModMatIA

🛢️ Análise de Dados de Poços de Petróleo com Aprendizado de Máquina

Este repositório contém o projeto desenvolvido para prever a densidade de formações geológicas em poços de petróleo utilizando técnicas de aprendizado de máquina supervisionado. O estudo visa comparar os resultados obtidos por modelos computacionais com a tradicional equação de Gardner, buscando avaliar a eficácia de abordagens baseadas em dados.

---

### 🔍 Objetivos

• Realizar a análise exploratória (EDA) dos dados de 10 poços  
• Aplicar técnicas de limpeza e pré-processamento, incluindo a remoção de outliers com auxílio do boxplot  
• Aplicar métodos estatísticos para compreender a relação entre variáveis, como a correlação de Spearman  
• Reduzir a dimensionalidade dos dados por meio da Análise de Componentes Principais (PCA)  
• Selecionar os atributos mais relevantes utilizando o método LASSO  
• Treinar e comparar modelos supervisionados de regressão:  
  • Regressão por Vetores de Suporte (SVR)  
  • Árvore de Decisão (AD)  
  • Rede Neural Artificial (RNA)  
• Avaliar o desempenho dos modelos com base nas métricas R² e MSE  
• Comparar os resultados obtidos com a equação empírica de Gardner  
• Verificar a robustez e a aplicabilidade dos modelos em contextos geologicamente consistentes

---

### 🧰 Tecnologias Utilizadas

• **Linguagem de Programação**: Python  
• **Ambiente de Desenvolvimento**: Google Colab  

• **Manipulação e Análise de Dados**:  
  • `pandas` – leitura e organização dos dados  
  • `numpy` – operações numéricas  

• **Visualização de Dados**:  
  • `matplotlib.pyplot` – geração de gráficos básicos  
  • `seaborn` – gráficos estatísticos e boxplots  

• **Análise Estatística e Redução de Dimensionalidade**:  
  • `scipy.stats` – correlação de Spearman  
  • `prince` – Análise de Componentes Principais (PCA)  
  • `sklearn.decomposition.PCA` – redução de dimensionalidade  
  • `sklearn.linear_model.LassoCV` – seleção de variáveis com Lasso  

• **Detecção de Outliers**:  
  • `sklearn.covariance.EllipticEnvelope` – remoção de valores extremos  

• **Modelagem de Regressão Supervisionada**:  
  • `sklearn.svm.SVR` – Regressão por Vetores de Suporte  
  • `sklearn.tree.DecisionTreeRegressor` – Árvore de Decisão  
  • `sklearn.neural_network.MLPRegressor` – Rede Neural Artificial  

• **Avaliação dos Modelos**:  
  • `sklearn.metrics` – cálculo de R² e MSE

👥 Equipe

Aline Souza do Vale Lessa Ribeiro
Luiza Freguglia Guedes S da Silva
Maria Fernanda Silva Piccolo
