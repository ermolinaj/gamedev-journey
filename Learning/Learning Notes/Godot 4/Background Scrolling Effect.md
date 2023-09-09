You can play with a region_rect position of a [[Sprite]] node.

![[Pasted image 20230909202149.png]]

You would want to limit the region rect position to limit how much its Vector2 values grow out of bound without breaking the scrolling effect (when exceeding image resolution it is setted to Vector2.ZERO again)