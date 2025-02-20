### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Pitfall

## Step 1
قم بتحريك وحش الطين للأمام بمقدار 6 بلوكات. عند مروره على لوحة الضغط، ستفتح حفرة لمدة ثانية واحدة. تأكد من أنه ينتظر عودة البلوك قبل أن يتحرك للأمام مرة أخرى.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
قم بتحريك وحش الطين للأمام باستخدام ``||hoc22.move golem forward by <number>||`` حرك الوحش للأمام بمقدار بلوكين، ثم استخدم ``||hoc22.wait for block||`` لجعله ينتظر لمدة ثانية واحدة قبل أن يتحرك للأمام بمقدار بلوكين إضافيتين.



```ghost
    hoc22.clayGolemMoveForward(1)
    hoc22.waitForBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    hoc22.clayGolemMoveForward(2) 
    hoc22.clayGolemMoveForward(2)    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```