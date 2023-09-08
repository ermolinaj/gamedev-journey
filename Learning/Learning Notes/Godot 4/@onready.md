If you use the `@onready` annotation you cant call whats defined as var after if the Node who has the script attached isn´t instantiated first.

For example:
![[Pasted image 20230907182428.png]]
If you don´t use the `add_child()`` function first it will