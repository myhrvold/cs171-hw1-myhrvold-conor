<b>1.	The domain() function is the data range upon which the scale is calculated. What does d3.selectAll("tbody tr")[0].length-1 mean?</b>

This selects the first column of all of the rows. (The length-1 is the full extent of every row.)

<b>2.	Add the snippet in your code. Describe, in words, what the following function calls return:color(0), color(10) and color(150)?</b>

They are all different colors as defined in the color scale.

<b>3.	If the array passed to domain() was the minimum and maximum rate values, how would that change the scale? In what situations would this be appropriate?</b>

You would scale to the rates, so each rate value would have a unique color associated with it. This is appropriate for the example we did in our problem set, where we want to represent the extent of rates in addition to each value in that extent with a unique visual identifying color.
