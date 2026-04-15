# 📚 Registro de Aprendizado - JavaScript

Este arquivo contém exercícios e desafios desenvolvidos durante meus estudos de lógica de programação com JavaScript.

---

## 🧠 Curso 1

### 🔹 Atividade inicial

Prática com variáveis, alert, prompt e condicionais.

```javascript
alert('Bem vindo!!');
let nome = 'Lua';
let idade = 25;
let numeroDeVendas = 50;
let saldoDisponivel = 1000;

alert('Erro! Preencha todos os campos');

let mensagemDeErro = 'Erro! preencha todos os campos';
alert(mensagemDeErro);

let nomeDoUsuario = prompt('Qual o seu nome?');
let idadeDoUsuario = prompt('Qual a sua idade?');

if (idadeDoUsuario >= 18) {
    alert('Pode tirar a habilitação!😁');
} else {
    alert('Menor de idade não tira habilitação😑');
}
```
### 🔸 Condicionais e concatenação

Desafio 1: Dia da semana.
```javascript
let dia = prompt ('Que dia é hoje?');
if (dia == 'sábado' || dia == 'sabado' || dia == 'domingo'){
    alert ('Bom fiind!!🥳');
}else{
    alert ('Espero que tenha uma ótima semana🤗');
}
```
Desafio 2: Número positivo ou negativo.
```javascript
let numero = prompt ('Informe o número que deseja saber se é positivo ou negativo');
if (numero > 0){
    alert ('Seu número é positivo!📈');
}else if (numero < 0){
    alert ('Seu numero é negativo!📉');
}else{
    alert ('Seu numero é 0😐');
}
```
Desafio 3: Sistema de pontuação.
```javascript
alert ('Tente ganhar com o maior número');
let numero = prompt ('Escolha um número');
if (numero >= 100){
    alert ('Parabéns você venceu!🥳');
}else{
     alert ('Tente novamente para ganhar😅');
}
```
Desafio 4: Exibir saldo.
```javascript
let saldo = 500;
alert (`Seu saldo é de R$${saldo}`);
```
Desafio 5: Boas-vindas.
```javascript
let nomeUsuario = prompt ('Qual o seu nome?');
alert (`Seja bem vindo(a) ${nomeUsuario}!😁`);
```
### 🔸 Loops (while)

Desafio 1: Contador 1 a 10.
```javascript
let contador = 1;

while (contador <= 10) {
    alert (`Contador: ${contador}`);
    contador++
}
```
Desafio 2: Contador 10 a 0.
```javascript
let contador = 10;

while (contador >= 0) {
    alert (`Contador: ${contador}`);
    contador--
}
```
Desafio 3: Contagem regressiva.
```javascript
let numeroDoUsuario = prompt ('Digite o número para a contagem regressiva');

while (numeroDoUsuario >= 0) {
    alert (`Contador: ${numeroDoUsuario}`);
    numeroDoUsuario--
}
```
Desafio 4: Contagem progressiva.
```javascript
let numeroDoUsuario = prompt ('Digite o numero para a contagem progressiva');
let contador = 0

while (contador <= numeroDoUsuario) {
    console.log(`Contador: ${contador}`);
    contador++
}
```
### 🔸 Boas práticas

DESAFIO 1: Mensagem no console.
```javascript
console.log ('Seja bem vindo!🤗');
```
DESAFIO 2: Saudação com variávelnavegador.
```javascript
let nome = ('Nina');
console.log (`Olá ${nome}!🤗`);
```
DESAFIO 3: Prompt e resposta.
```javascript
let nome = ('Nina');
alert (`Olá ${nome}!🤗`);
```
DESAFIO 4: Soma.
```javascript
let respUsuario = prompt ('Qual a lingueagem de programação que você mais gosta?');
console.log (respUsuario);
```
DESAFIO 5: Verificar idade.
```javascript
let valor1 = 30;
let valor2 = 20;
let resultado = valor1 + valor2;
console.log (`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`);
```
DESAFIO 6: Subtração.
```javascript
let valor1 = 25;
let valor2 = 47;
let resultado = valor1 - valor2;
console.log (`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}.`);
```
DESAFIO 7: Verificar idade.
```javascript
let idade = prompt ('Qual sua idade?');
if (idade >= 18){
    console.log ('Você é maior de 18');
}else{
    console.log ('Você é menor de 18');
}
```
DESAFIO 8: Número positivo, negativo ou zero.
```javascript
let numero = parseFloat(prompt("Digite um número:"));
if (numero > 0) {
    console.log (`O número ${numero} é positivo📈`);
}else if (numero < 0){
    console.log (`O número ${numero} é negativo📉`);
}else{
    console.log (`O número ${numero} é 0😐`);
}
```
DESAFIO 9: Contador no console.
```javascript
let contador = 1;
while (contador <= 10){
    console.log (contador);
    contador++;
}
```
DESAFIO 10: Verificar nota.
```javascript
let nota = 6.5;
if (nota >= 7) {
    console.log ('Aprovado!🥳');
}else {
    console.log ('Reprovado😟');
}
```
DESAFIO 11: Número aleatório.
```javascript
let numeroAleatorio = Math.random();
console.log (numeroAleatorio);
```
DESAFIO 12: Número inteiro (1 a 10).
```javascript
let numeroAleatorio = parseInt(Math.random() * 10) + 1;
console.log (numeroAleatorio);
```
DESAFIO 13: Número inteiro (1 a 1000).
```javascript
let numeroAleatorio = parseInt(Math.random() * 1000) + 1;
console.log (numeroAleatorio);
```
## 🧠 Curso 2
###🔸 Interação com HTML

