# first steps with GitHub

## R-Studio
library(datasets)
#Load Data
data(mtcars)
#View first 5 rows
head(mtcars, 5)
#load ggplot package
library(ggplot2)

#create weight histogram
ggplot(aes(x=wt),data=mtcars) + 
  geom_histogram(binwidth=0.25) + 
  labs(x = "Weight in 1000 kgs") + 
  ggtitle("Histogram for Cars")
  
![R-Studio Tests with Cars](https://github.com/dom-swiss/test/blob/main/r-studio.PNG)
