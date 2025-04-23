### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# الرافعات ملونة

## الخطوة الأولى
يجب قلب الأربع رافعات بالترتيب الصحيح وبسرعة كبيرة لفتح الباب. قم ببرمجة الفارس السريع لسحب الرافعات بسرعة نيابة عنك.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم بلوك ``||hoc22.اقلب (اللون) الرافعة||`` لتحريك الفارس السريع إلى اللون المحدد وقلب الرافعة. انتبه جيدا لعدد قطع السجاجيد الموجودة، فذلك سيوفر لك تلميحا حول الترتيب.

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
hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```