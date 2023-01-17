# Higher Order Functions

A function which takes one or more functions as arguments and/or returns a function is a Higher order function.

#### Callback function
A function which is passed as an argument to another function
#### Array Higher Order Functions
forEach, map, filter, reduce are highorder functions

#### Example
lets consider an example, We have an array of radius = [2,4,6,5]

find the area, diameter and circumference of the circle

One way of acheiving the results are

![SS1](https://user-images.githubusercontent.com/88746202/212942456-650a6f93-9caf-412e-821b-52f27ffdc859.svg)

There is nothing wrong with the above approach but we are repating the code over and over again, each individual function doesn't have single responsiblity.
It's always good to follow DRY(Don't repeat yourself) principle.
Using functional programming paradigms, The above code can be refactored by breaking the code into smaller functional units.

Abstracting the logic from each individual function, creating a new function for it and passing the function as parameter makes it more modular(separating a program's
functions into independent pieces each containing all the parts needed to execute a single aspect of the functionality) 

![image](https://user-images.githubusercontent.com/88746202/212945839-d4eb7228-8029-44e7-9e56-cee017a443cc.png)
