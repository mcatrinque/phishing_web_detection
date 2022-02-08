# Phishing Website Detection

A proposta busca analisar as URLs dentro do dataset Phishing website dataset em busca de um modelo para a detecção de phishing, 
a partir de critérios elencados como possíveis indícios de que o site não se trata de um ambiente seguro. Para se saber se uma 
URL é phishing ou não, será utilizada a variável Result. 

Ao verificar os trabalhos anteriores relativos ao dataset alvo, foram identificados como principais métodos utilizados a 
regressão logística, o SVM, os KNN e a árvore de decisão, utilizando como critério de validação a acurácia. 

Com esse projeto, pretende-se avaliar os modelos com melhor desempenho a partir dos trabalhos anteriores, buscando atingir 
resultados similares ou superiores com o uso de um menor conjunto de “features”, elegendo os atributos a serem explorados 
através da matriz de correlação.

Baseado no dataset fornecido por um desafio proposto no [Kaggle](https://www.kaggle.com/dnyaneshsatpute/phishing-webiste-detection/notebook)
