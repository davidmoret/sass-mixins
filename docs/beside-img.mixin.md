## [@insite](../../README.md)/[sass-mixins](../README.md)/beside-img.mixin

Place en flex une image dans un :before ou un :after 

* *$width: 25px*
* *$height: 25px*
* *$img: 'url(../images/ico/ico-download.svg)'*
* *$margin: 0 15px 0 0*
* *side: before*

#

#### Usage :


```bash
@include beside-img(10px, 10px, url(../images/ico/ico-dowload.svg), 0 10px 0 0);
```

ou

```bash
@include beside-img(20px, 20px, get-icon($icons, 'bag'), 0 0 0 10px, after);
```

 



