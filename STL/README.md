# Using the STL files

Using the STL/FBX files is a little more tricky but if you're opting for this method then i'm assuming you know what you're doing. If you don't then here's how i do it:

1. Open Blender
2. Create new Blender file
3. Delete camera, light and cube
4. Set units to mm _(the deskmat is 900x400mm)_
5. In the top menubar `File > Import > Import Stl`
6. Select the 2 files from the downloaded directory
7. _(Optional)_ I set the scale to 0.001 initially to get it somewhere near normal on import
8. Once they're both imported select them both and scale correctly
9. _(Optional)_ Select the edging object in the viewport, right click and select "Shade Smooth" to get it all looking clean and tasty

This should now have the desk-mat sitting pretty in the middle of your scene. Add a surface for the desk-mat to sit on, create your materials (follow the same steps in the "[Using the Materials](./Materials/README.md)" section if you don't know), light the scene, add a camera and off you go!
