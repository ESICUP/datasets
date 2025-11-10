# 3D Irregular

This folder contains a collection of publicly available datasets used in different publications about cutting and packing problems with 3D irregular items (originally hosted at https://gitlab.kuleuven.be/codes/datasets/3d-irregular-data-sets).

Created by Jonas Tollenaere (jonas.tollenaere@kuleuven.be).

### Original publications

| Authors                                                                     | Year | Title & Journal                                                                                                                                         | DOI/Link                                                                     |
|-----------------------------------------------------------------------------|------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Silva, E. F., Çalık, H., Vancroonenburg, W., Leao, A. A. S., & Wauters, T.  | 2021 | Extracting maximal objects from three-dimensional solid materials. Computers & Operations Research, 132, 105290–.                                       | [10.1016/j.cor.2021.105290](https://doi.org/10.1016/j.cor.2021.105290)       | 
| Egeblad, J., & Pisinger, D.                                                 | 2009 | Heuristic approaches for the two-and three-dimensional knapsack packing problem. Computers & Operations Research, 36(4), 1026-1049.                     | [10.1016/j.comgeo.2008.06.003](https://doi.org/10.1016/j.comgeo.2008.06.003) |
| Lamas-Fernandez, C., Bennell, J. A., & Martinez-Sykora, A.                  | 2022 | Voxel-Based Solution Approaches to the Three-Dimensional Irregular Packing Problem. Operations Research.                                                | [10.1287/opre.2022.2260](https://doi.org/10.1287/opre.2022.2260)             |
| Liu, X., Liu, J., Cao, A., & Yao, Z.                                        | 2015 | HAPE3D a new constructive algorithm for the 3D irregular packing problem. Frontiers of Information Technology & Electronic Engineering, 16(5), 380–390. | [10.1631/FITEE.1400421](https://doi.org/10.1631/FITEE.1400421)               |
| Stoyan, Y. G., Gil, M., Pankratov, A., & Scheithauer, G.                    | 2004 | Packing non-convex polytopes into a parallelepiped. Preprint MATH-NM-06-2004: Technische Universität of Dresden.                                        |                                                                              |
| Stoyan, Y. G., Gil, N. I., Scheithauer, G., Pankratov, A., & Magdalina, I.  | 2005 | Packing of convex polytopes into a parallelepiped. Optimization, 54(2), 215–235.                                                                        | [10.1080/02331930500050681](https://doi.org/10.1080/02331930500050681)       |
| Tollenaere, J., Çalık, H., & Wauters, T.                                    | 2024 | Efficient use of collision detection for volume maximization problems. European Journal of Operational Research.                                        | [10.1016/j.ejor.2024.05.048](https://doi.org/10.1016/j.ejor.2024.05.048)     |
| Tollenaere, J., Sykora, T. M., & Wauters, T.                                      | 2025 | Mixed-integer linear programming models for 3D irregular strip packing problems. European Journal of Operational Research.                                              | [10.1016/j.ejor.2025.10.041](https://doi.org/10.1016/j.ejor.2025.10.041)

### Other sources

* Edwards, T. (2014). Classic Chess Set from glChess. https://www.thingiverse.com/thing:322616

* Harrel, E. (2015). Toyota 4 Cylinder Engine 22RE. https://www.thingiverse.com/thing:644933

# JSON format for strip packing instances

Irregular 3D Open Dimension Problems (I3DODP), or 3D irregular strip packing problems (3DISP), instances are stored as JSON files in this repository. 
Each file contains a single instance of the problem. 
They contain the following information:
+ **"name"**: Human-readable identifier
+ **"comment"**: If there is a comment about the instance, it can be added here
+ **"container"**:
    + **"size-x"**: Fixed size of the container, along the x-axis
    + **"size-y"**: Fixed size of the container, along the y-axis
+ **"item-types"**:
    + **"path"**: Path to a .stl or .obj file, defined relative to root folder of this data repository
    + **"demand"**: Number of items of this type to be placed in the container

#### Example

```json
{
  "name": "STOYAN_2005_03_ITEMS",
  "container": {
    "size-x": 8,
    "size-y": 11
  },
  "item-types": [
    {
      "path": "Stoyan et al. 2005/polytope1.obj",
      "demand": 1
    },
    {
      "path": "Stoyan et al. 2005/polytope5.obj",
      "demand": 1
    },
    {
      "path": "Stoyan et al. 2005/polytope7.obj",
      "demand": 1
    }
  ]
}
```

### Contributors

* Jonas Tollenaere
* Sahar Chehrazad
