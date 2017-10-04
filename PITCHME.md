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
![Logo](pres-assets/logo.jpg)
this is sketch of the first logo idea for legrandjeu
to demonstrate the handling of images
+++
and what follows is an inline image call
and the logo as it is now..
![Logo](http://legrandjeu.net/wp-content/uploads/2017/06/cropped-loghino-sito-le-grand-jeu-10-2.png)
pretty minimal
