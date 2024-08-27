# Segmentação de Perfís de Clientes e Classificação

## 🎯 Objetivo 
Este projeto tem como objetivo segmentar grupos de clientes com perfís diferentes com auxilio de algoritmo de clusterização, e com o auxilio de algoritmos de classificação conseguir prever se uma um novo cliente pertencerá ao grupo alvo desejado.

## 📜 Como utilizar
**O projeto foi divido em 4 etapas, apresento a sequência correta para vizualizar:**

- **1.Analise_exploratoria -** É a primeira etapa e onde analisamos os dados, suas distribuições e sua formatação, geramos alguns insights prévios sobre os dados e analisamos as correlações das variáveis e limpamos os dados para posteirmente aplicarmos modelos de Machine Learning.

- **2.Clusterizacao -** Aqui aplicamos o algoritmo de K-Means, um método bastante conhecido e utilizado responsável por agrupamento de dados com base na distância entre seus centros. Para melhorar o desempenho do algoritmo fazemos usos de lgun putros métodos estatísticos como o Método de Cotovelo para nos ajudar a encontrar o melhor valor de grupos para passar ao algoritmo, fazemos a análise dos grupos segmentados e definimos o grupo algo para a próxima etapa que é criar um modelo de classificação.
  
- **3.Classificacao -** Nesta etapa o objetivo é criar um modelo cllassificador capaz de predizer a probabilidade de um novo cliente pertencer ao grupo algo que escolhemos para o projeto, aqui utilizamos alguns algoritmos bastante utilizados como SVM (Support Vector Machines), Regressão Logística e Árvores de Decisão. Após comparar os modelos escolhemos o que possuir melhor resultado para nosso projeto. Também utilizamos de métricas estatísticas para medir os desempenhos de cada modelo, e utilizamos tecnologias como GridSearchCV para ajudar a escolher melhores hiperparâmetros, Validação Cruzada para garantir que o modelo seja responsivo com a entrada de dados nmovos, Matriz de confusão para medir a taxa de acertos do modello treinado com o valor previsto.
  
- **Relatorio -** Aqui apresento um relatório detalhado e todos os insights obtidos neste projeto, apresento de forma convincente bons resultados, possíveis tomadas de decisões para o time de negócio e uma conclusão geral sobre o estudo.

## ✔️ Conclusão
- Os dados já vieram previamente pré-processados pois é um dataset fictício disponibilizado no site do Kaggle, tivemos que fazer poucas alterações nos dados e dar uma checagem rápida se há valores nulos, duplicados, formatação correta etc. 

- Na etapa de Análise Exploratória tivemos alguns Insights: A presença de outliers em algumas colunas, proporção de classes assimétricas em algumas variáveis.

- Em clusterização utilizamos o algoritmo de K-Means pois é funcional para os nossos tipos de dados, é um modelo bastante confiável e que exige um processamento computacional baixo, algo que reduz o tempo e o gasto do nosso projeto.

- Dentre os algoritmos de classificação previamente testados, o de Árvores de Decisão apresntou o melhor desempenho, portanto foi o escolhido para este projeto.

## 🙇 Altor
Olá! Meu nome é Diego Armando Teles de Carvalho, sou ciêntista de dados, apaixonado por tecnologias e transoformar dados em insights valiosos. Confira meu perfil no [Linkedin](https://www.linkedin.com/in/diegoarmandods/) e meus outros trabalhos no [GitHub](https://github.com/DieGod69).