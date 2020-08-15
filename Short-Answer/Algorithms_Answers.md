#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(N)
while a is less than n^3, a is set to equal itself plus n^2. The function time to run is directly related to how big n is. 
If n is 3, the function will run 3 times

The time complexity is linear or directly related to how big or small n is

b) O(log N)
I would argue logarithmic time because when j doubles itself, it doesn't have to double itself again 
for several numbers after that. If n is 2, j only doubles itself once. If n is 3, j doubles itself twice, if n is 4, j still 
only has to double itself twice. If n is 5, j doubles itself three times and doesn't double itself again until n is 
greater than 8, then it doubles itself four times and now, instead of not having to do work for two numbers (6 &7) 
it doesn't need to double itself again until n is greater than 16. As n increases, j's work also increases but at a 
slightly slower rate than n.


c) O(N)
The function is recursively called but only increments by 1 regardless of the number size. The 
Space/Time complexity increase is directly correlated to the increase of the number of bunnies

## Exercise II
I would start by taking the number of floors in the building, and going half way up to drop an egg, if the egg 
breaks, this floor is my new top and I would find the halfway up floor between the ground and this floor and 
repeat the process. If the egg doesn't break, this floor is my new bottom, and I will find the halfway up floor
between this current floor that I'm on and the top and repeat the same process. By doing this I am halving 
the number of floors needed to test and number of eggs wasted, which would be O(log N) time complexity

