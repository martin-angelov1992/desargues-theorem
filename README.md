# Desargues-theorem
A 3d demonstration of Desargues theorem written in Elica Logo
-------------------------------------------------------------
Elica is a not very popular language written on top of openGL best suitable for geometrical/physical demonstrations. Other project I've seen written in this language is a small game.

Desargues theorem is a theorem about triangles in 2d and 3d space and you can read more about it here: http://en.wikipedia.org/wiki/Desargues%27_theorem

This is a small project I made for one of my courses in university. The program allows the user to enter the coordinates of the vertexes of 2 triangles and then the program visualizes those triangles and if they are [perspective](http://en.wikipedia.org/wiki/Desargues'_theorem), the program shows:
 - axis of perspectivity - in light blue
 - center of perspectivity - in a dashed purple line
If you want to have irrational numbers for the coordinates of the vertexes of the triangles, you will have to compute the floating point representation of those numbers via a calculator for example. The geometry related stuff in the program are located in [GeometryLib.ELI](https://github.com/martin-angelov1992/desargues-theorem/blob/master/GeometryLib.ELI)
