# [16,21,11,8,12,22] --> Order By Merge Sort Algorithm


--> Split the array in half : [16,21,11] and [8,12,22]

--> Split again in half our two pieces of array : [16] [21,11] and [8,12] [22]

--> Split again : [16] [21] [11]  and  [8] [12] [22]

--> Now, Merge the parts, smallest one at the begining : [16] [11,21]  and [8,12] [22]

--> Merge together : [11,16,21] and [8,12,22]

--> Merge all numbers, compare the first ones amongst themselves. After compare the second ones amongst themselves...  : **[8,11,12,16,21,22]**

**Big O Notation : O(nlogn)**