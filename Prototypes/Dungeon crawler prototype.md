Playing around with some dungeon crawler ideas.
Repository: https://github.com/ermolinaj/dungeon-crawler-prototype

---
## 230916
Implemented base map scene and basic player movement
## 230917
Improved player movement using a Raycast2D for detecting collisions with map terrain (in the first implementation it used a signal wich corrected movement next in the next `_process(delta)` frame)
## 230918
Now player has a proper sprite. rotation only applies to the feedback polygon. Some visual improvements.
## 230919
Started working on proyectiles and proyectile emiters for dungeons as a first obstacle.
Emiters emit proyectiles at a set time. Proyectiles move in the setted direction over the node exported property.

## 230922
Fire projectiles behaviour implemented:
	- dissapears when out of bounds
	- collides and hurts player
Hp system
	- Player has hp
	- PLayer gets hurt by fire projectiles
Basic HP HUD
	- Hearts represents player's health
	- hearts are setup on ready taking information from player node
	- hearth contaiiner system where max hp is represented by containers and smaller hearts inside those containers represent current health

## 230924
Skill shield implemented.
	- Activating the shield with W makes the player invulnerable to projectiles
	![[Pasted image 20230924203635.png]]
	- basic UI for skills implemented
	 ![[Pasted image 20230924203643.png]]

## Next Steps
- Visual feedback in skillbar
- refactor (Player and Dungeon level scripts are growing out of control)