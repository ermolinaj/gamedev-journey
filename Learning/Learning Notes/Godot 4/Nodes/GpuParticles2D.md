When creating this node a warning will show:
![[Pasted image 20230906170743.png]]
We need to create a process material.
We can create a new ParticleProcessMaterial from this inspector property:
![[Pasted image 20230906170843.png]]
By modifying the amount property the quantity of particles is modified.

You can change the velocity of emission over the ParticleProcessmaterial
![[Pasted image 20230907160223.png]]
Emission shape can also be modified (by default particles are emitted from a single point)
![[Pasted image 20230907160414.png]]
Particle Size can be modified over the Scale set of properties o nthe inspector.
Scale can be defined as a Curve if you want it to change over the lifetime of the particle:
![[Pasted image 20230907161545.png]]

Something similar can be done with particle colors, setting a color gradient to color particles:
![[Pasted image 20230907161942.png]]
You can click at any point inside the gradient curve to add new colors.
![[Pasted image 20230907162259.png]]

Variable lifetime of particles can be modified the same way over the ParticleProcessMaterial