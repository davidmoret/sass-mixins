## [@insite](../../README.md)/[sass-mixins](../README.md)/bgi.mixin

Place une image en background, et permet le changement 
de couleur des svg via mask-image

* *$url: "ur('../images/logos/logo-epec.svg')"*
* *$size: contain*
* *$position: center center*
* *$repeat: no-repeat*
* *$color: false*

#

#### Usage :


```bash
@include bgi("url(./images/logos/logo.jpg')", cover, left center, repeat);
```

ou

```bash
@include bgi(get-icon($icons, 'bag'), cover, left center, repeat);
```
 



