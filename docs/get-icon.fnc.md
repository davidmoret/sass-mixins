## [@insite](../../README.md)/[sass-mixins](../README.md)/get-icon.fnc

Permet de récupérer un icon svg en dataUri et éventuellement d'injecter 
une couleur via le remplacement des %%COLOR%% présents dans le svg.

* *$folder*
* *$icon*
* *$color*

#

#### Usage :


```bash
@include get-icon($icons, 'check');
```

ou

```bash
@include get-icon($icons, 'check', #F0F);
```
 



