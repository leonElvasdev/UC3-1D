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
  
* O que é string?
  
 strings são sequências de letras, números e/ou símbolos usadas em programação. Em Javascript, uma string sempre estará entre (aspas).
 
Ex:
```JS
const fruta = "banana"
// ["b", "a", "n", "a", "n", "a"]
```
```JS
console.log('Estudando')
```

* O que é numbers?

  É um objeto encapsulado que permite você trabalhar com valores numéricos. Um objeto Number é criado utilizando o construtor Number().

* O que é array?
  
 Os arrays são estruturas que servem para guardar dados, e organizá-los. Seu objetivo é ser um espaço fixo na memória do computador que armazena elementos.
  

* O que é switch case

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

Nós aprendemos a criar um tipo de biblioteca, aonde aprendemos códigos para retirar livros e adicionar novos livros, a nossa livraria. Também aprendemos como saber o numero da posição, em que os livros estão.

```JS
const livros = ["Javascript Assertivo", "ECMAScript 6", "MongoDB", "Leon", "vivi", "run", "lavi", "bob"]
console.log(livros[0]);
console.log(livros[1]);
console.log(livros[2]);
console.log(livros[3]);
```
Consultar o nomero dos livros da const 
```JS
let consulta = livros.indexOf("ECMAScript 6")
console.log(consulta)
```
Para retilar o ultimo livro do "const livros"
```JS
console.log(livros.pop());
```
