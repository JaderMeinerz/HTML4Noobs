<p align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</p>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" 
target="_blank">He4rt Developers&trade;</a></p>

<h2>A importância de declarar a linguagem</h2>
<p>A declaração da linguaguem é parte crucial do seu documento HTML, ajudando o navegador a identificar a linguagem do seu documento você
também ajuda-o a oferecer traduções para outras linguagens e <b>principalmente</b> ajuda leitores de tela a identificar a linguagem a ser
usada. <a href="https://www.youtube.com/watch?v=0uzxu9dQnuU">Efeito da declaração da linguagem errada  a leitores de tela</a>.</p>

<h2>Como declarar a linguagem</h2>
<p>A declaração da linguagem se dá logo no início do código, na abertura da tag HTML, dessa forma:</p>

```html
<!DOCTYPE html>
<html lang="pt-br"><!--aqui você declara a linguagem usando o atributo lang-->
  <head>
  </head>
  <body>
  </body>
</html>
```
<p>Lembre-se também de usar o <em>charset</em> para definir o tipo de caracteres usados</p>

```html
<!DOCTYPE html>
<html lang="pt-br"><!--aqui você declara a linguagem usando o atributo lang-->
  <head>
    <meta charset="UTF-8"><!-- você declara o tipo de caracteres assim-->
  </head>
  <body>
  </body>
</html>
```
