Los bloques dentro de un bloque `si... entonces`{:class="block3control"} solo se ejecutarán si la **condición** en la entrada hexagonal es **verdadera**.

```blocks3
if <> then
end
```

Hay muchos bloques de **condición** de forma hexagonal en Scratch, incluyendo bloques en los Menús de bloques `Sensores`{:class="block3sensing"} y `Operadores`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Si lo que quieres es ejecutar diferentes bloques cuando la **condición** es **falsa**, utiliza en su lugar un bloque `si...entonces...si no`{:class="block3control"}:

```blocks3
if <(dinero) > [9]> then
hide
change [dinero v] by [-10]
else
say [No tienes suficiente] for [2] seconds
end
```

Puedes crear comprobaciones más complejas 'anidando' bloques `si...entonces`{:class="block3control"} y `si...entonces...si no`{:class="block3control"} uno dentro del otro.

