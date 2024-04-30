[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/9YUeXH71)
# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.
I would start by just throwing random lists and inputs at it and see if they're getting sorted. Then I would compare the time complexity of this super algorthim to known algorthims and see how the sorts compare. I would then see if the time to sort any and all lists was linear. If the time complexity were all linear then I would see if I could find a worst case scenerio by reversing the orders or amount of elements, maybe put multiple duplicates in the list. 
I don't think this is possible becasue with the known lower bound of $O(nlogn)$ in sorting and unless the reasearcher found a way to sort without comparing all the elements then the claim of $O(n)$ is bogus.

Well if I tested numerous lists of different values (100,1000, 10,000,000 elements) and plotted the points based of $n$ elements and time, the line would be a straight line.
