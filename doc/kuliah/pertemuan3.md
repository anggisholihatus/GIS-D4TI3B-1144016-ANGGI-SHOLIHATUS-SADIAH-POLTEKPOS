SHP is one file that resides in the shapefile that store geometry data.
In shp file contained some data such as:

1. Bbox is a boundary box (coordinates of four points) or view the existing boundary coordinates on the map.
2. Point is the point of a coordinate
3. Shapetype is geometric data types that have a standard number assigned by ESRI as number 1 for points, 2 for polygons, 3 to polyline, etc.
Examples exist on the link: shapefile.esri

DBF is a file that stores tabular files that store data attributes.

The amount of data read geometry with python:
- Reading data shp
>> Import shapefile
>> Sf = shapefile.Reader ( "namafile.shp")
>> Sf.shapes ()
>> A = sf.shapes ()
>> Len (a)

- Reading data DBF
>> Import shapefile
>> Sf.records ()
>> Sf.records (n)


To see the number of shapefile can use python programming language, because using python programming language allows us and also quite simple to use.


Python
A programming language that is easy dipahamin and has a structure of data efficiently. And this python we can apply to penentua number shapefile.
At Shapefile there are two types of techniques that we use in deciding the layout, the reader and shapes. Reader to read the files that we have made and the output data from the file, for example in the data file "negara.shp". and shapes untun read data on the number of files that the amount of existing data as the data 254 shp.
And this process can be done at a command prompt that of the windows.

Conclusion: knowing how to calculate the number of records using ESRI shapefile with python programming language through the terminal.
Suggestion: More to learn about geographic information systems again and practicum using python.
