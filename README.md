# Javascript-iniciante </br>
__Um guia básica para quem está começando em Javascript__ ![logo javascript](https://www.google.com/url?sa=i&url=https%3A%2F%2Fpcodinomebzero.neocities.org%2FPages%2FJavaScript.html&psig=AOvVaw3sd6kxYw9J3wefhF-9Db5t&ust=1647089726133000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCNi_zcaNvvYCFQAAAAAdAAAAABAO)
## 1 Variáveis
Responsaveis por guardar dados na memória.
inicia com a palavra var,let ou const

<p>
Exemplo </br>
var nome = 'thiago'; </br>                            
let idade = 28; </br>
const posuiFaculdade = false; </br>
</p>

_obs: mas tarde vamos ver a diferença dessas três_

### Sintaxe

<p>
Palavra chave **var** seguida do **nome**, sinal de **igual** e o **valor**.</br>

var nome = 'Thiago';</br>
var idade = 27;</br>
var possuiFaculdade = true;</br>
</p>

### Vírgula
<p>
Utilizei a vírgula para criar mais de uma variável, sem repetir a
palavra chave var. </br>

var nome = 'Thiago',</br>
idade = 27,</br>
possuiFaculdade = true;
</p>
### Sem valor
<p>
Pode declarar ela e não atribuir valor inicialmente. </br>

var precoBanana;<br>
// retorna undefined
</p>

### Como nomear uma variavel

1. podem iniciar com $, _, ou letras.
Podem conter números mas não iniciar com eles

2. Case sensitive
nome é diferente de Nome

3. Não utilizar palavras reservadas
aqui vai um link das palavras reservadas--> https://www.w3schools.com/js/js_reserved.asp

4. Camel case
É comum nomearmos assim: abrirModal

<p>
exemplo

// Inválido</br>
var §nome;</br>
var function;</br>
var 1possuiFaculdade;</br>

// Válido</br>
var $selecionar;</br>
var _nome;</br>
var possuiFaculdadeNoExterior;
</p>

### Hoisting
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
