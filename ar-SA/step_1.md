يتم تشغيل الكتل البرمجية الموجودة داخل كتلة `إذا`{:class="block3control"} فقط اذا كان **الشرط** في الادخال بالشكل السداسي هو **صحيح**.

```blocks3
if <> then
end
```

هناك الكثير من كتل الاشكال السداسية للـ**شرط** في Scratch، بما في ذلك المقاطع البرمجية في قوائم كتل `الاستشعار`{:class="block3sensing"} و `العمليات`{:class="block3operators"}.

```blocks3
<touching (mouse-pointer v) ?>

<touching color (#ff00d7) ?>

<[] = [50]>
```

إذا كنت تريد تشغيل مقاطع برمجية مختلفة عندما يكون **الشرط** هو **خطأ** فاستخدم المقطع البرمجي`اذا .... والا`{:class="block3control"}بدلاً من ذلك:

```blocks3
if <(مال) > [9]> then
hide
change [مال v] by [-10]
else
say [ليس لديك ما يكفي] for [2] seconds
end
```

يمكنك إنشاء عمليات تحقق أكثر تعقيدًا عن طريق "تداخل" المقطع البرمجي `إذا`{:class="block3control"} و `اذا..... والا`{:class="block3control"} بحيث يتم وضع أحدهما داخل الآخر.

