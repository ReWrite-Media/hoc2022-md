### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# سحب الرافعة

## الخطوة الأولى
ها هي الرافعة! قم بتحريك الروبوت نحو الرافعة ثم اسحبها للأسفل!

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
استخدم بلوك ``||hoc22.agent move||`` ، لوضع الروبوت أمام الرافعة، ثم استخدم بلوك ``||hoc22.pull lever down||`` لتفعيلها!

```ghost
    hoc22.agentMove(SixDirection.Up, 2)
    hoc22.pullLeverDownLime()
```
```template
    hoc22.agentMove(SixDirection.Forward, 2)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```