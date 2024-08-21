# Projeto DesafioControleFluxo

## Descrição do Projeto

O projeto **DesafioControleFluxo** tem como objetivo criar um sistema que recebe dois parâmetros via terminal, realiza uma validação e imprime uma sequência de números no console. Se o primeiro parâmetro for maior que o segundo, o sistema deve lançar uma exceção personalizada.

## Estrutura do Projeto

O projeto é composto por duas classes principais:

1. **Contador.java**: Esta classe é responsável por ler os parâmetros do usuário, validar os parâmetros e realizar a contagem e impressão dos números.
2. **ParametrosInvalidosException.java**: Esta classe representa a exceção personalizada que é lançada quando o primeiro parâmetro é maior ou igual ao segundo.

## Código

### Classe `ParametrosInvalidosException`

```java
// Crie um arquivo chamado ParametrosInvalidosException.java
public class ParametrosInvalidosException extends Exception {
    public ParametrosInvalidosException(String mensagem) {
        super(mensagem);
    }
}
