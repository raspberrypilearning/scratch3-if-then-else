Bloki wewnątrz bloku `if...then`{:class="block3control"} będą działać tylko wtedy, gdy **warunek** na wejściu sześciokątnym ma wartość **true**.

```blocks3
if <> then
end
```

W Scratchu istnieje wiele sześciokątnych bloków związanych z **warunkiem**, w tym bloki z menu `Sensing`{:class="block3sensing"} oraz `Operators`{:class="block3operators"}.

```blocks3
<touching (wskaźnik myszy v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Jeśli chcesz uruchamiać różne bloki, gdy **warunek** to **fałsz**, użyj zamiast tego bloku `if...then...else`{:class="block3control"}:

```blocks3
if <(pieniądze) > [9]> then
hide
change [pieniądze v] by [-10]
else
say [Nie masz wystarczająco] for [2] seconds
end
```

Możesz budować bardziej złożone kontrole poprzez "zagnieżdżanie" bloków `if...then`{:class="block3control"} oraz `if...then...else`{:class="block3control"} jeden wewnątrz drugiego.
