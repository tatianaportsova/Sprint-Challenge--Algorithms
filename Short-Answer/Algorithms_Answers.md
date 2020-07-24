#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
   Since we are incrementing a by n^2 , then n^3 / n^2 = n.


b) O(n log n)
   When the function is iterating through each of the items in n, it's O(n).
   For the while loop (j < n), we don't need to check every item in n, only 
   the ones that a smaller then j. That's where O(log n) comes in.


c) O(n)
   The function is called n-1 for each time, so we deduct 1 from n before 
   calling the function again, but n-1 is also O(n).

## Exercise II

I'd use binary search because the floors in the bulding are already sorted. 
A binary search has time complexity of O(log n).

First, find the middle floor and drop an egg.

   Then, if the egg breaks, go to the middle of the lower floors.

   If the egg doesn't break, go to the middle of the upper floors. 

Repeat until the top floor is found.
