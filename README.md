# Controle de Fluxo - Desafio

Neste projeto, exercitamos o conteúdo de Controle de Fluxo em Java, implementando o seguinte cenário:

O sistema recebe dois parâmetros via terminal que representam dois números inteiros. Com esses números, calculamos a quantidade de iterações (usando um loop `for`) e imprimimos os números incrementados no console.

## Requisitos

- JDK (Java Development Kit) instalado na máquina.
- Ambiente de desenvolvimento Java, como Eclipse ou IntelliJ IDEA.
- Conhecimento básico de Java e controle de fluxo.

## Funcionamento

1. Execute o programa Java fornecendo dois números inteiros como parâmetros via terminal.
2. O programa calculará a quantidade de iterações necessárias para imprimir os números entre os dois parâmetros (inclusive).
3. Os números serão impressos no console como "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.

### Exceção Personalizada

Se o primeiro parâmetro for MAIOR que o segundo parâmetro, uma exceção personalizada chamada `ParametrosInvalidosException` será lançada com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

## Estrutura do Projeto

O projeto contém as seguintes classes:

- `Contador.java`: Contém o código principal para contar e imprimir os números.
- `ParametrosInvalidosException.java`: Contém a classe de exceção personalizada.

## Executando o Projeto

1. Compile e execute a classe `Contador.java` em seu ambiente de desenvolvimento Java.
2. Siga as instruções no terminal para fornecer os dois parâmetros.



