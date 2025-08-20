# Challenge_Telecom_X_Alura_Pt2
Objetivo: Prever a evasão de clientes utilizando três modelos de Machine Learning.
Modelos avaliados: Regressão Logística, KNN e Árvore de Decisão.

Tecnologias e Bibliotecas Utilizadas:
- Python
- Jypiter Notebook
- Pandas e Numpy (manipulação de dados)  
- Scikit-learn (modelos de Machine Learning e métricas)  
- Matplotlib, Plotly e Seaborn (visualização de dados) 

Principais resultados:

A Regressão Logística apresentou a melhor acurácia geral (79,8%), equilibrando precisão e recall.
O KNN teve o pior desempenho (75,6% de acurácia) e não é recomendado para este problema.
A Árvore de Decisão teve o melhor desempenho para detectar clientes que saem (Recall de 57,2% e F1-score de 59,7%), o que a torna mais útil em estratégias de retenção.

Conclusão: Para esse caso de uso, recomenda-se a utilização da Árvore de Decisão, já que detectar clientes em risco é mais valioso para o negócio do que apenas ter maior acurácia geral. Entretanto, a Regressão Logística também é uma boa alternativa caso se busque mais interpretabilidade e estabilidade do modelo.
