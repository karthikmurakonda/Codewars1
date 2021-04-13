# meet_time
## Statement
gopi has set his no-screen sessions*, which is strictly adhered to.write a program to check whether he was in no-screen session or not at a given particular time.

gopi has **N** no-screen sessions.

No-screen sessions will be inputed as "START-TIME" "END-TIME".(24-hour format)

Assume all no-screen sessions will be occuring in only one day(no day change is observed during these sessions)
## Input
* input's first line has no.of no-screen sessions N.
* following N lines contains time of that sessions "START-TIME"-"END-TIME"(24-hour format)
* Last line contains Time **T** at which we have to find gopi is in no-screen time or not.
## output
print "Yes" if he able to attend the meet otherwise "No"
## Constraints 
* 1 <= N <= 100
## Sample input 
```
3
08:00 09:00
13:45 14:55
15:00 15:23
14:30
```
## Sample output
```
Yes
```
## Explanation
* he will be in the second no-screen session 13:45 to 14:55 where 14:30 is there in between.
