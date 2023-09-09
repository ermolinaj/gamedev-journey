## Working with pixel art
If a texture asset is too small and pixel art you can change its Texture Filtering to `Nearest`
![[Pasted image 20230907190703.png]]

If you don´t want to do this for every individual texture you can go to Projects > Settings > Rendering > Textures and set a default Texture Filter for every texture in your project:
![[Pasted image 20230907191037.png]]
Aside from texture filter if you don´t want to scale every sprite you can set a smaller view port and change the project Stretch Mode like this:
![[Pasted image 20230907191325.png]]
Window size can be overriden like this, by changing the Window W/H Override Settings:
![[Pasted image 20230907191449.png]]

## RegionRects

By enabling the Region>Enable property, Rect properties will show on inspector:
![[Pasted image 20230909195716.png]]
By defining a rect the sprite will render inside the dimension of these properties.
At first it can look like this:
![[Pasted image 20230909195821.png]]
Inside the Inspector > Texture > Repeat property you can enable texture repetition inside the rendering rectangle:
![[Pasted image 20230909200354.png]]
The region rect also allows you to render a smaller version of the same image.