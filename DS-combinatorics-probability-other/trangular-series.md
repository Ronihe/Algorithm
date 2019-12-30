# Triangular

A **triangular series** is a series of numbers where each number could be the row of an equilateral triangle.

So 1, 2, 3, 4, 5 is a triangular series, because you could stack the numbers like this:
![](triangular_series__triangle_of_stacked_circles.svg)

Since the only thing that changes in triangular series is the value of the highest number, it’s helpful to give that a name. Let’s call it nn.

Triangular series are nice because no matter how large n is, it’s always easy to find the total sum of all the numbers.

Take the example above. Notice that if we add the first and last numbers together, and then add the second and second-to-last numbers together, they have the same sum! This happens with every pair of numbers until we reach the middle. If we add up all the pairs of numbers, we get:

```
1 + 8 = 9
2 + 7 = 9
3 + 6 = 9
4 + 5 = 9
```

This is true for every triangular series:

1. Pairs of numbers on each side will always add up to the same value.
2. That value will always be 1 more than the series’ n.

This gives us a pattern. Each pair's sum is n+1, and there are n/2 pairs. So our total sum is: (n+1)∗n/2.
​
**What if we know the total sum, but we don't know the value of n?**

Let’s say we have:

1 + 2 + 3 + \ldots + (n - 2) + (n - 1) + n = 78 No problem. We just use our formula and set it equal to the sum!

{n^2 + n}{2}=78 
Now, we can rearrange our equation to get a quadratic equation (remember those?)
n^2 + n - 156 = 0
Here's the quadratic formula:

-b+/-sqrt{b^2-4ac/2a
​	 
If you don't really remember how to use it, that's cool. You can just use an online calculator. We don't judge.

Taking the positive solution, we get n = 12

So for a triangular series, remember—the total sum is:

(n^2 + n)/2
​	
 
