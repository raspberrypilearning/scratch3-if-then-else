Les blocs à l'intérieur d'un bloc `si...alors`{:class="block3control"} ne s'exécuteront que si la **condition** dans l'entrée hexagonale est **vraie**.

```blocks3
if <> then
end
```

Il y a beaucoup de **condition** de forme hexagonale dans Scratch, y compris des blocs dans les menu blocs `Capteurs`{:class="block3sensing"} et `Opérateurs`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Si tu souhaites exécuter différents blocs lorsque la **condition** est **fausse** alors utilise à la place un bloc `si...alors...sinon`{:class="block3control"} :

```blocks3
if <(argent) > [9]> then
hide
change [argent v] by [-10]
else
say [Tu n'en as pas assez] for [2] seconds
end
```

Tu peux créer des contrôles plus complexes en « imbriquant » des blocs `si...alors`{:class="block3control"} et `si...alors...sinon`{:class="block3control"} l'un dans l'autre.
