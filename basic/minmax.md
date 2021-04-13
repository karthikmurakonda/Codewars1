# minimum and maximum
## Statement
Given an array of integers of length L.find maximum and minimum of sub array made of elements from Mth element of array to N th element of given array(m and n inclusive). 
## Input
* first line has a n integer T.(no.of test cases)

Each test has this following input:
* first line : positive integer L.
* second line: space seperated positive integers M and N.
* third line : elements of array(space seperated). 
## output
* for each testcase print minimum value and maximum value(space seperated)
## Constraints 
1 <= M < N <= L <= 10<sup>6</sup>
## Sample input 
```
3
6
3 6
1 2 3 4 5 6
4
1 3
45 78 45 66
```
## Sample output
```
3 6
45 78
```
## Explanation
* In the first case the sub array is 3 4 5 6 so minimum is 3 and maximum is 6
* In the second case the sub array is 45 48 45 so minimum is 45 and maximum is 48