# localZBackProjector

Retrieves the height map from 2D denoised projected epithelia image

For images of epithelia that have been projected in 2D (eg with CARE method), and eventually denoised, modified, retrieves its height map (Z position of the projected pixels) by comparing the projection and the original 3D stack.

Need the 3D original stack and the 2D projected result.
Produce the height map and can reproject it in all/other channels as well. 
