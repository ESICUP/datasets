There are currently 2 data files.

These data files are the test problems used in the paper:
"Placing boxes on shelves: a case study" by N.P. Hoare and J.E. Beasley
Journal of the Operational Research Society, vol.52, no.6, 2001, 
pp605-614.

These test problems have a common products file. 
This file is products and the format of this file is:
For each product in turn:
   product family, quantity to be shelved, length, width, height
All orientations of each product are allowed and no product is allowed 
to overhang a shelf.
The two test problems have different bay files. 
These files are baytp1 and baytp2 and the format of these files is:
For each bay in turn:
   width, height, depth, available height
Bays must be shelved/used in same sequence as given in each file.
Each bay can have a number of possible shelves.
These are given in the file shelves
The format of this file is:
For each shelf in turn:
    shelf number, thickness, position, top gap, left gap, inter gap, right gap
The position given is the height of the top flat surface of the shelf (on which boxes stand).
Top gap for shelf i is the gap that must exist below the shelf (i.e. the gap between shelf i and
boxes placed on the shelf below shelf i. For example if a shelf has a position of 1700, 
a top gap of 15 and a thickness of 40 then the boxes on the shelf below must not intrude 
into the space between 1700-40-15 (=1645) and 1700.
The largest file is products of size 110Kb (approximately)
The entire set of files is of size 130Kb (approximately).