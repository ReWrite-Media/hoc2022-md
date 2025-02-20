### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Maze

## Step 1
يحتاج خادم الإنديرمان مساعدتك للعبور عبر المتاهة للوصول إلى بلوك الزمرد في الجهة الأخرى. تبدو الأذرع الموجودة على الجدار متطابقة مع ألوان الأبواب. عند تحريك الذراع، يفتح باب ويغلق آخر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
قم بإنشاء مسار إلى بلوكات الزمرد باستخدام الروافع. كن حذرا! فتح باب واحد سيؤدي إلى إغلاق الباب الآخر. بعد ذلك، استخدم  ``||hoc22.move enderman||`` لإيصالهم عبر المتاهة إلى البلوكات الزمردية.



```ghost
    hoc22.npcMoveForward(1)
    hoc22.npcMoveBack(1)
    hoc22.npcMoveLeft(1)
    hoc22.npcMoveRight(1)
```
```template
    hoc22.npcMoveForward(2)
    hoc22.npcMoveRight(3) 
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```