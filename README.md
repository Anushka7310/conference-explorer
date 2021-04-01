# R Conference Events Explorer (Tests)

## Test 1
Create a simple demo flexdashboard.

**Explanation**
For this I've created a simple `flexdashboard` using

`install.packages("flexdashboard")`.

I have used the data from (https://github.com/benubah/r-community-explorer/blob/master/docs/R_Events.rds) for creating this simple `flexboard`.

## Test 2
And also added interactivity using the `crosstalk` package and updated the `flexdashboard`.

**Explanation**
In all, i have  added one plot in the flexdashboard. 
This plot is created using `plotly`, it shows the frequency of the language used on y-axis and languages in x-axis. To add more interactivity, I've added a slider which contains the days. This will monitor the popularity of R-related events and understanding the interests of the global R community over time by tracking event topics/content. 

![Screenshot (106)](https://user-images.githubusercontent.com/61081130/113322739-b472c380-9332-11eb-8629-c5ce637bc1de.png)

 I've used some other packages to remove punctuations, link etc.



 
