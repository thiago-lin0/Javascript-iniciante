![logo javascript](https://cdn.iconscout.com/icon/free/png-256/javascript-2752148-2284965.png)
# Javascript para iniciante </br>

__Um guia básica para quem está começando em Javascript__
## 1 Variáveis
Responsaveis por guardar dados na memória.
inicia com a palavra var,let ou const

<p>
Exemplo
</p>

~~~javascript
var nome = 'thiago';                      
let idade = 28;
const posuiFaculdade = false; 
~~~

_obs: mas tarde vamos ver a diferença dessas três_

### Sintaxe


Palavra chave **var** seguida do **nome**, sinal de **igual** e o **valor**.

</br>

~~~javascript
var nome = 'Thiago';
var idade = 27;
var possuiFaculdade = true;
~~~

### Vírgula
<p>
Utilizei a vírgula para criar mais de uma variável, sem repetir a
palavra chave var.</p>
</br>

~~~javascript
var nome = 'Thiago',
idade = 27,
possuiFaculdade = true;
~~~
### Sem valor
<p>
Pode declarar ela e não atribuir valor inicialmente.
</p>
</br>

~~~javascript
var precoBanana;
// retorna undefined
~~~

### Como nomear uma variavel

1. podem iniciar com $, _, ou letras.
Podem conter números mas não iniciar com eles

2. Case sensitive
nome é diferente de Nome

3. Não utilizar palavras reservadas</br>
aqui vai um link das palavras reservadas --> (https://www.w3schools.com/js/js_reserved.asp)

4. Camel case
É comum nomearmos assim: abrirModal

<p>
exemplo
</p>

__Inválido__
~~~javascript
var §nome;
var function;
var 1possuiFaculdade;
~~~
__Válido__
~~~javascript
var $selecionar;
var _nome;
var possuiFaculdadeNoExterior;
~~~

### Hoisting
<p>
São movidas para cima do código, porém o valor atribuído não é
movido.
</p>

~~~javascript
console.log(nome);
var nome = 'André';  //Retorna undefined
var profissao = 'Professor';
console.log(profissao); //Retornar Professor
~~~

### Mudar o valor atribuído
<p>É possível mudar os valores atribuídos a variáveis declaradas com
var e let . Porém não é possível modificar valores das declaradas com const</p>

~~~javascript
var idade = 27;
idade = 29;
let preco = 50;
preco = 25;
const possuiFaculdade = true;
possuiFaculdade = false;

//Retorna um erro
~~~
**obs: dentro da pasta variaveis tem uns exercicios tente fazer para práticar**

## 2 tipos de dados

Todos são primitivos exceto os objetos

~~~javascript
var nome = 'Thiago'; // String
var idade = 27; // Number
var possuiFaculdade = true; // Boolean
var time; // Undefined
var comida = null; // Null
var simbolo = Symbol() // Symbol
var novoObjeto = {} // Object
~~~
Primitivos são dados imutaveis 

### Veerificar tipo de dado

~~~javascript
var nome = 'Thiago';
console.log(typeof nome);
// retorna string
~~~
typeof null  retorna object

### String

Você pode somar uma string e assim concatenar as palavras.

~~~javascript
var nome = 'Thiago';
var sobrenome = 'Lino';
var nomeCompleto = nome + ' ' + sobrenome;
~~~
Você pode somar números com strings, o resultado nal é sempre uma string.
~~~javascript
var gols = 1000;
var frase = 'Romário fez ' + gols + ' gols';
~~~

Aspas Duplas, Simples e Template String

~~~javascript
'JavaScript é "super" fácil';
"JavaScript é 'super' fácil";
"JavaScript é \"super\" fácil";
`JavaScript é "super" fácil"`;
"JavaScript é "super" fácil"; // Inválido
~~~

Não necessariamente precisamos </br>
atribuir valores a uma variável

### Template String

~~~javascript
var gols = 1000;
var frase1 = 'Romário fez ' + gols + ' gols';
var frase2 = `Romário fez ${gols} gols`; // Utilizando Template String
~~~

Você deve passar expressões / <br>
variáveis dentro de ${}

**obs: dentro da pasta tipos de dados tem uns exercicios tente fazer para práticar**
