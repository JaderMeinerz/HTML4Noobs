<p align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</p>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" target="_blank">He4rt Developers&trade;</a></p>

<h3>Criando links do jeito certo</h3>
<p>O uso incorreto dos links pode ser um grande impecilho para pessoas que usam Leitores de Tela pois muitos sites usam indicadores como "Clique aqui" para referênciar um link
sendo que uma das maneiras a se navegar pela página é através dos links, fazendo com que a pessoa chegue a um link dito como "Clique aqui" mas não explique o para que serve esse link
seja pra direcionar outro site, para uma outra parte da página, para fazer download de alguma coisa. Por isso a primeira boa prática para criação de links é <strong>use 
palavras-chave</strong>. Exemplo:</p>
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
