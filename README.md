# Formação Python

<p> <a href="https://cursos.alura.com.br/formacao-Python-linguagem">Alura - Formação Python</a></p>

<p>Resumo teórico do conteúdo abordado</p>

<h2 style="color:green;"> Sobre o Python</h2> </p>
<p> <h3 style="color:yellow;">Python</h3> é uma linguagem de programação interpretada de alto nível e que suporta múltiplos paradigmas de programação: imperativo, orientado a objetos e funcional. É uma linguagem com tipagem dinâmica e gerenciamento automático de memória.</p>
<p> <h3 style="color:yellow;">Linguagem</h3> Interpretada significa que a implementação do código Python em cada computador é feita a partir de um interpretador.</p>
<p> <h3 style="color:yellow;">Linguagem</h3> de Alto Nível possui maior proximidade com a linguagem humana do que a linguagem de máquina(binário)  </p>
<p>	<h3 style="color:yellow;">Suporta múltiplos paradigmas da computação:</h3>

<p><b>Paradigmas de Programação</b> são as diferentes abordagens que um programador pode utilizar para desenvolver um código e resolver uma questão específica.

<ul>
       <li>Imperativo ou Procedural: As instruções são passadas ao computador na sequência que devem ser executadas.</li>
       <li>Orientado a Objetos: Talvez o mais popular dos paradigmas. Utiliza estruturas denominadas classes e objetos e sua principal característica é permitir uma programação multiplataforma.</li>
       <li>Funcional: Possui como principal característica o uso de estruturas chamadas de funções. Essas funções separam o código em blocos nos quais cada um tem uma tarefa específica</li>
</ul>
<p> <h3 style="color:yellow;">Possui tipagem dinâmica </h3>
<p> Os tipos de dados não precisam ser definidos o próprio Python entende cada tipo informado.

<p> <h3 style="color:yellow;">Gerenciamento Automático de Memória:</h3>
<p> O Python constantemente realiza uma manutenção ou “limpeza” da memória não utilizada através de mecanismos como o garbage collector (coletor de lixo) e a Reference Counting (Contagem de Referência).Dessa forma, o programador não tem que se preocupar em fazer um gerenciamento manual de memória.

<p> <h3 style="color:yellow;"> Variáveis e String </h3>
<p> <b>Variáveis</b> são usadas para armazenar valores. 
<p> Uma <b>String</b> é uma série de Caractere, entre aspas simples ou duplas

<p><b style="color:red;">Exemplos:</b></p>
<p> Entrada </p>

![img_1.png](img/img_1.png)

<p> Saida </p>

![img_2.png](img/img_2.png)

<p> Entrada </p>

![img_3.png](img/img_3.png)

<p> Saida </p>

![img_4.png](img/img_4.png)

<p> Entrada </p>

![img_5.png](img/img_5.png)

<p> Saida </p>

![img_6.png](img/img_6.png)

<p> <h3 style="color:yellow;"> Funções </h3> <p> </p>
Uma função é um bloco de código que pode ser guardado, para ser chamado assim que desejarmos, contanto que saibamos seu nome
<P> Para declarar funções em python devemos utilizar a palavra reservada def.
        O Consenso de nomeclatura do Python é snake_case
	
    def nome_da_funcao():
    # todo o código identado faz parte da função
        print("aprendendo funções")

<p><h3 style="color:yellow;">Listas</h3></p>

<p>Uma lista armazena uma série de itens em uma ordem específica.
Pode acessar os itens usando um índice ou dentro de um loop de repetição.<b>Mutáveis</b>
        <p>Listas são representadas por Colchetes [ ] </p>

<p><h3 style="color:yellow;">Tuplas</h3></p>
<p>Tuplas são semelhantes a listas, mas os itens em uma tuplas não podem ser
modificado. <b>Imutáveis</b>
<p>Tuplas são representadas por Parêntese () </p>

<p><h3 style="color:yellow;">Set</h3></p>
<p>Um set é uma coleção não ordenada de elementos. Cada elemento é único, isso significa que não existem elementos duplicados dentro do set.
<p>Set são representadas por Chaves { } </p>

<p><h3 style="color:yellow;">Dictionary</h3></p>
<p> São coleções de itens que contém elementos que são guardados de forma não ordenada.
    Esses elementos contém uma CHAVE e VALOR
<ul>
       <li> Chave servirá para indexar(posicionar) determinado elemento no dicionário</li><br>
       <li> Contém os valores desses elementos, Este valor aceita diversos tipos: listas,outos dicionários, inteiros, string e etc</li><br>
       <li>Sua sintaxe básica é: { 'chave': valor }. Utiliza-se {} para delimitar o dicionário e a chave é separada do valor por dois pontos :. </li><br>
</ul>


<p><h3 style="color:yellow;">List Comprehension</h3></p>
<p> É uma forma mais sucinta de manipular listas </p>
<ul>
       <li>Sua sintaxe básica é: [expr for item in lista]</li><br>
       <li>Exemplo da forma tradicional:<br>
         for item in lista:<br>
         resultado.append(str(item).upper()) </li><br>
       <li>Exemplo List Comprehension<br>
         resultado = [str(item).upper() for item in lista]
</li>

</ul>


