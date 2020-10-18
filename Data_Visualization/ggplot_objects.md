## **ggplot Objects**

The first step in creating a ggplot2 graph is to define a ggplot object. We do this with the function ggplot, which initializes the graph. If we read the help file for this function, we see that the first argument is used to specify what data is associated with this object:_ggplot(data = murders)_We can also pipe the data in as the first argument. So this line of code is equivalent to the one above:_murders %>% ggplot()_
It renders a plot, in this case a blank slate since no geometry has been defined. The onlystyle choice we see is a grey background.W
hat has happened above is that the object was created and, because it was not assigned,it was automatically evaluated. But we can assign our plot to an object, for example likethis:

_p <- ggplot(data = murders)_
_class(p)-_#> [1] "gg" "ggplot"_To render the plot associated with this object, we simply print the object p. The following two lines of code each produce the same plot we see above:_print(p)__p_
