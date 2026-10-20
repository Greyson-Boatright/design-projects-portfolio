# A7 – FEA on Bracket

## Objective
The objective of this assignment is to use finite element analysis on the bracket we made previously to improve the designs strength, stiffness, and weigh ratio to those. In that we will record that data we get from each design improvement and compare it to the last through a percentage. I will use the same material from assignments 5 and 6 with that being A36 steel and I will not make any initial changes to the design of the bracket, once I am done analyzing the bracket I will do the same set of steps on the link I created as well.

## Analyze
For this assignment we are going for a safety factor of 4, on both the bracket and link I will fully constrain one part of the part while applying the same 500lb force I had previously chosen for my calculations.

<img src="a7-3.png" alt="initial design" width="350"> 
<img src="a7-4.png" alt="initial design" width="350"> 

## Decide
Each set of FEA will generally follow the same process, they will have the same constraints and loads as seen below. I will make adjustments with parameters. The first analysis will be with the mesh setting at 10%, the second analysis will be at about 7% and right at the end we will do a fine mesh analysis at about 2% to check our convergence.
<img src="a7-1.png" alt="initial design" width="350"> 
<img src="a7-2.png" alt="initial design" width="350"> 
<img src="a7-5.png" alt="initial design" width="350"> 

## Communicate

### Initial design

<img src="a7-6.png" alt="initial design" width="350"> 
<img src="a7-7.png" alt="initial design" width="350"> 
<img src="a7-8.png" alt="initial design" width="350"> 
<img src="a7-10.png" alt="initial design" width="350"> 
<img src="a7-11.png" alt="initial design" width="350"> 
<img src="a7-12.png" alt="initial design" width="350"> 
<img src="a7-55.png" alt="initial design" width="350"> 

The initial design shocked me, my safety factor was well below where I thought it was going to be, the weight and deflection was okay and the max stress was very high. I thought that maybe the load or constraints were applied incorrectly or that I probably just made an error in my calculations. The later is what I presumed in this case. I considered going back and redoing the math and change my dimensions but I decided not to and make the best with what I had and see if adding supports in some areas would help me achieve my goals.

### Adding supports

<img src="a7-19.png" alt="initial design" width="350"> 
<img src="a7-13.png" alt="initial design" width="350"> 
<img src="a7-14.png" alt="initial design" width="350"> 
<img src="a7-15.png" alt="initial design" width="350"> 
<img src="a7-16.png" alt="initial design" width="350"> 
<img src="a7-17.png" alt="initial design" width="350"> 
<img src="a7-18.png" alt="initial design" width="350">
<img src="a7-20.png" alt="initial design" width="350"> 
<img src="a7-21.png" alt="initial design" width="350"> 
<img src="a7-22.png" alt="initial design" width="350"> 
<img src="a7-23.png" alt="initial design" width="350"> 
<img src="a7-24.png" alt="initial design" width="350"> 
<img src="a7-25.png" alt="initial design" width="350"> 
<img src="a7-26.png" alt="initial design" width="350"> 
<img src="a7-27.png" alt="initial design" width="350"> 
<img src="a7-28.png" alt="initial design" width="350">  
<img src="a7-56.png" alt="initial design" width="350"> 

I added a triangular support underneath the bracket in hopes this would increase my safety factor and decrease my max stress. This did help me out quite a bit from the initial design but my stress was pretty concentrated on the backside still. I didn't calculate the necessary dimensions of the support, I just made a support that was somewhat proportional to the existing dimension.


### Thinning the Design

<img src="a7-20.png" alt="initial design" width="350"> 
<img src="a7-21.png" alt="initial design" width="350"> 
<img src="a7-22.png" alt="initial design" width="350"> 
<img src="a7-23.png" alt="initial design" width="350"> 
<img src="a7-24.png" alt="initial design" width="350"> 
<img src="a7-25.png" alt="initial design" width="350"> 
<img src="a7-26.png" alt="initial design" width="350"> 
<img src="a7-27.png" alt="initial design" width="350"> 
<img src="a7-28.png" alt="initial design" width="350"> 
<img src="a7-57.png" alt="initial design" width="350">

