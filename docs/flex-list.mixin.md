## [@insite](../../README.md)/[sass-mixins](../README.md)/flex-list.mixin

Permet de faire simplement des listes responsives avec flex en conservant 
l'alignement à gauche et avec des espaces uniquement entre les éléments.

* *$cols: 3*
* *$margin: 10*
* *$first_bp: map-get($breakpoints, "tablet")*
* *$second_bp: map-get($breakpoints, "desktop")*
* *$third_bp: map-get($breakpoints, "large")*

#

#### Usage :


```bash
@include flex-list(3, 10, 500px, 900px);
```

ou

```bash
@include flex-list(4, 1, 500px, 900px, 900px);
```
ou encore

```bash
@include flex-list(5, 5, map-get($breakpoints, "tablet"), map-get($breakpoints, "desktop"), map-get($breakpoints, "large"));
```
 



