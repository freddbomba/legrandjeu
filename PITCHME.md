first test
---
@title[a wonderful news]
this is a slide delimiter
- and a list bullet
- another

* another
---
# and a new slide
with
```
function logic:init(scene)
  trace("logic:init()")

  -- global RNG
  dofile("rng.lua")
  F_RNG = rng()
  
  dofile("flock.lua")
  dofile("flockScene.lua")

```
