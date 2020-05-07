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

### 009 - Numeros decrescentes (by: @azure)

Seu objetivo é pegar um inteiro não-negativo e transforma-lo em um outro inteiro, porem com os numeros em forma decrescente.

#### Exemplos:

Input: 
`21445`
Output: 
`54421`

Input: 
`145263` 
Output: 
`654321`

Input: 
`1254859723` 
Output: 
`9875543221`

---

### 010 - Projeto Educativo

Crie um programa que seja do tema educativo, didático. 
Basicamente, você terá que criar um programa educativo, que o usuário possa interagir com o mesmo.
O desafio pode ser um jogo, site, app pra celular, programa de pc, pode até mesmo ser feito em Arduino.

#### Instruções:
O programa pode ser, tanto por linha de texto, quanto por interface gráfica.
O projeto poderá ser feito em qualquer linguagem de programação ou marcação, pode inclusive ser um site.
O usuário deve, de alguma forma, interagir com o programa, nem que seja só com **1** entrada de informação.

---

### 011 - Sequência de Fibonacci (by: @sidemazE)

A seguinte sequência de números `0 1 1 2 3 5 8 13 21...` é conhecida como sequência de **Fibonacci**.
Nessa sequência, cada número depois dos 2 primeiros, é igual à soma dos 2 anteriores.
Escreva um algoritmo que leia um inteiro N (N < 46) e mostre os N primeiros números dessa série.

#### Exemplo:

Entrada:
`6`

Saída:
`0 1 1 2 3 5`

---

### 012 - Acordes intergaláticos (by: https://neps.academy/problem/29)

---

### Desafio Extra

> O quanto vocês conseguem dificultar um hello world sem dificultar a vida do usuário?

#### Regras

- Precisa ser criativo.
- Não pode usar dependências externas.
- Pode usar qualquer linguagem, porém, não pode usar mais de 2 linguagens.

Ex.:

`print("Hello, World!")`

Pode virar:

`print("48656c6c6f2c20576f726c6421".decode("hex"))`

Que pode virar:

```js
hex_hello_world = "48656c6c6f2c20576f726c6421" 

def hello_world(hex):
    return bytearray.fromhex(hex).decode()

print(hello_world(hex_hello_world))
```

E assim por diante.

---

### 013 - Quadrado mágico (by: https://neps.academy/problem/236#comments)

---

### 014 - Números gado (by: @jooj)

Um número é gado se ele é formado apenas pelos dígitos x e y.
Um número é demasiado gado se ele é gado e se a soma dos seus dígitos também é gado.

O desafio consiste em receber dois dígitos x e y (0 <= x,y <= 9) e dizer quantos números de n dígitos (1 <= n <= 10^6) são demasiado gado.

Como a resposta pode ser bem grande, ela deverá ser impressa módulo 10^9 + 7.
(Os exemplos abaixo contém 3 números na entrada, pois são os elementos Y, X e N.)

#### Exemplos:

Entrada:
`1 3 3`

Saída:
`1`

O único número que é composto por 1s e 3s com 3 dígitos e é demasiado gado é 111, pois 111 é gado (já que só é composto por 1s) e a soma dos dígitos de 111 (1+1+1 = 3) também é gado.

Entrada:
`1 2 1`

Saída:
`2`

Nessa caso, os únicos números demasiado gado são 1 e 2

Entrada:
`2 3 10`

Saída:
`165`

#### Extra:

Rode esses testes em menos de 1 segundo:
`A: 3 6 1000000`
`B: 8 9 999999`
`C: 1 2 1000000`

---

### Desafio Extra 2: Pares consecutivos

> A soma de três pares consecutivos é igual a X. Determine os números.

Faça um programa que peça a entrada de um número inteiro, maior ou igual a 12.
A saída deverá ser os 3 pares consecutivos, que somados devem dar o número da entrada.

#### Exemplo:

Entrada: 
`90`
Saída: 
`28, 30 e 32`

---

### 015 - Empacotando e Desempacotando Dados (by: @kinash)

Jubileu foi contratado por uma empresa para programar os servidores de um jogo online, que roda pelo navegador. Ao observar que os números enviados pelo servidor ao cliente estavam muito grandes, Jubileu decidiu diminuir o tamanho desses valores, porém, sem deixá-los grandes. Sabendo disso, ajude Jubileu fazendo um programa que converta um número 32-bits em uma lista de 4 números (empacotar). Depois, faça o reverso dessa operação (desempacotar).

Observação:
O valor máximo de cada número dessa lista é 255.

#### Exemplos:

Empacotar:

```js
255 retorna [0, 0, 0, 255]

65535 retorna [0, 0, 255, 255]
```

