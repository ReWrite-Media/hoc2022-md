### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Picture Slide

## Step 1
يبدو أن الصورة قد أصبحت مشوشة! لنحاول تحريك الأجزاء لإعادة تنظيمها.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
استخدم البلوك ``||hoc22.push <color> <direction>||``  لتفعيل المكابس من أجل تحريك البلوكات في الاتجاه المطلوب. يتطلب الأمر على الأقل ثلاث حركات لإعادة ترتيب الصورة بشكل صحيح.

```ghost
    hoc22.mosaicPushUp()
    hoc22.mosaicPushDown()
    hoc22.mosaicPushLeft()
    hoc22.mosaicPushRight()
```
```template
    hoc22.mosaicPushLeft()
    hoc22.mosaicPushRight()
    hoc22.mosaicPushDown()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```