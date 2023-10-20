# Teste de Caixa Branca - ETAPA 2

## Introdução

O código presente no repositório trata-se de uma conexão com um banco de dados hipotético.

## Estrutura do Código

O código está organizado em uma classe Java chamada `User`. Esta classe tem os seguintes métodos e variáveis:

- `conectarBD()`: Este método estabelece uma conexão com o banco de dados MySQL e retorna a conexão.
- `verificarUsuario(String login, String senha)`: Este método verifica as credenciais do usuário no banco de dados e armazena o resultado em uma variável booleana `result` e o nome do usuário em `nome`.

## Avaliação

Aqui está uma avaliação dos aspectos do código:

1. **Documentação Detalhada**: A documentação do código é essencial para facilitar a compreensão. Adicione comentários explicativos no código para melhorar a documentação e esclarecer como os métodos funcionam.

2. **Comentários no Código**: Comentários foram adicionados em trechos críticos do código para explicar a lógica e o funcionamento.

3. **Exceções e Tratamento de Erros**: Saliente a importância do tratamento de exceções para evitar problemas inesperados durante a execução do código.

4. **Melhorias de Nomenclatura**: As variáveis `nome` e `result` foram renomeadas para `nomeDoUsuario` e `autenticado`, tornando o código mais legível.

5. **Arquitetura e Organização**: Recomenda-se organizar o código em pacotes ou classes para melhorar a arquitetura e modularidade.

6. **Fechamento de Conexões**: Reforce a necessidade de fechar as conexões com o banco de dados de forma apropriada para evitar vazamentos de recursos.

## Grafo de Fluxo

![Grafo de Fluxo](https://github.com/NicolasSegat0/CaixaBrancaTeste/assets/100158925/5e1b4937-2c10-4878-8169-e13c74b8abe6)

## Complexidade Ciclomática

O cálculo da complexidade ciclomática é:

M = E - N + 2P
M = 8 - 7 + 2 * 1
M = 1 + 2
M = 3

## Caminhos no Grafo de Fluxo

Aqui estão os caminhos identificados no grafo de fluxo:

1. Início → conectarBD() → verificarUsuario() → Fim
2. Início → conectarBD() → verificarUsuario() → Conexão com sucesso → Fim
3. Início → conectarBD() → verificarUsuario() → Conexão com falha → Fim

Lembre-se de que esta é uma versão aprimorada do seu README, tornando-o mais informativo e fácil de entender para outros desenvolvedores que revisarem o projeto. Certifique-se de que todas as informações estejam bem organizadas e de fácil acesso. Se houver mais melhorias específicas que você gostaria de adicionar, sinta-se à vontade para fazê-lo.
