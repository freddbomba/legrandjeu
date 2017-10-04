first test of PITCHME.md
---
@title[a wonderful news]
this is a slide delimiter
- and a list bullet
- another

* another
---
# and a new slide
with code
```
function logic:init(scene)
  trace("logic:init()")

  -- global RNG
  dofile("rng.lua")
  F_RNG = rng()

  dofile("flock.lua")
  dofile("flockScene.lua")

```
@[1-2]
@[4-6]
@[8,9]
---
---?image=pres-assets/logo.jpg&size=auto 50%
---
this is sketch of the first logo idea for legrandjeu
to demonstrate the handling of images
+++
and what follows is an inline image call
and the logo as it is now..
![Logo](http://legrandjeu.net/wp-content/uploads/2017/06/cropped-loghino-sito-le-grand-jeu-10-2.png)
pretty minimal
---
some math
$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$
---
some charts
---

<canvas data-chart="line">
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[65,59,80,81,56,55,40],
    "label":"My first dataset","backgroundColor":"rgba(20,220,220,.8)"
   },
   {
    "data":[28,48,40,19,86,27,90],
    "label":"My second dataset","backgroundColor":"rgba(220,120,120,.8)"
   }
  ]
 },
 "options": { "responsive": "true" }
}
-->
</canvas>

---

<canvas class="stretch" data-chart="bar">
My first dataset, 65, 59, 80, 81, 56, 55, 40
<!-- This is a comment that will be ignored -->
My second dataset, 28, 48, 40, 19, 86, 27, 90
<!--
{
 "data" : {
  "labels" : ["Enero", "Febrero", "Marzo", "Avril", "Mayo", "Junio", "Julio"],
  "datasets" : [{ "borderColor": "#0f0", "borderDash": ["5","10"] }, { "borderColor": "#0ff" } ]
 }
}
-->
</canvas>

---

<canvas data-chart="radar">
Month, January, February, March, April, May, June, July
My first dataset, 65, 59, 80, 81, 56, 55, 40
My second dataset, 28, 48, 40, 19, 86, 27, 90
</canvas>

---

### Learn By Example
