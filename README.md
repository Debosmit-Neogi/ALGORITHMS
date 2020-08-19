# ALGORITHMS
This repository contains codes of  various algorithms required for coding interview preparation

 ## KADANE'S  ALGORITHM:
    kadane's algorithm helps us to compute maximum subarray sum in linear time -> O(N); where N is the size of the input array.
    According to kadane's algorithm , we don't need to compute sums of all possible subarray (and find out the greatest sum). 
    Instead, we can do in a single loop by maintaining 2 variables (current_sum, max_sum)."max_sum" variable gives the maximum sum of subarray.



 ## SEARCHING AN ELEMENT IN A SORTED BUT ROTATED ARRAY:
    Searching an element in a sorted but rotated array can be done by the application of binary search in  O(logn) time.The first main step is to find if the mid 
    lies in first fragment or second fragment (1st and 2nd fragments explained in code). After finding mid two cases arise for each possibility of mid(part1 and
    part2 search space).Whwn we get the search space apply binary search.
