Given an integer N, find a permutation P=P1,P2,…,Pn of length N that satisfies the following two conditions:

Pi /=i(1≤i≤N);Consider the set which contains Pi%i for all 1≤i≤N. This set should have the minimum number of distinct integers possible, over all permutations P.

Note that a permutation of length N is an array containing every integer from 1 to N exactly once.

### Input Format
The first line will contain T, number of test cases. Then the test cases follow.Each test case consists of a single line of input, an integer N, the length of the required permutation.

### Output Format
For each test case, output on a new line,N space-separated integers, denoting the permutation P of length N satisfying the above conditions.

### Constraints

1≤T≤700

2≤N≤10^5
 
Sum of N over all test cases does not exceed 2⋅10^5.

### Input	
2

2

3
## Output
2 1

2 3 1

Test case 1: The possible permutations of length2 are [1,2] and [2,1]. The only permutation that satisfies the conditions is [2,1]. 

The values Pi%i[2%1,1%2]=[0,1]. Thus there are 2 distinct values of Pi%i, which is the minimum possible.

Test case 2: There are 6 possible permutations of length 3 out of which [2,3,1] satisfies the above conditions. The values Pi%i are [2%1,3%2,1%3]=[0,1,1].

Thus there are 2 distinct values of Pi%i, which is the minimum possible.
