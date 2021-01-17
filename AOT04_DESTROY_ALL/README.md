# Destroy All

Eren wants to destroy all the titan’s on the earth with his titan powers, but he has just got the power of the founding titan and he is not efficient in using its power.

He can transform into a titan only once in his lifetime so he wants to kill as many titans as he is capable of, only then he can be truly happy.

Eren also can’t go all out against the titans as he is a great source of information about titans, so captain Levi has not allowed Eren to go all out. Eren’s titan has a damage index D
which means if he takes damage strictly greater than D
he will be killed and humanity will lose a great soldier.

Each enemy titan has a happy index X
damage index Y
, which means for every titan Eren kills his happiness will rise by X
, and his titan will take damage by Y
.

Mikasa wants to make Eren happy, and also she doesn’t want him to be killed by titans. So she wants to pre-calculate the maximum happy index Eren can achieve by killing the titans such that the damage taken by them is not strictly greater than D
. She has asked you (Armin) for her help and being a good friend you have accepted her request.

## Input

- Every first line will contains two integers N and D, Number of titans on the earth and the Damage index of Eren.

- Next N lines contains 2 integers each Y and X, the damage it gives to Eren's titan and the happiness gained by Eren after killing this titan respectively.
- The current happiness of Eren is zero.

## Output

For each testcase, You are expected to print a single integer: The maximum happiness Eren can gain by killing maximum titans he can.

## Constraints

- 1≤N≤100
- 1≤D≤1e5
- 1≤X≤D
- 1≤Y≤1e9

## Sample Input

```
4 12
10 100
4 50
6 70
12 4
```

## Sample Output

```
120
```

## Explaination

We will choose to kill 2nd and 3rd titan as this will give us a happiness count of 120 and Eren will take damage of 10 which is less than the maximum damage index of Eren.
