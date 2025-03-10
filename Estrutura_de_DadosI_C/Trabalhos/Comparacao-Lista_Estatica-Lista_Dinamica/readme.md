# 📊 Comparação entre Lista Estática e Lista Dinâmica

Este repositório contém a implementação de um sistema para comparação de desempenho entre **listas estáticas** e **listas dinâmicas**, desenvolvido como parte da disciplina **Estrutura de Dados I da Universidade Federal de Mato Grosso (UFMT)**. O objetivo é **analisar a eficiência** dessas estruturas em operações de inserção e acesso, considerando o custo computacional e o uso de memória.

## 🎯 Objetivo do Projeto

O projeto visa avaliar listas estáticas e dinâmicas em diferentes contextos, medindo o **tempo de execução** das operações de inserção em:

**Lista Estática** (vetor com capacidade fixa de 10.000 elementos).
**Lista Dinâmica Encadeada** (lista simplesmente encadeada).
**Lista Duplamente Encadeada** (permite navegação em ambos os sentidos).

## 🛠️ Funcionalidades do Sistema
✅ *Geração randômica* de 10.000 valores inteiros para inserção.
✅ *Inserção* em três cenários diferentes: **início, fim e posição aleatória**.
✅ Medição do *tempo de execução* usando clock() da biblioteca <time.h>.
✅ *Análise comparativa* do tempo de execução entre os três tipos de lista.
✅ Relatório final com resultados e interpretação dos dados.

## 📌 Estrutura do Código

O projeto está organizado da seguinte maneira:

- 📂 **lista_estatica.c** → Implementação da Lista Estática (vetor de tamanho fixo).
- 📂 **lista_dinamica.c** → Implementação da Lista Dinâmica Encadeada.
- 📂 **lista_duplamente_encadeada.c** → Implementação da Lista Duplamente Encadeada.
- 📂 **main_estatica.c** → Teste da Lista Estática e medição de tempo.
- 📂 **main_dinamica.c** → Teste da Lista Dinâmica Encadeada e medição de tempo.
- 📂 **main_duplamente_encadeada.c** → Teste da Lista Duplamente Encadeada e medição de tempo.

## 🔄 Fluxo do Sistema

- 1️⃣ **Geração dos dados** → São gerados 10.000 números aleatórios.
- 2️⃣ **Inserção dos dados** → Os valores são inseridos em três partes:
   1/3 no início da lista.
   1/3 no fim da lista.
   1/3 em posições aleatórias.
- 3️⃣ **Medição do tempo de execução** → Cada operação de inserção é executada 10 vezes, e o tempo médio é calculado.
- 4️⃣ **Análise dos resultados** → Os tempos de execução são comparados e analisados.

## 🔧 Tecnologias Utilizadas
- **Linguagem: C**
- **Paradigma:** Programação estruturada
- **Conceitos aplicados:** Alocação dinâmica, listas encadeadas, vetores estáticos, medição de tempo

## 🚀 Como Executar o Projeto

## Clone este repositório:
```
git clone https://github.com/cavalcantiraissas/Comparacao-Lista_Estatica-Lista_Dinamica.git
cd Comparacao-Lista_Estatica-Lista_Dinamica
```
## Compile os arquivos:

Para testar a lista estática:
```
gcc main_estatica.c lista_estatica.c -o cod_lista_estatica
./cod_lista_estatica
```
Para testar a lista encadeada:
```
gcc main_dinamica.c lista_dinamica.c -o cod_lista_dinamica
./cod_lista_dinamica
```
Para testar a lista duplamente encadeada:
```
gcc main_duplamente_encadeada.c lista_duplamente_encadeada.c -o cod_lista_duplamente_encadeada
./cod_lista_duplamente_encadeada
```

# 📌 Sobre o Trabalho

- Disciplina: Estrutura de Dados I
- Aluna: Raissa Cavalcanti
- Professor: Ivairton Monteiro Santos
- Universidade: Universidade Federal de Mato Grosso (UFMT)

📌 Projeto acadêmico para fins educacionais. Contribuições são bem-vindas! 🚀
