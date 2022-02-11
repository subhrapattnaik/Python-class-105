# Python-class-105


https://www.mathsisfun.com/data/standard-deviation.html



Here, if we look closely, we can see that this second graph’s Y Axis does not start with 0, since there are no values below 60.
To make both the graphs consistent with each other, we will add the following line ​before​ ​fig.show()​.
fig.update_yaxes(rangemode="tozero ")
This line will update the figure’s Y Axis, and we are asking the code to start the range of the Y Axis to 0.
The Graph now looks like the following.




Both of the graphs have the same average, which is 75. Average is considered to be the central value of a data set which can be used to represent a data.
In here, If we look closely, we can see that while all the points are close to the line in the second graph, they are pretty far away in the first graph.
In the first graph, where the lowest point is 20 and the average is 75, is it fair that 75 is used to represent 20?



We need to find out how much our data is spreading out from the central tendency. Just by looking at the graph, we can clearly see that the
data spread in graph 1 is much more than the data spread in graph 2.
The question is, by how much? Can we represent this with a number, of how much data spread each of the graphs represents from their central tendency?

Standard deviation​ is a measure of how spread out a data set is.

The formula to calculate standard deviation is
