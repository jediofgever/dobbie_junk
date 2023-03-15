# Resources

1. Blender
2. [phobos](https://github.com/dfki-ric/phobos), An add-on for Blender allowing to create URDF, SDF and SMURF robot models in a WYSIWYG environment.
3. [AWSIM](https://github.com/tier4/AWSIM), Unity based AV Simulator but we extend it to general purpose Mobile Robot with dobbie.
4. [CityGen3D](https://www.citygen3d.com/), A Unity asset to generate real worl location envoirments, the data is pulled from OpenStreetMap.
5. [URDF-Importer](https://github.com/Unity-Technologies/URDF-Importer), A unity package to import robot defined with a URDF into a functioing UNity GameObject.

# To be aware ofs

1. CityGen3D creates terrain + other objects (buildings, roads, sidewalks, etc.), but [RobotecGPULidar](https://github.com/RobotecAI/RobotecGPULidar), wonts see through the terrain. As a workaround, use terrain -> mesh converter hosted in [this gist](https://gist.github.com/jediofgever/cdc5471bd8faa390fab032719d134ee1). 
