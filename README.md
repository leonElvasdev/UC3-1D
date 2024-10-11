# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 




## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

* O que é logica da programação?
  
   Logica da programação seria uma sequências logica de códigos, para alcançar algo um objetivo especifico.
  
* O que seria código?
  
  Eles são responsaveis por criar programas de computador, que podem realizar uma ampla variedade de tarefas. 

* O que é java Javascript

  Javascript é conhecido como uma linguagem de código, muito avançada e difícil, ele serve para deixar, os códigos, mais dinâmicos e interessantes.
  
 ## String
  
 strings são sequências de letras, números e/ou símbolos usadas em programação. Em Javascript, uma string sempre estará entre (aspas).
 
Ex:
```JS
const fruta = "banana"
// ["b", "a", "n", "a", "n", "a"]
```
```JS
console.log('Estudando')
```

## Numbers

  É um objeto encapsulado que permite você trabalhar com valores numéricos. Um objeto Number é criado utilizando o construtor Number().

## Array

**O que é uma Array?**
 
  Os arrays são estruturas que servem para guardar dados, e organizá-los. Seu objetivo é ser um espaço fixo na memória do computador que armazena elementos. Esses elementos podem ser acessados por um tipo de indicação, que chamamos de índice.
  
 
**Para que serve um array?**
 
  array é uma estrutura de dados que serve para guardar elementos em um espaço da memória. Estes espaços da memória são chamados de **variáveis**.
  

  **Como funciona um Array em Javascript?**
  
  Em Javascript os arrays se comportam de forma parecida ao buscar o item na lista, a diferença é que ele começa a contar do zero.
  
  
  **Como declarar um Array em JavaScript?**

  Existem duas formas de declarar um array em Javascript, mas a mais comum delas é criando uma variável da seguinte forma:
  ```JS
  var listaDeFrutas = ['Maçãs','Uvas','Bananas','Abacaxi','Morangos'];
  ```
  cada item da lista é separado por vírgulas e ocupa uma posição do array *listaDeFrutas* iniciando no índice zero. Essa forma é chamada de método literal de array.



## switch case

* variaveis
  Var: Ela pode ser reatribuída e redeclarada. Diferentemente da const e da let ela não tem escopo de bloco.
  Let: Ela também pode ter o seu valor reatribuido mas não pode ser redeclarado.
  const: Ela não pode ter seu valor reatribuído nem redeclarado. Diferentemente da let e da var. E assim com a let ela também tem escopo de bloco.



## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

[Switch Case: Da farmacia](https://codepen.io/LEONCIoo/pen/GRbOQQd?editors=0012)

Nós aprendemos a criar um tipo de atendimento, para uma farmácia, a onde a gente teria que escrever um código para pergunta qual o medicamento que o cliente deseja e o bairro em que o cliente mora, programar as respostas, possíveis do atendimento

Codigos Usados: 

#### Para fazer as perguntas 
```JS
const produto = prompt("Qual remedio você deseja?")
const bairro = prompt("Qual o bairro que você mora?")
```
[Array: Biblioteca](https://codepen.io/LEONCIoo/pen/gONoQJV)

Nós aprendemos a criar um tipo de biblioteca, onde aprendemos códigos para retirar livros e adicionar novos livros à nossa livraria. Também aprendemos como saber o número da posição, em que os livros estão.

```JS
const livros = ["Javascript Assertivo", "ECMAScript 6", "MongoDB", "Leon", "vivi", "run", "lavi", "bob"]
console.log(livros[0]);
console.log(livros[1]);
console.log(livros[2]);
console.log(livros[3]);
```

Consultar o número dos livros da const 
```JS
let consulta = livros.indexOf("ECMAScript 6")
console.log(consulta)
```

Para retirar o ultimo livro do "const livros"
```JS
console.log(livros.pop());
```

Para adicionar um novo livro
```JS
console.log(livros.push("Moi"));
```

Para deixar em ordem alfabética   
```JS
console.log(livros.sort());
```
[Switch Case: Mercadinho de Fruta ](https://codepen.io/LEONCIoo/pen/bGPaOYg)

Essa atividade,foi feita em equipe por mim, julia e Victoria. a gente fez quase o mesmo esquema da farmacia.



