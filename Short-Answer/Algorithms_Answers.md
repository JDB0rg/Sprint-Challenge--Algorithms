Add your answers to the Algorithms exercises here.

Exercise 1
a. O(n)
    Here we have a simple loop. As the list of items it has to iterate over grows the time grows. 

b. O(n^4)
    Each for loop is roughly O(n). With one nested in another it will be the number of times the first loop runs times the number of times the nest loop runs. So 4 nested for loops would be O(n * n * n * n)

c. O(n)
    Here the recursive funciton will recall itself more as n grows and since it simply returns either 0 or 2 + the recursive call it will be linear time.  

Exercise 2
1. Divide the building in half and drop an egg. 
2. If the eggs breaks
    a. Divide the lower half of the portion of the building that is untested and drop an egg
3. if the egg doesn't break
    b. Divide the upper half of the portion of the building that is untested and drop an egg
4. Repeat steps 2 or 3 depending on the result of step 1 until you have narrowed down _f_

O(n^2)
Basically the for loop would be O(n) and the recursive call would be O(n) combining the two would be O(n^2)