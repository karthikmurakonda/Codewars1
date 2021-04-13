# Sum upto i in an array
## Statement
Given an array of integers, find the sum upto element i in the array, and store it in a new arrray. Now, print this new array in a seperate line for each test-case.
first line contains no. of test cases **T**
each test case has 2 lines of input
the first line of each test case gives the number of elements in the array **N**
the second line gives the elements of the array
## Constraints
1<=T<=10<sup>2</sup>
1<=N<=10<sup>6</sup>
## Sample Input
```
3
5
2 5 7 8 9
2
19 50
10
4 2 6 7 12 34 77 45 69 100
```
## Sample Output
```
2 7 14 22 31
19 69
4 6 12 19 31 65 142 187 256 100
```
## Explanation
```
In the first case, there are 5 elements in the array, namely, 2, 5, 7, 8 and 9
the sum till the first element (i.e.  index 0) is 2
sum till the second element (i.e. index 1) is 2 + 5 = 7
sum till the third element (i.e. index 2) is 2 + 5 + 7 = 14
sum till the fourth element (i.e. index 3) is 2 + 5 + 7 + 8 = 22
sum till the fifth element (i.e. index 4) is 2 + 5 + 7 + 8 + 9 = 31
```
