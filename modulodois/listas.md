<h1 align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</h1>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" 
target="_blank">He4rt Developers&trade;</a></p>

<h2>Listas</h2>
<p>Em HTML existem listas ordenadas, não ordenadas e de definição e podemos montá-las desta forma:</p>
<h3>Listas ordenadas</h3>
<p>Para montarmos listas ordenadas usamos a tag ol e a tag li sendo <em>ol</em> a definição de uma lista ordenada e <em>li</em> cada 
item da lista. Ficando desta forma:</p>

```html
<ol>
  <li>Tópico da lista</li>
  <ol>
    <li>item</li>
    <li>item</li>
  </ol>
  <li>Tópico da lista</li>
  <ol>
    <li>item</li>
    <li>item</li>
  </ol>
</ol>
```
<p>resultando nisso:</p>
<ol>
  <li>Tópico da lista</li>
  <ol>
    <li>item</li>
    <li>item</li>
  </ol>
  <li>Tópico da lista</li>
  <ol>
    <li>item</li>
    <li>item</li>
  </ol>
</ol>

<p>Você também pode usar o atibuto <em>type</em> para definir o tipo da lista e o atributo <em>start</em> para definir onde começa. 
Assim:</p>

```html
<h4>Este é um tópico fora da lista</h4>
  <ol type="1">
    <li>exemplo</li>
    <li>exemplo</li>
    <li>exemplo</li>
  </ol>
<h4>Este é outro tópico onde a lista continuará</h4>
  <ol type="1" start="4">
    <li>exemplo</li>
    <li>exemplo</li>
  </ol>
```
<h4>Este é um tópico fora da lista</h4>
  <ol type="1">
    <li>exemplo</li>
    <li>exemplo</li>
    <li>exemplo</li>
  </ol>
<h4>Este é outro tópico onde a lista continuará</h4>
  <ol type="1" start="4">
    <li>exemplo</li>
    <li>exemplo</li>
  </ol>
  
<p>As listas numeradas podem ser do tipo <em>1</em>,<em> A</em>,<em> a</em>,<em> I</em> e <em>i</em>

<h3>Listas não ordenadas</h3>
<p>As listas não ordenadas seguem o mesmo padrão, porém dessa vez com as tags <em>ul</em> e <em>li</em>, sendo melhores usadas em 
tópicos.</p>

```html
<ul>
  <li>Tópico principal</li>
  <ul>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
  </ul>
</ul>
```
<p>Ficando desta forma:</p>
<ul>
  <li>Tópico principal</li>
  <ul>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
  </ul>
</ul>

<p>Assim como nas listas ordenadas, existem tipos de listas não ordenadas porém, estes você definirá somente em 
<a href="https://github.com/mathh95/css4noobs/blob/master/Modulo-Basico/lists.md">CSS</a>.</p>

<h3>Listas mistas</h3>
<p>Lembre-se, assim como em listas ordenadas, em listas não ordenadas você também pode colocar uma lista dentro da outra, podendo 
inclusive misturar os dois tipos de listas como você achar melhor. Como neste exemplo:</p>

```html
<ol><!--lista ordenada-->
  <li>Lista com números</li>
  <ol>
    <li>Item</li>
    <li>Item</li>
    <li>Item</li>
  </ol>
  <li>Lista com formas</li>
  <ul><!--lista não ordenada-->
     <li>Item</li>
    <li>Item</li>
    <li>Item</li>
  </ul>
</ol>
```
<p>Resultando nesta lista mista:</p>

<ol><!--lista ordenada-->
  <li>Lista com números</li>
  <ol>
    <li>Item</li>
    <li>Item</li>
    <li>Item</li>
  </ol>
  <li>Lista com formas</li>
  <ul><!--lista não ordenada-->
     <li>Item</li>
    <li>Item</li>
    <li>Item</li>
  </ul>
</ol>

<h3>Listas de definição</h3>
<p>As listas de definição funcionam de uma forma um pouco mais complicada e são usadas para definições. Essas listas são criadas 
usando as tags <em>dl</em> para abrir a lista, <em>dt</em> para definir o termo e <em>dd</em> para a descrição do termo. Assim:</p>

```html
<dl><!--abre a lista-->
  <dt>Termo 1</dt><!--define o termo-->
  <dd>Aqui vai a descrição do primeiro termo</dd><!--descreve o termo-->
  <dt>Termo 2</dt>
  <dd>Descrição número 1 do segundo termo</dd>
  <dd>Descrição número 2 do segundo termo</dd>
</dl>
```
<p>Tendo esse resultado:</p>

<dl><!--abre a lista-->
  <dt>Termo 1</dt><!--define o termo-->
  <dd>Aqui vai a descrição do primeiro termo</dd><!--descreve o termo-->
  <dt>Termo 2</dt>
  <dd>Descrição número 1 do segundo termo</dd>
  <dd>Descrição número 2 do segundo termo</dd>
</dl>
