### Santander Coders 2023 | 2º semestre - DS (Turma #1114)

### **Dupla:** Mariana Cassundé, Suzielli Mendonça

### **Projeto**  
Banco de Dados I   
Análise Descritiva do Conjunto de Dados do Titanic

---

[Link para o conjunto de dados](https://www.kaggle.com/datasets/brendan45774/test-file)   

### **Sobre o conjunto de dados:**    
O Titanic foi um navio britânico de passageiros que afundou após colidir com um iceberg durante sua viagem inaugural de Southampton para Nova York. Muitos apssageiros morreram por conta desta colisão, tornando-o um dos desastres marítimos mais mortais em tempos de paz na história.

Conjuntos de dados sobre o Titanic são frequentemente usados em competições de ciência de dados e machine learning, especialmente para iniciantes, como um exercício para praticar habilidades de limpeza de dados, análise exploratória e modelagem preditiva.  

O conjunto de dados utilizado para [essa análise](https://www.kaggle.com/datasets/brendan45774/test-file) é uma combinação do arquivo de teste originalmente usado na competição do Titanic no Kaggle e o arquivo de submissão de gênero, que juntos fornecem informações sobre os passageiros, incluindo se eles sobreviveram ou não ao desastre. O arquivo .csv foi criado por um usuário da plataforma [Kaggle](https://www.kaggle.com/). Os dados fornecidos no Data Set em tela não necessariamente reflete a veracidade dos fatos referentes ao acidente ocorrido em 1912.

### **Objetivo Geral:**  
Fazer uma Análise Descritiva de um conjunto de dados para aplicar os conhecimentos adquiridos sobre Structured Query Language ([SQL](https://en.wikipedia.org/wiki/SQL#:~:text=Structured%20Query%20Language%20(SQL)%20(,database%20management%20system%20(RDBMS)))) utilizando um conjunto de dados sobre passageiros do Titanic.

### **Objetivos Específicos:**
1. Quantos passageiros embarcaram em cada porto?    
2. Qual foi a tarifa média paga por passageiros de cada classe (dólares)?   
3. Qual a idade do passageiro mais jovem e do mais velho a bordo (anos)?   
4. Quantos passageiros são do sexo masculino e quantos do sexo feminino?   
5. Quantos passageiros sobreviveram e quantos não sobreviveram?   
6. Qual a distribuição de passageiros por faixa etária e sobrevivência?   
7. Qual a média de idade dos passageiros que sobreviveram (em anos)?   
8. Qual a classe de passagem tinha o maior número de sobreviventes?   
9. Qual a média de tarifa paga por passageiros que sobreviveram versus os que não sobreviveram?   
10. Quem foi o(a) passageiro(a) mais velho(a) que sobreviveu?  

### **Metodologia**
Utilizamos as seguintes bibliotecas Python para construir *queries* de consulta ao conjunto de dados selecionado:
- Pandas
- PandaSQL
- SQLAlchemy
- Psycopg2 (database adpater for Python)

### **Conlusão**
#### A partir das consultas realizadas com as *queries* construídas tirar algumas conclusões sobre os dados.
Do conjunto de dados extraídos do arquivo .csv selecionado, cujo tema aborda o acidente ocorrido com o navio Titanic em abril do ano de 1912, conclui-se que a embarcação possuía passageiros das mais variadas faixas etárias, sendo o mais jovem possuindo menos de um ano de idade e o mais velho na casa dos 76 anos, sendo a grande maioria pertencente ao sexo masculino.    
A maior parte dos viajantes partiu do Porto de Southampton, embora alguns tenham embarcado de Cherbourg e também de Queenstown, este em sua minoria. Enquanto a média de idade dos sobreviventes foi de aproximadamente 30 anos, apenas 4 idosos e 24 crianças conseguiram sair com vida.    
Por fim, tendo em vista que a média do valor pago para desfrutar do conforto de viajar de primeira classe foi de aproximadamente 94 dólares, isso não foi o suficiente para garantir um maior índice de sobreviência, já que a maioria dos que resistiram foram passageiros da terceira classe, os quais pagaram em média aproximadamente 12 dólares pela cabine. Titanic é, de longe, o caso de naufrágio mais famoso do mundo, tendo inclusive sido retratado em filme no ano de 1997.    

---

### **Fim do projeto**
