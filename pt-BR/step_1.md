Os blocos dentro de um bloco `se... então`{:class="block3control"} serão executados apenas se a **condição** na entrada hexagonal for **verdadeira**.

```blocks3
if <> then
end
```

Existem vários blocos hexagonais de **condição** no Scratch, incluindo blocos nos menus `Sensores`{:class="block3sensing"} e `Operadores`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Se você quiser executar blocos diferentes quando a **condição** for **falsa** então use um bloco `se...então... senão`{:class="block3control"}:

```blocks3
if <(money) > [9]> then
hide
change [money v] by [-10]
else
say [You don't have enough] for [2] seconds
end
```

Você pode criar verificações mais complexas "aninhando" blocos `se... então`{:class="block3control"} e `se... então... senão`{:class="block3control"} um dentro do outro.
