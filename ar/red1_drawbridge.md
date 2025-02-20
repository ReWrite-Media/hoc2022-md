### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Drawbridge

## Step 1
يحتاج خادم إنديرمان إلى المساعدة لعبور النهر. قم بنقل الخادم عبر النهر إلى بلوك الماس. ثم حرك الخادم نحو الرافعة واسحبها للأسفل.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
قم بنقل خادم الإنديرمان إلى بلوك الماس باستخدام ``||hoc22.teleport enderman||`` ثم استخدم ``||hoc22.move enderman||`` لتحديد موقعه و ``||hoc22.pull lever down||``  لسحب الرافعة. سيتجه الإنديرمان تلقائيا نحو الرافعة عند استخدامك لبلوك ``||hoc22.pull lever down||`` .



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
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```