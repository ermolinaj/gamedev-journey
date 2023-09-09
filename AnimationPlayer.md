By double clicking an AnimationPlayer Node the Animation panel opens up.
![[Pasted image 20230908180847.png]]
Animation position canbe changed here:
![[Pasted image 20230908181115.png]]
If another node present in the scene is selected while the animation panel is opened, over the inspector panel keys will appear over the diferent properties. This can be used for key-frame modifications of these properties over the animation timeline:
![[Pasted image 20230908181312.png]]
![[Pasted image 20230908181606.png]]
*in this example the transform property for the Area2D is changed on the 0.5 frame*

Animation length can be changed with this box:
![[Pasted image 20230908181744.png]]

If looping (red) is enabled, the distance (green) between the last defined key and the end of the animation will reset the modified properties so they're the same as in the start of the animation:
![[Pasted image 20230908183626.png]]

Its not advised to modify the root position inanimation.

Interpolation can be changed to generate different effects:
![[Pasted image 20230908183857.png]]

You can also create different tracks with different functionalities, like function calls:
![[Pasted image 20230908185132.png]]