Desempacotar:
```js
[0, 0, 0, 127] retorna 127

[0, 0, 127, 255] retorna 32767
```

---

### 016 - Datas (by: @toor)

Faça um programa em que o usuário insira duas datas (mês e dia) e ele retorne quantos dias tem entre essas datas.

#### Exemplo:

Entrada:
```js
data1: 01/05
data2: 01/06
```

Saída:
```js
30
```

(Deve se considerar os meses que tem 28 e 30 dias)

---

### 017 - Gangorra (by: https://neps.academy/problem/260)

---

### 018 - Conversão De Bases

Sônia deseja enviar um número para seu computador, mas não sabe como fazer isso, ela pede ajuda ao seu neto que é técnico em informática, como ele sabe que os computadores utilizam a base binária e hexadecimal, ele cria um algoritmo para fazer a conversão da base decimal para a binária e hexadecimal, e envia ao computador.

Escreva um programa com uma função que faça a conversão de um número decimal para binário e hexadecimal, e mostre na tela.

Entrada: 
`Lê o número na base decimal.`

Saída:  
`Retorna o número convertido para a base binária e hexadecimal.`

*Restrições*: Você deve criar sua própria função para fazer a conversão. Sem utilizar funções ja prontas

#### Exemplos:

Entrada:
```js
130
```

Saída:
```js
10000010
82
```

Entrada:
```js
1215
```

Saída:
```js
10010111111
4BF
```

---

### Desafio Extra 3: Triângulo retângulo (by: https://github.com/codehub-discord/desafios/tree/master/06-desenhando-triangulos )

---

### Desafio Extra 4: Trocando Maiúsculas e Minúsculas (by:https://github.com/codehub-discord/desafios/tree/master/13-trocando-maiusculas-minusculas)

---

### 019 - Números Balanceados (by: https://www.codewars.com/kata/5a4e3782880385ba68000018/)

---

### 020- Festa

Astrogildo quer organizar uma festa com seus amigos. Ajude ele para escolher quais
convidar e quais excluir da lista de convidados, para fazer a melhor festa possível.

#### Desafio: 

Astrogildo tem N amigos e cada um possui um A[i] indicando o nível de amizade com
Astrogildo que, quanto maior for, mais Astrogildo aprecia sua presença. Obviamente que
enquanto menor ele não gostaria da sua presença. A beleza da festa é definida pela
soma do nível de amizade dos convidados. É possível que em uma festa, a melhor
soma seja 0, ou seja, uma festa sem amigos.


**Dados de entrada***: A primeira linha do arquivo de entrada contém um inteiro T, que indica a quantidade
de casos de teste. A próxima linha tem o Inteiro N que indica quantos amigos terá, e na
próxima, deverá ter o nível de amizade dos convidados.

***Dados de saída***: A saída deve conter a resposta dos casos de testes que o programa resolveu, para
cada caso de teste deve conter uma linha com esses caracteres:

Caso #t: k

Onde t é o numero de casos de teste (começando do 1) e k o valor da soma.

#### Exemplos:
Você receberá um arquivo e terá que ler suas informações para resolver-lo.
Exemplo de arquivo de entrada:
```js
2
8
1 -4 5 -2 -1 8 0 1
3
-1 -2 -4
```

Saída:
```
Caso #1: 15
Caso #2: 0
```

No primeiro caso de teste, a melhor solução foi obtida convidando o primeiro, terceiro,
sexto, sétimo e oitavo amigo, totalizando a soma de 15.

No segundo caso de teste, a melhor solução foi obtida convindando nenhum amigo,
logo totalizando a soma de 0.

--- 

### Desafio extra 5: Combinações genéticas (by: @cowcow)

Faça um quadrado de Punnett  para encontrar combinações genéticas entre genes.
(O programa deverá suportar uma entrada indefinida de genes, ou seja, pode ser AA aa, AABb AaBb, AaBbCc aaBBcc, entre outros.)

Exemplo:

Considerando a entrada "AaBb aabb", a saída deverá mostrar:
```
----------------------
|      |  AB  |  ab  |
----------------------
|  ab  | AaBb | aabb |
|  ab  | AaBb | aabb |
----------------------
AaBb: 1/2 or 50%
aabb: 1/2 or 50%
```

Nota: 
É obrigatório a saída ser em quadrado e também mostrar a porcentagem e fração dos genes.

#### Exemplos:

