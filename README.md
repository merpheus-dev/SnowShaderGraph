# Simple Snow Shader with Unity Shader Graph
Snow deformation shader with shadergraph URP/HDRP

Uses a dedicated camera with runtime generated render texture to store trail as a splatmap.
Then applies it to vertices and blurs deformation with neighbours.

## Snow Trails
![snow trails](https://i.imgur.com/PWGoCB1.png)
## Vertex Deformation
![Wireframe](https://i.imgur.com/2yJEWS5.png)

**Note: Snow ground plane needs to be pre-subdivided by a 3d program or tessellated via another shader since shader graph has no tess shader support yet.**
