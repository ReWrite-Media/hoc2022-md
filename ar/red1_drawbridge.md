### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# الجسر المتحرك

## الخطوة الأولى
يحتاج إنديرمان إلى المساعدة لعبور النهر. قم بنقله عبر النهر إلى بلوك الماس. ثم حركه نحو الرافعة واسحبها للأسفل.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
قم بنقل إنديرمان إلى بلوك الماس باستخدام بلوك ``||hoc22.نقل إنديرمان||`` ثم استخدم بلوك ``||hoc22.تحريك إنديرمان||``  لتحديد موقعه و ``||hoc22.سحب الرافعة للأسفل||`` لسحب الرافعة. سيتجه إنديرمان تلقائيا نحو الرافعة عند استخدامك لبلوك ``||hoc22.سحب الرافعة للأسفل||``.


```ghost
    hoc22.endermanButlerMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()
```
```template
    hoc22.endermanButlerMoveForward(2)
    hoc22.superJump()
    hoc22.endermanButlerMoveForward(2)
    hoc22.pullLeverDown()  
```
```package
minecraft-hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```