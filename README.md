# COMS-4771-Assignment-1-solution

Download Here: [COMS 4771 Assignment 1 solution](https://jarviscodinghub.com/assignment/coms-4771-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1.       Explain the academic honesty policy for the class and state your commitment to that policy.

[10 points]

2.       Sign up to Khan Academy with your Columbia email. Set ml4771.f14@gmail.com

as your coach. Make sure you are comfortable with the material in the sections Random variables and probability distributions and Inferential Statistics, and solve all tasks in those sections.
[20 points]      

 

3.       Make sure you can effectively use MATLAB. Write a MATLAB function that simulates housing prices in the Columbia campus area, assuming the price of a housing unit depends on the size of the apartment, its location (higher as you go west and south), and floor it is on.
The function Prices = SimHousingPrices(Market, StdDev, Houses)
should receive as input:
Market:    The parameters of the housing market –  a column vector of size  5, whose

coordinates are (a,b,c,d,e)T where
a is the price increase per square foot
b is the price increase per avenue, going west
c is the price difference per cross street, going north
d is the price increase per floor
e is the fixed component of the price

StdDev:    A non-negative scalar s  that denotes the scale of fluctuation of the price of a housing unit given the size, location and floor for that apartment.

Houses:    Data regarding the N housing units for which price should be simulated – a matrix of size N×4, whose i-th row lists area, avenue, street and floor for the i-th housing unit.

The function should provide as output:
Prices:    The prices for the N  units as a column vector. Each price needs to be a linear

combination of the corresponding row of Houses, with coefficients (a,b,c,d) ,

plus the fixed cost e, plus a simulated value of a normally-distributed random
variable, with mean zero and variance s 2 .

Please submit SimHousingPrices.m in a folder called Assignment01.Problem03
in your CourseWorks dropbox [20 points]
