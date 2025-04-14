### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# الأنابيب

## الخطوة الأولى
ستحتاج إلى إضافة عدد معين من البلوكات إلى كل حاوية. ربما يوجد شيء في الغرفة يمكنه مساعدتك في معرفة العدد المطلوب؟

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
احسب عدد البلوكات الموجودة على المنصة خلف اللغز. استخدم بلوك ``||hoc.اسقاط (العدد) (اللون)||`` ، لإضافة هذا العدد من البلوكات إلى الحاويات.


```ghost
    hoc22.summonColoredBlockMagenta(1)
    hoc22.summonColoredBlockLightBlue(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockLime(1)
```
```template
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockLightBlue(1) 
    hoc22.summonColoredBlockMagenta(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```