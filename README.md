# Spirograph-curve  
For the Spirograph curve point creation, use the following parametric equations (with R=8, r=1, a=4):  
x(t) = (R+r)*cos((r/R)*t) - a*cos((1+r/R)*t)  
y(t) = (R+r)*sin((r/R)*t) - a*sin((1+r/R)*t)  
Using the above equations, loop through t from 0.00 to n*Pi (eg. 2*Pi; note that 'n' might need to be more than 2, for the curve to close on itself; and, t is in radians, not degrees), in steps of 0.01. That will create the sequence of (x,y) points that make up the Spiro curve, which would look like the curve of the screenshot below, when R=8, r=1, a=4:  
![Sorry!Something wrong with the img.]( Spirograph-curve/screenshot/Spiro.png )
