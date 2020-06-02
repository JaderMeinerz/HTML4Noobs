<h1 align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</h1>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" 
target="_blank">He4rt Developers&trade;</a></p>

<h2>Tabelas</h2>
<p>A criação de tabelas se dá por partes e é parecida com a criação de listas, sendo mais avançado e por isso, adicionarei comentários 
na abertura de cada tag. Leia mais de uma vez se necessário. Para criar uma tabela são usadas as tags <em>table</em>, <em>tr</em>, 
<em>th</em> e <em>td</em>.</p>

<table>
  <tr>
    <th>Tag</th>
    <th>O que significa</th>
    <th>Tradução</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>table</td>
    <td>Table</td>
    <td>Tabela</td>
    <td>Esta tag tem a função de abrir uma tabela</td>
  </tr>
  <tr>
    <td>tr</td>
    <td>Table Row</td>
    <td>Linha da Tabela</td>
    <td>Esta tag tem a função de criar a linha de uma tabela, dentro dessa linha vão titulos ou descrições</td>
  </tr>
  <tr>
    <td>th</td>
    <td>Table Header</td>
    <td>Cabeçalho/Título da tabela</td>
    <td>Esta tag tem a função de dar um título à uma coluna</td>
  </tr>
  <tr>
    <td>td</td>
    <td>Table Data</td>
    <td>Dados da Tabela</td>
    <td>Esta tag tem a função de atribuir dados à cada coluna da tabela</td>
  </tr>
<table>

<p>Ou seja:</p>

```html
<table><!--com esta tag criamos a tabela-->
  <tr><!-- nesta tag criamos a primeira linha, onde ficam os títulos-->
    <th>Tag</th><!-- aqui criamos a primeira coluna, com o título "Tag"-->
    <th>O que significa</th> <!-- aqui criamos a segunda coluna, com o título "O que significa"-->
    <th>Tradução</th><!-- aqui criamos a terceira coluna, com o título "Tradução"-->
    <th>Descrição</th><!-- aqui criamos a quarta coluna, com o título "Descrição"-->
  </tr>
  <tr><!-- aqui criamos a segunda linha, será a primeira linha de informações-->
    <td>table</td><!-- aqui adicionamos a primeira "Tag", no caso table-->
    <td>Table</td><!-- aqui adicionamos "O que significa" a tag table-->
    <td>Tabela</td><!--aqui adicionamos a "Tradução" da tag table--> 
    <td>Esta tag tem a função de abrir uma tabela</td><!-- aqui adicionamos a "Descrição" da tag table-->
  </tr>
  <tr><!-- aqui criamos a terceira linha, a segunda linha de informações-->
    <td>tr</td><!-- aqui adicionamos a segunda "Tag", no caso tr-->
    <td>Table Row</td><!-- aqui adicionamos "O que significa" a tag tr-->
    <td>Linha da Tabela</td><!--aqui adicionamos a "Tradução" da tag tr--> 
    <td>Esta tag tem a função de criar a linha de uma tabela, dentro dessa linha vão titulos ou 
    descrições</td><!-- aqui adicionamos a "Descrição" da tag tr-->
  </tr>
  <tr>
    <td>th</td><!-- aqui adicionamos a terceira "Tag", no caso th-->
    <td>Table Header</td><!-- aqui adicionamos "O que significa" a tag th-->
    <td>Cabeçalho/Título da tabela</td><!--aqui adicionamos a "Tradução" da tag tr--> 
    <td>Esta tag tem a função de dar um título à uma coluna</td><!-- aqui adicionamos a "Descrição" da tag td-->
  </tr>
  <tr>
    <td>td</td><!-- aqui adicionamos a quarta "Tag", no caso td-->
    <td>Table Data</td><!-- aqui adicionamos "O que significa" a tag td-->
    <td>Dados da Tabela</td><<!--aqui adicionamos a "Tradução" da tag tr--> 
    <td>Esta tag tem a função de atribuir dados à cada coluna da 
    tabela</td><!-- aqui adicionamos a "Descrição" da tag td-->
  </tr>
<table>
```
