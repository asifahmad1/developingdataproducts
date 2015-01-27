Coursera Presentation - Developing Data Products
=================================================
author: Asif Ahmad
Presentation_link:  (https://asifahmad.shinyapps.io/Coursera_Project/)

First Slide
========================================================
- Project have interactive data visualization through graphs and tables 
     
- For visualization of data products there are `6 Tabs` as:

Boxplot | Summary | Structure | DataTable  |Selected Variable| Histogram |

- Side bar consists of following:
        
 1. `Dropdown menu` -->  from which user can select a variable                                 
 2. `slider`--> is used to select bins and observations
 3. `Radio Buttons`--> is used to to select color of bins and boxplot


Slide Without Code
========================================================

```{r echo=FALSE }
par(mfrow=c(2,2))
boxplot(iris)
plot(iris$Sepal.Length,iris$Sepal.Width, main="Scatterplot of SepalLength vs. SepalWidth")
hist(iris$Sepal.Width,  main="Histogram of Sepal.Width")
hist(iris$Sepal.Length, main="Histogram of Sepal.Length")
```

Slide With Code
========================================================

```{r, echo=TRUE}
summary(iris[,1:3])
summary(iris[,4])

```

Project Interface Figure and Link 
========================================================
[Click Here to See Project] (https://asifahmad.shinyapps.io/Coursera_Project/) 
![alt text](shiny.jpg) 
Screen Shot of Project: ![](shiny.jpeg) (https://asifahmad.shinyapps.io/Coursera_Project/) 
