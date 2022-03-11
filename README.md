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
var nome = 'thiago'; </br>                            
let idade = 28; </br>
const posuiFaculdade = false; </br>
~~~

_obs: mas tarde vamos ver a diferença dessas três_

### Sintaxe

<p>
Palavra chave **var** seguida do **nome**, sinal de **igual** e o **valor**.
</p>
</br>

~~~javascript
var nome = 'Thiago';</br>
var idade = 27;</br>
var possuiFaculdade = true;</br>
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
aqui vai um link das palavras reservadas--> (https://www.w3schools.com/js/js_reserved.asp)

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
