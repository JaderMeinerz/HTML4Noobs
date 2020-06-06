<p align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</p>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" 
target="_blank">He4rt Developers&trade;</a></p>

<h2>Utilização correta dos títulos</h2>
<p>Os títulos se dão pelas tags <em>h1</em>, <em>h2</em>, <em>h3</em>, <em>h4</em>, <em>h5</em> e <em>h6</em> e deve ser usado de forma 
hierárquica, sendo <em>h1</em> usado para o título principal e somente para isso, com <em>h2</em>como subtópico e assim sucessivamente,
 <b>não se devendo pular uma tag só por estilo a estilização se dá pelo CSS</b>, sendo usado da forma correta assim:</p>
 
 ```html
 <!DOCTYPE hmlt>
 <html lang="pt-br">
    <head>
      <meta charset="UTF-8">
      <title>Uso correto dos títulos</title>
    </head>
    <body>
      <header>
        <h1>Título principal</h1><!-- lembre-se que o título principal vai dentro da tag header-->
      </header>
      <h2>Subtópico comum</h2>
        <h3>Subtópico do subtópico acima</h3>
      <h2>Outro subtópico comum</h2>
    </body>
 </html>
 ```
 
 <p>Forma errada de usar os títulos:</p>
 
  ```html
 <!DOCTYPE hmlt>
 <html lang="pt-br">
    <head>
      <meta charset="UTF-8">
      <title>Uso correto dos títulos</title>
    </head>
    <body>
      <header>
        <h1>Título principal</h1><!-- lembre-se que o título principal vai dentro da tag header-->
      </header>
      <h3>Subtópico</h3>
      <h5>Subtópico</h5>
    </body>
 </html>
 ```
