### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Colored Levers

## Step 1
يجب قلب الأربعة رافعات بالترتيب الصحيح وبسرعة كبيرة لفتح الباب. قم ببرمجة الفارس السريع لسحب الرافعات بسرعة نيابة عنك.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم ``||hoc22.flip <color> lever||`` لتحريك الفارس السريع إلى اللون المحدد وقلب الرافعة. انتبه جيدا لعدد قطع السجاد الموجودة، فذلك سيوفر لك تلميحا حول الترتيب.

```ghost
    hoc22.teleportLightBlueLever()
    hoc22.teleportMagentaLever()
    hoc22.teleportYellowLever()
    hoc22.teleportOrangeLever()
```
```template
    hoc22.teleportLightBlueLever()
    hoc22.teleportOrangeLever()
    hoc22.teleportYellowLever()
    hoc22.teleportMagentaLever()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```