# Rocketseat - Guia Estelar de HTML
Neste curso iremos aprender o básico de HTML com _**Mayk Brito**_ da Rocketseat

>HTML é a base de qualquer website ou aplicação web e nesse guia vamos dominar essa linguagem e tudo que podemos criar com ela

## Aula 1 - Abertura
Iremos aprender sobre os conceitos essenciais, tags, atributos, alinhamentos, hierarquia, elementos, links, navegação entre diretórios e muito mais

## Aula 2 - Instalando plugin de preview HTML
Para visualizar oque digitamos e para a página atualizar automaticamente iremos usar a dependência abaixo, esta dependência vai mostrar tudo que acontece mesmo se o arquivo não foi salvo novamente
````
HTML Preview
````

## Aula 3 - O que é HTML
O HTML é uma abreviação de Hypertext Markup Language

Ela é uma linguagem de marcação de hyper textos, a marcação é a criação de tags e o hyper texto que alem de escrevemos damos funcionalidades ao mesmo como criação de links, está linguagem é totalmente diferente de uma de programação como o Java ou JavaScript

## Aula 4 - Comentários
Existe os comentários que nos ajudar a lembrar rapidamente para que serve aquele grupo de comandos, para criar um temos que utilizar o seguinte comando e ele possuirá uma cor diferente
````
<!-- SEU COMENTÁRIO AQUI -->
````
## Aula 5 - Anatomia das Tags
O Emmet Abbreviation vem instalado junto do Visual Studio Code facilitando a digitação de comandos pois ele possui diversos atalhos

A abertura e fechamento de uma tag é a combinação de sinais de menor e maior
````
<h1>O CONTEÚDO AQUI</h1>
````
## Aula 6 - Atributos
Atributos são itens que utilizamos para definir algumas configurações as tags, os atributos não booleano são compostos por um nome, sinal de igual e aspas duplas para evitar conflito

Podemos ate usar aspas simples mais ai ficamos exposto a erros

## Aula 7 - Atributos Globais
Os atributos globais são aplicados a todas as tags e estes são os mais utilizados
````
class: Muito usado para criação de estilos
contenteditable: Permite alterações
data-qualquer: Usamo com uma linguagem de programação
hidden: Oculta uma tag
id: Identifica um tag onde o nome não pode repetir
style: Cria uma estilização
tabindex: Define a sequencia dos tabs
title: Define um título para a tag
````

Existe diversos atributos, para ver mais temos o site [Developer Mozilla - Global Attributes](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes)

## Aula 8 - Aninhamento Hierarquia
Conseguimos colocar tag dentro de outras mais devemos ficar atento com sua abertura e fechamento

Quando colocamos uma dentro de outra elas acabam recebendo uma hierarquia de familia onde a próxima tag será filha da anterior

O posicionamento dos elementos quer dizer que alguns tipos de tags quando forem criados iram criar uma nova linha com o conteúdo, se quisermos força a quebra de uma linha usamos o comando abaixo
````
<br/>
````

## Aula 9 - Praticando
Iremos colocar tudo em pratica criando tags, quebrando linhas, destacando alguns texto e criando link para um site

## Aula 10 - Caracteres Reservados
A utilização de caracteres especial, principalmente os utilizados na programação, pode criar bugs fazendo a aplicação não funcionar

Para evitar isso devemos usar os comandos especiais para mostrar que queremos um carácter como abaixo, com este método conseguimos aplicar qualquer tipo de carácter
````
&lt; <
&amp; &
&quot; "
&iecy; e
````

Para uma lista completo dos comandos temos o site [Dev Media](http://arquivo.devmedia.com.br/artigos/devmedia/html-entities.html)

## Aula 11 - Anatomia Documento
Isto é as tags que devemos sempre criar para o nosso site poder funcionar, podemos criar manualmente ou utilizar comandos rápidos, os comandos abaixo servem para criar as tags com especificações únicas
````
!
!!
html:5
html:xml
````

## Aula 12 - Criando Projetos
A criação dele é muito fácil temos somente que criar os arquivos com as extensões correta como html e as pastas em um local onde conseguimos achar depois

## Aula 13 - Semântica
A semântica é muito utilizada por site de busca e por programas terceiros
Devemos criar grupos por tipo de dado como cabeçalho, rodapé, fotos e outros

## Aula 14 - Títulos e Parágrafos
A utilização destes elemento cria um texto semântico assim permitindo uma experiencia para o usuário boa, pois um site mal montado todos iram ignorar

## Aula 15 - Listas
As listas podem ser criadas em forma ordenada ou não

Temos os comandos abaixo que são utilizado
````
<ul></ul> <!-- CRIA UMA LISTA COM PONTOS -->
<ol></ol>  <!-- CRIA UMA LISTA COM NÚMEROS -->
<li></li> <!-- CRIA UMA LINHA -->
````

## Aula 16 - Citações
Temos um recurso que podemos usar para falar que o conteúdo que existe em nosso site é uma citação, por exemplo
````
<blockquote></blockquote> <!-- TAG ESPECIAL PARA CITAÇÕES -->
<a></a> <q></q> <!-- PODEMOS USAR ESTE GENÉRICO --->
````

Mais todos modelos acima precisa combinar com este comando informando o link tanto no formato de uma tag ou atributo
````
<cite></cite>
cite=""
````
