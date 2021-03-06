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
Given a interger `x`, print out whether it is a prime number.

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

## Palindrome
A palindrome is a word that is the same when you read it forwards from the beginning or backwards from the end.
Given a number `n` and a string with length `n` on the next line.
Print out whether it is a palindrome.

**Example Input 1**
```
5
level
```

**Example Output 1**
```
Yes
```

**Example Input 2**
```
4
noon
```

**Example Output 2**
```
Yes
```

**Example Input 3**
```
7
adobeee
```

**Example Output 3**
```
No
```

## 2D Array
Given 2 integers `h` and `w`.
The following will be a 2D-array with height `h` and width `w`.
Read it into a 2D-array and print it out.

**Example Input 1**
```
4 5
1 2 3 4 5
6 7 8 9 10
11 12 13 14 15
16 17 18 19 20
```

**Example Output 1**
```
1 2 3 4 5
6 7 8 9 10
11 12 13 14 15
16 17 18 19 20
```

**Example Input 2**
```
5 3
1 2 3
4 5 6
7 8 9
10 11 12
13 14 15
```

**Example Output 2**
```
1 2 3
4 5 6
7 8 9
10 11 12
13 14 15
```

## Array Manipulation
Given 2 integers `h` and `w`.
The following will be a 2D-array with height `h` and width `w`.
Read it into a 2D-array, change the value of the position on 2nd row, 1st column to 10.

**Example Input 1**
```
4 5
1 2 3 4 5
6 7 8 9 10
11 12 13 14 15
16 17 18 19 20
```
**Example Output 1**
```
1 2 3 4 5
10 7 8 9 10
11 12 13 14 15
16 17 18 19 20
```

**Example Input 2**
```
5 3
1 2 3
4 5 6
7 8 9
10 11 12
13 14 15
```

**Example Output 2**
```
1 2 3
10 5 6
7 8 9
10 11 12
13 14 15
```

# Challenges
In this section, I'll provide you with more complex problems than above.

You may have to combine several concepts and use multiple steps.

For each problem, you can first think of your own solution and try to implement it.

After you finished, (or you couldn't think of any), check out the hints of the problem and try to follow the hints to complete it.

## Max in Array
Given an integer `n`, and an array, which consist of positive integers, of size `n` in the next line.
Print out the max integer inside the array.
If there are multiple values that are the same, and are maximum value, just print it.

**Example Input 1**
```
10
1 51 123 5 94 81 2 34 219 384
```

**Example Output 1**
```
384
```

**Example Input 2**
```
15
109 38 4 7 128 7 935 651 43 85 19 3 24 7258 67
```

**Example Output 2**
```
7258
```

<details>
<summary>Hint</summary>
  <ol>
    <li>Reading array</li>
      By printing out the whole array, you can check whether you can read the whole array in correctly.
    <li>Iteration through array</li>
      We can create a variable called <code>max</code>, which contains the <i>current</i> max value. <br>
      When we iterate through the array, update <pre>max</pre> if the ith integer is bigger than <code>max</code>. <br>
      For example, consider the following array <br>
      <pre>3 4 2 1</pre>
      When we meet 3, we'll update <code>max</code> to 3 since it's the biggest so far. <br>
      Then, we meet 4, update <code>max</code> to 4 since it's the biggest so far (bigger than the privous one(3)). <br>
      Then, we meet 2, we won't update <code>max</code> since it's smaller than <code>max</code>(4). <br>
      Finally, we meet 1, we won't update <code>max</code> since it's stiller than <code>max</code>(4). <br>
  </ol>
<br>
</details>

## Stars
Given an odd integer `n`, `n >= 5`, print out certain kind of patterns (watch examples to see the pattern).

**Example Input 1**
```
7
```

**Example Output 1**
```
 *******
* ***** *
** *** **
*** * ***
** *** **
* ***** *
 *******
```

**Example Input 2**
```
5
```

**Example Output 2**
```
 ***** 
* *** *
** * **
* *** *
 *****
```

<details>
<summary>Hint</summary>
  <ol>
    <li>Reading n</li>
    By printing out the number, you can check whether you can read <code>n</code> correctly.
    <li>Finish top half (from row <code>0</code> to row <code>n/2</code>)</li>
      In order to finish this, we need even smaller steps.
      <ol>
        <li>Print certain <code>i</code>(<code>0 &lt= i &lt= n/2+1</code>) row</li>
          <i>Note: the index of center row is <code>n/2 + 1</code></i><br>
          By observing the pattern, you may find out that <code>i</code> is the same as the stars number before first space, and the stars number after second space. <br>
          Therefore, the number of remaining center stars is <code>n - 2*i</code>, and the total length of a row is a contant <code>n+2</code>.
          With the coditions above, we can contruct a loop to print <code>i</code> row.
          <details>
            <summary>Code</summary>
<pre>
for (int a = 0; a < n+2; a++) {
  if (a == i) {
    printf(" ");
  } else if (a == n+1 - i) {
    printf(" ");
  } else {
    printf("*");
  }
}
printf("\n");
</pre>
          </details>
          <li>Print each row</li>
             If your last step succeed, now you can create a loop to print each row of top half.
      </ol>
    <li>Finish bottom half</li>
      Just the same as the top half, only in reversing order, and the middle row should be omitted.
  </ol>
<br>
</details>