Entrada: Aabb aaBb
```
----------------------
|      |  Ab  |  ab  |
----------------------
|  aB  | AaBb | Aabb |
|  ab  | aaBb | aabb |
----------------------
AaBb: 1/4 or 25%
Aabb: 1/4 or 25%
aaBb: 1/4 or 25%
aabb: 1/4 or 25%

Entrada: AAbb aaBb
----------------------
|      |  Ab  |  Ab  |
----------------------
|  aB  | AaBb | Aabb |
|  ab  | AaBb | Aabb |
----------------------
AaBb: 1/2 or 50%
Aabb: 1/2 or 50%

Entrada: AABB aabb
----------------------
|      |  AB  |  AB  |
----------------------
|  ab  | AaBb | AaBb |
|  ab  | AaBb | AaBb |
----------------------
AaBb: 1/1 or 100%

Entrada: AABBcc aabbCc
----------------------------
|        |  ABc   |  ABc   |
----------------------------
|  abC   | AaBbCc | AaBbcc |
|  abc   | AaBbCc | AaBbcc |
----------------------------
AaBbCc: 1/2 or 50%
AaBbcc: 1/2 or 50%

Entrada: AABBcc aabbCC
----------------------------
|        |  ABc   |  ABc   |
----------------------------
|  abC   | AaBbCc | AaBbCc |
|  abC   | AaBbCc | AaBbCc |
----------------------------
AaBbCc: 1/1 or 100%
```

---

### 021 - Bits Trocados (by:https://br.spoj.com/problems/BIT/)

---

### 022 - Baralho Francês (by: https://github.com/codehub-discord/desafios/tree/master/01-baralho-frances)

---

### 023 - Validando IP (by: https://wiki.python.org.br/ExerciciosArquivos)

---

### 024 - Palíndromos (by: https://br.spoj.com/problems/PALIMG14/)

---

### Desafio extra 6: Meses

Construa uma função que receba uma data no formato DD/MM/AAAA e devolva uma string no formato DD de mesPorExtenso de AAAA. Faça também com que o programa valide a data e retorne NULL caso a data seja inválida.

#### Exemplos:
1. Para a entrada 21/08/2019 a saída deverá ser 21 de Agosto de 2019
2. Para a entrada 01/32/3064, ou 2019/21/08 a saída deverá ser Data inválida.

Considerações:
1. Não deve ser usado nenhum tipo de biblioteca, módulos ou afins na resolução do desafio, use apenas recursos da própria linguagem (também não será aceito libs já inclusas com a linguagem).
2. Além de 31, deverá também ser considerados os meses de 28 e 30 dias, também deve se considerar os anos bissextos.

---

### 025 - Jogo de Tabuleiro (by:https://neps.academy/problem/22)

---

### Desafio extra 7: Pilha de bolas (by: @gabe)

O contribuidor Black, depois de algumas semanas tentando resolver um problema em seu código em Java, desistiu e foi para o bar do Lado afogar sua mágoas. Ao chegar lá, se deparou com uma mesa de sinuca e pensou na seguinte situação:

> Se essa mesa de sinuca tivesse N bolas, quantas bolas seriam usadas para forma pirâmide de base quadrangular com H bolas de altura?

#### Desafio: 

Crie um programa que ajude Black com essa situação.

*Bônus*: E se a pirâmide que Black imaginou tivesse base triangular?

**Exemplo**: 
(3 bolas de altura -> 14 bolas no total)
Para a entrada 3, a saída deverá ser 14.

---

### 026 - Trio parada dura (by: @jooj)

SiDeMaZe é um amante de música sertaneja e também um caçador de talentos. No fim de semana passado, ele foi à um show sertanejo e lá ele encontrou n talentos promissores. Cada pessoa possui um inteiro positivo que representa seu talento de modo que quanto maior o número, maior o talento "sertanejístico" daquela pessoa.

SiDeMaZe quer reviver a lenda do trio parada dura, para isso ele organizou as n pessoas em fila e agora pretende selecionar os trios promissores. Um trio promissor é um trio onde i<j<k e Pi>Pj>Pk (i,j e k são posições e Pi,Pj e Pk representam o talento "sertanejístico" das pessoas que se encontram nessas posições).
     
Nesse desafio você irá receber na primeira linha de entrada um inteiro n (3 <= n <= 10^6) , que indica o número de pessoas talentosas, e na segunda linha n valores (que pertencem ao intervalo [0,10^9]) ,separados por espaço, que representam o nível de talento de cada uma das pessoas talentosas (é garantido que duas pessoas diferentes não possuem níveis de talentos iguais). 

Desafio: Seu objetivo é ajudar SiDeMaZe, calculando a quantidade de trios promissores que podem ser formados e talvez futuramente, se tornar o novo Trio Parada Dura.

#### Exemplos:
1.
Entrada:
```
3
3 2 1
```

Saída:
```
1 
```

> Já que 1<2<3 (i,j,k) e 3>2>1 (Pi,Pj,Pk)

