Bloky uvnitř `když...tak`{:class="block3control"} bloku poběží pouze v případě, že **podmínka ** v šestiúhelníkovém vstupu je **pravdivá**.

```blocks3
if <> then
end
```

There are lots of hexagonal shaped **condition** blocks in Scratch, including blocks in the `Sensing`{:class="block3sensing"} and `Operators`{:class="block3operators"} blocks menus.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Pokud chceš spustit různé bloky s **nepravdivou ** **podmínkou**, použij místo toho blok `když...tak...jinak`{:class="block3control"}:

```blocks3
if <(money) > [9]> then
hide
change [money v] by [-10]
else
say [You don't have enough] for [2] seconds
end
```

Složitější kontroly můžeš vytvořit 'vnořením' `když...tak`{:class="block3control"} a `když...tak...jinak`{:class="block3control"} bloků jeden do druhého.
