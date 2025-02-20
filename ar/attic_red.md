### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
لفتح الباب الأحمر، يجب أن تعمل أنت والروبوت معا. قم بتحريك الرافعة لرفع الجدار الحديدي، ثم انقل الروبوت ليكون فوق البلوك الذهبي الموجود أمام الباب الأحمر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتحريك الرافعة للأسفل لرفع الجدار الحديدي، ثم قم بتحريك الروبوت 14 بمقدار 14 بلوك للأمام باستخدام   ``||hoc22.agent move <direction> by <number>||``



```ghost
    hoc22.agentMove(SixDirection.Up, 1)
```
```template
    hoc22.agentMove(SixDirection.Forward, 10)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```