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

