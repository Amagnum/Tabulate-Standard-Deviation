# Tabulate-Standard-Deviation
Hey there,
This HTML PAGE will help you tabulate standard deviation (was created for physics lab calculations)
* Bootstrap, HTML5, Javascript (all in same page).
* Page will work offline.
* Dynamically add fields into html page using javascript.
* Used Math.sqrt() and Math.abs() for square root and absolute operations respectively.

![alt screen](https://github.com/Amagnum/Tabulate-Standard-Deviation/blob/master/Screenshot%20from%202019-03-17%2020-52-30.png)

## Instructions (how to use):
1. just input all your xi using input box and clicking add button 
    {this will dynamically add the xi in your table, and will also store it in a global variable which will be used later}
2. Once all the data(xis) are inputed, click on calculate button
    {this will do all the calculations for standard deviation, it contains two for loops one for calculating the mean, the other loop will
    calculate abs(xi-mean(xi)), abs^2, and standard deviation also it will be dynamically adding data into table's respective rows and columns}
3. You can reset the whole page by clicking reset button
    {it just relodes the page}
    
## JavaScript Functions:
1. additem - used to add items/input_numbers into table(dynamically) also stores it in data[] variable
2. calculate - used to do all calculations related to Standard Deviation and Tabulate all the respective fields.
3. reset - used to refresh the page.

Thats all!!
use it and enjoy!
