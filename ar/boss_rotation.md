### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Unlock the Trap

## Step 1
الآن لدينا الفرصة للقبض على روبوتات الزمن! يجب محاذاة الأقراص الثلاثة الملونة لاحتجازهم.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتدوير كل جزء باستخدام ``||hoc22.rotate <section> <direction> by <number>||`` تأكد من محاذاة المسارات الملونة بين الجزئين. عند الانتهاء من ذلك، يجب أن نتمكن أخيرا من إيقاف هذه الروبوتات الزمنية!

```ghost
    hoc22.outerRingClockwise(1)
    hoc22.outerRingCounterclockwise(1)
    hoc22.middleRingClockwise(1)
    hoc22.middleRingCounterclockwise(1)
    hoc22.innerRingCounterclockwise(1)
    hoc22.innerRingClockwise(1)
```
```template       
    hoc22.outerRingClockwise(1)
    hoc22.middleRingCounterclockwise(3)

```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```