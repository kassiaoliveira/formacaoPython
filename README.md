# Formação Python

 <a href="https://cursos.alura.com.br/formacao-Python-linguagem">Alura - Formação Python</a>

Resumo teórico do conteúdo abordado

## Sobre o Python

Python é uma linguagem de programação interpretada de alto nível 
e que suporta múltiplos paradigmas de programação: 
imperativo, orientado a objetos e funcional. 
É uma linguagem com tipagem dinâmica e gerenciamento automático de memória.

Linguagem Interpretada significa que a implementação do código Python em cada computador é feita a partir de um interpretador.

Linguagem de Alto Nível possui maior proximidade com a linguagem humana do que a 
linguagem de máquina(binário)

###### Tipos de Dados
- Booleano True/False 
- Inteiro 10 
- Flutuante 10.5 
- Lista ['Valor1','Valor2']
- Dionário = {'Chave1': Valor1,'Chave2': Valor2 }
- Tupla  =('Valor1','Valor2') 

###### Operadores Númericos
- Adição (+)  
- Subtação (-)
- Multiplicação (*)
- Divisão (/)
- Exponenciaçâo (**)
- Resto  (%)        

###### Operadores Boleanos 

- and Lógica `e´    
- or Lógica `ou´  
- not Lógica `Negação´
- 
###### Operadores Listas

- Lista [] Cria uma lista vazia            
- Lista [x]= 1 Armazena valor na posição x 
- Lista [x] Acessa o valor na posição X    
- Lista [-1] Acessa o ultimo valor lista   
- Lista [x:y] Seleciona periodo da lista   
- Del Lista [x] remove o valor list        

Paradigmas de Programação</b> são as diferentes abordagens que um programador pode utilizar para desenvolver um código e resolver uma questão específica.


       Imperativo ou Procedural: As instruções são passadas ao computador na sequência que devem ser executadas.
       Orientado a Objetos: Talvez o mais popular dos paradigmas. Utiliza estruturas denominadas classes e objetos e sua principal característica é permitir uma programação multiplataforma.
       Funcional: Possui como principal característica o uso de estruturas chamadas de funções. Essas funções separam o código em blocos nos quais cada um tem uma tarefa específica

 ###Possui tipagem dinâmica
 Os tipos de dados não precisam ser definidos o próprio Python entende cada tipo informado.

 ###Gerenciamento Automático de Memória:
 O Python constantemente realiza uma manutenção ou “limpeza” da memória não utilizada através de mecanismos como o garbage collector (coletor de lixo) e a Reference Counting (Contagem de Referência).Dessa forma, o programador não tem que se preocupar em fazer um gerenciamento manual de memória.

 ### Variáveis e String
 Variáveis</b> são usadas para armazenar valores. 
 Uma String</b> é uma série de Caractere, entre aspas simples ou duplas

 Exemplos
 Entrada 

![img_1.png](img/img_1.png)

 Saida 

![img_2.png](img/img_2.png)

 Entrada 

![img_3.png](img/img_3.png)

 Saida 

![img_4.png](img/img_4.png)

 Entrada 

![img_5.png](img/img_5.png)

 Saida 

![img_6.png](img/img_6.png)

 ### Funções  
Uma função é um bloco de código que pode ser guardado, para ser chamado assim que desejarmos, contanto que saibamos seu nome
Para declarar funções em python devemos utilizar a palavra reservada def.

O Consenso de nomeclatura do Python é snake_case
```python
def nome_da_funcao():
    # todo o código identado faz parte da função
    print("aprendendo funções")
```
###Listas

Uma lista é uma coleção ordenada e podem passar por modificações.
Pode acessar os itens usando um índice ou em um ‘loop’ de repetição.
Mutáveis</b>
Listas são representadas por Colchetes [ ] 

###Tuplas
Tuplas são como listas, mas os itens em uma tuplas não podem ser
modificado.
Imutáveis</b>
Tuplas são representadas por Parêntese () 

###Set
Set são conjuntos de elementos distintos
Set são representadas por Chaves {} 

###Dictionary
 São coleções de itens que contém elementos guardados de forma não ordenada.
    Esses elementos contêm uma CHAVE e VALOR

Chave servirá para indexar(posicionar) determinado elemento no dicionário
Contém os valores desses elementos, Este valor aceita diversos tipos: listas,outos dicionários, inteiros, string e etc

A sua sintaxe básica é: {'chave': valor}.
Utiliza-se {} para delimitar o dicionário e a
chave é separada do valor por dois pontos:.

 ```python
## Exemplo da forma tradicional:
dicio = {'chave': 'valor'}
```

###List Comprehension
 É uma forma mais sucinta de manipular listas 
A sua sintaxe básica é: [expr for item in lista]

 ```python
## Exemplo da forma tradicional:
for ‘item’ in lista:
         resultado.append(str(item).upper()) 
```
 ```python
##Exemplo List Comprehension
         resultado = [str(item).upper() for item in lista]
```

### Parâmetros, Argumentos, *args e **kwargs
- Parâmetros são os nomes dado aos atributos que uma função pode receber
- Argumentos são valores que são realmente passados para uma função
- *args É usado para passar uma lista de argumentos variável sem palavras-chave em forma de tupla, pois a função que o recebe não necessariamente saberá quantos argumentos serão passados. 
- **kwargs keyword arguments (argumentos de palavras-chave). Ele permite passar um dicionário com inúmeras keys para a função.

###Fluxo de Controle

<h4>ESTUTURAS CONDICIONAIS</h4>

<h5>if</h5>
```python
valor = 10
if valor > 5:
    print('O valor é maior que 5.')
```
<h5>if/else</h5>
```python
idade = 20
if idade < 17:
    print('A idade é MENOR que 17')
else:
    print('A idade é MAIOR que 17')
```
<h5>if-elif-else</h5>
O elif é utilizado quando mais de uma condição if precisa ser testada. Exemplo:
```python
linguagem = "Python"

if linguagem == "C++":
    print('C++ é uma linguagem de programação compilada.')
elif linguagem == "Python":
    print("Python é uma linguagem de programação de alto nível")
elif linguagem == "Java":
    print("Java é uma linguagem de programação amplamante utilizada no mercado")
else:
    print('Não é nenhuma das duas opções')
```
<h5>Ternária (if em uma linha)</h5>
Python provê uma forma concisa de se testar valores com apenas uma linha de código
```python
velocidade = 75

resultado = 'Multado' if velocidade > 60 else 'Dentro do limite'

print(resultado)
```

<h4>ESTUTURAS DE REPETIÇÕES</h4>

- As estruturas de repetição são recursos das linguagens de programação responsáveis por executar um bloco de código repetidamente através de determinadas condições especifica.
- Loops com for e loops com While

<h5>for</h5>
```python
lista = [1, 2, 3, 4, 5]
for item in lista:
    print(item)
```

<h5>while</h5>
```python
contador = 0

while contador < 10:
    print(f'Valor do contador é {contador}')
    contador += 1
```