I made the design thinner in some areas where there wasn't a lot of stresses and I did three different analysis on it. I used a mesh percentage of 10, 7, and 2 percent this time to see if I could get closer to convergence.

### Removing Excess Material

<img src="a7-29.png" alt="initial design" width="350"> 
<img src="a7-30.png" alt="initial design" width="350"> 
<img src="a7-31.png" alt="initial design" width="350"> 
<img src="a7-32.png" alt="initial design" width="350"> 
<img src="a7-58.png" alt="initial design" width="350">

With the last iteration of the bracket I took out a ton of material where stresses were very low to allow for a reduction in weight. Additionally I smoothed out the edges of the material remove to account for any stress concentrations. Unlike the first couple analysis. I only did one FEA on a mesh setting of 10% and did not compare like I had done previously. The weight of the bracket did decrease greatly but It was not as light as the initial design due to the fact I had added an extra support.

### Link Initital Design

<img src="a7-33.png" alt="initial design" width="350"> 
<img src="a7-34.png" alt="initial design" width="350"> 
<img src="a7-35.png" alt="initial design" width="350"> 
<img src="a7-36.png" alt="initial design" width="350"> 
<img src="a7-37.png" alt="initial design" width="350"> 
<img src="a7-38.png" alt="initial design" width="350"> 
<img src="a7-39.png" alt="initial design" width="350"> 
<img src="a7-59.png" alt="initial design" width="350"> 

The Link saw much better results than the bracket did. The overall mass was adequate, the stress was about expected with some concentration around the holes of the link. I constrained it at the upper hole and applied the same load on the lower hole as I previously applied on the bracket. I would say that we saw better results on the link than the bracket because of the much simpler geometry of the link. I went through the same analysis of the bracket looking at the safety factor, max stress, max deflection, and mass of the link as i did the bracket with varying meshes.

### Thinner Link

<img src="a7-40.png" alt="initial design" width="350"> 
<img src="a7-41.png" alt="initial design" width="350"> 
<img src="a7-42.png" alt="initial design" width="350"> 
<img src="a7-43.png" alt="initial design" width="350"> 
<img src="a7-44.png" alt="initial design" width="350"> 
<img src="a7-45.png" alt="initial design" width="350"> 
<img src="a7-60.png" alt="initial design" width="350"> 

I decided to essentially cut the width in half to optimize weight and see how my other variables were affected. The max stress and deflection increased on the design. The safety factor became lower after making it thinner as well. I was certain that the calculations were correct and I came to the conclusion that, the dimension of width was critical in the design. I also could've made it a bit shorted to save some weight.

### Cutting Out Material
<img src="a7-46.png" alt="initial design" width="350"> 
<img src="a7-47.png" alt="initial design" width="350"> 
<img src="a7-48.png" alt="initial design" width="350"> 
<img src="a7-49.png" alt="initial design" width="350"> 
<img src="a7-50.png" alt="initial design" width="350"> 
<img src="a7-51.png" alt="initial design" width="350"> 
<img src="a7-52.png" alt="initial design" width="350"> 
<img src="a7-53.png" alt="initial design" width="350"> 
<img src="a7-54.png" alt="initial design" width="350"> 
<img src="a7-61.png" alt="initial design" width="350"> 

Similar to the bracket from earlier I decided to cut out some material, this time I removed material between the two holes as there was some stress there previously but It wasn't near the max stress. I decided to go with like a trianglular shape in the middle to preserve some extra support near the bottom. I made the edges of the triangle smooth to eliminate any stress concentrations. With the final analysis I did three different meshes like I did with the bracket and I calculated two seperate convergences.

### Reflection
I think a lot of mistakes in my FEA came from my previous calculations. I think it is important to understand how to essentially analyze the load acting on a piece of the part and what formulas then to use. I learned that FEA is a great tool to use in engineering because it allows us to simulate things in the world before they are put out there. I also learned that the way we set up our simulation is very important as well because the way the simulation computes values is dependent a lot on the nodes/mesh you give to it. I spent approximately 6 hours working on this assignment.

### CAD File
[Download the Bracket](./A6.f3d)

[Download the Link](./A6-Link.f3d)
