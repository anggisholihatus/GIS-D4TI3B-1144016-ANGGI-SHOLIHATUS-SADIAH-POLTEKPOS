Background

Geospatial is crucial in learning geography. Because in learning geography always give priority to understanding spatial because that is one characteristic compared to other lessons. More Partoso Hadi also explained as a reference to the main curriculum, in learning, its implementation needs to be attempted in accordance with the rules and the essence of geography Science itself.

Geospatial information is an increasingly important role in development, but there are still many problems that appeared due to the existence of legislation which has not been specifically set about geospatial information. Geospatial is crucial in learning geography. Because in learning geography always give priority to understanding spatial because that is one characteristic compared to other lessons. More Partoso Hadi also explained as a reference to the main curriculum, in learning, its implementation needs to be attempted in accordance with the rules and the essence of geography Science itself.

There are three sources of data that can be retrieved from geospatial information systems, including:
1. Data field (Teristis), namely data obtained directly (primary data) of the observations in/pengukuran airy.
2. Map Data i.e. data in the form of information that is printed on the map/film.
3. Remote Sensing Data

Discussion


Spatial data (keruangan data) is data in the form of a graphic that shows the location of spaces or places on the Earth's surface. Spatial data represented by points, lines, and polygons.

Attribute data is the data that give explanations or descriptions of any object on the surface of the Earth. Attribute data serves to describe the symptoms of the topography as it has a descriptive and qualitative aspects.

Data are facts about objects, events, and activities stated by value (angaka, characteristics, symbols). These kinds of GIS data is spatial data and attribute data. examples of spatial data, among others, the location of an area, the position of the source of petroleum, etc. Forms of spatial data: dot (dot), example: the position of the terminal; line (poly line), for example: a network of highways; and in area (polygon), example: subdistrict. Examples of attribute data such as population density, soil type, etc. Forms adalahdata quantitative attribute data (numbers/statistics), for example: the number of inhabitants and the qualitative data (quality/quality), for example: a level soil fertility.

Create Geospatial Data
Import shapefile
The input variable, suppose that variable a to shapefile. writer ()
a = shapefile. writer ()
So, the format make geospatial data is no 2, namely:
. shp = > a. point (x, y)
a. poly [(x, y), (v, w)]
. dbf = > a. field (' name. field ', ' c ', ' 40 ')
a. record (' bdg ')
Geospatial data are stored using method a. save (' URfile.shp ').
The meaning of the method on the writer:
Point (x, y): entering data into paint shaped. shp and all data must be formatted ESRI. 1
Poly [(a, b), (c, d)]: entering a polygon-shaped geospatial data (back to the starting point) or polyline (ketitik does not return).
Field (' name ', ' c ', ' 40 '): it means to create a polygon attribute table with ' name ' with the data type varchar with a length of 40. This method can be repeated and can be done for krbuthan new field again.
Record (' Bandung '): fill in the table which is only one field with value ' Bandung '.
Save (' name. '): saves the file with the save file.

1. Point (zero-dimensional point)
The point is a graphical representation or the simplest geometry for spatial objects. This representation does not have dimensions, but can be identified at the top of the map and can be displayed on the monitor screen by using certain symbols. It should be understood that the scale of the map will determine whether an object will be displayed as a point or polygon. On a large scale map, building elements will be shown as a polygon, while on a small scale will appear as elements of a point.
Format: single coordinate point, without long, without extents.
Example: the location of the accident, the location of the tree

2. Line (one dimension – line or polyline)
The line is the linear geometric shapes that will connect at least two points and are used to represent the objects that one dimensional. The boundaries of the polygon Geometry object is also the lines, as well as electricity networks, communication networks, drinking water pipes, exhaust duct, and other utility can be represented as an object with geometric lines. This will depend on the scale of the map be the source or a scale representation of the end.

Format: the coordinates of the starting and ending point, had long without extents.
Examples: roads, rivers, utility

3. Polygon (two-dimensional – area)
Geometry polygon is used to represent two dimensional objects. Unsurunsur spatial as the provincial boundaries, lakes, boundaries
