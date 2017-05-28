Developing Data Products Peer-graded Assignment: Shiny Application and Reproducible Pitch
========================================================
author: Ng Siok Yen
date: 28 May 2017
autosize: true

Background
========================================================
This presentation is done as part of the peer-graded assignment for the coursera developing data products class. The assignment has two parts:
- A Shiny application and deploy it on Rstudio's servers
- Rstudio Presenter to prepare a reproducible presentation

In this assignment, the R dataset `trees` is used in designing the Shiny app. This project is to study the effect of girth of the tree on the volume of timber for the black cherry trees. Slide bar is used for the user to input the girth of the tree and thus the volume of timber can be predicted through the linear regression model built.


Guide on the Application
========================================================
The shiny application in ios can be accessed at:
https://ngsiokyen.shinyapps.io/DevDataProd_Week4_Project/

The source code in github (ui.R & server.R files) can be accessed at:
https://github.com/ngsiokyen/Developing-Data-Products-Course-Project

1. User has to select the girth of the tree using the slide bar.
2. After making selection, the predicted volume of timber will be illustrated in the plot based on the linear regression model built.
3. The predicted volume varies with the girth of the tree and the plot will be refreshed automatically each time after a new selection has been made.


Summary of Dataset
========================================================
This data set provides measurements of the girth, height and volume of timber in 31 felled black cherry trees.

```r
summary(trees)
```

```
     Girth           Height       Volume     
 Min.   : 8.30   Min.   :63   Min.   :10.20  
 1st Qu.:11.05   1st Qu.:72   1st Qu.:19.40  
 Median :12.90   Median :76   Median :24.20  
 Mean   :13.25   Mean   :76   Mean   :30.17  
 3rd Qu.:15.25   3rd Qu.:80   3rd Qu.:37.30  
 Max.   :20.60   Max.   :87   Max.   :77.00  
```

Plot of the Dataset
========================================================
This is the plot of girth and the volume for black cherry trees.

<img src="DevDataProd_Week4_Project_Presentation-figure/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

