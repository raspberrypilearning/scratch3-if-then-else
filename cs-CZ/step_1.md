Bloky uvnitř `když...tak`{:class="block3control"} bloku poběží pouze v případě, že **podmínka** v šestiúhelníkovém vstupu je **pravdivá**.

```blocks3
if <> then
end
```

Ve Scratchi je spousta bloků ve tvaru šestiúhelníku s **podmínkou**, včetně bloků v nabídkách bloků `Vnímání`{:class="block3sensing"} a `Operátory`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Pokud chceš spustit různé bloky s **nepravdivou** **podmínkou**, použij místo toho blok `když...tak...jinak`{:class="block3control"}:

```blocks3
if <(peníze) > [9]> then
hide
change [peníze v] by [-10]
else
say [Nemáš jich dost] for [2] seconds
end
```

Složitější kontroly můžeš vytvořit 'vnořením' `když...tak`{:class="block3control"} a `když...tak...jinak`{:class="block3control"} bloků jeden do druhého.
