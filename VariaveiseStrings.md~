#Variáveis e Strings

O que podemos fazer para que nossos programas fiquem mais interativos?
Existe uma função em Python chamada **input** cujo propósito é receber informações do usuário. Para que possamos utilizar as informações que o usuário insere no programa precisamos utilizar as **variáveis**.

**Variável** é um espaço alocado pelo programa em tempo de execução para armazenar dados. Através das variáveis podemos recuperar dados que um usuário inseriu no programa para realizar diversos tipos de operações. Podemos simplesmente fazer uso desses dados invocando em qualquer parte do programa o nome da variável.

Ficou confuso?
Podemos fazer a seguinte analogia. Temos um armario com vários compartimentos para guardar objetos de diversos tipos. E cada compartimento possui um número para que possamos localizar o compartimento onde guardamos nosso(s) objeto(s). O armário é a memória do computador (memória ram) e o número ou nome de cada compartimento é o nome da variável que podemos utilizar para localizar ou recuperar nossos objetos ou valores que inserimos em seu interior.

*Todo programa de computador utiliza variáveis para armazenar algum tipo de informação em algum momento durante a sua execução.*

*A variável pode ter ser seu valor alterado durante a execução de um programa.*

Em Python não é preciso declarar o tipo das variáveis. Essa linguagem trabalha com o modo de operação chamado tipagem dinamica que reconhece o tipo da variável de acordo com o seu valor durante a execução. Ou seja, você pode criar uma variável e inserir qualquer valor que o interpretador irá reconhecer o seu tipo como: *numérico, string ou object*.

As variáveis em Python podem ser reutilizadas com outros tipos de valores. Ou seja, eu posso utilizar inicialmente uma variável com um tipo numérico  e depois utilizar essa mesma variável com um tipo string ou object.

*Dica de usabilidade:*
Ao nomear suas variáveis utilize nomes significativos. O nome da variável deve deixar explicito qual a função que ela desempenha no programa. Ao seguir essa boa prática seu código ficará mais reutilizável e melhor documentado.

##Regras para nomear variáveis

+ Python é case-sensitive. O que significa que o interpretador diferencia letras maiúsculas de minúsculas. Ou seja, *name* é diferente de *Name*.
+ As variáveis não podem conter espaços
+ Não podem começar com número. Os nomes das variáveis devem iniciar sempre com letras ou underline(_), mas podem conter números em seu interior ou no final. O interpretador não admite caracteres especiais como @, $, %, * etc.
+ Não pode utilizar palavras reservadas da linguagem. Veja a lista.

```python
import keyword
print keyword.kwlist
```
Saída:

```
['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
```

##Boas práticas para nomear variáveis
A comunidade de desenvolvedores definiu algumas recomendações de como escrever as variáveis que você não é obrigado a seguir, mas que ao por em prática essas recomendações seu código se tornará mais legivel e consequentemente fácil de realizar a manutenção.

##camelCase
O **camelCase** é utilizado normalmente para *variáveis, métodos e argumentos*. O formato camelCase estabele que todo nome composto a primeira palavra deve utilizar todas as letras minúsculas e a partir da segunda palavra a primeira letra deve ser maiúscula e as subsequentes todas minúsculas. Não foi adotado pelo desenvolvedores da linguagem Python esse formato preferindo manter todas as letras minúsculas ou separar as palavras utilizando o underline.

##PascalCase
O **PascalCase** é utilizado comumente para *classes*. O formato CamelCase estabelece que a primeira letra da palavra deve iniciar com letra maiúscula e as subsequentes minúsculas. Se for um nome composto as outras palavras seguem as mesmas regras da primeira palavra.

##Operações com Strings

Para facilitar a vida dos desenvolvedores a linguagem Python possui alguns métodos built-in que podem ser utilizados com strings. A proposta é tornar o desenvolvimento mais ágil e garantir que sejam utilizados algoritmos  otimizados no desenvolvimento de softwares. 

**upper()**
Este método retorna uma string com todas as letras maiúsculas.

Como usar:

```python
linguagem = "Python"
linguagem.upper()
```

**lower()**
Este método retorna uma string com todas as letras minúsculas.

Como usar:

```python
linguagem = "Python"
linguagem.lower()
```

**swapcase()**
Este método retorna uma string com a primeira letra minúscula e o restante maiúsculas.

Como usar:

```python
linguagem = "Python"
linguagem.swapcase()
```


##Voltando ao input

O **input** é uma função que aceita como argumento strings que podem ser utilizadas para solicitar algum tipo de dado ao usuário. Ao executar um programa ou script que possui a função input será retornado ao usuário do programa a informação que foi passada como argumento. Esta função interrompe a execução do programa até que o usuário aperte a tecla enter do teclado. 

```python
nome = input("Qual é o seu nome? \n")
print("Olá "+nome+", seja bem-vindo!")
```



