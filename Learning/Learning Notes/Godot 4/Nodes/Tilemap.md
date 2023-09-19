A tileMap node slices an image into tiles to be used inside scenes and displayed in a Grid of tiles.
A TileMap requires a TileSet resource.
When working with these Node two menues appear at the bottom:
![[Pasted image 20230909021203.png]]

TileSet allows you to create a new Atlas. An atlas contains a Texture and allow you to create tiles:
![[Pasted image 20230909021321.png]]

After creted in the atlas you may select a tile and use it to "paint" over the scene:
![[Pasted image 20230909021649.png]]

Multiple tiles may be selected as once:
![[Pasted image 20230909021457.png]]

You can select tiles in a pattern you like, and drag them over the Patterns Tab of the TileMap Menu to create easy reusable paterns made with your tiles:
![[Pasted image 20230909022038.png]]

Over the Select tab
![[Pasted image 20230909023100.png]]
You can select one or multiple tiles and define collision shapes for tiles over the Physics options:
![[Pasted image 20230909023152.png]]
You can select points using the polygon tools:
![[Pasted image 20230909023002.png]]
F key selects the whole square

In order to do this a Physics layer must be defined for the TileSet.

One way collisions can be made by selecting this option:
![[Pasted image 20230909024050.png]]
This must be used in the scene defining the tilemap and cannot be changed from other scene.

## Terrains
You can change the terrain sets inside the TileSet Resource:
![[Pasted image 20230909164436.png]]
You can add new terrain types:
![[Pasted image 20230909164746.png]]
Going to the TileSet editor you can select the Terrains property with a tyle selected:
![[Pasted image 20230909164926.png]]
By default tiles have the TerrainSet property set as -1 by default, which means it doesn't have a terrain assigned:
![[Pasted image 20230909165021.png]]
TerrainSet and Terrain propertys start to cound from zero when a new terrain type is created.

When a terrain is set the Terrains Peering Bit group of properties appear:
![[Pasted image 20230909165159.png]]
These properties are the rules used to draw tiles when using the terrains feature.
-1 means empty space.
For example, this configuration:
![[Pasted image 20230909165350.png]]
Means this tile is going to be used if every other tyle surrander is not an empty space.
To paint using the terrains defined go to the terrains tab, select the terrain and use the paint tool:
![[Pasted image 20230909170413.png]]