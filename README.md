# Desafio de Controle de Fluxo

## Descrição
Este projeto tem como objetivo exercitar os conceitos apresentados no módulo de Controle de Fluxo. O sistema recebe dois números inteiros via terminal e imprime no console a quantidade de interações correspondente à diferença entre eles.

## Regras de Negócio
1. O sistema recebe dois números inteiros como parâmetros.
2. Se o primeiro número for menor que o segundo, ele imprime uma sequência de mensagens indicando a contagem.
3. Se o primeiro número for maior que o segundo, o sistema lança a exceção `ParametrosInvalidosException` com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

## Estrutura do Projeto
- `Contador.java`: Classe principal que contém a lógica do programa.
- `ParametrosInvalidosException.java`: Classe que representa a exceção personalizada.

## Exemplo de Uso
Entrada no terminal:
```sh
java Contador 12 30
```
Saída esperada:
```sh
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```

Caso os parâmetros sejam inválidos:
```sh
java Contador 30 12
```
Saída esperada:
```sh
Exception in thread "main" ParametrosInvalidosException: O segundo parâmetro deve ser maior que o primeiro
```

## Como Executar
1. Compile os arquivos Java:
```sh
javac Contador.java ParametrosInvalidosException.java
```
2. Execute o programa:
```sh
java Contador <numero1> <numero2>
```

## Tecnologias Utilizadas
- Java
- Terminal/Console


