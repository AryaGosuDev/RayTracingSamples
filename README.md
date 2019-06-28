These images are sample images of my multi-threaded CPU ray tracing program. All objects are added using an n-ordered object file then segmented into a binary space partition data structure using auto-partitioning.
Some of the objects include a yellow gourd and a low-poly Buddha statue. The lighting and shading effects of each scene are described in the name of the respective file.

File explanation :

dofeffect -> Depth of field effect where the depth of focus is near the depth of the Buddha statue.

sceneNormalAmbientOccl200Rays2UnitRadius -> Ambient Occlusion shadow effect, can compare it with the shading in the file sceneNormalAmbientOcclOff

sceneNormalAnti-Aliasing -> 4x AA with a reflecting Buddha statue. Note the reflections of the cubes in the Buddha statue. Can compare it the the file sceneNormalNon-AA

sceneRefractingSheet1 and sceneRefractingSheet1 -> Note the reflection of the reflecting glass on the Buddha belly through the glass !

sceneRefractionAntiAliasing and sceneSoftShadows -> Soft shadows with a reflecting sphere and reflecting glass. Note the soft shadows through the glass and sphere.

sceneRoomRadiosity -> A model of a room where the light is shining from outside the room then peering into the window. The light shines partly on the ground and the left wall; thus, the right wall near the window and the ceiling are illuminated more due to the radiosity of the light emitted from the ground. The ground on the right side of the room and part of the right wall does not have much illumination due to the fact that the light needed to light these sections are second and third reflections. The physical qualities that define room are that of gypsum or dry wall. I researched the specific reflectance and emissitivity of gypsum, which is essential to the radiosity solution.

sceneRoomRadiosityOffAmbOcc -> Light peering in the the room and lighting the ground. No radiosity added and slight ambient occlusion shading.

sceneRoomRadiosityColor -> Color + light + radiosity

sceneRoomRadiosityLowAO -> Low AO shading in the room + radiosity.

sceneRoomRadiosityHighAO -> High AO shading + radiosity ( note the reflected light below the window and ceiling)
