# UC10 - Realizar Testes nas Aplicações Desenvolvidas
## Tayla Prado Cabral de Oliveira Suares 

## Descrição e Funcionalidades

- Aplicação de controle de tarefas.
- Cadastra tarefas: Insert -> Create.
- Consultar/listar tarefas: Select -> Read.
- Atualizar tarefas: Update -> Update.
- Excluir tarefas: Delete -> Delete.

## Tecnologias

| Técnologias | Função | 
| ----------- | ------ |
| HTML | Estrutura/esqueleto da página web |
| CSS | Estilização/design da página | 
| JavaScript | Interatividade/Comportamento |
| Node.js | Permite executar o JS no servidor |
| Jest | Framework de testes automatizados |
| SQLite | Banco de dados relacional |
| Express | Framework back-end que recebe requisições do front-end |
| Supertest | Ferramenta que simula requisições HTTP para testar a sua API |

# Testes
## Testes Unitários

| Caso de Teste | Entrada | Saída esperada | 
| ------------- | ------- | -------------- |
| 1 | "segunda-feira" | "segunda-feira" | 
| 2 | "      segunda-feira      " | "segunda-feira" | 
| 3 | null | Erro: O título da tarefa é obrigatório.| 
