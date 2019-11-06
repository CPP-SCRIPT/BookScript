# Modulus

## Arithmetic

Modulus in a fundamental in modern cryptography and the public key cryptosystem. Another term for it is to find the remainder of something

For Example 

```
12/6 = 2; remainder 0
12/5 = 2; remainder 2
```

To find the remainder you use the modulus function

```
12 (mod 5) = 2
12 % 5 = 2
```

## Euler's **Totient** Function 

Given problem

```
ax = b (mod N) :: where a, b and N are given; solve for x
ex. 7x = 5 (mod 143)
```

Like most mathematics if you input numbers you can have multiple solutions, no solutions, or one solution.

For Cryptography we try to find problems that yield only one solution. 

The answer to this is to find the Greatest Common Divisor using a and N.

If the gcd \(a, N\) =1, then a and N are relatively **prime** or **coprime.**

Also if the gcd\(a, N\)= 1, then you can make 

```
a * c = 1 (mod N)
x = b * c (mod N)
```

This is the basis for **Public Key** and **Private Key Generation**

Steps:

```
 Pick A and B:: where A and B are prime and A != B
 C = A*B
 ϕC =(A-1)(B-1)
 Pick D where gcd(ϕC, D) = 1 and 1<D<ϕC
 Calculate E where ED mod ϕC = 1
 
 Public Key (E, 1)
 Private Key (D, 1)
```

