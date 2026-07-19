###Desafios - Minhas Respostas

## 1. Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```javascript
let chute = prompt('Que dia da semana é hoje?').toLowerCase();

if (chute == 'sábado') {
    alert('Bom fim de Semana!');
} else if (chute == 'domingo') {
    alert('Bom fim de Semana!');
} else {
    alert('Boa Semana!');
}
```

---

## 2. Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```javascript
let numero = prompt('Digite um positivo ou negativo');

if (numero > 0) {
    alert('Número positivo!');
} else if (numero < 0) {
    alert('Número negativo!');
} else {
    alert('Número neutro!');
}
```

---

## 3. Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!" no console do navegador. Caso contrário, mostre "Tente novamente para ganhar.".

```javascript
let pontuacao = prompt('Digite sua pontuação:');

if (pontuacao >= 100) {
    console.log('Parabéns, você venceu!');
} else {
    console.log('Tente novamente para ganhar!');
}
```

---

## 4. Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma string de modelo para incluir o valor do saldo.

```javascript
let saldo = prompt('Digite seu saldo R$:');

alert(`Seu saldo é de ${saldo}`);
```

---

## 5. Peça ao usuário para inserir seu nome usando `prompt`. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```javascript
let nome = prompt('Digite o seu nome:');

alert(`Boas vindas, ${nome}!`);
```
