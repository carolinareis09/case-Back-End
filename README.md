# Case de Back-End: Desenvolvimento da Lógica de Negócios


## Sobre o projeto
Foi desenvolvida a primeira parte do case baseado nos conhecimentos iniciais de Python e lógica de programação.
A aplicação consiste em um código no qual os dados são cadastrados e podem ser consultados, alterados e excluídos.
Observação: a aplicabilidade em API será demostrada via explicação abaixo.



### Armazenamento de Dados:
O armazenamento de dados será realizado em memória, de modo ser possível coletar, consultar, editar e deletar dados pelo próprio programa.



### Tecnologias utilizadas
- Python
- PyCharm

  

### Explicação do desenvolvimento do código em Python para execução em PyCharm:
* Foi desenvolvido um laço de repetição que contém as opções que podem ser selecionadas pelo usuário (Cadastrar novo funcionário / Localizar cadastro de funcionário / Alterar cadastro de funcionário / Excluir cadastro de funcionário / Sair)
* Ao selecionar a opção 1, o programa retorna a inserção dos dados de Nome, Data de nascimento, CPF, Endereço completo e Estado Civil para cadastro;
* Ao selecionar a opção 2, o programa retorna a opção de localizar cadastro;
* Ao selecionar a opção 3, o programa retorna a opção de alterar cadastro;
* Ao selecionar a opção 4, o programa retorna a opção de excluir cadastro;
* Ao selecionar a opção 5, o programa é fechado.




### Explicação de como executar a aplicação como API:
- Framework: Flask
- Criação de API no Flask
- URL base: localhost.com
- Endpoints:
    -  localhost/pessoa (POST)
    -  localhost/pessoa (GET)
    -  localhost/pessoa (PUT)
    -  localhost/pessoa (DELETE)
- Armazenamento de Dados: em memória
- Desenvolvimento do código em Python para execução em Flask


# Autora

Carolina H. B. dos Reis

[https://www.linkedin.com/in/carolina-helena-benedicto-dos-reis/]
