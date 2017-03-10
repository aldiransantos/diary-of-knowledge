# Diary of Knowledge
Some days ago I was studying and learning about Web Development but I'm not was noting what I was learning. I decided to create a diary to know what I'm learning and remember when I forget something.

I'm using the [Habitica](https://habitica.com/) to manage my tasks during the day and the week.

The days ago I don't remember either write down the courses I did and what I learned.

Let's to start.

## February 13, 2017
I completed the [Codecademy's Course: Learn HTML & CSS: Part I](https://www.codecademy.com/learn/learn-html-css)

## February 14, 2017
I completed almost all projects in [General Assembly](https://dash.generalassemb.ly/)

P.S. I will still do the Tumblr Project

## From the 15th to the 16th of February 2017
I completed [Flexbox Frog](http://flexboxfroggy.com/) and I learned more about CSS

I started the course of [Free Code Camp: Learn to Code and Help Nonprofits](http://freecodecamp.com/)
 - Getting Started;
 - Front End Development Certification: 
  - HTML5 and CSS;
  - Resposive Design with Boostrap;
  - Gear up for Success.

### What I learned:

#### HTML5 and CSS
  - **class="nameClass01 nameClass02 ... nameClassN"** | That is, how we can to separate nameClasses in the same class
  - **!important** | To give priority to some class or id, in other words, it override whatever parameter passed to another class or id
  
#### Bootstrap
  - **```<div class="col-xs-4"></div>```** | col = column, xs = extra small, 4 = number of parts that you want to catch. There are 12 parts of column in Bootstrap, I caught 4 parts
  - **```<div class="col-md-*"></div>```** | md = medium, * = all. Catchs all parts of columns, that is, 12 parts
  - **```<div class="img-responsive"></div>```** | Class of Bootstrap. Turns your image in a responsive image
  - **```<i class="fa fa=into-up"></i>```** | Like icon
  - **```<i class="fa fa-into-trash"></i>```** | Trash icon
  - **```<i class="fa fa-into-circle"></i>```** | Information icon
  - **```<i class="fa fa-paper-plane"></i>```** | Paper's plane icon
  - **```<button type="submit" class="btn form-control"></button>```** | Used for submit button
  
## From the 16th to the 17th of February 2017
I completed the course [Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line) in [Codecademy](https://www.codecademy.com)

### I learned the follow commands:
- **```ls```** | Lists
- **```pwd```** | Print working directory
- **```cd```** | Change directory
- **```mkdir```** | Make directory
- **```touch```** | Create a new file
- **```-a, -l, -t```** | Are options
- **```-a```** | Show directories starting with a dot (.)
- **```-l```** | Long format
- **```-t```** | The time they were last modified
- **```-alt```** | -alt lists all contents, including hidden files and directories, in long format, ordered by the date and time they were last modified.
- **```cp```** | Copies files
- ```*``` | Wildcards selects all files in the working directory
- **```mv```** | Moves and renames files
- **```rm```** | Command deletes files
- **```-r```** | Is an option = stands for "recursive" and it's used to delete a directory and all of its child directories
- **```rm -r```** | Remove directories
- **```cat```** | Command outputs
- **```grep```** | "Global Regular Expression Print". It searches files for lines the match a pattern and return the results
- **```grep -i```** | Enables the command to be case insensitive

## February 17, 2017
I completed the course [`Learn Git`](https://www.codecademy.com/learn/learn-git) in [`Codecademy`](https://www.codecademy.com/)

### What I learned:

- **```git init```** | Initialize the git
- **```touch```** | To create a file
- **```git add name_file```** | Directs the file to be committed
- **```git commit -m "Commit's message"```** | 'Commit' the file with a message
- **```git commit```** | Is usually used to commit more than one file. It will open a window for you to write comments about the changes of your files
- **```:q```** | Used to exit the commit editor after saving by pressing Ctrl + O
- **```git commit -a -m "comentario"```** | The "-a" is used to commit all files that are to be committed
- **```git status```** | Shows the status of the file (s)
- **```git log```** | Informs by whom and when the file was 'committed'
- **```git branch new_file```** | To create a new branch 
- **```git log -p```** | See all comits and their changes
- **```git log - p 2```** | See the last 2 commits and their changes. The number can change for you to reach more commits.
- **```git log --stats```** | Shows the file change statistics
- **```.gitignore```** | Responsible for saving which files can be ignored by the user in git status
- **```git reset HEAD <file>```** | Return the file from 'Changes to be comitted' mode to 'Untracked files'
- **```git add . ```** | Add all files that are in 'Untracked files'
- **```git log pretty=oneline```** | Shows commits one line at a time
- **```git log --since=2.days```** | Shows commits made two days ago
- **```git checkout <numero do commit>```** | Used to return the version of a given commit 
- **```git reset HEAD~numero```** | Returns a commit according to the number you place. For example, if you put the number 1, it will return 1 commit, if you put the number 2, two commits, and so on. 
There are two types of git reset HEAD. One is the soft (git reset HEAD ~ 1 --soft) to return as many commits as you want without deleting the files that have changed, and you can change them again
The other is the hard (git reset HEAD ~ 1 --hard) where there is no cakewalk. It returns as many files as you want excluding anything that has been modified in previous commits
- **```master```** | Main branch (the trunk of the tree)
- **```branch```** | The branch of the tree, that is, branches created to continue the development of something
- **```git branch```** | Know which branch is in
- **```git ckeckout -b nome_do_branch```** | Create a new branch and give it a name
- **```git checkout nome_do_branch```** | Go to the branch you want
- **```git merge nome_do_branch```** | Will mix a branch with the current branch. If you are in the master branch, you can choose a branch created to mix with it
- **```git push origin nome_do_branch```** | Push/up the branch to the Github website
- **```git clone url_do_arquivo```** | Clone to your computer the current Github branch
- **```git branch -a```** | Shows all branches that exist local and remote
- **```git pull```** | Verifies that all files are synchronized
- **```git checkout -b nome_do_branch origin/nome_do_branch```** | Create a branch directly to the repository
- **```git pull origin master```** | Bring the 'changes' made to your computer. It's the opposite of push
- **```git tag numero_do_release (x.x.x)```** | Indicate a version of a project
- **```git push origin master --tags```** | Create the version of the project that will appear in release on Github
- **```git init --bare```** | Repository created just to serve. Just to host your version control files
- **```git remote add local ssh://localhost/endereço_dos_seus_arquivos```** | Create a local repository
- **```git push local master```** | Add a local machine repository

## From the 18th to the 19th of February 2017

#### CSS
- **```vertical-align: middle;```** | To put the content in the middle of thing in the vertical
- **```text-shadow: 2px 2px 8px #FF0000;```** 

## February 19, 2017

#### CSS
- **```display: flex;```** | Too let the itens of horizontal form
- **```flex-wrap: wrap;```** | Items wrap around to additional lines
- **```content-flex: center;```** | Itens align in the center of a div
- **```:active```** | To active some item

## February 21, 2017

#### jQuery - biblioteca do Javascript
- **```$(document).ready(function(){});```** | Estrutura inicial do jQuery
- **```:nth-child('number');```** | Selects the position of an element within another element. Example: if it were ('ol: nth-child (2)') would select the number 2 line inside the ol
- **```.append()```** | Inserts an element in the last position of a target element
- **```.prepend()```** | Inserts an element in the first position
- **```.before()```** | Before an element
- **```.after()```** | After an element
- **```.empty()```** | Empty all elements within a tag
- **```.delete()```** | Deletes the current element and all its tags
- **```.height / .width```** | Used to increase or decrease the height and / or width of an element
- **```.css("border-radius", "10px")```** | You can also put the structure of the CSS to modify some element
- **```.html("I love jQuery!")```** | Just as it can be done with html
- **```$('element').over(function{
	$(this).addClass('cssClass');	
},
	$(this).removeClass('cssClass');
);```** - To give effect to a "button" when the mouse is passed over it
- **```.focus(function() {});```** | Give focus in some element
- **jQuery UI** | It's jQuery with AJAX
<script src="//ajax.googleapis.com/ajax/libs/jqueryui/1.9.1/jquery-ui.min.js"></script>
- **```.draggable()```** | Is a function that causes you to drag an item created somewhere on your browser screen
- **```.selectable()```** | Effect on a selected item
- **```.accordion()```** | Gives effect to open what is inside an element. Concertina effect

## February 22, 2017

#### CSS
- **overflow** | Receives the scroll or hidden attribute, which serves to show the scroll bar or not

## February 23, 2017

#### Games
- **REKT** = Completamente Destruido

#### jQuery
- **Mouse Events** | click - dbclick - focusin - fucusout - mousedown - mouseup - mousemove - mouseout - mouseover - mouseleave - mouseenter
- **Keyboard Events** | keypress - keydown - keyup
- **Form Events** | blur - focus - select - submit - change
- **Object Methods** | .fadeIn() - .fadeOut() - .fadeToggle()
- **```fuction nome_da_função(){parametros}```**;
- **event.preventDefault** | Causes, when clicking on an event, the page does not go to the top

## February 24, 2017

#### jQuery

- **```.attr()```** | Add attribute to something
- **```.appendTo()```** | Add some element to another location
- **```.clone()```** | Duplicate element
- **```:nth-child```** | Child's placement number. N-number, th-placement, type fourth, fiveth...
- **```.addClass("animated hinge")```** | Make a drop screen
- **```.addClass("shake")```** | Shakes to and fro
- **```.addClass("bounce")```** | Shake up and down

## February 25, 2017

#### Habitica
- **Base** -> Meat 
- **CC Blue** -> Blue Cotton Candy
- **CC Pink** -> Pink Cotton Candy
- **Desert** -> Potato
- **Golden** -> Honey
- **Red** -> Strawberry
- **Shade** -> Chocolate
- **Skeleton** -> Fish
- **White** -> Milk 
- **Zombie** -> Rotten Meat

## February 26, 2017

#### CS
- **border-collapse** | Used to connect lines that look separate

## March 1, 2017

#### Brackets
- I downloaded Brackets because it has Live Preview for HTML and CSS, in which you can see what you did in the code automatically by the Google Chrome browser

#### Bootstrap

- Bootstrap Screen Sizes:
 - Very small - up to 750px | col-xs
 - Small - between 750 and 970px | col-sm
 - Medium - between 970 and 1170px | col-md
 - Great - up 1170px | Col-Ig
- col-xs-offset-6 | Makes the first 6 columns empty

## March 2, 2017

#### Bootstrap
- **```<small> conteudo </small>```** | Decreases text size
- **```class="lead"```** | Give emphasis to something. It automatically adds a 21px font-size
- **```<mark> conteudo </mark>```** | Gives the appearance of text mark in which it wishes to be applied
- **```<del> conteudo </del>```** | Streak in the middle a text
- **```<ins> conteudo </ins>```** | Underline text
- **```<class="text-right/center/justify/nowrap">```** | Align text to right / center / justify / break line
- **```<class="text-lowercase/uppercase/capitalize">```** | Lowercase / uppercase / all words with the first letter in uppercase
- **```<abbr title="este texto foi abreviado"> conteudo </aabr>```** | Abbreviate text
- **```<adress> conteudo </adress>```** | Creates a text that is focused on the address of something
- **```<class="text-muted">```** | Remove the text highlight
- **```<class="text-primary">```** | Light blue text
- **```<class="text-success">```** | Green
- **```<class="text-info">```** | Dark blue
- **```<class="text-warning">```** | Dark yellow
- **```<class="text-danger">```** | Red
- **```<blockquote> conteudo </blockquote>```** | Citation text
- **```<cite> conteudo </cite>```** | Citation
- **```<class="pull-right">```** | Push to right
- **```<ul class="list-unstyled>```** | Remove the points that appear in the lists
- **```<ul class="list-inline>```** | Display the elements online
- **```<dl><dt><dd>```** | Title list and description
- **```<dl class="dl-horizontal">```** | Left side title, right side description
- **```<table class="table table-striped">```** | Color yes, color not on the table
- **```<table class="table table-bordered">```** | Paint the edges of the table
- **```<table class="table table-condensed">```** | Narrow the lines
- **```<table class="table table-hover">```** | The line darkens when the mouse is passed over
- **```<tr class="active">```** | Line currently active
- **```<div class="table-responsive">```** | Give responsiveness to the table
- **```<form class="form-inline">```** | Leave the items on the form side by side
- **```<form class="form-horizontal">```** | Leave the form horizontally
- **```<div class="form-group">```** | For form creation
- **```<label class="sr-only">```** | Make the label name disappear on the screen
- **```<input class="form-control">```** | To fit automatically to the screen size
- **```<p class="form-control-static">```** | Create an element that does not change
- **```<input class="has-feedback"> <span class="glyphicon glyphicon-ok/warning-sign/remove form-control-feedback">```** | For field validation / warning / delete symbol
- **```<span class="help-block">```** | Warning to be given under some element

## March 3, 2017

#### Boostrap
- **```<a href="# "class="btn btn-default">```** | Button default
- **```<a href="# "class="btn btn-primary">```** | Button blue
- **```<a href="# "class="btn btn-success">```** | Button green
- **```<a href="# "class="btn btn-info">```** | Button light blue
- **```<a href="# "class="btn btn-warning">```** | Button orange
- **```<a href="# "class="btn btn-danger">```** | Button red
- **```<a href="# "class="btn btn-link">```** | Button link visualization
- **```<a href="# "class="btn btn-primary btn-xs">```** | Button extra small
- **```<a href="# "class="btn btn-info btn-sm">```** | Button small
- **```<a href="# "class="btn btn-default">```** | Button size normal (default)
- **```<a href="# "class="btn btn-danger btn-lg">```** | Button long
- **```<a href="# "class="btn btn-default btn-block">```** | The button take all space available
- **```<a href="# "class="btn btn-default active">```** | Button active
- **```<a href="# "class="btn btn-default disable">```** | Button disable
- **```<img src="#" alt="image#" class="img-responsive">```** | Responsive image
- **```<img src="#" alt="image#" class="img-rounded">```** | Little circle in the borders of image
- **```<img src="#" alt="image#" class="img-circle">```** | To circle the image
- **```<img src="#" alt="image#" class="img-thumbnail">```** | Line around the image with a little border
- **```<p class="text-muted">```** | Text gray
- **```<p class="text-primary">```** | Text light blue
- **```<p class="text-success">```** | Text green
- **```<p class="text-warning">```** | Text orange
- **```<p class="text-info">```** | Text blue
- **```<p class="text-danger">```** | Text red
- **```<p class="bg-primary">```** | Background light blue
- **```<p class="bg-success">```** | Background green
- **```<p class="bg-warning">```** | Background yellow
- **```<p class="bg-info">```** | Background blue
- **```<p class="bg-danger">```** | Background red

## March 4, 2017

#### Boostrap
- **```<span class="glyphicon glyphicon-search"></span>```** | To show a magnifier icon
- **```<span class="glyphicon glyphicon-envelope pull-right"></span>```** | To show a envelope icon in right side

##### To see more icons click in [Bootstrap Glyphicons](http://getbootstrap.com/components/)

## March 7, 2017

#### Photoshop
- Cut images using pen

## March 9, 2017

#### Bootstrap
- Menu DropDown
- Menu DropUp
- Button Group
- Menu DropDown inside Button Group
- **```<button class="btn-group btn-group-justified">```** | Justify links inside a btn group
- **```<button class="btn-group btn-group-vertical">```** | Put butttons in vertical position
- Input Groups
- Tabs
- Pills
- **```<ul class="nav nav-pills nav-stacked">```** | Put the elements of ul in a vertical position
- Nav
- **```<nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">```**> | Inverts the colors of navbar

## March 10, 2017

#### Bootstrap

- **```<span class="label label-default"></span>```** | Label
- **```<span class="badge"></span>```** | Badge
- **```<div class="jumbotron"></div>```** | Jumbotron
- **```<div class="page-header">```** | Page Header
- **```<a href="#" class="thumbnail"><img src="img.png" alt="description"></a>```** | Thumbnail
- **```<div class="progress"><div class="progress-bar" role="progressbar" aria-valuemin="0" ariavaluemaz="100" style="width: 60%"></div></div>```** | Progress Bar 60% completed
- **```<div class="progress"><div class="progress-bar active" role="progressbar" aria-valuemin="0" ariavaluemaz="100" style="width: 60%"></div></div>```** | Progress Bar with animation
- **```<div class="alert alert-success">Success!</div>```** | Alert
- **```<div class="alert alert-danger alert-dismissible"><button type="button" class="close" data-dismiss="alert"><span aria-hidden="true">&times;</span>```** | Alert with button to close the message
