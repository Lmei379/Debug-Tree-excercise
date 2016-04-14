# Debug-Tree-excercise
For class excercise week 11
***PLEASE NOTE THAT THIS EDITED IS TO HELP AND NOT TURNED IN AS A LATE IN CLASS ASSIGNMENT***
***I TURNED ONE IN BEFORE THE DUE DATE, BUT THIS ONE IS JUST AN EDIT ON THE CODE AND CHECKING ITS PROBLEM -READ BELOW-***

It's a late, but I think I was able to solve the 2nd function's (test_is_words) problem 
since its late, it probably don't count, but I just thought you might want to know what the problem was before 
In the 1st for loop, for some reason results[c] kept giving out random numbers, which one of them was 0 which cause the function to return false
the problem was (I assuming from the debugging) that because 'results' is an empty boolean array, the computer just gave it random elements, so when running the code, results[c] just gave random numbers...
I thought maybe I should fix it by not making the array empty, so in the if statement (inside the switch statment), I added results[c] = 1 in else (since if the condition is true, results[c] = 0), this way the boolean array won't have random numbers (like 0, 204, etc.) in it. 
I'm not sure if its correct, but I hope this helps, and it was able to compile and run.
I didn't merge this one with the master, so is just on a branch
