<p align="center">
  <img src="/images//html.png" alt="HTML Logo" width="120px">
</p>
<h1 align="center">HTML4Noobs</h1>
<p align="center">Seja bem-vindo ao HTML4Noobs, seu curso introdutório de HTML5 provido pela <a href="https://heartdevs.com/" target="_blank">He4rt Developers&trade;</a></p>

<h2>Primeiro HTML</h2>
<p>Para começarmos, crie uma pasta com o nome "html4noobs" na sua área de trabalho, então abra o VSCode e vá em Open folder</p>
<img src="https://github.com/JaderMeinerz/HTML4Noobs/blob/readme-edit/images/openfolder.png">
<p>Após localizar a pasta e abrir-la vá em New File</p>
<img src="https://github.com/JaderMeinerz/HTML4Noobs/blob/readme-edit/images/newfile.png">
<p>Nomeie o arquivo como "exercicio01.html" e confirme.</p>
<h3>Marcas essênciais</h3>
<p>A primeira marca a ser adicionada ao código é o !DOCTYPE dessa forma:<p>

```html
<!DOCTYPE html> 
```

<p>Apesar de parecer uma tag o doctype é uma declaração que diz ao navegador que o tipo do documento é html, fazendo com que mesmo que você não
tenha adicionado o .html ao arquivo ele reconheça mesmo assim. </br> A próxima e então primeira tag a ser usada é o próprio html, simbolizando
que todo texto dentro das marcas faz parte do html. Faremos dessa forma:</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html>

</html>
```

<p>Lembre-se sempre de fechar as tag e de salvar o arquivo, você pode fazer isso indo em File>save ou apenas usando ctrl+s. Um fator importante
na hora de abrir a tag é declarar o idioma da página, então faremos isso:</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html--->

</html>
```

<p>Agora para o próximo passo, devemos abrir a tag head onde ficarão algumas informações como o título da página, o tipo de caracteres e
uma breve descrição da página</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html e declara o idioma da página--->
  <head>
  
  </head>
</html>
```
<p> Agora adicionaremos um título à página</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html e declara o idioma da página--->
  <head> <!--- onde ficarão informações gerais da página --->
    <title>Primeiro HTML</title>      
  </head>
</html>
```
<p>A partir de agora se você abrir o arquivo que está na sua pasta você já poderá ver o título da página</p>
<img src="https://github.com/JaderMeinerz/HTML4Noobs/blob/readme-edit/images/titulo.png">

<p>Adicionaremos então o tipo de caracteres e a descrição para completarmos a tag head.</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html e declara o idioma da página--->
  <head> <!--- onde ficarão informações gerais da página --->
    <meta charset="UTF-8"> <!--- declara o tipo de caracteres--->
    <title>Primeiro HTML</title>  <!--- declara o título da página--->   
    <meta name="description" content="minha primeira pagina em html"> <!--- descrição da página--->
  </head>
</html>
```
<p>Head concluido, partiremos para o Body, onde ficará todo o corpo da página</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html e declara o idioma da página--->
  <head> <!--- onde ficarão informações gerais da página --->
    <meta charset="UTF-8"> <!--- declara o tipo de caracteres--->
    <title>Primeiro HTML</title>  <!--- declara o título da página--->   
    <meta name="description" content="minha primeira pagina em html"> <!--- descrição da página--->
  </head>
  <body><!--- corpo da página--->
  
  </body>
</html>
```

<p>Dentro do corpo da página teremos uma tag chamada header, onde colocaremos o título principal contendo o assunto da página</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html e declara o idioma da página--->
  <head> <!--- onde ficarão informações gerais da página --->
    <meta charset="UTF-8"> <!--- declara o tipo de caracteres--->
    <title>Primeiro HTML</title>  <!--- declara o título da página--->   
    <meta name="description" content="minha primeira pagina em html"> <!--- descrição da página--->
  </head>
  <body><!--- corpo da página--->
    <header><!--- onde será introduzido o assunto principal--->
      <h1>Este é o meu primeiro documento HTML</h1> <!---titulo principal--->
    </header>
  </body>
</html>
```

<p>Com o conteúdo introduzido, agora iremos à parte principal, apesar do HTML não ser uma linguagem de programação, entre as linguagens de 
programação há uma maldição que diz que se você não iniciar os estudos àquela linguagem fazendo o programa mostrar "Hello, world!" na tela
você nunca aprenderia a linguagem, portanto, vamos nos precaver dessa maldição usando um parágrafo</p>

```html
<!DOCTYPE html> <!--- declara o tipo de documento --->
<html lang="pt-br"> <!--- declara que tudo entre as tags faz parte do html e declara o idioma da página--->
  <head> <!--- onde ficarão informações gerais da página --->
    <meta charset="UTF-8"> <!--- declara o tipo de caracteres--->
    <title>Primeiro HTML</title>  <!--- declara o título da página--->   
    <meta name="description" content="minha primeira pagina em html"> <!--- descrição da página--->
  </head>
  <body><!--- corpo da página--->
    <header><!--- onde será introduzido o assunto principal--->
      <h1>Este é o meu primeiro documento HTML</h1> <!---titulo principal--->
    </header>
    <p>Hello, world!</p><!--- aqui nos livramos da maldição---> 
  </body>
</html>
```

<p>E livres da maldição, encerramos esse primeiro exercício, não esqueça de salvar o arquivo e vá lá ver como ficou seu primeiro HTML!</p>
