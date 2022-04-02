# MagicavoxelShaders
<img width="600px" src="https://cdna.artstation.com/p/assets/images/images/047/893/454/large/mrbiggles-ca3-a.jpg?1648693986"/>
<img width="600px" src="https://cdna.artstation.com/p/assets/images/images/042/540/770/large/mrbiggles-planet-clouds-1.jpg?1634773420"/>

# Shaders

In general, the number after the shader indicates a version, and later versions generally do the same things.   However, some of the earlier veresions 
have different features, and so I keep them around 

== Planet

 * planet1.txt - 1st iteration, uses classic perlin noise
 * planet2.txt - 2nd iteration, supports worley noise as well as using a different noise algorithm for octaves.
 * planet3.txt - 3rd iteration, attempted to add a new type of noise (Clover).
 * planet4_clouds.txt - 4th iteration, this one removes alternate noise types and allows 
 selection of the pallette as opposed to defining start and end colors.  It also features a 
 2nd layer of noise, at a different zoom level, which can be used to produce cloud-like patterns.

== Cellular Automata (CA)

CA are rules that apply to cells in a grid.   Unlike most shaders, these are designed to be run over many 
iterations.   As such, you typically set the Shader count and run many iterations of the shader.   

The rules are simple, but you can achieve striking and amazingly complex structures.

 * [ca_totalistic.txt](https://en.wikipedia.org/wiki/Rule_30) - Supports the artist defining their own totalistic CA rules.   This basically means 
 they define the number of neighbors which are required to keep a cell alive or for a new cell to be born.





