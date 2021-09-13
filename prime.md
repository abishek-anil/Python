I've been fascinated with number theory for a long time, so I started out with developing my own algorithm for checking if a number is prime.

For generating prime numbers in an interval, this checking function can be used.

Here's how the problem is most commonly solved:
```
def prime(n):
  for d in range(2, n):
    if n%d == 0:
      return False
  return True
```
One problem of the above code is that it would tell you that a number that is either negative or a decimal is also a prime. But before I rectify that problem, I want to point out that int/float 0 is equivalent to _False_ in boolean, and non-zero numbers are equivalent to _True_
