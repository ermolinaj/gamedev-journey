Playing around with some dungeon crawler ideas.
Repository: https://github.com/ermolinaj/dungeon-crawler-prototype

---
## 230916
Implemented base map scene and basic player movement
## 230917
Improved player movement using a Raycast2D for detecting collisions with map terrain (in the first implementation it used a signal wich corrected movement next in the next `_process(delta)` frame)

## 230918
Now player has a proper sprite. rotation only applies to the feedback polygon. Some visual improvements.
