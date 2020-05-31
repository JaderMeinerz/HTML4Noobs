<h1 align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</h1>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" 
target="_blank">He4rt Developers&trade;</a></p>

<h2>Criando links</h2>
<p>Para a criação de um link usaremos a tag <a>. Desta forma:</p>

```html
<a href="https://github.com/JaderMeinerz/HTML4Noobs">Este link leva para o início do repositório</a>
```
<p>Resultando nisso:</p>
<a href="https://github.com/JaderMeinerz/HTML4Noobs">Este link leva para o início do repositório</a>

<p><br>Você também pode criar um link neste estilo:</p>

```html
<p>Clique <a href="https://github.com/JaderMeinerz/HTML4Noobs">aqui</a> para ir ao início do repositório.</p>
```
<p>Clique <a href="https://github.com/JaderMeinerz/HTML4Noobs">aqui</a> para ir ao início do repositório.</p>
<p>Normalmente os links ficam no meio do texto, ou então no rodapé da página, desta forma</p>

```html
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="description" content="terceiro documento html">
    <title>Adicionando itens</title>
</head>

<body>
    <header>
        <h1>Adicionaremos links nessa página</h1>
    </header>
    <p>Esta página de exercício foi desenvolvida para ser usada de exemplo no html4noobs, confira mais clicando <a
            href="https://github.com/JaderMeinerz/HTML4Noobs" target="_blank">aqui</a></p>
    <!--o atributo target="_blank" indica que a página será aberta em uma nova guia-->
    <footer>
        <!--esta tag abre o rodapé, aqui fica o copyright e possíveis menus de fim de página-->
        <a href="https://github.com/JaderMeinerz/HTML4Noobs">Voltar para a página anterior</a>
        <p>copyright &copy; He4rt Developers</p>
    </footer>
</body>

</html>
```
