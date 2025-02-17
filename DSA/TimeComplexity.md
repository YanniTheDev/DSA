# Time Complexity
### What Is It?
By definition, **time complexity** is used to measure the growth of the execution time of an algorithm as the size
of the input increases.

#### Consider this example:
**Imagine a classroom of 100 students in which you gave your pen to one person. You have to find that pen without knowing to whom you gave it**.

There are some ways you can find the pen, and what the **O** order is:
- O($$n^2$$): You go and ask the first person in the class if he has the pen. Also, you ask this person about the other 99 people in the classroom if they have that pen and so on. **This results in 100 people being asked individually 100 other times: hence $$n^2$$**.
- O($$n$$): Going and asking each student individually.
- O($$log(n)$$): Divide the class into two groups, then ask: “Is it on the left side, or the right side of the classroom?” Then take that group and divide it into two and ask again, and so on. Repeat the process till you are left with one student who has your pen.