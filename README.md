# New-repo
library(datasets)
data(iris)
View(iris)

library(ggplot2)
ggplot2(aes(x=mpg , y=wt), data(iris)) + geom.point() + ggtitle("Miles per gallon vs Weigt") + labs(x='Miles per gallon', y='Weight')
