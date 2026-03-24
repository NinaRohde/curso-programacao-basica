# curso-programacao-basica
Aqui vou colocar exercícios, testes e projetos simples conforme aprendo.💻✨

PRIMEIRA ATIVIDADE
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
alert (`Seu saldo é de ${saldo}`);
```
DESAFIO 5: Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
```javascript
let nomeUsuario = prompt ('Qual o seu nome?');
alert (`Seja bem vindo(a) ${nomeUsuario}!😁`);
```
