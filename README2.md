How many times does the loop body run each frame, once the x and y arrays are full?
one

What are two ways of increasing the spacing between rings?
x = x.slice(-300);  changes the size of the circles to 300 pixel
  y = y.slice(-300);

ellipse(x[i], y[i], 200 + (x.length - i)); change it to size 200 pixel

How can you make the ellipse trail longer?
for (var i = 0; i < x.length; i = i + 1) {
i = i + 1 makes it so that the distance of the circles are 1 pixel next to each other.
Making more cirles to follow mouse
