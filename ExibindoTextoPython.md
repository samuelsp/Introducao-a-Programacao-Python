#Exibindo Texto em Python

Python possui recursos para exibição de texto na tela. É possível exibir texto formatado para trabalhar de forma mais confortável com esse tipo de informação.

Quase todo programa utiliza texto para informar ao usuário o que esta ocorrendo em um certo momento. O texto é um dos meios de interação mais utilizados por programadores. Por isso é importante utilizar uma linguagem clara e objetiva além dos recursos disponíveis para formatação de texto para uma boa apresentação.

##Usando o print

Em Python utilizamos o comando **print** para mostrar alguma informação no console.
Exemplo:

```python
print('Seja bem vindo ao meu programa!')
```

É necessário utilizar **aspas simples(') ou duplas(")** dentro do comando print para indicar que a informação é uma cadeia de caracteres ou string. Uma *string* é qualquer texto. E por que existe as aspas simples e as aspas duplas? A resposta é simples: com as asplas duplas eu posso incluir as aspas simples na string e portanto eu terei mais recursos de formatação. Por exemplo eu poderei incluir palavras que possui apóstrofo.

```python
print('Olá, Seja bem vindo ao meu programa em Python!')
print("Vocẽ sabia que pode usar 'aspas simples' ou duplas para exibir strings?")
```

Legal e se meu texto não couber em uma linha eu terei que usar varios comandos print?
A resposta é não gafanhoto você poderá usar apenas um print e substituir as aspas simples ou duplas pela triplo aspas simples ou dupla. Mas como?
Assim:

```python
print('''Aqui você insere um texto que não irá
      caber em apenas uma linha''')		
```
ou assim:

```python
print("""Aqui você insere um texto que não irá
      caber em apenas uma linha""")
```

##Formatações com print

		\n - pula uma linha ou insere nova linha
		\t - insere tabulação ou insere um espaço entre palavras
		+ - concatena strings
		\ - caractere de escape

E se meu texto conter aspas simples ou duplas em alguma palavra?
Para isso você pode utilizar o caractere de escape "\" que faz com que o print desconsidere o que vem depois da barra invertida e interprete como uma string.

```python		
print("Eu posso inserir uma palavra que contem \"aspas\" em meu texto.")
print('Eu posso inserir uma palavra que contem \'aspas\' em meu texto.')
```
		
Muito bem e seu precisar imprimir um caminho de arquivo?

```python
print("C:\\Windows\\Documents\\file.txt")
```

Ai você precisa usar a contrabarra duas vezes.

##Cuidado com as aspas
O erro mais comum para todo iniciante em Python ao escrever programas que geram alguma saida em texto é  esquecer de inserir as aspas simples ou duplas ou não saber como utiliza-las dentro da função print. Portanto cuidado!


