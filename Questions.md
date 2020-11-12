# Basic Syntax
## Hello C
Print out "Hello C" on screen.

**Example Input**

No Input

**Example Output**
```
Hello C
```

## Variable 1
Read an interger `n`, and print the value of `2*n`

**Example Input 1**
```
1
```

**Example Output 1**
```
2
```
---
**Example Input 2**
```
10
```
**Example Output 2**
```
20
```

## Variable 2
Given 2 integers `x` and `y`, print out the value of `x/y` with 5 digit after decimal point.

**Example Input 1**
```
2 1
```

**Example Output2**
```
2.00000
```
---
**Example Input 2**
```
5 3
```

**Example Output 2**
```
1.66667
```

## Format 
Given 2 integers `x` and `y`, print out the percentage of `x/y` with 2 digit after decimal point.

**Example Input 1**
```
x = 1 
y = 2
```

**Example Output1**
```
x/y = 50.00%
```
---
**Example Input 2**
```
x = 5 
y = 3
```

**Example Output 2**
```
x/y = 166.67%
```


## Loop 1
Given an integer `n`, print out a pyramid of centain kind (See examples).

**Example Input 1**
```
3
```

**Example Output 1**
```
*
**
***
```
---
**Example Input 2**
```
10
```

**Example Output 2**
```
*
**
***
****
*****
******
*******
********
*********
**********
```

## Loop 2
Given 2 integers `a`, `b`, print out a pyramid of centain kind (See examples).

**Example Input 1**
```
1 3
```

**Example Output 1**
```
*
**
***
```
---
**Example Input 2**
```
5 10
```

**Example Output 2**
```
*****
******
*******
********
*********
**********
```

## Read until newline
Given an unlimit sized string(end with newline), print it.

**Example Input 1**
```
ttttttttaaaaaaaannnnnnnn0x0x0x0xtatatatanonononoc.c.c.c.rlrlrlrlahunahunatohatoh.p.p.p.p

```

**Example Output 1**
```
ttttttttaaaaaaaannnnnnnn0x0x0x0xtatatatanonononoc.c.c.c.rlrlrlrlahunahunatohatoh.p.p.p.p

```

**Example Input 2**
```
aoeusnthaoeusnth',.plrcg',.plrcg;qjkzvwmaoeusnth',.plrcg;qjklrcgaoeusnth',.pzvwm1234

```

**Example Output 2**
```
aoeusnthaoeusnth',.plrcg',.plrcg;qjkzvwmaoeusnth',.plrcg;qjklrcgaoeusnth',.pzvwm1234

```

## Max
Given 2 integers, print out the bigger one.

**Example Input 1**
```
3 5
```

**Example Output 1**
```
5
```

**Example Input 2**
```
10 3
```

**Example Output 2**
```
10
```

**Example Input 3**
```
10 10
```

**Example Output 3**
```
10
```

## Max 2
Given 3 integers, print out the biggest one.

**Example Input 1**
```
1 3 5
```

**Example Output 1**
```
5
```

**Example Input 2**
```
10 8 15
```

**Example Output 2**
```
15
```

**Example Input 3**
```
10 10 5
```

**Example Output 3**
```
10
```

**Example Input 4**
```
5 5 11
```

**Example Output 4**
```
11
```


## leap year
Given a year, print out whether it is a leap year.

**Example Input 1**
```
1996
```

**Example Output 1**
```
Yes
```

**Example Input 2**
```
2001
```

**Example Output 2**
```
No
```

**Example Input 3**
```
3000
```

**Example Output 3**
```
No
```

**Example Input 4**
```
2000
```

**Example Output 4**
```
Yes
```

# Concepts Intergration

## Array Iteration
Given an interger `n` and `n` intergers in the next line.
Print out the series of intergers backward.

**Example Input 1**
```
5
1 2 3 4 5
```

**Example Output 1**
```
5 4 3 2 1
```

**Example Input 2**
```
10
1 2 4 65 76 234 342 12 34 51
```

**Example Output 2**
```
51 34 12 342 234 76 65 4 2 1
```

## Even Filter
Given an interger `n` and `n` intergers in the next line.
Print out all even integers in the series in the same order.

**Example Input 1**
```
10
1 3 5 2 4 6 7 10 2 11
```

**Example Output 1**
```
2 4 6 10 2
```

**Example Input 2**
```
5
1 3 5 7 9
```

**Example Output 2**

No Output

## Prime Checker
Given a interger `x`, print out whether it is a prime.

**Example Input 1**
```
2
```

**Example Output 1**
```
Yes
```

**Example Input 2**
```
5
```

**Example Output 2**
```
Yes
```

**Example Input 3**
```
15
```

**Example Output 3**
```
No
```

## Grader
Given a series of scores with unlimited length.
All socers are integers.
For each score, print out the correponding ranking with a newline according to the table below.
| Score  | Ranking |
|--------|---------|
| 95~100 |   A+    |
| 90~94  |   A     |
| 80~89  |   B     |
| 70~79  |   C     |
| 60~69  |   D     |
| 0~59   |   F     |

**Example Input 1**
```
0 10 20 30 40 50 60 70 80 90 100
```

**Example Output 1**
```
F
F
F
F
F
F
D
C
B
A
A+
```

## Character Manipulation
Given an integer `n`, representing the size of the following string.
The string cosists of characters of any kind.
Your job is to make every lowercase letters uppercase, and vice versa.
For other characters that are not in the alphabet, just print it.

**Example Input 1**
```
10
abON19.[ta
```

**Example Output 1**
```
ABon19.[TA
```

**Example Input 2**
```
15
'9lrAEpg.,U,nuO
```

**Example Output 2**
```
'9LRaePG.,u,NUo
```
