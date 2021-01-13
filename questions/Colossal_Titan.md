# Colossal Titan

After seeing too many titans attacking team Levi, Levi decided to withdraw from the battle with titans and head towards the Shinganshina district.
As the gate of entrance to the Shinganshina district is too narrow such that only one horseman can enter through the gate at a time hence Levi instructed everyone to follow queue formation and head towards Shinganshina with Levi at the end of the queue and Mikasa in the front of the queue as they are most skilled worriers in the team. After forming the queue some horsemen are killed by titans now the queue has both horsemen and empty spots in it. Both Mikasa and Levi are still alive.
<br>
Suddenly the sky shined with yellow light and the Colossal Titan appeared. As the Colossal Titan is too big for a human, Colossal can kill all the horseman that come under his foot. The length of his foot is F.
<br><br>
The power of all the worriers in the team is 1 except for Levi and Mikasa with L and M respectively.
<br>
Colossal titan has only one move and he wants to maximize his damage to the team.
<br>

<b>Damage caused by Colossal titan is equivalent to the amount of power he removed from team Levi after killing the horseman with his foot. </b>
<br><br>

You will be given a binary string S (consisting of zero and one). Where 1 represents a horseman is present and 0 represents an empty spot in the queue. The first position of the string represents the end of the queue and the end of the string represents the start of the queue. It is guaranteed that the start and end of the string will always be with 1 representing Levi and Mikasa.

<br><br>
Find the maximum damage that Colossal titan can cause to team Levi.
<br>

Note: Colossal Titan can affect all the horsemen that come in a contiguous substring of Swith length <= F

## Input format

First-line gives T number of test cases
<br>For each test case
<br> the First line contains three space-separated integers L M F
<br> the Second line contains a binary string S

## Constraints

1 <= T <= 100 <br>
2 <= |S| <= 10^5 <br>
1 <= L,M,N <= 10^9 <br>

## Output Format

For each test case output a single line with the maximum damage that the Colossal Titan can cause

## Sample Test

Input

```
1
4 3 3
1001111
```

Output

```
5
```

### Explaination

Lets represent 1001111 as S1,S2,..S7
Colossal
can kill horsemen @ S1,S2,S3
can kill horsemen @ S4,S5,S6
..
can kill worries @ S5,S6,S7 etc (all contiguous substring possible)
The maximum damaged will be caused when Colossal puts his foot on the last three indexes of the string ie S5,S6,S7. Causing damage to two horsemen(at position S5 and S6) and Mikasa(at position S7).
max_damage = 1 + 1 + 3 = 5
