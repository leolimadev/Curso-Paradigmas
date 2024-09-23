# Paradigma Declarativo

O paradigma de programação declarativa é um estilo em que você se preocupa mais com o "o que" o programa deve fazer, em vez de especificar "como" ele deve fazer isso. Vamos simplificar ainda mais!

## O que é programação declarativa?

Na programação declarativa, você escreve código que descreve o que você deseja que aconteça, deixando para o sistema ou a linguagem a responsabilidade de resolver como alcançar esse resultado. É diferente do paradigma imperativo (que inclui a programação orientada a objetos e estruturada), onde você diz exatamente como o programa deve executar passo a passo.

## Características principais do paradigma declarativo:

### Foco no resultado: 

Você se concentra em descrever o resultado que deseja. Por exemplo, em vez de escrever um conjunto de passos para ordenar uma lista de números, você simplesmente pede para a lista ser ordenada:

```python
numeros = [3, 1, 4, 2]
numeros_ordenados = sorted(numeros) # Declarativo: quero a lista ordenada
```

Nesse exemplo, sorted é uma função que faz todo o trabalho para você. Você só especifica o que quer (a lista ordenada), sem se preocupar com os detalhes do algoritmo de ordenação.

### Imutabilidade:
 
Assim como na programação funcional, os dados na programação declarativa geralmente são imutáveis. Uma vez que um valor é definido, ele não é alterado.

### Domínios específicos: 

Muitas linguagens e tecnologias declarativas são feitas para resolver problemas em domínios específicos, como SQL para consultas de banco de dados ou HTML para estruturar conteúdo na web. Em SQL, por exemplo, você não diz como buscar os dados no banco, mas o que você quer:

```sql
SELECT nome FROM clientes WHERE idade > 18;
```
 
 ```html
<article>
  <header>
    <h1>Paradigmas de programação declarativo</h1>
  </header>
</article>
 ```

## Por que usar a programação declarativa?

### Código mais simples e legível: 

Foca mais no que deve ser feito, o que geralmente torna o código mais fácil de ler e entender.

### Menos erros: 

Como você não precisa detalhar todos os passos, há menos espaço para cometer erros relacionados a lógica de controle.

### Facilidade de manutenção: 

É mais fácil de modificar e estender, pois se concentra no resultado desejado.


## Resumo:

Na programação declarativa, você pensa mais no resultado que deseja alcançar e menos nos passos necessários para chegar lá. Você "diz o que quer" e deixa que a linguagem ou a ferramenta escolha a melhor forma de realizar o que foi solicitado.
