# developdataproduct
## Explanation for app use
This is for shiny app. The dataset is diamonds dataset in R. It explores the attributes of diamonds and the corresponding prices.

It mainly presents the graph to catch the changes of different variable groups. You can adjust the sample size(the smaller, the quicker the app would calculate), pick different Xs and Ys, to see the relationship that will be presented on the right. Also you can add smooth to see the trend. Then facet options you can use to adjust the panel figures.

About the dataset variables:
####price: price in US dollars (\$326--\$18,823)
####carat: weight of the diamond (0.2--5.01)
####cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
####colour: diamond colour, from J (worst) to D (best)
####clarity: a measurement of how clear the diamond is (I1 (worst), SI1, SI2, VS1, VS2, VVS1, VVS2, IF (best))
####x: length in mm (0--10.74)
####y: width in mm (0--58.9)
####z: depth in mm (0--31.8)
####depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
####table: width of top of diamond relative to widest point (43--95)
