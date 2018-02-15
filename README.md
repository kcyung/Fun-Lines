# Fun-Lines

A collection of 40 lines with randomly generated widths (1-10 pixels) and lengths (25-400 pixels) are drawn to the window.

Event handlers are used to allow the lines to be:
1) Generate a new list of 40 lines
2) Sort by length ascending (via CompareTo)
3) Sort by length descending (via System.Comparison compliant function)
4) Sort by width ascending (via a lambda expression)
5) Sort by width then by height (via System.Comparison compliant function)
6) Removal of all lines shorter than 75 pixels (via System.Predicate with compliant predicate function)
7) Removal of all lines greater than 325 pixels (via System.Predicate with lambda expression)
8) Ability to highlight all lines within ten pixel long of the trackbar value (via lambda expressions with extension methods)

![fun lines](https://user-images.githubusercontent.com/21131519/36241411-5d7e80e8-11d3-11e8-87c6-701ca54746d0.png)
