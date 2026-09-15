# A4 – Motor Mount

## Objective

### Objective & Plan
Our objective is to design a motor mount that attaches to a motor on one side and a rigid wall on the other. We are to design for yield strength based on a material of either ABS, PETG, or PLA. we are also to design for a maximum deflection of 0.30mm at the free end. Our factor of safety is set to 3 and for this we will not consider the weight of the motor. The first step is to draw a FBD of our design with the forces and research some motor mounts for this.

## Analyze

### Feature 1
The first step in the design process was to start with feature 1, I drew a simple picture of the scenario and wrote down some of the information I had. I started feature 1 with a simple block and labeled my dimensions and what I knew about the block. We had several knowns which were more essentially material properties of young's modulus and tensile stress which were dependent on the material that I had not chosen yet. There were quiet a bit of unknowns at this point in the process and I needed to use the beam bending equation to come up with dimensions. From here taking the Inertia of a rectangular cross section I was able to plug it into the beam bending equation and solve for h. The point in solving for h is it is inversely proportional to out tensile stress. I drew a free body diagram of feature 1 to solve for the moment. the first equation was an equation that prioritizes stress in out design but keep in mind that our maximum deflection was 0.3mm so we utilized the formula h= the cube root of 6ML^2/max deflectionEb to prioritize deflection in our design. I went into Fusion and chose the PLA material based on its tensile strength and young's modulus, from there we chose a b dimension of 40mm based on the geometry of the motor and solved for both equations. Our deflection equation was the constraint we had to go by so I went with 10mm after I rounded up from the calculated 4.15mm

<img src="a4-13.png" alt="initial design" width="400">
<img src="a4-14.png" alt="initial design" width="400">
<img src="a4-15.png" alt="initial design" width="400">
<img src="a4-16.png" alt="initial design" width="400">

### Feature 2
With feature 1 done my focus shifted to feature 2 I drew a free body diagram of what the shape should be and solved for the moment similar to feature 1. I knew that for feature 2 I wanted to have the same base dimension of 40mm for a simple transition from feature to feature. Along with that we needed to solve for h using both our stress and deflection equations which were the same as the ones we used from earlier. Plugging in our values our stress equation dictated h to be 5.47mm and our deflection came out to be 5.93mm. So as you can see it is much closer but once again deflection decides the dimension and so I rounded up to 6mm for standardization. 

<img src="a4-17.png" alt="initial design" width="400">
<img src="a4-18.png" alt="initial design" width="400">

## Decide

### Sketch
I then created a Isometric sketch of the motor mount with a few dimensions. In this process I only drew one set of holes for bolts on feature two to give a simple representation of the motor because I knew that drawing the hole features on feature 1 was going to be very in depth and would most likely be more detailed and cleaner on the CAD drawing I was going to create later.

<img src="a4-19.png" alt="initial design" width="400">

### CAD Model (Parametric)
It was now time to create the motor mount in CAD using a parametric approach. I first applied the PLA material to my model and created my parameters in Fusion. Once this was complete I was able to draw a simple sketch of the mount and assign the dimension the variables from my parameters tab. The sketch was finished and the part was extruded to its width.


<img src="a4-8.png" alt="initial design" width="400">
<img src="a4-5.png" alt="initial design" width="400">
<img src="a4-6.png" alt="initial design" width="400">
<img src="a4-7.png" alt="initial design" width="400">

I started on the holed for feature 1 which were four holes evenly spaced on a 22mm diameter circle on the center of feature 1. Each hole is design for an M6 fastener and have a 3.4mm diameter hole all the way through. I decided to recess the motor into the mount so I created a 18mm diameter holes about the center and went down 2mm and created a 0.5mm chamfer on that inside edge to give it a smooth finish. I then went on to feature 2 and placed four of those 3.4mm holes all the way through on the face of feature 2. Those first two holes are placed parallel 10mm from that inside corner of the bracket and 10mm from outside edge to center on each. The second set of holes follow the same criteria as the first set except they are 20mm from the first set center to center.

<img src="a4-12.png" alt="initial design" width="400">
<img src="a4-11.png" alt="initial design" width="400">
<img src="a4-9.png" alt="initial design" width="400">

## Communicate

### Drawing
Below is a picture and downloadable link to a drawing of my motor mount with different views and the required dimension of the part.
<img src="a4-20.png" alt="initial design" width="400">

[Download the Motor Mount Drawing](./a4-1Drawing.pdf)

### Lessons Learned
I thought that a lot of the lessons learned in this assignment were trying to understand different approaches to design and that there isn't necessarily one way or the best way. It depends on many factors. Below I included a picture of the motor with its drawing. I learned that I had to base some decisions on the pre-existing motor and its dimension. I researched two motor mounts as well with their pictures and links below. One is from Walmart and the other was from a different company. I tried to analyze the design of each and determine advantages and disadvantages of each to see what I could use in my design. I really thought about making elongated holes on the design to allow for it to be positioned in different ways but decided not to because I thought this could cause problems if vibrations occurred. I spent approximately 6 hours working on this assignment.

<img src="a4-1.png" alt="initial design" width="400">
<img src="a4-2.png" alt="initial design" width="400">
<img src="a4-3.png" alt="initial design" width="400">
<img src="a4-4.png" alt="initial design" width="400">

### Websites for Mounts

https://www.walmart.com/ip/BERTDOMD-Gear-Motor-Mounting-Bracket-Motor-Mounting-Holder-Stepper-Motor-Mounting-Stand-Motor-Holder-Motor-Rack-Motor-L-Shaped-Bracket/14093907278?wmlspartner=wlpa&selectedSellerId=102708123&selectedOfferId=8792B7A3E359356EA49348191686AEC9&conditionGroupCode=1&veh=seo_fpl&cn=google

https://vxb.com/products/heavy-duty-l-shaped-dc-motor-mounting-bracket-made?s=rec&w=p

### CAD FIle
[Download the Motor Mount](./a4-1.f3d)
