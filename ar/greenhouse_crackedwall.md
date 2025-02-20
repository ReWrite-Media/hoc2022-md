### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Cracked Wall

## Step 1
الحديقة بحاجة إلى مزيد من الماء! استخدم المؤشر لكسر بعض هذا الطوب التالف لزيادة تدفق الماء.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتحريك المؤشر باستخدام البلوكات  ``||hoc22.cursor move <direction>||`` ثم استخدم ``||hoc22.break block||`` لكسر البلوك في ذلك الموضع. قم بكسر البلوكات الأربعة للحصول على كمية كافية من الماء للانتقال إلى اللغز التالي.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.breakBlock()
```
```template
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.breakBlock()
    hoc22.cursorMoveOrientationOneRight(4) 
    hoc22.breakBlock() 
    hoc22.cursorMoveOrientationOneDown(4)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.breakBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```