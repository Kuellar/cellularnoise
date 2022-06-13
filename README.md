# Cellular Noise Playground

## Cellular Noise

In 1996, sixteen years after Perlin's original Noise and five years before his Simplex Noise, Steven Worley wrote a paper called “A Cellular Texture Basis Function”. In it, he describes a procedural texturing technique now extensively used by the graphics community.

To understand the principles behind it we need to start thinking in terms of iterations. Probably you know what that means: yes, start using for loops. There is only one catch with for loops in GLSL: the number we are checking against must be a constant (const). So, no dynamic loops - the number of iterations must be fixed.
