# Teste de Caixa Branca - ETAPA 2

## Introdução

Este repositório contém um código que se refere a uma conexão hipotética com um banco de dados.

## Estrutura do Código

O código está organizado em uma classe Java chamada `User`. Nesta classe, você encontrará os seguintes métodos e variáveis:

- `conectarBD()`: Este método estabelece uma conexão com o banco de dados MySQL e retorna a conexão.
- `verificarUsuario(String login, String senha)`: Este método verifica as credenciais do usuário no banco de dados e armazena o resultado em uma variável booleana `autenticado` e o nome do usuário em `nomeDoUsuario`.

## Avaliação

Aqui está uma avaliação dos aspectos do código:

1. **Fechamento de Conexões**: É reforçada a necessidade de fechar as conexões com o banco de dados de forma apropriada para evitar vazamentos de recursos.

2. **Melhorias de Nomenclatura**: As variáveis `nome` e `result` foram renomeadas para `nomeDoUsuario` e `autenticado` para aumentar a legibilidade do código.
   
3. **Documentação Detalhada**: A documentação é fundamental para compreender o código. Foram adicionados comentários explicativos nos trechos críticos do código para melhor documentação e para esclarecer o funcionamento dos métodos.

4. **Comentários no Código**: Comentários foram incluídos em partes importantes do código para explicar a lógica e o funcionamento.

5. **Exceções e Tratamento de Erros**: É enfatizada a importância do tratamento de exceções para evitar problemas inesperados durante a execução do código.

7. **Arquitetura e Organização**: Recomenda-se organizar o código em pacotes ou classes para melhorar a arquitetura e modularidade.

## Grafo de Fluxo

![image](https://github.com/GarciaGGOO/CaixaBranca/assets/111614180/4d06be71-666c-4130-939a-2f555ed929bc)

## Caminhos no Grafo de Fluxo

Aqui estão os caminhos identificados no grafo de fluxo:

1. Início → `conectarBD()` → `verificarUsuario()` → Fim
2. Início → `conectarBD()` → `verificarUsuario()` → Conexão com sucesso → Fim
3. Início → `conectarBD()` → `verificarUsuario()` → Conexão com falha → Fim

## Complexidade Ciclomática

O cálculo da complexidade ciclomática é o seguinte:

M = E - N + 2P

M = 8 - 7 + 2 * 1

M = 1 + 2

M = 3


