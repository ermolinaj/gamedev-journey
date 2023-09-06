IF you define a Camera2D as a child an its Enabled property is true it will follow its parent node.
![[Pasted image 20230904024238.png]]

You can play with Zoom property to play with the viewport size:
![[Pasted image 20230904024413.png]]

Smooth scrolling activates the position speed property which, for example, can be used for certain player control schemas in which you want the camera to use this smooth effect when the node speed varies:
![[Pasted image 20230904024633.png]]

Drag effect is used  when you dont want the camera to move inmediatly if the parent position changes.
![[Pasted image 20230904025130.png]]
It can be used with position smoothing to create a better effect.
