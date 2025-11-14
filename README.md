# Carrinho de Compras em Python

Este projeto implementa um sistema de carrinho de compras em Python, utilizando Programação Orientada a Objetos (POO), listas, validação de entrada e manipulação de estoque.  
O usuário pode adicionar, remover e visualizar itens, além de finalizar ou cancelar uma compra.

---

## Funcionalidades

### 1. Adicionar itens ao carrinho
- Exibe produtos disponíveis em estoque  
- Permite escolher quantidade  
- Atualiza o estoque automaticamente  

### 2. Remover itens do carrinho
- Lista o carrinho atual  
- Permite reduzir quantidades  
- Reintegra itens ao estoque  

### 3. Exibir carrinho
- Exibe itens adicionados  
- Mostra quantidade, preço unitário e total acumulado  

### 4. Limpar carrinho
- Zera todas as quantidades  
- Restaura o estoque inicial  

### 5. Finalizar compra
- Exibe uma “nota de compra”  
- Mostra o valor total  
- Encerra a simulação  

### 6. Cancelar compra
- Cancela todo o processo  
- Restaura o estoque  
- Exibe mensagem adequada conforme o estado do carrinho  

---

## Estrutura do Código

### Classe `Item`
Representa um produto com:
- `id`
- `nome`
- `preco`

Inclui métodos getters e setters.

### Listas Utilizadas
- `produtos` – lista de objetos Item  
- `estoque` – controle de estoque  
- `carrinho` – itens adicionados  
- `quantCarrinho` – quantidade por produto  

### Funções Principais
- `opcoes()` — exibe o menu  
- `exibirProdutos()` — lista produtos disponíveis  
- `exibirCarrinho()` — mostra itens do carrinho  
- `carrinhoVazio()` — verifica se o carrinho está vazio  

---

## Como Executar

1. Certifique-se de ter Python 3 instalado.  
2. Salve o código em um arquivo, por exemplo:  
3. Execute no terminal:

---

## Produtos Disponíveis

| ID | Produto           | Preço (R$) |
|----|-------------------|------------|
| 1  | Hidratante facial | 50.99      |
| 2  | Sabonete facial   | 79.99      |
| 3  | Tônico facial     | 45.50      |
| 4  | Protetor solar    | 90.20      |
| 5  | Sérum facial      | 62.90      |

---

## Objetivo do Projeto

Este código foi desenvolvido com fins didáticos, aplicando:
- Estruturas condicionais  
- Estruturas de repetição  
- Manipulação de listas  
- Programação orientada a objetos  
- Validação de entrada  
- Controle de estoque  

---

## Melhorias Futuras

- Criar uma classe `Carrinho` para melhor organização  
- Salvar dados em arquivo JSON  
- Criar interface gráfica (Tkinter ou PyQt)  
- Usar exceções para validação  
- Modularizar o código em múltiplos arquivos  

---

