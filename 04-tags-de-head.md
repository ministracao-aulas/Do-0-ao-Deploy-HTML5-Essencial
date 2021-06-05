- [00 - Menu](00-menu.md)

--------------

--------------

# Tags de HEAD

Tags que o `head` aceita:

```html
<title> (Obrigatório em todo documento HTML)
<style>
<base>
<link>
<meta>
<script>
<noscript>
```

Há algumas tags que podem ficar tanto dentro `<body></body>` quanto de `<head></head>` porém há tags bem específicas que devem ficar APENAS em `<head></head>`.

Vou começar com as que devem ser inseridas APENAS dentro de `<head></head>`, essas são: `meta`, `base`, e `link`:

> _PS: Me reservo no direito de errar ;)_

```html
<!-- --------------------------------------------
    Tag meta
    Exemplos de tag meta:
-->
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta atributo-personalizado="valor que eu quero">

<!-- --------------------------------------------
    Tag title -->
    <title>Título da Página</title>

<!-- --------------------------------------------
    Tag base
    Exemplo de tag base:
-->
<base href="http://alguma_url.base.com">

<!-- --------------------------------------------
    Tag link
    Exemplos de tag link:
-->
<link rel="stylesheet" href="http://algumsite.com/style.css">
<link rel="import" href="component.html">
<link rel="alternate" href="rss.xml" type="application/rss+xml" title="RSS">
<link rel="manifest" href="manifest.json">
<link rel="stylesheet" href="print.css" media="print">
<link rel="apple-touch-icon" href="favicon.png">
<link rel="alternate" href="atom.xml" type="application/atom+xml" title="Atom">


```

---

Agora vamos às tags que podem ficar tanto dentro `<body></body>` quanto de `<head></head>`, essas são: `style`, `script`, e `noscript`:

```html
<!-- --------------------------------------------
    Tag style
    Exemplos de tag style:
-->
<style>
    .cor-azul{ color: blue;}
    .fundo-vermelho{ background: red;}
</style>

<!-- --------------------------------------------
    Tag script
    Exemplos de tag script:
-->
<script>
    console.log('algo no JavaScript');
</script>

<!-- --------------------------------------------
    Tag noscript
    Exemplos de tag noscript:
-->
<noscript>
    Seu navegador não aceita JavaScript, por isso está vendo isso!
</noscript>
```


### Links úiteis

- [W3 Schools | HTML](https://www.w3schools.com/html)
- [W3 Schools | HTML - The Head Element](https://www.w3schools.com/html/html_head.asp)
- [W3 Schools | HTML - Head Tag](https://www.w3schools.com/tags/tag_head.asp)