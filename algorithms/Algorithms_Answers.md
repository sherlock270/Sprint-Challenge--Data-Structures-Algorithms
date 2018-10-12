Add your answers to the Algorithms exercises here.

I.
a. O(log(n))
b. O(n^4)
c. O(2n)

II. First, drop an egg from floor f=n/2. If the egg breaks, drop the egg from f=(f-1)/2 and if the egg breaks again repeat the process until you find the floor where eggs don't break. When you reach a floor where the egg doesn't break, split the number of floors between the current floor and either the last floor where the egg broke or the top floor and drop from the halfway point. Keep going until you find the breaking point
