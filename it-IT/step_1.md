I blocchi all'interno di un blocco `se...allora`{:class="block3control"} verranno eseguiti solo se la **condizione** inserita nel campo esagonale è **vera**.

```blocks3
if <> then
end
```

In Scratch ci sono molti blocchi **condizione** a forma di esagono, tra cui i blocchi nei menu `Sensori`{:class="block3sensing"} e `Operatori`{:class="block3operators"}.

```blocks3
<touching (puntatore del mouse v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Se vuoi eseguire blocchi diversi quando la **condizione** è **falsa**, puoi utilizzare un blocco `se...allora...altrimenti`{:class="block3control"}:

```blocks3
if <(denaro) > [9]> then
hide
change [denaro v] by [-10]
else
say [Non ne hai a sufficienza] for [2] seconds
end
```

Puoi creare controlli più complessi "annidando" blocchi `se...allora`{:class="block3control"} e `se...allora...altrimenti`{:class="block3control"} uno dentro l'altro.
