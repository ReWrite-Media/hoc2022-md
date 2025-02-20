### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
الصندوق الذي يحمل السهم البرتقالي على الأرض هو المؤشر الخاص بك. ستستخدم هذه المؤشرات في مختلف أنحاء المنزل لتغيير البلوكات. في هذا النشاط، سنستخدم المؤشر لفتح الباب السري وإطلاق سراح الروبوت. (تفاعل مع المصباح للحصول على مزيد من المساعدة.)

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتحريك المؤشر ثلاث بلوكات للأمام باستخدام البلوك ``||hoc22.cursor move||`` ثم استخدم البلوك ``||hoc22.open trapdoor||`` لإطلاق الروبوت.


```ghost
    hoc22.cursorMoveOrientationOneUp(3)
    hoc22.openTrapdoor()
```
```template
    hoc22.cursorMoveOrientationOneUp(2)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```