There are 9 data files.

All of these files were contributed by M.S.W. Ratcliff (mspmax@swansea.ac.uk)

(i) Files thpack1,thpack2,...,thpack7

These files were generated and used in:

[1]  E.E. Bischoff and M.S.W. Ratcliff, "Issues in the development of 
     Approaches to Container Loading", OMEGA, vol.23, no.4, (1995) pp 377-390.

The procedure used to create these test problems is presented in the above 
paper.

These problems are single container loading problems, the objective being to 
maximise the volume utilisation of the container.

The format of these data files is:
Number of test problems (P)
For each problem p (p=1,...,P) the data has the format
shown in the following example:

     Example:

 60 2508405    the problem number p, seed number used in [1]
 587 233 220   container length, width, height
 10            number of box types n
 1  78 1 72 1 58 1 14
 2  107 1 57 1 57 1 11      where there is one line for each box type
 3 ...................
 etc for n lines
The line for each box type contains 8 numbers:                         
box type i, box length, 0/1 indicator
box width, 0/1 indicator
box height, 0/1 indicator
number of boxes of type i

After each box dimension the 0/1 indicates whether placement in the 
vertical orientation is permissible (=1) or not (=0).


(ii)  File thpack8

This data was originally used in:

[2]  H.T. Loh & A.Y.C. Nee, 1992, A packing algorithm for hexahedral 
     boxes, Proc. Industrial Automation 92 Conf. Singapore, 115-126

and then in

[3]  B.K.A. Ngoi, M.L. Tay & E.S. Chua, 1994, Applying spatial 
     representation techniques to the container packing problem, Int. J. 
     Prod. Res., Vol. 32, No. 1, 111-123

and then in [1]

These problems are single container problems, the objective being to 
maximise the volume utilisation of the container.

These problems have the same format as above except that there is
no seed number.


(iii) File thpack9

This data was originally used in:

[4]  N. Ivancic, K. Mathur & B.B. Mohanty, 1989, An integer-programming 
     based heuristic approach to the three-dimensional packing problem, J. of 
     Manuf & Ops. Man., vol. 2, 268-298

and then in [1]

These problems involve multiple containers, the objective being to
minimise the number of containers required to ship the entire consignment.

The format for this file is identical to that of thpack8

The largest file is thpack7 of size 50Kb (approximately).
The entire set of files is of size 200Kb (approximately).