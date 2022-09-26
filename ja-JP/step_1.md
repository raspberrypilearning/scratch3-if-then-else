`もし...ならば`{:class="block3control"}ブロック内にあるブロックは、六角形の中の**条件**が**真（true）**の時にだけ実行されます。

```blocks3
if <> then
end
```

Scratchには、`調べる`{:class="block3sensing"}や`演算`{:class="block3operators"}ブロックメニューなどに、六角形の形をした**条件**ブロックがたくさんあります。

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

**条件**が**偽（false）**の時に別のブロックを実行したい場合は、代わりに`もし..ならば...でなければ`{:class="block3control"}ブロックを使います。

```blocks3
if <(お金) > [9]> then
hide
change [お金 v] by [-10]
else
say [手持ちが足りません] for [2] seconds
end
```

`もし...ならば`{:class="block3control"}と`もし...ならば...でなければ`{:class="block3control"}ブロックを他のブロック内で「ネスト」すると、より複雑な条件を判定できます。
