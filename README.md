# cp-hw3

HOMEWORK3 What code draws the blades of grass? THIS PARTS make sure to keep it drawing the blades of grass. 
if (x > width) { x = random(10); h = h + 3; }

What code makes the "lawnmower" come by? How often does it come by? This part adjust the lawnmover. The number "0.999" is used to changes how long you want the grass.And when to cut them. 
if (random() > 0.999) { fill(255); rect(0, 0, width, height-15); h = 10; }

What's the point of the h variable? 
The h variable can changed in this part.As the numbers increased the grass become taller. x = x + 10;

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there? 
It is to adjust the position of grass and brown ground.And make sure it is well positioned.