2.
Entrada:
```
4
7 5 2 1
```

Saída:
```
4
```

> Já que as possíveis respostas são: (7,5,2),(7,5,1), (7,2,1) e (5,2,1)

3.
Entrada:
```
5
10 2 7 5 4
```

Saída:
```
4
```

> Já que as possíveis respostas são: (10,7,5),(10,7,4), (10,5,4) e (7,5,4)

4.
Entrada:
```
3
2 3 1
```

Saída:
```
0
```

---

### Desafio extra 8: Matriz identidade (by: @sidemaze)

Matriz identidade é uma matriz diagonal, cujos elementos da diagonal são todos iguais a 1. É denotada por I. Ou seja, a matriz identidade I tem a seguinte forma:
```
    [1 0 0 0]
I = [0 1 0 0]
    [0 0 1 0]
    [0 0 0 1]
 (Exemplo de matriz 4x4.)
 ```
 
Desafio: Faça um programa que solicite ao usuário que digite uma matriz 4 x 4 de inteiros, o programa dará como saída se a matriz é identidade ou não.

---

### 027 - Soma de casas (by: https://neps.academy/problem/255)

---

### Desafio extra 9 - Redstone contraption

O objetivo é fazer um sistema que receba redstone e devolva bolas de neve na mesma quantidade, e que retorne itens que não sejam redstone, como o exemplo do cogumelo.
Edit: A resolução tem que ser feita no minecraft vanilla.

---

### 028 - Hackerman

Bee acabou de hackear um servidor cheio de Bukkiteiros e roubou diamantes e uma senha (MTIz) que protege o dicionário deles, apos alguns dias o enviaram uma mensagem e ele precisa responder.  Decifre a senha e crie um programa capaz de criptografar a mensagem, ajude-o nessa corrida hacker.

Senha: MTIz
Dicionário: https://ghostbin.co/paste/euntocfx
Mensagem do Bee para criptografar: *You will never catch me!!!*

Dica:  Bee descobriu que a senha para o dicionário pode estar protegida em Base64 

Exemplos:

Entrada:
```css
Fish
Cat
Dog
```

Saída:
```js
|=15#
(47
[)06
```

---

### 029 - FizzBuzz (by: @bee)

O teste de FizzBuzz é baseado em um jogo criado para crianças que estão aprendendo a
operação de divisão. Apesar de ser simples, uma solução computacional é desafiadora para alguns
programadores menos experientes na implementação de desvios condicionais (ifs) encadeados. 

É necessário definir uma estratégia para o encadeamento dos ifs, e qualquer falha neste encadeamento
leva a uma solução errada do problema. 

#### Desafio:

Escreva um programa que imprima os números de 1 a N, mas nos múltiplos de 3 imprima "Fizz" em vez do  número e nos múltiplos de 5 imprima "Buzz". Para os números que são múltiplos de tanto 3 como 5, imprima "FizzBuzz".

#### Exemplos:
Entrada: `8`

Saída:
```
1
2
Fizz
4
Buzz
Fizz
7
8
```

---

### 030 - Bactérias

Na tentativa de criar bactérias mais resistentes a antibióticos, Dr. Naccib avaliou o DNA de algumas delas e percebeu uma semelhança nas bactérias que eram mais resistentes do que as demais. Todas elas possuiam uma parte do código genético igual (composto pelas proteínas A, C, G, T). Logo, constatou que aquele trecho de código genético é o que define se uma bactéria é resistente ou não. Assim, Naccib pediu para que você fizesse um programa que avalie se uma bactéria é resistente dado seu DNA e o código genético que leva a resistência.

Entrada:
`Cada caso teste contém duas strings, D e S, cada qual em uma linha, e representam o DNA da bactéria e a sequência de código genético que leva a resistência. 1 ≤ D, S ≤ 100. As strings são compostas apenas pelos caracteres: A, C, G, T.`

Saída:
`Imprima uma linha por cada caso teste, contendo a string "Resistente" (sem aspas) caso a bactéria possua o código genético requerido em seu DNA, ou a string "Nao resistente" (sem aspas) caso contrário.`

#### Exemplos:

```
Entrada    |  Saída
ACGTC  |  Resistente
CGT    |
```

```
CCCT   |  Não resistente
AG     |
-
```

### Desafio extra 10: Alfabeto

**Desafio**: Dada uma letra do alfabeto, informe qual a sua posição,

Entrada: `Um único caractere L, uma letra maiúscula (A-Z) do alfabeto.`
Saída: `Um único inteiro, que representa a posição da letra no alfabeto.`

#### Exemplos:
```
Entrada   |     Saída
C         |     3

```

---
