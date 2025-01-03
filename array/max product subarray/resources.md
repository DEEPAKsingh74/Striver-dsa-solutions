# Links:

- [Geeks For Geeks](https://www.geeksforgeeks.org/problems/maximum-product-subarray3604/1)

# Problem Statement :

Given an array arr[] that contains positive and negative integers (may contain 0 as well). Find the maximum product that we can get in a subarray of arr[].

Note: It is guaranteed that the output fits in a 32-bit integer.

#### Examples :

Input: arr[] = [-2, 6, -3, -10, 0, 2]
Output: 180
Explanation: The subarray with maximum product is {6, -3, -10} with product = 6 * (-3) * (-10) = 180.


Input: arr[] = [-1, -3, -10, 0, 6]
Output: 30
Explanation: The subarray with maximum product is {-3, -10} with product = (-3) * (-10) = 30.


Input: arr[] = [2, 3, 4] 
Output: 24 
Explanation: For an array with all positive elements, the result is product of all elements. 

#### Constraints :

1 ≤ arr.size() ≤ 10^6
-10  ≤  arr[i]  ≤  10



## Related Problems :


### Optimized Solution Complexity

**_Time_** : O(n)
**_Space_** : O(n)