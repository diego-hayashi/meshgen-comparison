# Mesh Generator Comparison

This repository creates meshes of the same domains with multiple mesh generators and
compares the results. The used mesh generators are

  * [Gmsh](https://gmsh.info/) (via [pygmsh](https://github.com/nschloe/pygmsh)),
  * [CGAL](https://www.cgal.org/) (via [pygalmesh](https://github.com/nschloe/pygalmesh)),
  * [MeshPy](https://github.com/inducer/meshpy),
  * [dmsh](https://github.com/nschloe/dmsh),
  * [meshzoo](https://github.com/nschloe/meshzoo), and
  * [SeismicMesh](https://github.com/krober10nd/SeismicMesh).

For each domain and mesh generator (if applicable), the repostory shows the following
data:
   * the mesh generation time
   * the average and minimum cell quality
   * the nummber of CG iterations for the FEM-Poisson-problem on the mesh.

If you'd like to see other mesh generators, domains, or quality measures: Let me know!

### Disk

<img src="figs/disk-mesh.png" width="50%"> | ![alt text](figs/disk-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/disk-quality.svg) | ![alt text](figs/disk-poisson.svg)


### L-shape

<img src="figs/l-shape-mesh.png" width="50%"> | ![alt text](figs/l_shape-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/l_shape-quality.svg) | ![alt text](figs/l_shape-poisson.svg)


### Rectangle with refinement

<img src="figs/rect-with-refinement-mesh.png" width="50%"> | ![alt text](figs/rect_with_refinement-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/rect_with_refinement-quality.svg) | ![alt text](figs/rect_with_refinement-poisson.svg)


### Quarter annulus

<img src="figs/quarter-annulus-mesh.png" width="50%"> | ![alt text](figs/quarter_annulus-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/quarter_annulus-quality.svg) | ![alt text](figs/quarter_annulus-poisson.svg)


### Sphere (surface)

<img src="figs/sphere-mesh.png" width="50%"> | ![alt text](figs/sphere-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/sphere-quality.svg) | (Poisson problem not applicable.)


### Ball

<img src="figs/ball-mesh.png" width="50%"> | ![alt text](figs/ball-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/ball-quality.svg) | ![alt text](figs/ball-poisson.svg)

### Cylinder

<img src="figs/cylinder-mesh.png" width="50%"> | ![alt text](figs/cylinder-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/cylinder-quality.svg) | ![alt text](figs/cylinder-poisson.svg)

### L-shape in 3D

<img src="figs/l-shape-3d-mesh.png" width="50%"> | ![alt text](figs/l_shape_3d-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/l_shape_3d-quality.svg) | ![alt text](figs/l_shape_3d-poisson.svg)

### Box with refinement

<img src="figs/box-with-refinement-mesh.png" width="50%"> | ![alt text](figs/box_with_refinement-times.svg) |
:-------------:|:-----------------:|
| ![alt text](figs/box_with_refinement-quality.svg?raw=true) | ![alt text](figs/box_with_refinement-poisson.svg)

### License
This software is published under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.en.html).
