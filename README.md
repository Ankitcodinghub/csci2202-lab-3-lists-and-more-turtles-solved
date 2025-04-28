# csci2202-lab-3-lists-and-more-turtles-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 Lab 3-Lists and More Turtles Solved](https://www.ankitcodinghub.com/product/csci2202-21-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116957&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 Lab 3-Lists and More Turtles Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Lists and Introduction to Projectile Motion

Lists and More Turtles:

1. (a) Create a program staRect.py. The program takes two integers, R and C, as inputs and prints an R C rectangle array of asterisks (*). For example, R = 5, C = 10 should produce:

Note: When you use print(“A”) it adds a newline character (‘‘ ’’). To avoid the newline character, use print(“A”, end=‘‘’’)

(b) Modify staRect.py to accept a single integer R as input and produce a triangle with a single star in the first row, two in the second, etc. Save the program as sTri.py.

(1)

(2)

The motion of the projectile can be broken down into two independent components of the motion:

(i) Along the x-axis, with an acceleration ax = 0 and an initial velocity v0x = v0∗ cosθ and (ii) Along the y-axis, with an acceleration ay = −g (the negative sign indicates that it is pointing downwards.) and the initial velocity: v0y∗sinθ Along the horizontal and vertical directions:

vx = v0 ∗ cosθ and x = x0 + v0 ∗ cosθ ∗ t. (3)

vy = v0 ∗ sinθ − g ∗ t a

Using the x and y equations above, plot the trajectory of a turtle launched at an angle θ, and initial velocity v0 (entered by the user). To compute cos, sin etc. import math, convert the angle entered in degrees, θ, into radians (θ ∗ π/180). Use as: math.cos(θ∗π/180). The math module expects angles in radians). Fire the projectile from (x0,y0) = (−200,0).

• Pick a travel time that will (at least) cover the entire range of the x motion (experiment to find the right travel time).

• Compute the (x,y) position at small time increments (using the x and y equations above) making up the total travel time. A convenient way to do this is to use the range function in the form: range(start, stop, step). The step parameter allows you to control the increment (the default increment is 1).

(See: https://docs.python.org/3/library/functions.html#func-range). Use the turtle stamp() function to leave an impression of the turtle at each time-increment.

• Create lists for x, y and time and append each new x, y and time value to the respective lists. Print the lists (side-by-side) after the turtle has finished moving.

• Modify your program to compute an estimate of and print the max. distance the turtle travels in the x-direction (the “range”). The range is found by finding the time at which the y position of the turtle first becomes ≤ 0, and then using that time in the x equation.

• Modify your program to find the maximum height the projectile reaches. When the projectile is at its maximum height, vy = 0. You can approximate this using the vy equation: Find the time when vy switches from positive to negative. Use the time in the y equation to find the max. height.

• Finally, save a copy of your program and change it to create a list of firing angles θ from 20 to 80 degrees, in steps of 5 degrees (with fixed value for v0) and make a list of the max. heights reached and a list of the max. x-value (range) reached, for each value in the list of firing angles.

Below is the turtle trajectory for x0 = −200, y0 = 0, θ = 60, v0 = 70m/s
