## Mini projeto Santander Coders 2023 | 2º Semestre - DS

Buenas! Esse é um mini projeto feito para o módulo Lógica de Programação II (Py) do curso em parceria da Ada Tech com o Santander.

## Objetivo do projeto

O objetivo aqui era o de implementar o modelo supervisionado de Machine Learning [K-Nearest Neighbors (KNN)](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm), para classificação e/ou rotulação de dados. Não era permitida a utilização de nenhuma biblioteca nem nenhum módulo externo do Python para a sua implementação.

## Proposta de problema

Estimar o perfil de investimento de clientes utilizando o algoritmo implementado do KNN. Os dados utilizados são referentes ao cadastro de clientes de uma empresa de investimentos com suas respectivas carteira de investimentos, que indica se esse cliente tem o perfil de investidor **Conservador**, **Moderado** ou **Agressivo**. O intuito do projeto é, a partir do investimento de alguns clientes que já tem um perfil definido, estimar esse perfil para aqueles que ainda não estão classificado, afim de oferecer novos produtos que sejam mais adequados a eles.  
Os dados utilizados (presentes no primeiro bloco do Jupyter Notebook) seguem o seguinte padrão:

[**CPF**: INT, **Perfil Do Investidor**: STRING, **Carteira de Investimento**: TUPLA]

## Algoritmo: passo-a-passo sugerido

- Passo 1: Definir um valor para K (número de vizinhos utilizados para fazer a estimativa);
- Passo 2: Definir os K vizinhos mais próximos do ponto a ser classificado de acordo com uma função de distância (aqui foi utilizada a [distância Euclidiana](https://pt.wikipedia.org/wiki/Dist%C3%A2ncia_euclidiana));
- Passo 3: 
    - Se for um problema de **regressão**: calcular a **média** de todos os vizinhos;
    - Se for um problema de **classificação**: calcular a **moda** de todos os vizinho (*modelo implementado*)

