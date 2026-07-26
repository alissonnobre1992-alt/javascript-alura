# Desafios - Minhas Respostas

1. Crie um programa que utilize o `console.log` para exibir uma mensagem de boas-vindas.

```javascript
console.log('Olá, seja muito bem vindo!!');
```

2. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o `console.log` para exibir a mensagem "Olá, [seu nome]!" no console do navegador.

```javascript
let nome = 'Alisson' ;
console.log(`Olá, ${nome}!`);
```

3. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o `alert` para exibir a mensagem "Olá, [seu nome]!".

```javascript
let nome = 'Alisson' ;
alert(`Olá, ${nome}!`);
```

4. Utilize o `prompt` e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

```javascript
let LinguagemPreferida = prompt ('Qual a sua linguagem de programação que você mais gosta ?');
console.log(LinguagemPreferida);
```

5. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o `console.log` para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.

```javascript
let valor1 = 98;
let valor2 = 763;
let resultado = valor1 + valor2;
console.log(`A soma de ${valor1} + ${valor2} é igual a ${resultado} `);
```

6. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o `console.log` para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.

```javascript
let valor1 = 791;
let valor2 = 763;
let resultado = valor1 - valor2;
console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado} `);
```

7. Peça ao usuário para inserir sua idade com `prompt`. Com base na idade inserida, utilize um `if` para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

```javascript
let idade = prompt('Digite a sua idade:');
if (idade >= 18) {
    console.log(`Você é maior de idade`);
} else {
    console.log(`Você é menor de idade`)
}
```

8. Crie uma variável "numero" e peça um valor com `prompt` verifique se é positivo, negativo ou zero. Use `if-else` para imprimir a respectiva mensagem.

```javascript
let numero = prompt ('Digite um valor:');
if (numero > 0) {
    console.log(`${numero} é um número positivo!`);
} else if (numero < 0) {
    console.log (`${numero} é um número negativo!`);
} else {
    console.log(`${numero} é zero`);
}
```

9. Use um loop `while` para imprimir os números de 1 a 10 no console.

```javascript
let numero = 1
while (numero <= 10){
    console.log(`${numero}`);
    numero++
}
```

10. Crie uma variável "nota" e atribua um valor numérico a ela. Use `if-else` para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

```javascript
let nota = 10 
if (nota >= 7){
    console.log('Aprovado');
} else {
    console.log('Reprovado');
}
```

11. Use o `Math.random` para gerar qualquer número aleatório e exiba esse número no console.

```javascript
console.log(Math.random());
```

12. Use o `Math.random` para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.

```javascript
console.log(parseInt(Math.random() * 1000 + 1));
```
