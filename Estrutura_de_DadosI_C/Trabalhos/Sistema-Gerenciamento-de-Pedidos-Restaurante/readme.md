# 🍽️ Sistema de Gerenciamento de Pedidos de Restaurante

Este repositório contém a implementação de um **Sistema de Gerenciamento de Pedidos** para um restaurante, desenvolvido como parte da disciplina **Estrutura de Dados I** da **Universidade Federal de Mato Grosso (UFMT)**. O projeto utiliza **listas encadeadas, filas e pilhas** para simular o fluxo de pedidos, desde a criação até a entrega.

## 🎯 Objetivo do Projeto
O objetivo é aplicar conceitos fundamentais de **estrutura de dados dinâmicas** em C, como **listas encadeadas, filas e pilhas**, para gerenciar pedidos de um restaurante de forma eficiente.

## 🛠️ Funcionalidades do Sistema
✅ **Lista Encadeada** para armazenar pedidos e seus status (pendente, em preparo, pronto, entregue).  
✅ **Fila** para gerenciar a ordem de preparo dos pedidos.  
✅ **Pilha** para controlar a entrega dos pedidos prontos.  
✅ **Menu interativo** para inserção, remoção e atualização dos pedidos.  
✅ **Alocação dinâmica de memória** para garantir flexibilidade no armazenamento de dados.  

## 📌 Estrutura do Sistema

O código está organizado nos seguintes arquivos:

📂 **pedido.h** → Define a estrutura do pedido.  
📂 **pedido.c** → Implementa funções para manipular pedidos.  
📂 **fila.h** → Define a estrutura e funções da fila.  
📂 **fila.c** → Implementa as funções da fila.  
📂 **pilha.h** → Define a estrutura e funções da pilha.  
📂 **pilha.c** → Implementa as funções da pilha.  
📂 **main.c** → Contém o menu principal e a lógica do programa.  

## 🔄 Fluxo do Sistema
1️⃣ **Novo Pedido** → Adicionado à **lista encadeada** com status "pendente".  
2️⃣ **Pedido em Preparo** → Adicionado à **fila de preparo** e status atualizado para "em preparo".  
3️⃣ **Pedido Pronto** → Status atualizado para "pronto" e movido para a **pilha de pedidos prontos**.  
4️⃣ **Pedido Entregue** → Retirado da **pilha**, entregue ao cliente e status alterado para "entregue".  

## 🔧 Tecnologias Utilizadas
- **Linguagem**: C  
- **Paradigma**: Programação estruturada  
- **Conceitos aplicados**: Estruturas encadeadas, filas, pilhas, alocação dinâmica  

# 🚀 Como Executar o Projeto
## Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/Sistema-Gerenciamento-de-Pedidos-Restaurante.git
   cd Sistema-Gerenciamento-de-Pedidos-Restaurante

## Compile os arquivos
```gcc main.c pedido.c fila.c pilha.c -o sistema_pedidos
```

## Execute o Programa
```
./sistema_pedidos
```
# 📌 Sobre o Trabalho

- Disciplina: Estrutura de Dados I
- Aluna: Raissa Cavalcanti
- Professor: Ivairton Monteiro Santos
- Universidade: Universidade Federal de Mato Grosso (UFMT)

📌 Projeto em constante evolução! Contribuições são bem-vindas! 🚀
