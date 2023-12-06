# Conceitos Básicos

<h2>Tipo de Dados</h2>

<img src="../assets/Tipo de dados.jpeg">

<h2>Modo interativo</h2>
<p>O interpretador Python pode executar em modo que possibilite o desenvolvedor a escrever código e ver o resultado na hora</p>

<p>Existem duas formas de iniciar o modo interativo, chamando apenas o interpretador (python) ou executando o script com a flag -i (python -i app.py)</p>

<h2>Funções dir e help</h2>

<h3>dir</h3>
<p>Sem argumentos, retorna a lista de nomes no escopo local atual. Com um argumento, retorna uma lista de atributos válidos para o objeto. Exemplo: </p>

~~~
dir()
dir(100)
~~~

<h3>help</h3>
<p>Invoca o sistema de ajuda integrado. É possível fazer buscas em modo interativo ou informar por parâmetro qual o nome do módulo, função, classe, método ou variável. Exemplo:</p>

~~~
help
help(100)
~~~

<h2>Variáveis e Constantes</h2>

<h3>Variável</h3>
<p>Em linguagens de programação podemos definir valores que podem sofre alterações no decorrer da execução co programa. Esses valores recebem o nome de variáveis, pois eles nascem com um valor e não necessariamente devem permanecer com o mesmo durante a execução do programa. Exemplo:</p>

~~~
age = 23
name = 'João'
~~~

<h3>Constantes</h3>
<p>Assim como as variáveis, constantesnsão utilizadas para armazenar valores. Uma constantw nasce com um valor e permanece com ele até o final da execução do programa, ou seja, o valor é imutável</p>

<p>Porém Python não tem constantes, não existe uma palavra reservada para informar ao interpretador que o valor é constante. Em Python usuamos a convenção que diz ao programador que a variável é uma constante. Para fazer isso, você deve criar a variável com o nome todo em letras maiúsculas:</p>

~~~
DEBUG = True
STATES = [
    'SP',
    'RJ',
    'MG',
]
AMOUNT = 30.2
~~~







