# Special Bond

To make a powerful army so that all the citizens of Mitras city stay safe from attack by Titans, huge giants. So one of the three parts of this army that is Scout Regiment wants to make a new plan with a new powerful team and for this Recruiter is recruiting soldiers. The recruiter also belongs to the Scout Regiment.

This Scout Regiment has it’s a specialty that each soldier has a unique number like 1,2,3,4,5….
where these numbers are in increasing order of their rank.If a soldier has a higher rank that means he is senior for all those with rank lower than him.

But there are some rules for this which are decided by the recruiter, he will choose only those soldiers who have that special bond with him, so to check that bond he is having one equation if this holds true then and then only he will recruit these soldiers also he will choose juniors only as he wants to be the Head of the New team with the highest rank.

Suppose the recruiter’s rank is N and the soldier he is choosing has rank i
then the Equation by which he is checking that special bond is

### X=(i\*N)

where integer X
is the least common multiple of i
and N.

So now you have to find the size of this new team including him.

## Input

- First line will contain T, the number of test cases. Then the test cases follow.
- Each test case contains a single line of input, integer N that is the rank of the recruiter.

## Output

For each test case output one new line single integer i.e. size of the new team including recruiter.

## Constraints

- 1≤T≤1000
- 2≤N≤1e6

## Sample Input

```
2
5
10
```

## Sample Output

```
5
5
```

## Explaination

For the 1st test case Here when n=5 He can choose from a 1,2,3,4
ranking and there are all 4 with whom he has that special bond i.e lcm(1,5)=1∗5,lcm(2,5)=2∗5,lcm(3,5)=3∗5,lcm(4,5)=4∗5
so the size of the team including himself is 5.
