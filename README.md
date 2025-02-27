Download link :https://programming.engineering/product/program-3-csc2100-001-2/

# PROGRAM-3-CSC2100-001
PROGRAM 3 / CSC2100-001
PECIFICATIONS:

Write a program that can be used to gather data about the number of hours college students spend on Facebook and Twitter (combined) in one month.

Main Function

In Main, ask the user how many students were surveyed.

Main should make an array to define an array of floats with the number of elements equal to the number of students surveyed.

Main should then call a function called getFBTData to allow the user to enter the number of hours each student spent on Facebook and/or Twitter (combined) this month into the array.

Main should then call a function called printArray to print out the values in the array.

Main should then call a function called getMIn to get the minimum hours spent in a month.

Main should then call a function called getMax to calculate and display the maximum of the values entered.

Main should then call a function called getAverage to calculate and display the average of the values entered.

Main should then call printAboveAvg. This function will print out all the times that are greater than the average.

Main should then call printBelowAvg. This function will print out all the times that are equal to or below the average.

Main should then print out a tab and then the header “STATISTICS FOR TIME SPENT ON FACEBOOK & TWITTER” in all capital letters, then skip down to the next line and then print out the average, median & mode.

The labels “Average:”, “Minimum:”, and “Maximum:” should all have a colon “:” after the word.

The labels and the values should all be left aligned.



getFBTData Function

Allow the user to enter the number of hours each student spent on Facebook and/or Twitter into the array. The function will accept as arguments the following:

An array of floats

An integer that indicates the number of elements in the array.

Input Validation: Do not accept negative numbers for input.



printArray Function

This function should print out the text “Number of hours each student spent on Facebook/Twitter: “. Then, the function should print out each element in the array with a space between each element.

The function will accept as arguments the following:

An array of floats
An integer that indicates the number of elements in the array.

getMin Function

The function should iterate through the array and find the minimum value which should be returned.

Write a function that accepts as arguments the following:

An array of floats

An integer that indicates the number of elements in the array.

getMax Function

The function should iterate through the array and find the maximum value which should be returned.

Write a function that accepts as arguments the following:

An array of floats

An integer that indicates the number of elements in the array.


getAverage Function

The average of a set of values is calculated by adding all the values and then dividing the sum by the number of values in the set.

Write a function that accepts as arguments the following:

An array of floats

An integer that indicates the number of elements in the array.

The function should determine the average of the array. The average is the value the function should return.

printAboveAvg Function

This function should print out the text “Number of hours each student spent on Facebook/Twitter that is above the average is: “. Then, the function should print out each element in the array that is greater than the average with a space between each element.

The function will accept as arguments the following:

An array of floats
An integer that indicates the number of elements in the array.
The average time
printBelowAvg Function

This function should print out the text “Number of hours each student spent on Facebook/Twitter that are equal to or below the average is: “. Then, the function should print out each element in the array that is equal to or less than the average with a space between each element.

The function will accept as arguments the following:

An array of floats
An integer that indicates the number of elements in the array.
The average time

