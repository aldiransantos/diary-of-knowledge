# Diary of Knowledge
Some days ago I was studing and learning about Web Development but I'm not was noting what I was learning. I decided to create a diary to know what I'm learning and remember when I forget something.

I'm using the [`Habitica`](https://habitica.com/) to manage my tasks during the day and the week.

The days ago I don't remember either write down the courses I did and what I learned.

Let's to start.

## February 13, 2017
I completed the [`Codecademy's Course: Learn HTML & CSS: Part I`](https://www.codecademy.com/learn/learn-html-css)

## February 14, 2017
I completed almost all projects in [`General Assembly`](https://dash.generalassemb.ly/)

P.S. I will still do the Tumblr Project

## From the 15th to the 16th of February 2017
I completed [`Flexbox Frog`](http://flexboxfroggy.com/) and I learned more about CSS

I started the course of [`Free Code Camp: Learn to Code and Help Nonprofits`](http://freecodecamp.com/)
 - Getting Started;
 - Front End Development Certification: 
  - HTML5 and CSS;
  - Resposive Design with Boostrap;
  - Gear up for Success.

### What I learned:

#### HTML5 and CSS
  - **class="nameClass01 nameClass02 ... nameClassN"** | that is, how we can to separate nameClasses in the same class
  - **!important** | to give priority to some class or id, in other words, it override whatever parameter passed to another class or id
  
#### Bootstrap
  - **col-xs-4** | col = column, xs = extra small, 4 = number of parts that you want to catch. There are 12 parts of column in Bootstrap, I caught 4 parts
  - **col-md-*** | md = medium, * = all. Catchs all parts of columns, that is, 12 parts
  - **class="img-responsive"** | class of Bootstrap. Turns your image in a responsive image
  - **```<i class="fa fa=into-up"></i>```** | Like icon
  - **```<i class="fa fa-into-trash"></i>```** | Trash icon
  - **```<i class="fa fa-into-circle"></i>```** | Information icon
  - **```<i class="fa fa-paper-plane"></i>```** | Paper's plane icon
  - **form-control** | used for submit button
  
## From the 16th to the 17th of February 2017
I completed the course [`Learn the Command Line`](https://www.codecademy.com/learn/learn-the-command-line) in [`Codecademy`](https://www.codecademy.com)

### I learned the follow commands:
- ls | lists
- pwd | print working directory
- cd | change directory
- mkdir | make directory
- touch | create a new file
- -a, -l, -t | are options
- -a | show directories starting with a dot (.)
- -l | long format
- -t | the time they were last modified
- -alt | -alt lists all contents, including hidden files and directories, in long format, ordered by the date and time they were last modified.
- cp | copies files
- * | wildcards selects all files in the working directory
- mv | moves and renames files
- rm | command deletes files
- -r | is an option = stands for "recursive" and it's used to delete a directory and all of its child directories
- rm -r | remove directories
- cat = command outputs
- grep = "global regular expression print". It searches files for lines the match a pattern and return the results
- grep -i = enables the command to be case insensitive

## February 17, 2017
I completed the course [`Learn Git`](https://www.codecademy.com/learn/learn-git) in [`Codecademy`](https://www.codecademy.com/)

### What I learned:

- ```git init``` | inicializa o git
- ```touch``` | cria um arquivo
- ```git add name_file``` | direciona o arquivo para ser comitado
- ```git commit -m "Commit's message"``` | 'comita' o arquivo com uma mensagem
- ```git commit``` | normalmente usado para comitar mais de um arquivo. Abrirá uma janela para você escrever comentários sobre as mudanças de seus arquivos
- ```:q``` | serve para sair do editor de commit apos salvar apertando Ctrl+O
- ```git commit -a -m "comentario"``` | o "-a" serve para comitar todos os arquivos que estiverem para serem comitados
- ```git status``` | mostra o status do(s) arquivo(s)
- ```git log``` | informa por quem e quando o arquivo foi 'comitado'
- ```git branch new_file``` | To create a new branch 
- ```git log -p``` | ver todos os comits e suas alterações
- ```git log - p 2``` | ver os 2 ultimos commits e suas alterações. o numero pode mudar para voce alcançar mais commits
- ```git log --stats``` | mostra as estatisticas de mudança dos arquivos
- ```.gitignore``` | responsavel por guardar quais arquivos podem ser ignorados pelo usuario no git status
- ```git reset HEAD <file>``` | volta o arquivo do modo 'Changes to be comitted' para 'Untracked files'
- ```git add . ```| adiciona todos os arquivos que estao em 'Untracked files'
- git log pretty=oneline | mostra os commits uma linha por vez
- git log --since=2.days | mostra os commits realizados a dois dias atras
- git checkout <numero do commit> | serve para voltar a versão de um commit dado. 
- git reset HEAD~numero | volta um commit de acordo com o numero que colocar. Por exemplo, se colocar o numero 1, vai voltar 1 commit, se colocar o numero 2, dois commits, and so on
existem dois tipos de git reset HEAD. Um é o soft (git reset HEAD~1 --soft) serve para voltar quantos commits voce quiser sem excluir os arquivos que sofreram alteração, podendo voce altera-los novamente
O outro é o hard (git reset HEAD~1 --hard) onde nao tem moleza. Ele volta quantos arquivos voce quiser excluindo tudo o que foi modificado em commits anteriores
- master | branch principal (o tronco da arvore)
- branch | o galho da arvore, ou seja, ramificações criadas para continuar o desenvolvimento de algo
- git branch | saber em qual branch esta
- git ckeckout -b nome_do_branch | criar um novo branch e dar a ele um nome
- git checkout nome_do_branch | vai para o branch que voce deseja
- git merge nome_do_branch | vai misturar um branch com o branch atual. se caso voce estiver no branch master, poderá escolher um branch criado para se misturar a ele
- git push origin nome_do_branch | empurrar/upar o branch para o site do Github
- git clone url_do_arquivo | clona para seu computador o branch atual do Github
- git branch -a | mostra todos os branchs que existem locais e remotos
- git pull | verifica se todos os arquivos estão sicronizados
- git checkout -b nome_do_branch origin/nome_do_branch | cria um branch direto para o repositorio
- git pull origin master | trazer as 'alterações' realizadas para o seu computador. É o contrario do push
- git tag numero_do_release (x.x.x) | indicar uma versão de um projeto
- git push origin master --tags | criar a versão do projeto que aparecerá em release no Github
- git init --bare | repositorio criado apenas para servir. apenas para hospedar seus arquivos de controle de versao
- git remote add local ssh://localhost/endereço_dos_seus_arquivos | criará um repositorio local
- git push local master | adicionar um repositorio local da maquina

## From the 18th to the 19th of February 2017

#### CSS
- vertical-align: middle;
- dar a altura de uma "div", independente de onde esteja, era só ter pensando em height e o valor da aula
- text-shadow: 2px 2px 8px #FF0000; 

## February 19, 2017

#### CSS
- display: flex; | "Deixa os itens de forma horizontal"
- flex-wrap: wrap; | "Deixa os itens dentro do site quando o tamanho do browser é alterado"
- content-flex: center; | "Alinha os itens para o centro da Div"
- :active | "Para alguma coisa quando um algo for pressionado"

## February 21, 2017

#### jQuery - biblioteca do Javascript
- $(document).ready(function(){}); | Estrutura inicial do jQuery
- :nth-child('number'); | Seleciona a posição de um elemento dentro de outro elemento. Exemplo: se fosse ('ol :nth-child(2)') iria selecionar a li de número 2 dentro da ol 
- .append() | insere um elemento na ultima posição de um elemento alvo
- .prepend() | insere na primeira posição
- .before() | antes de um elemento
- .after() | depois de um elemento
- .empty() | esvazia todos os elementos dentro de uma tag
- .delete() | deleta o elemento atual e todas as suas tags
- .height e .width | pode ser usado para aumentar ou diminuir a altura e/ou largura de um elemento
- .css("border-radius", "10px") | Também pode-se colocar a estrutura do CSS para modificar algum elemento
- .html("I love jQuery!") | Assim como pode ser feito com html
- $('element').over(function{
	$(this).addClass('cssClass');	
},
	$(this).removeClass('cssClass');
);
Para dar efeito a um "botao" quando o mouse é passado por cima dele
- .focus(function() {}); | dar foco a algum elemento
- jQuery UI | é o jQuery com AJAX
<script src="//ajax.googleapis.com/ajax/libs/jqueryui/1.9.1/jquery-ui.min.js"></script>
- .draggable() | é uma função que faz voce arrastar um item criado para algum lugar da tela do seu navegador (MUITO MASSA, VARIAS IDEIAS)
- .selectable() | da algum efeito em um item selecionado
- .accordion() | dá efeito de abrir o que estiver dentro de um elemento. Efeito sanfona

## February 22, 2017

#### CSS
- overflow | pode receber o atributo scroll ou hidden, que serve para mostrar ou não a barra de rolagem

## February 23, 2017

#### Games
- REKT = Completamente Destruido

#### jQuery
- Mouse Events = click | dbclick | focusin | fucusout | mousedown | mouseup | mousemove | mouseout | mouseover | mouseleave | mouseenter
- fuction nome_da_função(){parametros};
- Keyboard Events = keypress | keydown | keyup
- Form Events = blur | focus | select | submit | change
- Object Methods = .fadeIn() | .fadeOut() | .fadeToggle()
- event.preventDefault = Faz com que, ao clicar em algum evento, a página não vá para o topo

## February 24, 2017

#### jQuery

- .attr() | adicionar atributo a alguma coisa
- .appendTo() | adicionar algum elemento para um outro local
- .clone() | duplicar elemento
- :nth-child | numero da colocação da criança. n-numero, th-colocação, tipo fourth, fiveth...
- .addClass("animated hinge") | faz a tela cair
- .addClass("shake") | treme para um lado e para o outro
- .addClass("bounce") | treme pra cima e pra baixo

CRIAR UM SISTEMAZINHO MOSTRANDO O PREÇO DE VIAJENS PARA CAPITAIS COM JQUERY

## February 25, 2017

#### Habitica
- básicos -> carne, 
- branco -> leite, 
- deserto -> batata, 
- vermelho -> morango, 
- sombrio -> chocolate, 
- esqueleto -> peixe, 
- zumbi -> carne podre, 
- rosa -> algodão doce rosa, 
- azul -> algodão doce azul, 
- dourado -> mel

## February 26, 2017

#### CS
- border-collapse = serve para ligar as linhas que parecerem separadas

## March 1, 2017

#### Brackets
- Baixei Brackets, pois possui Live Preview para HTML e CSS, no qual você pode ver o que fez no código automaticamente pelo browser Google Chrome

#### Bootstrap
- Tamanhos de telas do Bootstrap:
-- muito pequeno - até 750px | col-xs
-- pequeno - entre 750 e 970px | col-sm
-- medio - entre 970 e 1170px | col-md
-- grande - acima de 1170px | col-lg
- col-xs-offset-6 = deixa as 6 primeiras colunas vazias

## March 2, 2017

#### Bootstrap
- ```<small> conteudo </small>``` | diminui o tamanho de texto
- ```class="lead"``` | dar destaque a alguma coisa. ela adiciona um font-size de 21px automaticamente
- ```<mark> conteudo``` </mark> | dá aparencia de marca texto no que desejar ser aplicado
- ```<del> conteudo </del>``` | risca no meio um texto
- ```<ins> conteudo </ins>``` | sublinhar o texto
- ```<class="text-right/center/justify/nowrap">``` | alinhar texto para direita/centralizar/justificar/nao quebrar linha
- ```<class="text-lowercase/uppercase/capitalize">``` | caixa baixa/caixa alta/todas as palavras com a primeira letra em maiusculo
- ```<abbr title="este texto foi abreviado"> conteudo </aabr>``` | abreviar texto
- ```<adress> conteudo </adress>``` | cria um texto focado em endereço de algo
- ```<class="text-muted">``` | texto para tirar o destaque dele
- ```<class="text-primary">``` | texto fica azul claro
- ```<class="text-success">``` | verde
- ```<class="text-info">``` | azul escuro
- ```<class="text-warning">``` | amarelo esculo
- ```<class="text-danger">``` | vermelho
- ```<blockquote> conteudo </blockquote>``` | texto de citação
- ```<cite> conteudo </cite>``` | citação
- ```<class="pull-right">``` | empurrar para direita
- ```<ul class="list-unstyled>``` | tirar os pontos que aparecem nas listas
- ```<ul class="list-inline>``` | exibir os elementos em linha
- ```<dl><dt><dd>``` | lista de titulo e descrição
- ```<dl class="dl-horizontal">``` | titulo do lado esquerdo, descrição do lado direito
- ```<table class="table table-striped">``` | cor sim, cor não na tabela
- ```<table class="table table-bordered">``` | pintar as bordas da tabela
- ```<table class="table table-condensed">``` | estreitar as linhas
- ```<table class="table table-hover">``` | a linha escurece quando o mouse é passado por cima
- ```<tr class="active">``` | linha ativa no momento
- ```<div class="table-responsive">``` | dar responsividade para a tabela
- ```<form class="form-inline">``` | deixar o itens do formulario um do lado do outro
- ```<form class="form-horizontal">``` | deixar a o formulario na horizontal
- ```<div class="form-group">``` | para criação de formulario
- ```<label class="sr-only">``` | fazer o nome do label desaperecer na tela
- ```<input class="form-control">``` | para formulario se adequar automaticamente ao tamanho da tela
- ```<p class="form-control-static">``` | criar um elemento que não sofre modificação
- ```<input class="has-feedback">``` <span class="glyphicon glyphicon-ok/warning-sign/remove form-control-feedback"> | para validação de campo/aviso/simbolo de excluir
- ```<span class="help-block">``` | aviso para ser dado sob algum elemento

## March 3, 2017

#### Boostrap
- ```<a href="# "class="btn btn-default">``` | button default
- ```<a href="# "class="btn btn-primary">``` | button blue
- ```<a href="# "class="btn btn-success">``` | button green
- ```<a href="# "class="btn btn-info">``` | button light blue
- ```<a href="# "class="btn btn-warning">``` | button orange
- ```<a href="# "class="btn btn-danger">``` | button red
- ```<a href="# "class="btn btn-link">``` | button link visualization
- ```<a href="# "class="btn btn-primary btn-xs">``` | button extra small
- ```<a href="# "class="btn btn-info btn-sm">``` | button small
- ```<a href="# "class="btn btn-default">``` | button size normal (default)
- ```<a href="# "class="btn btn-danger btn-lg">``` | button long
- ```<a href="# "class="btn btn-default btn-block">``` | the button take all space available
- ```<a href="# "class="btn btn-default active">``` | button active
- ```<a href="# "class="btn btn-default disable">``` | button disable

- ```<img src="#" alt="image#" class="img-responsive">``` | responsive image
- ```<img src="#" alt="image#" class="img-rounded">``` | little circle in the borders of image
- ```<img src="#" alt="image#" class="img-circle">``` | to circle the image
- ```<img src="#" alt="image#" class="img-thumbnail">``` | line around the image with a little border
