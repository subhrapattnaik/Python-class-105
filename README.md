# Python-class-105


https://www.mathsisfun.com/data/standard-deviation.html



Here, if we look closely, we can see that this second graph’s Y Axis does not start with 0, since there are no values below 60.
To make both the graphs consistent with each other, we will add the following line ​before​ ​fig.show()​.
fig.update_yaxes(rangemode="tozero ")
This line will update the figure’s Y Axis, and we are asking the code to start the range of the Y Axis to 0.
The Graph now looks like the following.
