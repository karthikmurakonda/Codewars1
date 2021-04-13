# Making a Countdown Timer

## Statement
Given an integer, that takes input of the time in seconds . You have to print the countdown timer in the format of minutes and seconds as 00:00 [minutes:seconds].

First line contains no. of test cases **T**

The second line contains the input values to be tested **N**
## Constraints
1<=t<=4
## Sample Input
```
4
3600 600 2000 89

```
## Inference

It is clear that there will be a time constraint which will be applicable here .
There is also a dynamic printing going on here meaning for example, if the time in seconds is 2 then it will first print 00:02 then the very next second, the output appears to change to 00:01 and then to 00:00 .

```
