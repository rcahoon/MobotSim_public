This is a simulation environment that is designed for developing robot software
for Carnegie Mellon University's [Mobot challenge](http://www.cs.cmu.edu/mobot/)

It is built on top of the [Unity game engine](https://unity.com/). Download and
install Unity, clone this repo, and then open this project in Unity.

Currently, it produces a
[Motion PNG stream](https://github.com/rcahoon/Mobot/tree/master/http_stream)
with the images from the simulated robot camera. This stream can be viewed by
running the simulator in Unity and then opening `test_stream.html` in a web
browser like Chome or Firefox (other browsers may not support Motion PNG). Once
the simulation is running, the robot camera can be moved around by selecting
`Robot Camera` in the scene hierarchy and then changing its position/rotation.
You should see the images in the stream updating to match this movement.

Upcoming work will be to add a simulation of the robot's drive system and
inertial sensors.

Note: This public version of the repo doesn't include nice textures for the
grass and concrete because of licensing requirements for the assets purchased
in the Unity Asset Store. The private version of this repo uses "Grass 8" from
[True PBR Materials: Grass](https://assetstore.unity.com/packages/2d/textures-materials/nature/true-pbr-materials-grass-154894)
and "Concrete Floor" from
[Procedural Materials Vol 4](https://assetstore.unity.com/packages/vfx/shaders/substances/procedural-materials-vol-4-173812)
