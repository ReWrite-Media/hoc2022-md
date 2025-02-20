### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
كان الروبوت يمتلك الطاقة اللازمة لفتح الباب الأخضر فقط. إذا استطعت اكتشاف طريقة لفتح نافذة السقف، فسيتمكن من شحن طاقته بشكل أكبر وفتح الباب الأصفر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
انظر فوق الروبوت واستخدم ``||hoc22.cursor move||`` لتحديد موضع المؤشر فوق كل نافذة، ثم استخدم``||hoc22.open trapdoor||`` لفتحها، يمكنك استخدام الأسهم الملونة لتوجيهك في اختيار الاتجاه المناسب الذي يجب أن يتحرك فيه المؤشر.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.openTrapdoor()
```
```template
    hoc22.openTrapdoor()
    hoc22.cursorMoveOrientationOneRight(2)
    hoc22.cursorMoveOrientationOneUp(1)
    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```