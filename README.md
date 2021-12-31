# UM6P School of Collective Intelligence Data Science Lab Estimating Pi using the Monte Carlo Method
One method to estimate the value of pie (3.141592...) is by using a Monte Carlo method. In the demo above, we have a circle of radius 0.5, enclosed by a 1 × 1 square. The area of the circle is , the area of the square is 1. If we divide the area of the circle, by the area of the square we get .

We then generate a large number of uniformly distributed random points and plot them on the graph. These points can be in any position within the square i.e. between (0,0) and (1,1). If they fall within the circle, they are coloured red, otherwise they are coloured blue. We keep track of the total number of points, and the number of points that are inside the circle. If we divide the number of points within the circle,  by the total number of points, , we should get a value that is an approximation of the ratio of the areas we calculated above, .

In other words,
When we only have a small number of points, the estimation is not very accurate, but when we have hundreds of thousands of points, we get much closer to the actual value - to within around 2 decimal places of accuracy. You can add points one at a time, or you can tick the "animate" checkbox to add many points to the graph very quickly.
