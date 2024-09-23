# Paradigma Funcional

O paradigma de programação funcional é um estilo de programação que trata a computação como a avaliação de funções matemáticas. Vamos simplificar isso!

## Características principais da programação funcional:

### Funções de primeira classe:

Significa que, assim como variáveis, você pode passar funções como argumentos para outras funções, retornar funções de outras funções e até armazená-las em variáveis. Isso permite criar códigos mais flexíveis e reutilizáveis.

### Funções puras: 

Uma função pura é aquela que sempre devolve o mesmo resultado para os mesmos valores de entrada e não causa efeitos colaterais (não altera nada fora dela mesma). Isso facilita a compreensão e a previsibilidade do código. Por exemplo, uma função que apenas soma dois números é pura:


## Vamos priorizar Orientado a Objetos


```csharp

public int Soma(int a, int b) => a + b;

```

Sempre que você passar os mesmos números, ela retornará o mesmo resultado e não mudará nada fora dela.

### Imutabilidade:

Na programação funcional, uma vez que um valor é criado, ele não é alterado. Se você precisa de uma nova versão de um valor, você cria um novo. Isso ajuda a evitar bugs, pois você sabe que os dados não vão mudar em locais inesperados.

### Funções de alta ordem:

São funções que recebem outras funções como argumentos ou retornam outras funções. Um exemplo é a função map, que aplica outra função a cada item de uma lista:

```python

numeros = [1, 2, 3, 4]
dobro = list(map(lambda x: x * 2, numeros))  # [2, 4, 6, 8]

```

Nesse exemplo, map recebe uma função anônima (lambda) que dobra cada número da lista.

### Recursão: 

Em vez de usar laços (for, while), na programação funcional usa-se muito a recursão, onde uma função chama a si mesma para resolver problemas. É um conceito um pouco mais avançado, mas é importante mencionar.

## Por que usar a programação funcional?

### Código mais previsível: 

Como funções puras sempre produzem o mesmo resultado com os mesmos inputs, é mais fácil prever o que o código fará.

### Fácil de testar e depurar:

Cada função é independente e não depende de estados externos, tornando os testes e a depuração mais simples.

### Menos bugs: 

A imutabilidade reduz os riscos de alterações inesperadas em dados, diminuindo a chance de erros.


## Resumo:

Na programação funcional, você pensa no seu programa como uma série de funções que recebem dados e devolvem resultados, sem alterar nada fora delas. É um jeito diferente de programar, que pode parecer estranho no começo, mas ajuda a escrever códigos mais limpos, previsíveis e confiáveis.