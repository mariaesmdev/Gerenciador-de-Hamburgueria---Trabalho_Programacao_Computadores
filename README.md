# Gerenciador-de-Hamburgueria---Trabalho_Programacao_Computadores
Trabalho acadêmico — Desenvolvimento de um sistema em C para gerenciamento de pedidos de uma hamburgueria, com cadastro validado, consultas e geração de estatísticas.

---
## Descrição do Projeto

Este projeto consiste na modelagem e implementação de um **Gerenciador de Hamburgueria**. O sistema controla vendas, entende o perfil dos consumidores e realiza consultas baseadas nos pedidos.

##  Funcionalidades

### 1. Cadastro de Pedidos

* Cadastrar **4 pedidos**.
* Cada pedido possui:

  * Valor total da venda.
  * Quantidade de itens vendidos.
  * Sexo do cliente (`m`, `f` ou `n`).
  * Código do pedido (`A` até `G`).

* **Validações:**
  * **Valor** não pode ser negativo ou maior que 1000.
  * **Sexo** deve ser apenas `m`, `f` ou `n`.
  * **Código** deve ser apenas uma letra de `A` a `G`.
* Informar **erro** em caso de valores inválidos.
* Exibir mensagem de **cadastro realizado com sucesso** ao finalizar corretamente.

### 2. Menu Principal

Após cadastrar os pedidos, o sistema exibe um **menu principal** com as opções:

* Pesquisar um pedido pelo código.
* Ver informações de todos os pedidos.
* Encerrar o programa.

### 3. Pesquisa de Pedidos

* Solicita ao usuário o **código** para pesquisa.
* Exibe:
  * Valor do pedido.
  * Quantidade de itens vendidos.
  * Sexo do cliente.
* Se o código **não for encontrado**, informa que não existem pedidos com esse código.
* Após a pesquisa, pergunta se o usuário deseja retornar ao menu principal.

### 4. Informações de Todos os Pedidos
* Solicita um valor para:
* Exibir a quantidade de pedidos abaixo deste valor.

* Exibe:
  * Quantidade de pedidos **acima de R\$35**.
  * Quantidade de **compradores homens**.
  * Valor total comprado por **mulheres**.
  * **Valor médio** dos pedidos.
  * **Pedido mais caro** e **pedido mais barato**.
  * Quantidade total de **itens vendidos**.
  * Quantidade de itens comprados por pessoas que **preferiram não informar o sexo**.
  * **Código mais vendido** (em caso de empate, qualquer um dos mais vendidos).
* Após exibir as informações, pergunta se o usuário deseja retornar ao menu principal.

## Tecnologias Utilizadas

* Linguagem: C.

## Regras de Negócio

* Não permitir valores inválidos durante o cadastro.
* Sempre validar a entrada do usuário.
* Garantir que o menu funcione até o usuário decidir encerrar o programa.



