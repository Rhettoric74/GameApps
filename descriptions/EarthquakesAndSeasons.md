This visualization tool is my extension of the assignment 
**Earthquake Visualization** designed by Professor Evan Suma Rosenberg.

This app gives the user a view of the when, where, and how destructively different earthquakes 
have occured since the year 1900. Against a backdrop of outer space, the user can choose to view 
the earth as either a flat map, or as a spherical globe, and watch as the map of the world morphs
between those two geometries. As the calendar progresses, showing different points in history, the
earthquakes which occured at the current time are displayed at their respective locations on the map.
Each earthquake is represented as a sphere, whose radius is proportional to the magnitude of the
earthquake (on the richter scale), and whose color is greener for earthquakes of lower magnitude, and
redder for earthquakes of higher magnitude.

The map of the earth also changes with each passing month, to animate how seasons change over time.
All of these maps were obtained through [NASA Visible Earth](https://visibleearth.nasa.gov/collection/1484/blue-marble?page=1).
This gives the user a view of how snow cover and greenery change in different regions of the world over time.
However, these maps only represent monthly changes, rather than year to year changes, so they do not capture
how seasonal patterns may have been different in previous decades due to climate change.

This assignment was meant to illustrate the basics of 3-D meshes and texture mapping. The user
can also switch between `textured` mode, which displays the map of the earth, `wireframe` mode, which 
displays the triangles that make up the mesh, and `vertices` mode, which displays the points in space that
make up the mesh. The user can also change the resolution of this mesh, allowing them to view more accurate
or less accurate spheres to render the globe.