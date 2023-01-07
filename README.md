# Simple-solution-for-extreme-terrain-function
A function to explain extreme terrain generation despite the smoothness of certain common algorithms like Perlin noise
By splitting the possible values generated into multiple pieces, you are able to define which has more influence
on the height of the result, from 0 to 0.4 for example you would get a flatter piece of land regardless of the value
from initial generation, however from 0.4 to 0.5 the result would be given a bigger multiplier (or to match the previous
result a math function), and for values further on you would get smoother results, making you plains and plateaus in 
your world and creating steep rises
