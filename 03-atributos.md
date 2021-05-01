* [00 - Menu](00-menu.md)

- - -

- - -

## Atributos

Atributos são campos adicionais que passamos dentro de uma tag de marcação. As tags do XML também podem ter atributos.

Esses atributos seguem uma mesma estrutura independendo do atributo. Essa estrutura consiste basicamente em um nome e um valor.
Veja o exemplo dos atributos de um *input*:

```html
<input name="idade" type="text" placeholder="Informe sua idade" required>
```

Percebam `name`, `type` e `placeholder`, todos são atributos e o que está dentro das aspas ("") são os valores desse atributo.

Perceba também que nosso exemplo tem um `required`. Não se engane, apesar de não ter um igual e aspas `=""` ele também é um atributo. Ele poderia ser representado com `required=""` também sem problemas, porém esse e algumas outras exceções não precisam de valores ou do "igual aspas", se tiver não atrapalha, mas nao faz diferença caso não os tenha.

Basicamente tudo que está dentro da tag de abertura é atributo (excetuando o nome).

### Algums atributos e exemplos:

    - class

```html
    <div class="cor-azul">Algo aqui</div>
    <p class="cor-azul">Algo aqui</p>
    <span class="cor-azul">Algo aqui</span>
```

    - id 
        > Obs: só pode haver 1 elemento com um ID na página. Cada um pode ter um ID, mas deve ser diferente dos demais, ou seja: único.
```html
    <div id="meu_identificador_1">Algo aqui</div>
    <p id="meu_identificador_2">Algo aqui</p>
    <span id="meu_identificador_3">Algo aqui</span>
```

    - outro-atributo

```html
    <div outro-atributo="cor-azul">Algo aqui</div>
    <p outro-atributo="cor-azul">Algo aqui</p>
    <span outro-atributo="cor-azul">Algo aqui</span>
```
