# [22,27,16,2,18,6] --> Write Insertion(Selection) Sort Stages

**[2,27,16,22,18,6]**  --> The smallest number in the array is "2". Change its index with first number of array.

**[2,6,16,22,18,27]**  --> The smallest number in the array except first number is "6". Change its index with second number of array.

**[2,6,16,22,18,27]**  --> The smallest number in the array except first and second numbers is "16". It is already at third sequence.

**[2,6,16,18,22,27]**  --> The smallest number in the array except first, second and third numbers is "18". Change its index with fourth number of array.

**[2,6,16,18,22,27]**  --> Find other smallest numbers of array and check their position. Now our array looks like in order.

**Big O Notation** --> n + n-1 + n-2 + .... + 1 = Sum of numbers from 1 to n = n.(n+1)/2 = (n^2 +n)/2 = > **O(n^2)**

**In Ordered Array, "18" is in the middle of the array. So, its time complexity is "average case"**

# [7,3,5,8,2,9,4,15,6] --> Write first four steps of the array according to Selection Sort

[**2**,3,5,8,**7**,9,4,15,6] --> The smallest number in the array is "2". Change its index with first number of array.

[2,**3**,5,8,7,9,4,15,6] --> The smallest number in the array except first number is "3". It is already at second sequence..

[2,3,**4**,8,7,9,**5**,15,6] --> The smallest number in the array except first and second numbers is "4". Change its index with third number of array.

[2,3,4,**5**,7,9,**8**,15,6] --> The smallest number in the array except first,second and third numbers is "5". Change its index with fourth number of array.