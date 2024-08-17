# Sistema de inventário de produtos

###  _Sobre o sistema_
  * Trata-se de uma API RESTFUL de um sistema de inventário de produtos.

### _Finalidade_
  * O sistema possibilita o cadastro, consulta, alteração e exclusão de produtos. Além disso, o sistema informará se há um determinado produto em estoque

### _Principais tecnologias_
  * NodeJS
    * Utilizaremos a versão LTS mais recente do NodeJS para tirar o máximo proveito das últimas atualizações que essa linguagem robusta e amplamente utilizada fornece.
  * MongoDB
    * Trabalharemos com o banco de dados não relacional (NoSql) MongoDB. Pois em nosso sistema, não haverá relacionamentos complexos. Além disso, queremos priorizar o alto desempenho e escalabilidade na recuperação e
    armazenamento dados. Tendo em vista que futuramente o sistema armazenará um volume alto de produtos que serão persistidos em javascript object notation (JSON).
  * Express
    * Como trata-se somente de um API Restful que poderá ser consumida por algum cliente e não terá integração com o frontend, utilizaremos o framework Express em vez do NextJS.
  
