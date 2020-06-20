# Similarity-Dissimilairty-Analysis

Similarity-dissimilarity analysis
---------------------------------
---------------------------------
Python packages required for running reeb_graph python code:
1. sys
2. collections
3. numpy
4. os
5. matplotlib
6. sklearn
7. scipy
8. mpl_toolkits
9. math

Most of the libraries would be pre-installed in anaconda 3.6 
If libraries aren't found, run the following command in anaconda terminal: conda install name_of the_package
or pip install name_of the_package
---------------------------------------------------------------------------------------------------------------------

Parameter values and ranges to be entered for a feasible graph extraction:
lambda - float value in the range(0,1); parameter in calculating the mixed distance (defining the encompassing
ellipsoid volume curvature for node extraction). For a geometry with one overall dimension larger than others, use
lesser value of lambda

R - integer value in the range [5,200]; resulotion parameter (more the value of R, more number of graph node points
are extracted in general)

tau - float value in the range [10^-5, 10^-1]; distance parameter to say if two point clouds are connected or not
(lesser the value of tau, lesser the number of edges in the graph)

d_thresh - float value in (0,1) range; fraction which is to be specified. Used for plotting the regions of difference greater than the (d_thresh * maximum_difference)

*Note - the feasible graph extraction depends on the combination of the three parameters and have to be tuned for a 
geometry 
-- In the case when there is a graph with just 1 or 0 nodes, the code will abort and the user should re-run the code 
with a different combination of parameter values.
-- For a visual of the effect of the parameter variation on the graph extraction, refer the parameter description 
tabs in the GUI
---------------------------------------------------------------------------------------------------------------------

---------------------------------------------------------------------------------------------------------------------

Steps for making an .obj file from .iges file
1. In the "Files" tab, "Upload" the .iges file in Autodesk Fusion360 software 
2. In the "Files" tab, "Export" the file as a .obj file

Note: Other 3D softwares can be used to convert the file format to .obj
Various online converters can also be used

----------------------------------------------------end--------------------------------------------------------------



    


 
