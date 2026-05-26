# Constante de Kaprekar

Projeto desenvolvido em **Python** com foco em **lógica de programação**, utilizando apenas estruturas básicas da linguagem, como condicionais, laços de repetição, variáveis e operações matemáticas simples.

O programa implementa o **Desafio da Constante de Kaprekar (6174)**, exibindo o passo a passo completo do processo até alcançar a constante.

## Contextualização

Em 1949, o matemático indiano **Dattatreya Ramchandra Kaprekar** descreveu uma propriedade matemática curiosa envolvendo números de quatro dígitos.

Ao reorganizar os dígitos de um número em:

- **Ordem decrescente**
- **Ordem crescente**

e realizar a subtração entre eles, repetindo o processo sucessivamente, chega-se invariavelmente ao número **6174**, conhecido como a **Constante de Kaprekar**, desde que o número inicial seja válido.

Esse procedimento é conhecido como **Rotina de Kaprekar** e converge em **até sete iterações** para qualquer número elegível de quatro dígitos.

## Objetivo do Projeto

Desenvolver um programa em Python capaz de:

- Receber um número informado pelo usuário;
- Validar se o número atende às regras do desafio;
- Executar a **Rotina de Kaprekar**;
- Exibir todas as iterações realizadas;
- Encerrar o processo ao alcançar **6174** ou detectar entrada inválida.

## Como Funciona

O programa realiza as seguintes etapas:

1. Recebe um número digitado pelo usuário;
2. Valida se o valor é:
   - Inteiro;
   - Positivo;
   - Diferente de zero;
   - Possui no máximo **4 dígitos**;
   - Contém no máximo **duas repetições do mesmo dígito**;
3. Separa os dígitos em milhar, centena, dezena e unidade;
4. Reorganiza os dígitos em ordem crescente e decrescente;
5. Realiza a subtração:
   
   **Número Decrescente - Número Crescente**
   
6. Repete o processo até chegar ao número **6174**.

### Exemplo de execução

```text
Insira um número: 3524

Iteração 1: 5432 - 2345 = 3087
Iteração 2: 8730 - 378 = 8352
Iteração 3: 8532 - 2358 = 6174
```

## Estrutura do Projeto

```text
📁 constante_de_kaprekar
│── kaprekar.py
│── fluxograma_kaprekar.png
│── README.md
```

### Arquivos

- **kaprekar.py** → Código principal do programa;
- **fluxograma.png** → Fluxograma explicando a lógica de funcionamento;
- **README.md** → Documentação do projeto.

## Restrições do Projeto

Este projeto foi desenvolvido com fins acadêmicos e possui restrições específicas de implementação.

Foi permitido utilizar apenas:

- `if`
- `else`
- `elif`
- `while`
- `for`
- variáveis
- funções básicas
- operadores matemáticos
- manipulação simples de números

**Não foram utilizadas estruturas avançadas**, bibliotecas externas ou funções prontas de ordenação, priorizando exclusivamente o desenvolvimento da lógica de programação.

## Tecnologias Utilizadas

- Python 3

## Fluxograma do Programa

O projeto inclui um arquivo `.png` contendo o **fluxograma completo do funcionamento do algoritmo**, facilitando a compreensão da lógica implementada.

## Autor

**Gabriel Valois Rodrigues**

---

📚 Projeto acadêmico desenvolvido para prática de **lógica de programação em Python**, com foco em estruturas condicionais, repetição e manipulação numérica.
