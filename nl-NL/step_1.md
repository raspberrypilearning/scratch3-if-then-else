De blokken binnen een `als...dan`{:class="block3control"} blok zullen alleen worden uitgevoerd als de **voorwaarde** in de zeshoekige invoer **waar** is.

```blocks3
if <> then
end
```

Er zijn veel zeshoekige **voorwaarde** blokken in Scratch, inclusief blokken in de `Waarnemen`{:class="block3sensing"} en `Functies`{:class="block3operators"} blokkenmenu's.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Als je verschillende blokken wilt uitvoeren wanneer de **voorwaarde** **niet waar** is, gebruik dan in plaats daarvan een `als...dan...anders`{:class="block3control"} blok:

```blocks3
if <(money) > [9]> then
hide
change [money v] by [-10]
else
say [You don't have enough] for [2] seconds
end
```

Je kunt complexere controles bouwen door `als...dan`{:class="block3control"} en `als...dan...anders`{:class="block3control"} blokken in elkaar te 'nesten'.
