# Attack On Titan

<i>"Eren, When I get home…I’ll show you what’s in the basement that I’ve been keeping secret all this time ”

- Grisha Yeager </i>

Eren went to the basement to search the secret about Titans but the basement is secured with a password which can be obtained by solving the equation so help Eren and print the password as an answer.

You are given n
numbers b1,b2,.......,bn
and you have to find

### ∏1<=i<j<=n|bi−bj|

That is

<b> ∏(n)=|b1−b2|∗|b1−b3|∗.........∗|b1−bn|∗|b2−b3|∗|b2−b4|∗.........∗|b2−bn|∗|b3−b4|∗|b3−b5|∗.........∗|b3−bn|∗|b4−b5|∗|b4−b6|∗.........∗|b4−bn|∗.........∗|bn−1−bn| </b>

The final answer should be given after applying modulo m
to this as the answer may be large

Where |a| represents the absolute value of a.

## Input

- First line of input will be having N and m
- The second line will contain N elements I.e. b1,b2,b3........bn.

## Output

Output in a single line answer modulo m.

## Constraints

- 2≤N≤1e6
- 1≤M≤2000
- 1≤bi≤1e9

## Sample Input

```
3 10
1 2 9
```

## Sample Output

```
6
```
