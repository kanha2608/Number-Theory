# Number-Theory
here, I will post some famous number theory algorithm.

### Some Famous Conjecture about prime numbers.

There are many conjectures involving primes. Most people think that the conjectures are true, but nobody has been able to prove them. For example, the
following conjectures are famous:
• Goldbach’s conjecture: Each even integer n > 2 can be represented as a
sum n = a+ b so that both a and b are primes.
• Twin prime conjecture: There is an infinite number of pairs of the form
{p, p +2}, where both p and p +2 are primes.
• Legendre’s conjecture: There is always a prime between numbers n2 and (n+1)2, where n is any positive integer.

### inverse function :-
x^-1 = x^(m-2)



### Gray code:-
G[i] = i ^ ( i >> 1);


### Min xor of pair in array
Here, we just sort the array the answer will be the minimum of two consecutive 
How does this work ? 
suppose, A^B is min and there exist a C in between A and B;
Now suppose ith bit is highest index which A and B differs. 
Then this means if C[i] == A[i] then A^C < A^B
if C[i] == B[i] then B^C < A^B;

so both way better to include C. 

### Number of subarray have b as its elements.

----b-----
Now here, total subarray would be (l + 1)*(r + 1) how?
choosing one element from l is either choosing any of l or not choosing any so + 1, same for right. and Then multiply.

