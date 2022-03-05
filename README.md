Let's define two functions G(X) and F(X) where G(X) will give us the closest prime greater than or equal to Xand F(X) will give us the smallest digit (0-9) in X.

Given two integers N and M, Your task is to print the value the sum of values of F(G(i)) for each I from N to M.

Input
The input contains two space- separated integers depicting the values of N and M.

Constraints:-
1 <= N <= M <= 10000
Output
Print the sum of F(G(i)) for each i from N to M.

---------EXAMPLE----------

Sample Input:-
1 10

Sample Output:-
34

Explanation:-

Numbers:- 1 2 3 4 5 6 7 8 9 10

G(i):- 2 2 3 5 5 7 7 11 11 11

F(G(i)):- 2 2 3 5 5 7 7 1 1 1 

Sum=34
