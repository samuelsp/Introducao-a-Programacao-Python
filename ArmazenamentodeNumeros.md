#Utilizando as variáveis para armazenar números
A programação é um recurso da informatica que podemos fazer uso para resolver problemas de nosso cotidiano. A natureza dos problemas reais é muito diversificada e quase sempre nos deparamos com situações em que precisamos empregar calculos matematicos. Alguns exemplos de problemas da vida real em que precisamos utilizar a matematica para encontrar uma solução são: o valor da prestação de uma mercadoria comprada a prazo, calculo de tributos, hipoteca e por ai vai. A linguagem Python possui operadores matematicos e funções que realizam calculos matematicos para facilitar a criação de scripts ou programas que necessitam da matematica para resolver algum problema.

##Operadores matemáticos
Felizmente operações aritmeticas como somar, subtrair e dividir podem ser realizadas intuitivamente, pois utilizam os mesmos sinais da linguagem matematica. Deve-se no entanto se atentar para as operações que envolvem multiplicação e exponenciação, pois os sinais não são os mesmos. Por exemplo, nas operações que envolvem multiplicação na linguagem matematica utilizamos um ponto "." ou a letra "X". Em Python não podemos utilizar os caracteres ponto ou X devido o sinal de ponto ser utilizado para outras funções como por exemplo para invocar métodos de um objeto ou separar casas decimais em valores numericos do tipo float. A letra X o interpretador Python irá reconhecer como um caracter.

Simbolo | Operação | Exemplo
--- | --- | ---
+ | Adição | 5 + 2 = 7
- | Subtração | 5 - 2 = 3
* | Multiplicação | 5 * 2 = 10
/ | Divisão | 5 / 2 = 2
** | Exponenciação | 5 ** 2 = 25
% | Módulo | 5 % 2 = 1

##Precedência dos operadores
É possível trabalhar com expressões em Python para realizar calculos matematicos complexos. Em toda expressão existe a precedência de operadores aritméticos para chegar ao resultado correto. Na linguagem Python utiliza-se a mesma precedencia dos operadores aritméticos da matematica. 

Ordem das operações |
--- |
( ) parêntese |
** exponenciação |
* / multiplicação e divisão |
+ - adição e subtração |

Quando houver operadores com a mesma ordem de precedência em uma expressão, por exemplo adição e subtração o interpretador irá realizar o calculo da esquerda para direita. A expressão *valor = 6 - 1 + 2* gera o valor 7 como resultado, pois primeiro é executado a operação de subtração (6 - 1) que é igual a 5 que depois é somado com o valor 2 dando o resultado igual a 7 que é atribuido a variável de nome valor. 

##Formatações com números
A função **print** permite a inserção de formatações especificas para variáveis do tipo *int* e *float*. Esse tipo de formatação é muito útil quando é preciso inserir valores do tipo int ou float em uma saida que precisamos encadear esses tipos com o tipo caracter ou string.

```python
>>> print('Eu tenho %d cães.'%2)
Eu tenho 2 cães.

>>> print('Eu tenho %3d cães.'%2)
Eu tenho    2 cães.

>>> print('Eu tenho %03d cães.' %2)
Eu tenho 002 cães.

>>> print('Eu tenho %f cães.' %2)
Eu tenho 2.000000 cães.

>>> print('Eu tenho %.2f cães.' %2)
Eu tenho 2.00 cães.
```
Existe uma função chamada **format** que também pode ser utilizada para inserir números com caracteres dentro de um print. Sua sintaxe é um pouco mais complexa, porém possui mais recursos. Essa função é indicada quando precisamos *printar* posições especificas de uma lista por exemplo.

```python
>>> print("Eu tenho {0:d} cães".format(6)) 
Eu tenho 6 cães

>>> print("Eu tenho {0:3d} cães".format(6))
Eu tenho    6 cães

>>> print("Eu tenho {0:03d} cães".format(6)) 
Eu tenho 006 cães

>>> print("Eu tenho {0:f} cães".format(6))
Eu tenho 6.000000 cães

>>> print("Eu tenho {0:.2f} cães".format(6)) 
Eu tenho 6.00 cães
```

Explicando a sintaxe:
{0:d} = o primeiro valor antes do dois pontos ":" indica que estamos acessando o primeiro indice dos valores passados como argumento para a função format e o segundo como queremos que seja formatado esse valor. O *d* é para valor inteiro e *f* para decimal.

```python
>>> print('Eu tenho {0:f} cães e {1:f} gatos.'.format(2, 4))
Eu tenho 2.000000 cães e 4.000000 gatos.
```
##Funções para conversão de tipos
Existem situações em que ao utilizarmos algumas funções como o input para solicitar algum dado para o usuário, por exemplo idade ou altura, nos deparamos com algumas situações inesperadas. A função input sempre irá retornar uma string independente do valor que inserirmos e portanto não podemos utilizar uma string para realizar calculos. Nestes casos podemos fazer uso de funções como int() que converte uma string para inteiro quando a string representa um valor inteiro e float() que converte uma string para um valor decimal quando a string representa um valor decimal.

```python
>>> varStr = "42"
>>> varInt = int(varStr)
>>> varStr
'42'
>>> varInt
42
>>> 
```
Note que ao digitarmos varInt o valor retornado não possui aspas indicando que se trata de um valor inteiro.

