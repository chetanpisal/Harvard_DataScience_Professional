## Learning **ggplot2**

The first step in learning ggplot2 is to be able to break a graph apart into components.Let’s break down the plot above and introduce some of the ggplot2 terminology. The mainthree components to note are:### **Data**

The US murders data table is being summarized. We refer to this as the data component.### **Geometry**
The plot above is a scatterplot. This is referred to as the geometry component. Other possible geometries are barplot, histogram, smooth densities, qqplot, and boxplot. We will learn more about these in the Data Visualization part of the book.### **Aesthetic mapping** 

The plot uses several visual cues to represent the information provided by the dataset. The two most important cues in this plot are the point positions on the x-axis and y-axis, which represent population size and the total number of murders, respectively. Each point represents a different observation, and we map data about these observations to visual cues like x- and y-scale. Color is another visual cue that we map to region. We refer to this as the aesthetic mapping component. How we define the mapping depends on what geometry we are using.