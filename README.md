# Node groups

## Ico Tree

A node group for generating a low poly ico sphere tree.

| Parameter           | Description                                               |
| ------------------- | --------------------------------------------------------- |
| Geometry            | The geometry on which the ico tree forest is instanced    |
| Trunk Height        | The approximate height of the the tree trunks             |
| Trunk Resolution    | The number of subdivisions the tree trunks have           |
| Trunk Radius        | The widest radius the trunks have at the bottom           |
| Trunk Taper         | How much the trunks taper in towards the top of the tree  |
| Trunk Distortion    | How straight the trunks are                               |
| Trunk Bump          | The variation in thickness along the length of the trunks |
| Trunk Vertex Color  | The vertex color applied to every vertex of the trunk     |
| Trunk Material      | The material that is assigned to the trunk geometry       |
| Canopy Radius       | The approximate radius of the canopy                      |
| Canopy Vertex Color | The vertex color applied to every vertex of the canopy    |
| Canopy Material     | The material that is assigned to the canopy geometry      |
| Seed                | The random generator seed                                 |

## Ico Forest

A node group for creating a randomized tree of low poly ico sphere trees. Use a
vertex group call Tree to indicate on which vertices a tree can be instanced.

| Parameter           | Description                                               |
| ------------------- | --------------------------------------------------------- |
| Geometry            | The geometry on which the ico tree forest is instanced    |
| Trunk Height        | The approximate height of the the tree trunks             |
| Trunk Resolution    | The number of subdivisions the tree trunks have           |
| Trunk Radius        | The widest radius the trunks have at the bottom           |
| Trunk Taper         | How much the trunks taper in towards the top of the tree  |
| Trunk Distortion    | How straight the trunks are                               |
| Trunk Bump          | The variation in thickness along the length of the trunks |
| Trunk Vertex Color  | The vertex color applied to every vertex of the trunk     |
| Trunk Material      | The material that is assigned to the trunk geometry       |
| Canopy Radius       | The approximate radius of the canopy                      |
| Canopy Vertex Color | The vertex color applied to every vertex of the canopy    |
| Canopy Material     | The material that is assigned to the canopy geometry      |
| Seed                | The random generator seed                                 |

# Objects

## Ico Tree

An object with the Ico Tree geometry nodes node group.

## Ico Forest

An object with the Ico Forest geometry nodes node group.