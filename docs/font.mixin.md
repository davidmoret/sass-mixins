## [@insite](../../README.md)/[sass-mixins](../README.md)/font.mixin

Syntaxe raccourcie pour les fonts. Converti les px en rem 
pour le font-size et le line-height si l'unité d'entrée est le px

* *$style: normal*
* *$weight: 700*
* *$size: 62px*
* *$line: 74px*
* *$family: "'Arial', sans-serif"*
  
#

#### Usage :


```bash
@include font(italic, 600, 12px, 14px, Arial);
```

ou

```bash
@include font(normal, 400, 14px, 140%, $ff-body);
```
 



