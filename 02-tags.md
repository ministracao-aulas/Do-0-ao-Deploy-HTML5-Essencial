- [00 - Menu](00-menu.md)

---
---

## Tag é um elemento do HTML

Para se criar uma tag basta colocar o símbolo de "maior que" `<` seguido do nome da tag, por exemplo `div` e terminar com o símbolo de "menor que" `>`.

Exemplo:
```html
<div>
```

Porém algumas tags como a `div` no exemplo acima, precisam de uma `tag de fechamento`. Essa tag tag de fechamento precisa ser igual à tag de abertura contendo porém antes do nome da tag uma *barra* `/`.

Exemplo:
```html
</div>
```

Ou seja, uma tag `div` na realidade seria escrita como:

```html
<div> </div>
```

Há outras tags porém que não exigem tal fechamento, como por exemplo `meta`, `img`, `link`, `br`, `hr` e outras.

Como exemplo, as tags citadas acima ficariam assim:

```html
<meta>
<img>
<link>
<br>
<hr>
```

Vejam que essas tags não exigem uma outra para fechá-las.

> **Nota!**
>
> Algumas vezes essas tags tem seu fechamento representado por uma *barra* `/` ao final da tag de abertura, por exemplo: `<img/>`. Porém isso não é necessário, funciona, mas não é preciso.