# Sorting-Algorithm-Smackdown
Sort Smackdown compares the performance of a variety of sorting algorithms. Bucket and Bitwise sort are two of the fastest. Language is C++ and STL.

# Summary
Sort Smackdown is a project whose goal was to compare sorting algorithms under different
conditions to one another.

The sorting algorithms implemented are:
   Bucket sort
   Comb sort
   Heap sort
   Merge sort
   Quick sort
   Radix sort
   Bitwise sort
  
The results of Sort Smackdown was that Bucket and Bitwise sort were comparable in speed when the
number of items was under 1,000,000 however with larger data sets Bucket sort notably won. I was
surprised with the performance of my Quick sort; I expected it to be perform better.

Much improvement could be done to speed up these sorting algorithms. For example to get rid of the
deque object usage.
