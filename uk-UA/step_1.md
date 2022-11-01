Блоки, що знаходяться всередині блоків `якщо...то`{:class="block3control"} будуть працювати тільки в тому випадку, якщо **умова** у шестигранному вході дорівнює **істині**.

```blocks3
if <> then
end
```

У Scratch є багато блоків з шестикутними формами **condition**, включаючи блоки з меню блоків `Датчики`{:class="block3sensing"} та `Оператори`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

Якщо ти хочеш запускати різні блоки, коли **умова** дорівнює значенню **хибність**, тоді замість цього використовуй блок `якщо...то...інакше`{:class="block3control"}:

```blocks3
if <(money) > [9]> then
hide
change [money v] by [-10]
else
say [You don't have enough] for [2] seconds
end
```

Ти можеш побудувати більш складні перевірки за допомогою 'вкладення' блоків`якщо...то`{:class="block3control"} та `якщо...то...інакше`{:class="block3control"} один всередині іншого.
