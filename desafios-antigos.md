## Desafios antigos

### 001 - Validar Senha

Escreva um programa que valide uma senha. As regras pra isso são:

- Ter entre 5 e 10 caracteres
- Conter pelo menos um dígito de 0-9
- Conter pelo menos um caractere especial
- Não conter espaços

---

### 002 - Soma

Escreva um programa que receba como primeiro argumento (teu_programa arquivo.txt) o nome de um arquivo de texto cujo conteúdo é uma lista de números inteiros, um em cada linha, e imprima a soma de todos eles.

Exemplo de entrada:

```js
1
2
3
4
5
```

Exemplo de saída:

```js
15
```

---

### 003 - Maior Palavra (desafio by: @Black )

Escreva uma função ou método que receba um parametro do tipo String e compare qual é a maior palavra da String.

Especificações:

- Se a frase conter 2 ou mais palavras com o mesmo tamanho, retorne a primeira palavra com esse tamanho;
- A String precisa ter no minimo 2 palavras;
- Só são validos caracteres não especiais.

Exemplo de entrada:

```css
I&#$% love dogs
```

Exemplo de saida:

```css
love
```

---

### 004 - Chess Travel (desafio by: @Black )

Tenha em mente o seguinte tabuleiro 8x8:

```js
     01 02 03 04 05 06 07 08
     -----------------------
 A | 01 02 03 04 05 06 07 08
 B | 09 10 11 12 13 14 15 16
 C | 17 18 19 20 21 22 23 24
 D | 25 26 27 28 29 30 31 32
 E | 33 34 35 36 37 38 39 40
 F | 41 42 43 44 45 46 47 48
 G | 49 50 51 52 53 54 55 56
 H | 57 58 59 60 61 62 63 64
```

Faça com que o programa leia um inteiro entre 1 e 8 e um caractere entre A e H. Feito isso, calcule que posição essa coordenada corresponde no mapa do tabuleiro e mostre o numero dessa posição para o usuario.

Exemplo de entrada:

```js
5
F
```
Exemplo de saída:

```js
O numero dessa posição é: 45
```

---

### 005 - Cifra de César

Escreva um programa que receba uma string, uma chave e retorne o texto codificado usando a [Cifra de César](https://pt.wikipedia.org/wiki/Cifra_de_C%C3%A9sar).

Exemplo de entrada:

```css
eu amo pao de queijo
3
```

Exemplo de saída:

```
hx dpr sdr gh txhlmr
```

---

### 006 - Números Jooj (Desafio by: @jooj )

Geraldo está procurando algo para impressionar as meninas de sua sala e se tornar o gadão primordial. 
Nessa busca por fatos interessantes do universo, ele percebeu que existem alguns números que possuem exatamente 3 divisores distintos, 
os quais ele chamou de números Jooj. Geraldo está convencido que a melhor forma de se impressionar as garotas de sua sala é escrevendo um programa que indica se um número é jooj ou não, porém ele está tendo problemas com isso e pediu a ajuda de vocês.

Neste desafio, vocês terão que escrever um programa que indica se um número é Jooj ou não.
Um número Jooj é um número que possui exatamente 3 divisores distintos.

Entrada:

```
A entrada irá conter um inteiro positivo.
```

Saída:

```
A saída deverá conter "Eh jooj" caso o número seja jooj ou "Nao eh jooj" caso ele não seja.
```

Exemplos de execução:

#### Exemplo 1

```
4
Eh jooj
```

#### Exemplo 2

```
6
Nao eh jooj
```

No Exemplo 1, 4 é jooj porque possui exatamente 3 divisores: {1,2,4}

No Exemplo 2, 6 não é jooj porque possui 4 divisores: {1,2,3,6}

---

### Desafios Adicionais

Além de resolver o problema, ainda há mais alguns desafios. O intuito desses desafios adicionais é não somente resolver o problema, mas também resolvê-lo de forma eficiente. Dito isso, além do seu programa estar correto o tempo de execução dele deve ser inferior a 1 segundo (2 segundos para linguagens puramente funcionais)

#### Normal
Entrada: 100140049
Resultado esperado: Eh jooj

#### Difícil
Entrada: 953636840569344196225489
Resultado esperado: Eh jooj

#### Insano
Entrada: 1935156371024460472410954940561
Resultado esperado: Eh jooj

---

### 007 - Combinações Lotéricas (Desafio by: @Nosomy )

Geraldo, ainda na sua busca por fatos do universo, descobriu que para finalmente se tornar o Gadão Primordial e conquistar as meninas de sua sala percebeu que precisa ficar trilionário para o feito.

Geraldo então achou que o meio mais fácil para o mesmo, seria ganhando na Mega-Sena.
Para isto, Geraldo precisará da ajuda de vocês para criar um programa que faça Combinações Lotéricas.

Neste desafio, vocês terão que escrever um programa que peça uma quantidade de números da combinação, a quantidade de números que serão sorteados, a posição da combinação e retorne o resultado da mesma.

Entrada:

```
A entrada irá conter um número inteiro positivo, para a quantia de números da combinação, a quantidade de números sorteados e a posição da combinação.
```

Saída:

```
A saída deverá conter a combinação da faixa.
```

Exemplos de execução:

#### Exemplo 1:

> 60 6 1
01 02 03 04 05 06


#### Exemplo 2:

> 60 6 50063860
55 56 57 58 59 60


#### Exemplo 3:

> 60 6 1000000
01 04 13 23 30 60

---

### 008 - Validando entrada de dados

Crie um programa que crie uma função, usarei como exemploleiaInt(), que vai funcionar de forma semelhante à função input() do Python, só que fazendo a validação para aceitar apenas um valor numérico.

#### Exemplo 1:

Entrada:
```js
Digite um número:
7
```

Saída:
```js
Você acabou de digitar o número 7.
```

#### Exemplo 2:

Entrada:

```css
Digite um número:
```

Saída:

```css
Digite um número inteiro válido.
```

#### Exemplo 3:

Entrada:

```css
Digite um número: cinco
```

Saída:

```css
Digite um número válido!
```
---
