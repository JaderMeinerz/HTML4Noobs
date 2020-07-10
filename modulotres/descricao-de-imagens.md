<p align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</p>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" target="_blank">He4rt Developers&trade;</a></p>

<h2>Descrição de imagens</h2>
<p>Uma das tags essenciais a se integrar acessibilidade é a tag <em>img</em> já que imagens podem conter conteúdos importantes para o contexto do assunto. Podemos então descrever as imagens. A forma mais comum é adicionando o atributo <em>alt</em> à tag imagem, pois você pode descrever a imagem usando esse atributo, fazendo com que essa descrição seja lida no lugar da imagem ao se usar um leitor de tela. Exemplo:</p>

```html
<img src="html.png" alt="ícone do html">
```

<img src="html.png" alt="ícone do html">
<p>Veja que essa descrição aparece quando a fonte da imagem não é encontrada, o famoso "crash", mas não aparece quando a imagem é encontrada, sendo apenas lida pelos leitores
de tela.</p>

<img src="/images/html.png" alt="ícone do html">

<p>Você pode adicionar descrições visíveis e mais completas desta forma:</p>

```html
<figure>
  <img src="/images/html.png" alt="ícone do html">
  <figcaption>Ícone do HTML: Pentágono laranja com um número 5 de cor branca no centro, representando o 5 de HTML5</figcaption>
</figure>
```
<figure>
  <img src="/images/html.png" alt="ícone do html">
  <figcaption>Ícone do HTML: Pentágono laranja com um número 5 de cor branca no centro, representando o 5 de HTML5</figcaption>
</figure>
<p></br>Mas sempre use o atributo <em>alt</em> pois nem todos os leitores de tela reconhecem essa tag.</p>

<h3>Imagens decorativas</h3>
<p>Mesmo para imagens decorativas <b>deve-se usar o atributo <em>alt</em></b>, porém, deixa-se o atríbuto vazio. Desta forma:</p>

```html
<img src="html.png" alt="">
```
<p>Imagem crashada está aqui embaixo</p>
<img src="html.png" alt="">
<p>Imagem crashada está aqui acima</p>

<p>Perceba que novamente coloquei uma source inexistente, como no primeiro exemplo, dessa vez, porém, você pode ver que mesmo com a imagem <em>crashada</em>, nem um ícone nem 
uma descrição aparecem, pois é como se fosse uma imagem "fantasma" que só existe como decoração, não existindo em forma "legível".</p>
