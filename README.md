# refcause
Easily track which lines created objects and what variables (and where defined) refer to an object either directly or transitively.

# Idea
```py
# example.py
from refcause import where

foo = 1

bar = foo

where(bar)  # bar->foo from example.py:4
```


