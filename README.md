How many lines are drawn each frame? In other words, how often does the for loop run?
Should be 38 because -10 from both side of 400 is 380 divided by 10. 

What do the first, second, and third appearances of the number 10 do in the code?
for (var x = 10; x < width-10; x = x + 10) {
var x = 10 makes a margin 0f 10 from the left and x < width-10 makes it from the right
x = x + 10 makes 10 pixel wide gap in the margin 
