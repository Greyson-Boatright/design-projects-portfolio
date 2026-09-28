# A6 – Bracket Drawing

## Objective

### Objectives & Requirements
In this assignment I need to create a model and multi-view engineering drawing of the bracket I designed previously. In this model and drawing I need to ensure that it meets the previously calculated strength and stiffness requirements. This will allow me to combine skills I have learned from previous topics such as parametric modeling and engineering drawings to communicate technical information and conduct further analysis of the designed bracket.

## Analyze

### Parametric Design
For the parametric design of the T-beam bracket, I designed each feature with dimensions I calculated in A5 and I went through features sequentially in Fusion. I started by assigning Steel ASTM A36 to the model and for each feature I inputted the correct dimension to the variables, after assigning the variables I created a sketch of the features and extruded them all while assigning the variables to the dimensions. When creating my user defined functions it was more difficult to write an equation for my dimensions because in A5 a lot of my dimensions were rounded up from the calculated requirement. However because I assigned variables to all the dimensions it allows me to very easily change the whole models or a specific feature without having to redraw and extrude a feature. I was able to incorporate some formulas into the parametric design.
<img src="a6-1.png" alt="initial design" width="400">
<img src="a6-2.png" alt="initial design" width="400">
<img src="a6-3.png" alt="initial design" width="400">
<img src="a6-4.png" alt="initial design" width="400">
<img src="a6-19.png" alt="initial design" width="400">
<img src="a6-20.png" alt="initial design" width="400">
<img src="a6-6.png" alt="initial design" width="400">
<img src="a6-21.png" alt="initial design" width="400">
<img src="a6-8.png" alt="initial design" width="400">
<img src="a6-9.png" alt="initial design" width="400">
<img src="a6-10.png" alt="initial design" width="400">
<img src="a6-11.png" alt="initial design" width="400">
<img src="a6-12.png" alt="initial design" width="400">
<img src="a6-13.png" alt="initial design" width="400">
<img src="a6-14.png" alt="initial design" width="400">
<img src="a6-15.png" alt="initial design" width="400">
<img src="a6-16.png" alt="initial design" width="400">
<img src="a6-17.png" alt="initial design" width="400">


## Decide

### Drawing
I generated a drawing of the bracket in Fusion using third angle projection, I assigned dimensions that were essential to the model and I referenced the machinerys handbook to give tolerances to the most important fits of the drawing. I did not have the college of engineering templete for drawings in fusion so I tried to model my blocks similar to it and included the tolerance block.
<img src="a6-18.png" alt="initial design" width="400">

## Communicate

### Reflections
One equation I used in my design was the "h" dimension for feature B, through my analysis I was able to figure out that the strength equations was the governing equation in dimensions. In fusion I set some baseline variables like the force and allowable stress. My equation for the "h" dimension of feature b was h=ceil(( P / ( b_B * stress ) ) / 0.0625 in) * 0.0625 in. As you can see I have the normal equation for the dimension according to our stress but I knew I wanted to round up so using the ceil function I was able to round up from the minimum value to the next 16th of an inch. On dimension "d" of feature d I gave it a dimension of 1.5 plus 0.006 minus 0.000 on the tolerance, this dimension has a very tight tolerance because that is essentially the dimension c on the beam itself. the tolerance is so tight because we need to have an sliding fit (RC-2) between the beam and bracket. This is a very critical feature because if the dimension is too small it will not be able to fit on the beam. if it is just big enough to fit but exactly the size of the beam it will not be able to slide and if it is too big there could be issues of it not sliding effectively or even coming off. The diameter of feature A I gave a dimension of 0.81 plus/minus 10 thousands. this is not a very tight tolerance at all due to the fact it is a non-critical feature. the value is already rounded up a small amount from the required minimum value to withstand the force and plus/minus 10 thousands will not change the strength, deflection, or fit.

### Lessons Learned

### 2157 Students only: Drawings
#### Parametric Design
#### Drawing
#### Reflection


picture format

<img src="a5-14.png" alt="initial design" width="400">

cad format

### CAD File
[Download the Fusion Bar](./a3-1.f3d)
