| difficulty | OAs     | projects                |
| ---------- | ------- | ----------------------- |
| beginner   | strings | cipher, card validation |

# Remove String Spaces

[https://www.codewars.com/kata/57eae20f5500ad98e50002c5/train/javascript](https://www.codewars.com/kata/57eae20f5500ad98e50002c5/train/javascript)

Simples, remova os espaços da string e retorne a string resultante.

**Exemplos**

```js
noSpace('8 j 8   mBliB8g  imjB8B8  jl  B') ➞ '8j8mBliB8gimjB8B8jlB'
noSpace('8 8 Bi fk8h B 8 BB8B B B  B888 c hl8 BhB fd') ➞ '88Bifk8hB8BB8BBBB888chl8BhBfd'
noSpace('8aaaaa dddd r     ') ➞ '8aaaaaddddr'
```

> **Importante** ❗
>
> - As strings passadas consistirão apenas em letras e espaços.

↩️ [Voltar](../../README.md)

Resposta: 
![image](https://user-images.githubusercontent.com/83047245/174204773-30b9294b-eda2-4c16-9ff2-091c85888d68.png)

O método split() divide uma String em uma lista ordenada de substrings, coloca essas substrings em um array e retorna o array. A divisão é feita procurando um padrão, onde o padrão é fornecido como o primeiro parâmetro na chamada do método.

Como juntar um array em uma string JavaScript?
Para juntar os elementos do array, usamos o método arr. join(). Este método é usado para juntar os elementos de um array em uma string. Os elementos da string serão separados por um separador especificado e seu valor padrão é uma vírgula (,).
