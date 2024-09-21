
# Javascript
- Estado do JS (https://2020.stateofjs.com/en-US/tecnologies/)
- Onde é executado (pelo navegador)
- Omnipresent na web 
- App híbrido
- Aplicação de ponta-a-ponta: banco de dados, back-end / front-end
- Interagir com DOM (api-web)
- Requisições dinâmicas 
- IoT (internet das coisas): o JS está presente em tudo
- ECMAScript 

## Fundamentos do JS
- Fundamentos do JavaScript são essenciais para avançar no desenvolvimento de aplicações modernas, é a base de diversoso frameworks
- Neste curso evoluímos da base para o topo
- É meçhor que começar na frente e precisar retornar a base


## Lógica de Programação 
| - Computador 
|   -- M´quina que extrai dados 
|   -- Processar: realizar operações nos dados de entrada
| - Dado: é o que pode ser processado
| - Informação: resultado do processamento 
| - Processamento de dados: Entrada (dados) > Processamento > Saída (informação)
|
|Como escrever um programa?
| - Aplicar a lógica para descrever os passos para resolver um problema em ordem de execução 
|
|A Lógica de programação 
| - É a técnica de sequenciar pesnamentos, passos, fluxo de dados para atingir um objetivo: a informação
| - A sequencia de passos, instruções que o computador deve seguir é conhecida como algoritmo
|
| Algoritmo
| - Sequencia lógica e finita de instruções que resolvem o problema 
| - Exemplo: recetia de bolo, manual de instruções
| - Nem todo algoritmo é um programa de computador, mas todo programa é um algoritmo
| - Quem viabiliza o funcionamento dos algoritmos nos computadores: linguagens de programação


### Algoritmo para calcular a media de 3 números
1. Início;
2. Receber o primeiro número: entrada 1;
3. Receber o segundo número: entrada 2;
4. Receber o terceiro número: entrada 3;
5. Processamento: Somar os 3 números recebidos e dividir por três: (entrada 1 + entrada 2 + entrada 3) / 3;
6. Exibir o resultado: print, echo, console.log;
7. Fim;

### Torre de Hanoi
 - Mover todos os discos para a direita, com o menor número de movimentos possíveis, sem colocar um disco em cima de um disco menor: https://www.somatematica.com.br/jogos/hanoi

## Funcionalidades Gerais 
 - Cirar algoritmos e programas para executar no navegador: client side 
 - Manipular o DOM: elementos HTML, eventos (clics, submit), estilos CSS 
 - Node.js: framework JS para back-end / runtime em JS
 - Mongo.db / GraphQL: banco de dados em JS
 - React / Vue.js / Angular: framework JS para desenvolvimento web / mobile
 - React native: framework JS para desenvolvimento mobile

 - recebe e manipula dados 
 - tomar decisoes baseados na lógica computacional 
 - loop e interações 
 - condições de saída

 ### Executar o JS 
 - Console borwser
 - Editores: Sublime, VSCode
 - JS Fiffle https://jsfiddle.net/

 ### Instalação do Node.js
 - Para conseguir executar o scripts JS no terminal de comando, precisamos utilizar o node.js
 - Instalação: https://nodejs.org/pt-br/download/package-manager/

 ## Iniciar o Node
 - Abrir o terminal e digitar node

 ## Variáveis 
São utilizadas para referenciar espaço na memória

 - var
 - const (fica com valor imutável)
 - let
 - string (tipo de variável para conjunto de caracteres)
 - tipagem: numero ou string
 - array (conjunto de valores) utiliza os colchetes []

 ## Operadores 
 - Soma +
 - Subtração -
 - Multiplicar *
 - Dividir /
 - Módulo (rsto de divisão) %
 - Math: random(), round (), sqrt ().

 * Atribuição 
 a = b
 a += b
 a -= b
 a *= b
 a /= b
 a %= b
 No caso de usar os dois operadores (ex: a += b) irá primeiro somar o valor de a com o valor de b e o vaor de a sera transformado nesse valor resultante 

 * Operadores de Comparação 
 - Igual == ou ===
 - Diferente !=
 - Maior que >
 - Menor que <
 - Maior ou igual >=
 - Menor ou igual <=
 - === Igualdade de valor e tipo

 Adiciona 1 ++ (ex: a = 15; a++, a = 16)
 Subtrai 1 -- (ex: a = 15; a--, a = 14)

Consulta a operadores 
https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Expressions_and_operators

## Operadores de lógica e jumção lógica 
- Não (NOT) !
- E (AND) &&
- Ou (OR) ||

O sinal de exclamação é o operador NOT, utilizado para negar a sentença que vem na sequencia. 

### As condições lógicas são convertidas em números binários:
true é equivalente a 1 
false é equivalente a 0

### Operaor lógico de atribuição 

Tem a capacidade de atribuir valor a uma variável a partir de uma condição lógica, economiza IFs

Exemplo:

var meuCarro = cor == "preto" ? "preto" : "branco";

## If
if (...) {
    ...
}

## Else
else {

}

if (cor == "preto") {
    meuCarro = "preto";
} else {
    meuCarro = "cinza";
}

// o if e else é basicamente um 'se, entao' a primeira condição if em parenteses defique o valor que se verdadeiro ja aparece define a condição estabelecida, caso seja falso irá resultar o parametro else. 

## Else If
if (cor == "preto") {
    meuCarro = "preto";
} else if (cor == "vermelho") {
    meuCarro = "cinza";
} else if (cor == "amarelo") {
    meuCarro = "branco";
} else {
    meCarro = "azul";
}

## Switch

switch (cor) {
    case 'branco' : 
        meuCarro = 'branco'
        break;
    case 'vermelho' :
        meuCarro = 'vermelho'
        break;
    case 'amarelo' :
        meuCarro = 'amarelo'
        break;
    default :
        console.log('não temos a cor desejada');
}

## Media 
var nota1 = 10;
var nota2 = 8;
var nota3 = 9;
var nota4 = 7;

var media = (nota1 + nota2 + nota3 + nota4) / 4;

if(media >= 8) {
    console.log('Aluno aprovado')
} else {
    console.log('Aluno em recuperação)
}

## Laços de repetição 
for ([expressaoInicial]; [condicao]; [incremento])

// faer a revisão do carro aos 10 km //
var km;
var revisao = 10;

for(km = 0; km <= revisao; km++){
    console.log("apenas" + km "kms, então pode rodar")
}

## Cálculo de média de alunos 

var alunos = [
    [6, 7, 8, 6],
    [8, 5, 6, 8],
    [10, 6, 8, 7]
]

var nota = 0;
for (var i = 0; i < alunos.length; i ++){

    nota = 0
    aluno = alunos[i]
    console.log("Aluno: " + aluno);
    
    for(c = 0; c < aluno.length; c++){
        nota += aluno[c];
    }
	
  	var media;
    
    meida = nota / 4;
    
    if(media >= 7) {
        resultado = "aprovado";
    } else {
        resultado = "reprovado";
    }
    console.log("Media " + media + " - " + resultado);
}

while ( condição ) {    //Enquanto existir a condição ele irá executar//
    [execução] 
}
// Precisa ter uma condição de saida//

var contador  = 0;
while(contador < 10) {
    contador++
}    

ou

var hora = 23;
while(hora > 0) {
    hora--;
    console.log(hora):
}

## Funções 

- Evitar a repetição de código
- Realuizar chamadas dinamicas de algoritmos 

function claculoMedia( notas ) {

    let soma = 0;
    for( c = 0; c < notas.length; c++){
        soma += notas[c];
    }
    
    media = soma / notas.length;

    return media;
}

function aprovacao (media) {

	let condicao = media >= 7 ? "aprovado" : "reprovado";
  
  return condicao; 
}

function aprovacao2 (notas) {

	let media = claculoMedia( notas );
	let condicao = media >= 7 ? "aprovado" : "reprovado";
  
  return media + ' - Resultado: ' + condicao; 
}

//onsole.log("Média: " + claculoMedia([7, 6]))
//console.log(aprovacao2 (claculoMedia([7, 6])))

//console.log("Média: " + claculoMedia([7, 8, 9]))
//console.log(aprovacao2 (claculoMedia([7, 8, 9])))

console.log(aprovacao2([8, 8, 7]))

Explicação: A função é específica, criada para fazer uma ação, ela só funciona se for 'chamada' ou seja, ela é cirada e fica lá até precisar dela, entao coloca ela em uma ação. 
Estrutura: function NomeDaFunção (Parametros) {
    o que a função irá executar 

    return o que irá aparecer de resultado
}
Com isso você pode chamar a função quantas vezes forem necessário sem precisar repetir o código, evitando repetições desnecessárias. 

