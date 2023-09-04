A scene is a Tree of Nodes.
Scenes can be seen as blueprints.

## Instance
Instanced scenes can be recognized on the Scene tree by this Icon
![[Pasted image 20230902194329.png]]

Changing a property from an instanced scene doesn´t modify its original scene it came from.
If a change is made in the scene the node is instanced from and the node has changes in the current scene that property is not going to be affected.

If you want to modify a node´s instantiated from a scene children you can do so by right clicking the node and selecting this option:
![[Pasted image 20230902194940.png]]
Changes made to editable children nodes are undone if the option is toggled again.
## Local Monitoring 
When a game is running you can monitor scene current nodes and their properties in the Local tab:
![[Pasted image 20230902194217.png]]

## Draw Order
Nodes Above nodes will be displayed behind those nodes:
![[Pasted image 20230903023641.png]]

The Z Index can be changed inside Node2D nodes in order to change this behaviour.