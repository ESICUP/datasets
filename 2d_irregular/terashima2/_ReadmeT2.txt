TERASHIMA2 data set 

Description: 480 Irregular test instances 
Artificially created data set with convex and non-convex polygons.
Procedure described by López-Camacho, 2012.
In each instance name, the number after letter C is the number of non-convex pieces.
Example: Instance TA001C5.txt has 5 non-convex pieces.
(Except in instances TU***C*C*.txt and TX***C*C*.txt, in which the number of 
non-convex pieces may vary).


For each instance we report:
- first line: the number N of pieces;
- second line: the width and height of the rectangular objects where pieces are placed.
- each of next N lines: number of vertices and coordinates x1 y1 x2 y2 x3 y3 ... xN yN.  
  Coordinates are counterclockwise.

Optimum is known and it is given.  
Optimum placing for <INSTANCE>.txt is in file Op<INSTANCE>.txt

For each file Op<INSTANCE>.txt we report:
- first line: the number of objects followed by how many pieces are in each object.
- second line: the width and height of the rectangular objects where pieces are placed.
- each of next N lines: number of vertices and coordinates x1 y1 x2 y2 x3 y3 ... xN yN
  where each piece is placed in the optimal solution.


Reference: 

López-Camacho, E. An Evolutionary Framework for Producing Hyper-heuristics for 
Solving the 2D Irregular Bin Packing Problem PhD Dissertation. 
Tecnológico de Monterrey, 2012.


Some articles that have solved this data set:

López-Camacho, E., Terashima-Marín, H. and Conant-Pablos, S. E. The impact
of the bin packing problem structure in hyper-heuristic performance. In 
GECCO'12: Proceedings of the 14th Annual Conference on Genetic and Evolutionary 
Computation (2012), ACM New York, NY, USA, pp. 1545-1546.
DOI=10.1145/2330784.2331040

López-Camacho, E., Terashima-Marín, H. and Ross, P. A hyper-heuristic for
solving one and two-dimensional bin packing problems. In GECCO '11: Proceedings of
the 13th Annual Conference on Genetic and Evolutionary Computation (2011), Natalio
Krasnogor (Ed.), ACM, New York, NY, USA, pp. 257-258.
DOI=10.1145/2001858.2002003
