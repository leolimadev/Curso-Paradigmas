# Paradigma Imperativo

O paradigma de programação imperativa é um estilo em que você se concentra em "como" o programa deve executar tarefas. Esse é um dos paradigmas mais intuitivos para iniciantes, pois se assemelha à maneira como pensamos em resolver problemas passo a passo.

## O que é programação imperativa?

Na programação imperativa, você escreve instruções detalhadas que dizem ao computador exatamente como executar cada passo do processo para atingir um objetivo. É como seguir uma receita de bolo: você diz ao computador quais ingredientes usar e a ordem exata de cada ação.

### Características principais do paradigma imperativo:

### Passo a passo:

 A programação imperativa descreve uma sequência de passos ou instruções que devem ser seguidas para alcançar o resultado desejado. Por exemplo, se você quer somar os elementos de uma lista, você escreve código que especifica cada etapa desse processo:

 ```csharp 
    char[] myArray = {1, 2, 3, 4, 5};
    int soma = 0;

    for(int i = 0; i < myArray.Length; i++)
    {
        soma = soma + myArray[i];
    }
 ```

Aqui, você está explicitamente dizendo ao computador como somar os números: iniciar a soma em 0, percorrer a lista e adicionar cada número à soma.

### Mutação de estados: 

Na programação imperativa, o estado dos dados (valores armazenados em variáveis) é frequentemente alterado durante a execução do programa. Por exemplo, na soma acima, a variável soma é modificada a cada iteração do laço for.

### Controle do fluxo: 

No paradigma imperativo, você tem controle total sobre o fluxo do programa usando estruturas como loops (for, while) e condicionais (if, else). Isso permite que você controle exatamente como o código deve ser executado:

```csharp
for (int i = 0; i < 5; i++){
    if(i % 2){
        Console.WriteLine(String.Format("{0} é par", i));
    }else{
        Console.WriteLine(String.Format("{0} é impar", i));
    }
}
```

Neste exemplo, você especifica exatamente como o programa deve decidir se um número é par ou ímpar e o que fazer em cada caso.

### Programação orientada a objetos e estruturada:

Esses são estilos específicos dentro do paradigma imperativo. Na programação estruturada, você organiza o código em blocos lógicos (funções, procedimentos) que facilitam o entendimento e a reutilização. Na programação orientada a objetos, você modela seu código em torno de objetos que representam entidades do mundo real com estados (atributos) e comportamentos (métodos).

## Por que usar a programação imperativa?

### Controle total:

Como você especifica cada passo, tem controle completo sobre o comportamento do programa, o que pode ser útil em situações onde é necessário otimizar o desempenho ou lidar com operações complexas.

### Fácil de entender para iniciantes: 

Muitas pessoas acham mais fácil aprender programação começando com um estilo imperativo, já que ele se assemelha à forma como damos instruções e resolvemos problemas manualmente.

### Amplamente suportado:

Linguagens populares como C, Java, Python e JavaScript suportam e incentivam o estilo imperativo, com ampla documentação e recursos disponíveis.

## Resumo:

Na programação imperativa, você pensa no seu programa como uma série de passos que o computador deve seguir. Você diz como o programa deve fazer as coisas, detalhando cada etapa do processo. É um estilo direto e prático, com grande controle sobre os dados e o fluxo de execução do programa.