DESCRIPTION:
Test problems used in M.T. Alonso, R. Alvarez-Valdes, M. Iori, F. Parreño, Mathematical models for Multi Container Loading Problems with practical constraints, Computers & Industrial Engineering, Volume 127, 2019, Pages 722-733, https://doi.org/10.1016/j.cie.2018.11.012
The problem deals with a number of layers demanded for a specific day. 
The layers have to be stacked in pallets and the pallets are loaded into trucks according to the day demanded.
These instances have been provided courtesy by ORTEC.

STRUCTURE:
1. Line 1: 
	#products
	Amount of types of products
2. Line 2:
	Identifier of the product.
        Delivery day (0,1,2), in a horizontal planning the products can arrive the day 0, or 1 or 2.
        Demand, quantity of product demanded.
	Width dimension in milimetres.
	Length dimension in milimetres.
	Heigh dimension in milimetres.
	Weigth in kilograms.
	Rotation in X, 1 if It can be rotated, 0 if not.
	Rotation in Y.
	Rotation in Z.
	Identifier of stacking group, this products can be stacked with products of the same or minor identifier of stacking group.
	Always on top, 1 if the products must be allocated always on the top of a stack, 0 otherwise.
	Always on bottom, 1 if the products must be allocated always on the bottom of a stack, 0 otherwise.
	Identifier of the layer, layer composition of the product.
3. Line 3:
	#layers
	amount of types of layers
4. Line 4:
	Identifier of the layer.
	Width dimension in milimetres.
	Length dimension in milimetres
	Height dimension in milimetres
	Weigth in kilograms.
	Rotation in Z, 1 if the layer can be rotated in Z.
	Items per layers, amount of products that form a layer.
	Maximum number of layers of this type that can be stacked in a pile.
5 Line 5:
	#pallets
	Amount of types of pallets.
6. Line 6:
	Identifier of the type of pallet.
	Width of the pallet in milimetres.
	Length of the pallet in milimetres.
	Heigh of the pallet in milimetres.
	Weight of the pallet in kilograms.
7. Line 7:
	#trucks
	Amount of types of trucks.
8. Line 8:
	Identifier of type of truck.
	Width of the truck in milimetres.
	Length of the truck in milimetres.
	Heigh of the truck in milimetres.
	Maximum weight can bear in kilograms.
	distance from cabin until axle 1 in milimetres.
	Distance from cabin until axle 2 in milimetres.
	Maximum weight can bear first axle in kilograms.
	Maximum weight can bear second axle in kilograms.
