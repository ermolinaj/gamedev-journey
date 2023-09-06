Message a Node emits when something happens.

Available signals for a specific node can be seen on the Node tab, next to the Inspector tab:
![[Pasted image 20230904032134.png]]

Signals need to be connected in order to be used. Selecting a signal from the Node tab enables the Connect button:
![[Pasted image 20230904032344.png]]
The Node you connect to has to have a script. Godot will generate a function inside the script.
![[Pasted image 20230904032437.png]]

The function created this way will show you this icon:
![[Pasted image 20230904032603.png]]

Clicking the icon will show you the connection detail:
![[Pasted image 20230904032625.png]]

To stop the signal from calling the assigned method on connection you can use the disconnect button:
![[Pasted image 20230904040125.png]]

## Connect()
Connect method is available for every node and can be used to reference a signal and connect it by script, without using the inspector.
![[Pasted image 20230905160152.png]]
