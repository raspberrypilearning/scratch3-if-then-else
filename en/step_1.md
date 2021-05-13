The blocks inside an `if...then`{:class="block3control"} block will only run if the **condition** in the hexagonal input is **true**.

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

If you want to run different blocks when the **condition** is **false** then use an `if...then...else`{:class="block3control"} block instead:

```blocks3
if <(money) > [9]> then
hide
change [money v] by [-10]
else
say [You don't have enough] for [2] seconds
end
```

You can build more complex checks by 'nesting' `if...then`{:class="block3control"} and `if...then...else`{:class="block3control"} blocks one inside the other.
