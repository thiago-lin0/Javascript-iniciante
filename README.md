# Javascript-iniciante
## 1 Variáveis
Responsaveis por guardar dados na memória.
inicia com a palavra var,let ou const

exemplo
var nome = 'thiago';                             
let idade = 28;
const posuiFaculdade = false;

obs: mas tarde vamos ver a diferença dessas três

**Sintaxe**
Palavra chave var seguida do nome, sinal de igual e o valor.

var nome = 'Thiago';
var idade = 27;
var possuiFaculdade = true;

**Vírgula**
Utilizei a vírgula para criar mais de uma variável, sem repetir a
palavra chave var.

var nome = 'Thiago',
idade = 27,
possuiFaculdade = true;

**Sem valor**
Pode declarar ela e não atribuir valor inicialmente.

var precoBanana;
// retorna undefined

*Como nomear uma variavel

1-podem iniciar com $, _, ou letras.
Podem conter números mas não iniciar com eles

2-Case sensitive
nome é diferente de Nome

3-Não utilizar palavras reservadas
aqui vai um link das palavras reservadas--> https://www.w3schools.com/js/js_reserved.asp

4-Camel case
É comum nomearmos assim: abrirModal

exemplo

// Inválido
var §nome;
var function;
var 1possuiFaculdade;

// Válido
var $selecionar;
var _nome;
var possuiFaculdadeNoExterior;

*Hoisting
São movidas para cima do código, porém o valor atribuído não é
movido.

console.log(nome);
var nome = 'André'; // Retorna undefined

var profissao = 'Professor';
console.log(profissao); --> // Retornar Professor

*Mudar o valor atribuído
É possível mudar os valores atribuídos a variáveis declaradas com
var e let . Porém não é possível modificar valores das declaradas com const

var idade = 27;
idade = 29;
let preco = 50;
preco = 25;
const possuiFaculdade = true;
possuiFaculdade = false;
// Retorna um erro

--> obs: dentro da pasta variaveis tem uns exercicios tente fazer para práticar

## 2 tipos de dados
