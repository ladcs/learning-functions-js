# :construction: Learning functions js / Aprendendo funções js  :construction:

This is my first program in JavaScript, In this project I learning how use operator logical and create functions. In any moments I used some Hof and native functions.

<details>
  <summary><strong>🤷🏽‍♀️ Português</strong></summary><br />
  Esse é o meu primeiro programa em JavaScript, nesse projeto eu aprendi como usar operadores lógicos e criar funções. Em alguns momentos eu usei HoF e funções nativas.
</details>

<details>
  <summary><strong>:sunglasses: compareTrue</strong></summary><br />
  This function return a boolean, this boolean depends two other booleans, if both is true then return true, if any is false, return false, used operator &&.
</details>

  <details>
  <summary><strong>🤷🏽‍♀️ :sunglasses: Português: compareTrue </strong></summary><br />
    Essa função retorna um boleano, esse boleano depende de outros dois booleanos, se ambos forem verdadeiro, o retorno será verdadeiro, caso qualquer um seja falso o retorno será falso, foi usado o operador &&.
</details>

<details>
  <summary><strong>:sunglasses: calcArea </strong></summary><br />
  Return triangle area, depends two params base and heigth.
</details>
<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: calcArea</strong></summary>
  Retorna a área do triangulo, depende de dois parametros, base e altura.
</details>

<details>
  <summary><strong>:sunglasses: splitSentence </strong></summary>
  Get a string then split where find a space, then put in array. Used HoF split.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português:splitSentence </strong></summary>
  Recebe uma string, separa quando achar um espaço e armazena em um array. Usando a HoF split.
</details>

<details>
  <summary><strong>:sunglasses: concatName </strong> </summary> <br />
  Receve a Array, get the last element then concat with the first element, return '[last element], [first element]'.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: concatName </strong></summary>
  Recebe um array, pega o último elemento e concatena com o primeiro, retorno '[ultimo elemento], [primeiro elemento]'.
</details>

<details>
  <summary><strong>:sunglasses: footballPoints </strong> </summary> <br />
  receve wins and ties for a team then return points of this team, the points is 3*wins + ties.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: footballPoints </strong></summary>
  Recebe vitórias e empate de um time e retorna os pontos do time, os pontos são 3*vitoria + empates.
</details>

<details>
  <summary><strong>:sunglasses: highestCount </strong> </summary> <br />
  Receve a Array, return the number of high number appers in this array, used function max, today I do with HoF filter.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: highestCount </strong></summary>
  Recebe um array, retorna a quantidade de vezes que o maior número aparece nesse array, usando a função max, hoje eu iria fazer com HoF filter.
</details>

<details>
  <summary><strong>:sunglasses: catAndMouse </strong> </summary> <br />
  Receve three numbers, first is the position of mouse, second is the position of first cat and the last is the position of other cat, if the mouse is more near of first cat the return is cat1, if is near the second cat the return is cat2 and if the distance of two cats is the same the return is 'os gatos trombam e o rato foge'.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: catAndMouse </strong></summary>
  Recebe três parametros, o primeiro é a posição do rato, o segundo é a posição do primeiro gato e o ultimo é a posição do segundo gato, se o rato estivar mais perto do primeiro gato o retorno é 'cat1', se o rato estiver mais perto do segundo gato o retorno é 'cat2' e caso o rato estiver entre os dois gatos o retorno é 'os gatos trombam e o rato foge'.
</details>

<details>
  <summary><strong>:sunglasses: fizzBuzz </strong> </summary> <br />
  Receve a Array, if the number is multiple of 3 return 'fizz', if the number is multiple of 5 return 'buzz', if the number is multiple 3 and 5 return 'fizzBuzz' and if is not multiple 3 or 5 return 'bug!' for all numbers in array.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: fizzBuzz </strong></summary>
  Recebe um array, se o numero for múltiplo de 3 retorna 'fizz', se for múltiplo de 5 retorna 'buzz', se for múltiplo de 3 e de 5 retorna 'fizzBuzz' caso não seja múltiplo de 3 ou de 5 returna 'bug!' para todos os números no array.
