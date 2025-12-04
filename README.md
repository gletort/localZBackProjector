[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![DOI](https://zenodo.org/badge/852884400.svg)](https://doi.org/10.5281/zenodo.16911014)


# localZBackProjector

Retrieves the height map from 2D denoised projected epithelia image.

For images of epithelia that have been projected in 2D (eg with [CARE](https://csbdeep.bioimagecomputing.com/doc/) method), and eventually denoised, modified, retrieves its height map (Z position of the projected pixels) by comparing the projection and the original 3D stack.

Need the 3D original stack and the 2D projected result.
Produce the height map and can reproject it in all/other channels as well. 

![backprojection schema](./imgs/backproj.png)

The retrieved height map can then be used in software like [DeProj ](https://gitlab.pasteur.fr/iah-public/DeProj) to perform 3D analysis, correcting for the projection artifact. 
