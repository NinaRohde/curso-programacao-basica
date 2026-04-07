# JavaScript
Aqui vou colocar exercícios e desafios simples enquanto aprendo.💻✨

# Curso 1

ATIVIDADE
```javascript
alert ('Bem vindo!!');
let nome = 'Lua';
let idade = 25;
let numeroDeVendas = 50;
let saldoDisponivel = 1000;
alert('Erro! Preencha todos os campos');
let mensagemDeErro = 'Erro! preencha todos os campos';
alert (mensagemDeErro);

let nomeDoUsuario = prompt ('Qual o seu nome?');
let idadeDoUsuario = prompt ('Qual a sua idade?');
if (idadeDoUsuario >= 18){
    alert ('Pode tirar a habilitação!😁');
}else{
    alert('Menor de idade não tira habilitação😑');
}
```
➤ Condicionais e concatenação

DESAFIO 1: Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".
```javascript
let dia = prompt ('Que dia é hoje?');
if (dia == 'sábado' || dia == 'sabado' || dia == 'domingo'){
    alert ('Bom fiind!!🥳');
}else{
    alert ('Espero que tenha uma ótima semana🤗');
}
```
DESAFIO 2: Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
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
DESAFIO 3: Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
```javascript
alert ('Tente ganhar com o maior número');
let numero = prompt ('Escolha um número');
if (numero >= 100){
    alert ('Parabéns você venceu!🥳');
}else{
     alert ('Tente novamente para ganhar😅');
}
```
DESAFIO 4: Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
```javascript
let saldo = 500;
alert (`Seu saldo é de R$${saldo}`);
```
DESAFIO 5: Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
```javascript
let nomeUsuario = prompt ('Qual o seu nome?');
alert (`Seja bem vindo(a) ${nomeUsuario}!😁`);
```
➤ Loops e tentativas

DESAFIO 1: Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.
```javascript
let contador = 1;

while (contador <= 10) {
    alert (`Contador: ${contador}`);
    contador++
}
```
DESAFIO 2: Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```javascript
let contador = 10;

while (contador >= 0) {
    alert (`Contador: ${contador}`);
    contador--
}
```
DESAFIO 3: Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```javascript
let numeroDoUsuario = prompt ('Digite o número para a contagem regressiva');

while (numeroDoUsuario >= 0) {
    alert (`Contador: ${numeroDoUsuario}`);
    numeroDoUsuario--
}
```
DESAFIO 4: Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```javascript
let numeroDoUsuario = prompt ('Digite o numero para a contagem progressiva');
let contador = 0

while (contador <= numeroDoUsuario) {
    console.log(`Contador: ${contador}`);
    contador++
}
```
➤ Boas práticas de programação

DESAFIO 1: Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.
```javascript
console.log ('Seja bem vindo!🤗');
```
DESAFIO 2: Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.
```javascript
let nome = ('Nina');
console.log (`Olá ${nome}!🤗`);
```
DESAFIO 3: Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" .
```javascript
let nome = ('Nina');
alert (`Olá ${nome}!🤗`);
```
DESAFIO 4: Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.
```javascript
let respUsuario = prompt ('Qual a lingueagem de programação que você mais gosta?');
console.log (respUsuario);
```
DESAFIO 5: Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.
```javascript
let valor1 = 30;
let valor2 = 20;
let resultado = valor1 + valor2;
console.log (`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`);
```
DESAFIO 6: Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.
```javascript
let valor1 = 25;
let valor2 = 47;
let resultado = valor1 - valor2;
console.log (`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}.`);
```
DESAFIO 7: Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.
```javascript
let idade = prompt ('Qual sua idade?');
if (idade >= 18){
    console.log ('Você é maior de 18');
}else{
    console.log ('Você é menor de 18');
}
```
DESAFIO 8: Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.
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
DESAFIO 9: Use um loop while para imprimir os números de 1 a 10 no console.
```javascript
let contador = 1;
while (contador <= 10){
    console.log (contador);
    contador++;
}
```
DESAFIO 10: Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.
```javascript
let nota = 6.5;
if (nota >= 7) {
    console.log ('Aprovado!🥳');
}else {
    console.log ('Reprovado😟');
}
```
DESAFIO 11: Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.
```javascript
let numeroAleatorio = Math.random();
console.log (numeroAleatorio);
```
DESAFIO 12: Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.
```javascript
let numeroAleatorio = parseInt(Math.random() * 10) + 1;
console.log (numeroAleatorio);
```
DESAFIO 13: Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.
```javascript
let numeroAleatorio = parseInt(Math.random() * 1000) + 1;
console.log (numeroAleatorio);
```
# Curso 2
➤ Interagindo com HTML

DESAFIO 1: Altere o conteúdo da tag h1 com document.querySelector e atribua o seguinte texto: Hora do Desafio.
```javascript
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';
```
DESAFIO 2: Crie uma função que exiba no console a mensagem O botão foi clicado sempre que o botão Console for pressionado.
```javascript
function mensagemConsole() {
    console.log('O botão foi clicado');
}
```
DESAFIO 3: Crie uma função que exiba um alerta com a mensagem: Eu amo JS, sempre que o botão Alerta for pressionado.
```javascript
function mensagemAlerta() {
    console.log('Eu amo JS');
}
```
DESAFIO 4: Crie uma função que é executada quando o botão prompt é clicado, perguntando o nome de uma cidade do Brasil. Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: Estive em {cidade} e lembrei de você.
```javascript
function mensagemPrompt() {
    let pergunta = prompt ('Digite uma cidade do Brasil');
    alert (`Estive em ${pergunta} e lembrei de você`);
}
```
DESAFIO 5: Ao clicar no botão soma, peça 2 números inteiros e exiba o resultado da soma em um alerta.
```javascript
function matematica() {
    let num1 = parseInt(prompt('Digite o primeiro números inteiros'));
    let num2 = parseInt(prompt('Digite o segundo números inteiros'));

    alert(`A soma de ${num1} + ${num2} é ${num1 + num2} ✨`);
}
```
➤ Funções

DESAFIO 1: Criar uma função que exibe "Olá, mundo!" no console.
```javascript
function olaMundo() {
    console.log ('Olá mundo!');
}
olaMundo();
```
DESAFIO 2: Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
```javascript
function olaMundo(nome) {
    console.log (`Olá ${nome}!🤗`)
}
olaMundo(Nina)
```
DESAFIO 3: Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
```javascript
function dobro(numero) {
    return numero * 2;
}
let resultadoDobro = dobro(10);
console.log (resultadoDobro);
```
DESAFIO 4: Criar uma função que recebe três números como parâmetros e retorna a média deles.
```javascript
function media(a, b, c) {
    return (a + b + c) / 3;
}
console.log (`A média é ${media(5, 6, 7)}`); 
```
DESAFIO 5: Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
```javascript

```
DESAFIO 6:
```javascript

```
