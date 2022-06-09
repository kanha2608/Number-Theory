# Number-Theory
here, I will post some famous number theory algorithm.

# Some Famous Conjecture about prime numbers.

There are many conjectures involving primes. Most people think that the conjectures are true, but nobody has been able to prove them. For example, the
following conjectures are famous:
• Goldbach’s conjecture: Each even integer n > 2 can be represented as a
sum n = a+ b so that both a and b are primes.
• Twin prime conjecture: There is an infinite number of pairs of the form
{p, p +2}, where both p and p +2 are primes.
• Legendre’s conjecture: There is always a prime between numbers n2 and (n+1)2, where n is any positive integer.

# Euler totient function

Numbers a and b are coprime if gcd(a,b) = 1. Euler’s totient function ϕ(n)
gives the number of coprime numbers to n between 1 and n. For example,
ϕ(12) = 4, because 1, 5, 7 and 11 are coprime to 12.
The value of ϕ(n) can be calculated from the prime factorization of n using
the formula
ϕ(n) = product of( pi ^ (ai -1) ) (pi - 1 )    for all factors of n.

# Modular Arithmetic. 

(x+ y) mod m = (x mod m+ y mod m) mod m
(x− y) mod m = (x mod m− y mod m) mod m
(x · y) mod m = (x mod m· y mod m) mod m
x^n mod m = (x mod m)^n mod m

x^-1 mod m  =   x ^(m-2) mod m

x^-1  = x ^(ET-  1)   ET for prime is m-1 
x^-1 = x^(m-2)


# Min xor of pair in array
Here, we just sort the array the answer will be the minimum of two consecutive 
How does this work ? 
suppose, A^B is min and there exist a C in between A and B;
Now suppose ith bit is highest index which A and B differs. 
Then this means if C[i] == A[i] then A^C < A^B
if C[i] == B[i] then B^C < A^B;

so both way better to include C. 

