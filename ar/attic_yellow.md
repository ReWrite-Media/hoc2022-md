### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# العلية

## الخطوة الأولى
كان الروبوت يمتلك الطاقة اللازمة لفتح الباب الأخضر فقط. إذا استطعت اكتشاف طريقة لفتح نافذة السقف، فسيتمكن من شحن طاقته بشكل أكبر وسيتمكن من فتح الباب الأصفر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
انظر فوق الروبوت واستخدم  بلوك ``||hoc22.تحريك المؤشر||`` لتحديد موضع المؤشر فوق كل نافذة، ثم استخدم بلوك ``||hoc22.فتح باب الفخ||`` لفتحه واطلاق سراح الروبوت، يمكنك الاستناد على الأسهم الملونة لتوجيهك في اختيار الاتجاه المناسب الذي يجب أن يتحرك فيه المؤشر.


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
hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```