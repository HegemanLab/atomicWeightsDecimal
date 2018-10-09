# atomicWeightsDecimal

A Python dictionary of atomic weights in Decimal

Atomic weight measurements are from IUPAC's **Atomic Weights of the Elements: Review 2000** Table 3. IUPAC's measurements includes uncertainity which is not represented here.

## Implementation

Atomic elements without a measurement are not included.

Tab characters are used as whitespace to make regex manipulation simple.

```
{
	"H":	Decimal((0,(1,0,0,7,9,4),-5)),
	"He":	Decimal((0,(4,0,0,2,6,0,2),-6)),
	"Li":	Decimal((0,(6,9,4,1),-3)),
	"Be":	Decimal((0,(9,0,1,2,1,8,2),-6)),
	"B":	Decimal((0,(1,0,8,1,1),-3)),
	"C":	Decimal((0,(1,2,0,1,0,7),-4)),
	"N":	Decimal((0,(1,4,0,0,6,7),-4)),
	"O":	Decimal((0,(1,5,9,9,9,4),-4)),
	"F":	Decimal((0,(1,8,9,9,8,4,0,3,2),-7)),
	"Ne":	Decimal((0,(2,0,1,7,9,7),-5)),
	"Na":	Decimal((0,(2,2,9,8,9,7,7,0),-6)),
	"Mg":	Decimal((0,(2,4,3,0,5,0),-4)),
	"Al":	Decimal((0,(2,6,9,8,1,5,3,8),-6)),
	"Si":	Decimal((0,(2,8,0,8,5,5),-4)),
	"P":	Decimal((0,(3,0,9,7,3,7,6,1),-6)),
	"S":	Decimal((0,(3,2,0,6,5),-3)),
	"Cl":	Decimal((0,(3,5,4,5,3),-3)),
	"Ar":	Decimal((0,(3,9,9,4,8),-3)),
	"K":	Decimal((0,(3,9,0,9,8,3),-4)),
	"Ca":	Decimal((0,(4,0,0,7,8),-3)),
	"Sc":	Decimal((0,(4,4,9,5,5,9,1,0),-6)),
	"Ti":	Decimal((0,(4,7,8,6,7),-3)),
	"V":	Decimal((0,(5,0,9,4,1,5),-4)),
	"Cr":	Decimal((0,(5,1,9,9,6,1),-4)),
	"Mn":	Decimal((0,(5,4,9,3,8,0,4,9),-6)),
	"Fe":	Decimal((0,(5,5,8,4,5),-3)),
	"Co":	Decimal((0,(5,8,9,3,3,2,0,0),-6)),
	"Ni":	Decimal((0,(5,8,6,9,3,4),-4)),
	"Cu":	Decimal((0,(6,3,5,4,6),-3)),
	"Zn":	Decimal((0,(6,5,4,0,9),-3)),
	"Ga":	Decimal((0,(6,9,7,2,3),-3)),
	"Ge":	Decimal((0,(7,2,6,4),-2)),
	"As":	Decimal((0,(7,4,9,2,1,6,0),-5)),
	"Se":	Decimal((0,(7,8,9,6),-2)),
	"Br":	Decimal((0,(7,9,9,0,4),-3)),
	"Kr":	Decimal((0,(8,3,7,9,8),-3)),
	"Rb":	Decimal((0,(8,5,4,6,7,8),-4)),
	"Sr":	Decimal((0,(8,7,6,2),-2)),
	"Y":	Decimal((0,(8,8,9,0,5,8,5),-5)),
	"Zr":	Decimal((0,(9,1,2,2,4),-3)),
	"Nb":	Decimal((0,(9,2,9,0,6,3,8),-5)),
	"Mo":	Decimal((0,(9,5,9,4),-2)),
	"Ru":	Decimal((0,(1,0,1,0,7),-2)),
	"Rh":	Decimal((0,(1,0,2,9,0,5,5,0),-5)),
	"Pd":	Decimal((0,(1,0,6,4,2),-2)),
	"Ag":	Decimal((0,(1,0,7,8,6,8,2),-4)),
	"Cd":	Decimal((0,(1,1,2,4,1,1),-3)),
	"In":	Decimal((0,(1,1,4,8,1,8),-3)),
	"Sn":	Decimal((0,(1,1,8,7,1,0),-3)),
	"Sb":	Decimal((0,(1,2,1,7,6,0),-3)),
	"Te":	Decimal((0,(1,2,7,6,0),-2)),
	"I":	Decimal((0,(1,2,6,9,0,4,4,7),-5)),
	"Xe":	Decimal((0,(1,3,1,2,9,3),-3)),
	"Cs":	Decimal((0,(1,3,2,9,0,5,4,5),-5)),
	"Ba":	Decimal((0,(1,3,7,3,2,7),-3)),
	"La":	Decimal((0,(1,3,8,9,0,5,5),-4)),
	"Ce":	Decimal((0,(1,4,0,1,1,6),-3)),
	"Pr":	Decimal((0,(1,4,0,9,0,7,6,5),-5)),
	"Nd":	Decimal((0,(1,4,4,2,4),-2)),
	"Sm":	Decimal((0,(1,5,0,3,6),-2)),
	"Eu":	Decimal((0,(1,5,1,9,6,4),-3)),
	"Gd":	Decimal((0,(1,5,7,2,5),-2)),
	"Tb":	Decimal((0,(1,5,8,9,2,5,3,4),-5)),
	"Dy":	Decimal((0,(1,6,2,5,0,0),-3)),
	"Ho":	Decimal((0,(1,6,4,9,3,0,3,2),-5)),
	"Er":	Decimal((0,(1,6,7,2,5,9),-3)),
	"Tm":	Decimal((0,(1,6,8,9,3,4,2,1),-5)),
	"Yb":	Decimal((0,(1,7,3,0,4),-2)),
	"Lu":	Decimal((0,(1,7,4,9,6,7),-3)),
	"Hf":	Decimal((0,(1,7,8,4,9),-2)),
	"Ta":	Decimal((0,(1,8,0,9,4,7,9),-4)),
	"W":	Decimal((0,(1,8,3,8,4),-2)),
	"Re":	Decimal((0,(1,8,6,2,0,7),-3)),
	"Os":	Decimal((0,(1,9,0,2,3),-2)),
	"Ir":	Decimal((0,(1,9,2,2,1,7),-3)),
	"Pt":	Decimal((0,(1,9,5,0,7,8),-3)),
	"Au":	Decimal((0,(1,9,6,9,6,6,5,5),-5)),
	"Hg":	Decimal((0,(2,0,0,5,9),-2)),
	"Tl":	Decimal((0,(2,0,4,3,8,3,3),-4)),
	"Pb":	Decimal((0,(2,0,7,2),-1)),
	"Bi":	Decimal((0,(2,0,8,9,8,0,3,8),-5)),
	"Th":	Decimal((0,(2,3,2,0,3,8,1),-4)),
	"Pa":	Decimal((0,(2,3,1,0,3,5,8,8),-5)),
	"U":	Decimal((0,(2,3,8,0,2,8,9,1),-5))
}
```
