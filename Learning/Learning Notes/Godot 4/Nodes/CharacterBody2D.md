CharacterBody has a  `velocity` property.
When using the `move_and_slide()` method it will use this velocity property.

## is_on_floor()
Returns true if the body collided with the floor on the last call of `move_and_slide()`. Otherwise, returns false. The up_direction and floor_max_angle are used to determine whether a surface is "floor" or not.