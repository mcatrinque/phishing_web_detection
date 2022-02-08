# Phishing Website Detection

## Sobre o Projeto
A proposta busca analisar uma lista de URLs contida em um dataset fornecido por um desafio proposto no [Kaggle](https://www.kaggle.com/dnyaneshsatpute/phishing-webiste-detection/notebook) em busca de modelos eficientes para a detecção de phishing, a partir de aprendizado supervisionado, 
fazendo uso de features contendo informações que podem constituir possíveis indícios de que o site não se trata de um 
ambiente seguro.

Ao verificar os trabalhos anteriores relativos ao dataset alvo, foram identificados como principais métodos de aprendizado
de máquina utilizados:
- Regressão Logística 
- Random Forest
- K-Nearet Neighbors  
- Árvore de decisão

Com esse projeto, pretende-se avaliar os modelos com melhor desempenho a partir dos trabalhos anteriores, buscando atingir 
resultados similares de classificação, a partir de um menor conjunto de features.  Os atributos serão analisados a partir
dos valores obtidos para a correlação de Pearson, entre a coluna Result e as demais features.

Os modelos serão avaliados a partir dos resultados de acurácia obtidos a partir do treino e teste utilizando todo o conjunto
de features, e também, a partir de um subconjunto dessas features, selecionando apenas as que possuem maior correlação com 
a coluna Result.

A partir dessas execuções, será avaliado os resultados de acurácia obtidos para os casos propostos em busca de se mensurar
se é possível obter resultados de grau de precisão próximo ao obtido com todo o conjunto, apenas utilizando features de maior
correlação.
