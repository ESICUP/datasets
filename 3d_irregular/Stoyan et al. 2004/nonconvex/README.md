### Remark
 
This folder contains the triangle meshes of the non-convex polytopes as a union of convex polytopes, as they were described in Stoyan et al. (2004).

The underlying `sanitized` folder contains sanitized versions of the nonconvex polytopes that are better suited for geometric computations.
Facets that are not located on the surface of the polytopes have been removed, as well as any self intersections.
This allows for correct surface and volume computation, correct ray-triangle intersection tests, and so on. As a side effect, the triangulation of these polytopes might be slightly more complex.