DESAFIO 1: Alterar título.
```javascript
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';
```
DESAFIO 2: Clique no botão.
```javascript
function mensagemConsole() {
    console.log('O botão foi clicado');
}
```
DESAFIO 3: Alerta ao clicar no botão.
```javascript
function mensagemAlerta() {
    alert('Eu amo JS');
}
```
DESAFIO 4: Prompt com mensagem.
```javascript
function mensagemPrompt() {
    let cidade = prompt('Digite uma cidade');
    alert(`Estive em ${cidade} e lembrei de você`);
}
```
DESAFIO 5: Soma com prompt.
```javascript
function matematica() {
    let num1 = parseInt(prompt('Digite o primeiro números inteiros'));
    let num2 = parseInt(prompt('Digite o segundo números inteiros'));

    alert(`A soma de ${num1} + ${num2} é ${num1 + num2} ✨`);
}
```
### 🔸 Funções

DESAFIO 1: Olá mundo.
```javascript
function olaMundo() {
    console.log ('Olá mundo!');
}
olaMundo();
```
DESAFIO 2: Saudação com nome.
```javascript
function olaMundo(nome) {
    console.log (`Olá ${nome}!🤗`)
}
olaMundo(Nina)
```
DESAFIO 3: Dobro.
```javascript
function dobro(numero) {
    return numero * 2;
}
let resultadoDobro = dobro(10);
console.log (resultadoDobro);
```
DESAFIO 4: Média.
```javascript
function media(a, b, c) {
    return (a + b + c) / 3;
}
console.log (`A média é ${media(5, 6, 7)}`); 
```
DESAFIO 5: Maior número.
```javascript
function maiorNum(a, b) {
  return a > b ? a : b;
}

let resultado = maiorNum(10, 7);
console.log (maiorNumero);
```
DESAFIO 6: Quadrado.
```javascript
function quadrado(numero) {
    return numero * numero
}

let resultado = quadrado(5);
console.log (resultado);
```
### 🔸 Reiniciando o jogo

DESAFIO 1: IMC.
```javascript
function calcularIMC(peso, altura) {
    return peso / (altura ** 2);
}

let imc = calcularIMC(70, 1.70);
console.log(`Seu IMC é ${imc.toFixed(2)} 🧠`);
```
DESAFIO 2: Fatorial de um numero.
```javascript
function fatorial(numero) {
    let resultado = 1;

    while (numero > 1) {
        resultado *= numero;
        numero--;
    }

    return resultado;
}

let resultado = fatorial(5);
console.log(resultado);
```
DESAFIO 3: Conversão.
```javascript
function conversao(dolar) {
    let valorDolar = 4.80;
    let valorReais = dolar * valorDolar;
    return valorReais.toFixed(2);
}

let valorEmDolar = 10;
let resultado = conversao(valorEmDolar);

console.log(`$${valorEmDolar} dólares = R$${resultado}`);
```
DESAFIO 4: Conversão.
```javascript
function conversao(dolar) {
    let valorDolar = 4.80;
    let valorReais = dolar * valorDolar;
    return valorReais.toFixed(2);
}

let valorEmDolar = 10;
let resultado = conversao(valorEmDolar);

console.log(`$${valorEmDolar} dólares = R$${resultado}`);
```
DESAFIO 4: Conversão.
```javascript
function conversao(dolar) {
    let valorDolar = 4.80;
    let valorReais = dolar * valorDolar;
    return valorReais.toFixed(2);
}

let valorEmDolar = 10;
let resultado = conversao(valorEmDolar);

console.log(`$${valorEmDolar} dólares = R$${resultado}`);
```
DESAFIO 5: Area e Perimetro.
```javascript
function sala(altura, largura) {
    let area = altura * altura;
    let perimetro = 2 * (altura + altura);
     console.log (`A area é ${area} e o perimetro é ${perimetro}`);
}
sala (5, 3);
```
DESAFIO 6: Area e Perimetro.
```javascript
function sala(altura, largura) {
    let area = altura * altura;
    let perimetro = 2 * (altura + altura);
     console.log (`A area é ${area} e o perimetro é ${perimetro}`);
}
sala (5, 3);
```