</details>

<details>
  <summary><strong>:sunglasses: encode and decode </strong> </summary> <br />
  Receve a string to encode or to decode, the encode will change the letter to number and decode will change number to letter, this change is:

  a <-> 1 \
  e <-> 2 \
  i <-> 3 \
  o <-> 4 \
  u <-> 5
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: encode and decode </strong> </summary> <br />
  Recebe uma string para encode ou para decode, o encode mudará letra por número e decode mudará número por letra, essa mudança é:

  a <-> 1 \
  e <-> 2 \
  i <-> 3 \
  o <-> 4 \
  u <-> 5
</details>

<details>
  <summary><strong>:sunglasses: techList </strong> </summary> <br />
  Receve a Array and a name, return a array of object with key tech and name, tech receve a item of params array, and name the name receve, order by tech.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: techList </strong></summary>
  Recebe um array e um nome, retorna um array de obejtos com as chaves tech e nome, a chave tech recebe um item da lista de entrada e o nome recebe o nome, ordenado pela chave tech.
</details>

<details>
  <summary><strong>:sunglasses: generatePhoneNumber </strong> </summary> <br />
  Receve a Array with 11 numbers, if in this array are three or more equals numbers or one number is less then 0 or more then 9 return 'não é possível gerar um número de telefone com esses valores', if aren't 11 numbers in this array the return is 'Array com tamanho incorreto.', if the 11 numbers is correct return (array[0]array[1]) array[2]array[3]array[4]array[5]array[6]-array[7]array[8]array[9]array[10]array[11].
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: generatePhoneNumber </strong></summary>
  Recebe um array com 11 números, se no array tem três ou mais números iguais ou um número menor que zero ou maior que 9 retorna 'não é possível gerar um número de telefone com esses valores', se não tiver 11 números retorna 'Array com tamanho incorreto.', se tiver 11 números corretos retorna (array[0]array[1]) array[2]array[3]array[4]array[5]array[6]-array[7]array[8]array[9]array[10]array[11].
</details>

<details>
  <summary><strong>:sunglasses: triangleCheck </strong> </summary> <br />
  Receve three number, this numbers represent lines, sum of two lines need be more then other line and the absolut subtraction of 2 lines needs to be more then other line. In this case return true, in other case return false.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: triangleCheck </strong></summary>
  Recebe três números, esses números representam linhas, a soma de duas linhas precisam ser maior que a outra linha e a subtração absoluta de 2 linhas precisam ser maior que a outra linha. Nesse caso retorna true, em outro caso retorna false.
</details>

<details>
  <summary><strong>:sunglasses: hydrate </strong> </summary> <br />
  Receve a string, this string have numbers and drinks, for n drinks return n glasses of water, if is 1 drink the return is '1 copo de água' or if 3 beers, 1 wine return '4 copos de água'.
</details>

<details>
  <summary><strong>🤷🏽‍♀️:sunglasses: Português: hydrate </strong></summary>
  Recebe uma string, essa string tem números e bebidas, para n bebidas retorna n copos de água, exemplo 1 cerveja return '1 copo de água' ou se for '3 cervejas, 1 vinho' retorna '4 copos de água'.
</details>

# :construction: README em construção ! :construction:

<!-- Olá, Tryber!
Esse é apenas um arquivo inicial para o README do seu projeto.
É essencial que você preencha esse documento por conta própria, ok?
Não deixe de usar nossas dicas de escrita de README de projetos, e deixe sua criatividade brilhar!
:warning: IMPORTANTE: você precisa deixar nítido:
- quais arquivos/pastas foram desenvolvidos por você; 
- quais arquivos/pastas foram desenvolvidos por outra pessoa estudante;
- quais arquivos/pastas foram desenvolvidos pela Trybe.
-->