<p align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</p>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" target="_blank">He4rt Developers&trade;</a></p>

<h3>Criando links do jeito certo</h3>
<p>O uso incorreto dos links pode ser um grande empecilho para pessoas que usam Leitores de Tela, pois muitas páginas usam o indicador "Clique aqui" para referenciar um link. Para usuarios de leitores de tela, uma das maneiras a se navegar pela página é ir de link em link, agora pense se você <b>não pudesse ver a página</b>, usasse esse método, e chegasse a um link, que ao ser lido indicasse "Clique aqui", o que você concluiria?</br>
 Por isso a primeira boa prática para criação de links é <strong>use palavras-chave</strong>. Exemplo:</p>
<p><b>Maneira correta</b></p>

```html
<p>O 4Noobs é um projeto da <a href="https://heartdevs.com/">He4rt Developers</a> com o intuito de prover conteúdo gratuito 
para iniciantes, sendo um projeto feito pela comunidade para a comunidade.</p>
```
<p>"O 4Noobs é um projeto da <a href="https://heartdevs.com/">He4rt Developers</a> com o intuito de prover conteúdo gratuito 
para iniciantes, sendo um projeto feito pela comunidade para a comunidade."</p>
<p><b>Maneira incorreta</b></p>

```html
<p>O 4Noobs é um projeto da He4rt Developers com o intuito de prover conteúdo gratuito para iniciantes, sendo um projeto feito 
pela comunidade para a comunidade. 
<a href="https://heartdevs.com/">Clique aqui</a> para saber mais sobre a He4rt Developers</p>
```

<p>"O 4Noobs é um projeto da He4rt Developers com o intuito de prover conteúdo gratuito para iniciantes, 
sendo um projeto feito pela comunidade para a comunidade. 
<a href="https://heartdevs.com/">Clique aqui</a> para saber mais sobre a He4rt Developers"</p>

<p>Outra boa prática a ser usada é <strong>avise quando o link executar uma ação diferente de um redirecionamento padrão</strong>, pois muitos links podem redirecionar por exemplo
a um vídeo, fazendo com que o vídeo passe a ser executado automaticamente e cause algum possível espanto para algum usuário de Leitor de Tela que não estará preparado para
uma voz que inicie-se repentinamente. Portanto use indicadores da ação a ser realizada no link caso esse seja o caso. Exemplos:</p>

```html
<p><a href="https://sitedeexemplo.com/apostila-curso.pdf">Baixe a apostila completa do curso</a></p>
```

<p>Ou</p>

```html
<p><a href="https://stopfly.com/devinho176">Ouça nosso podcast sobre programação</a></p>
```
