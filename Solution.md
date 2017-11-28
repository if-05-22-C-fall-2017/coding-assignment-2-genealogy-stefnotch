# Solution - Stefan Brandmair
## 1.
See `genealogy.pl`

## 2.
`parent(X, pat).`  
Tries to find an X, where X is a parent of pat.

## 3.
`parent(lisa, X).`  
Tries to find lisa's child. Since lisa doesn't have a child, it prints `no`.

## 4. 
See `genealogy.pl`

## 5. 
See `genealogy.pl`  

```
grandparent(X, Y) :- parent(X, A), parent(A, Y).
```
It tries to find an `A`, where `A` is a child of `X` and `A` is a parent of `Y`.  
e.g.  
X = john  
A = pat  
Y = jacob  

<br><br><br>
<br><br><br>

P.S. What prevents me from checking out [any of the other repositories](https://github.com/if-05-22-C-fall-2017)? They are all public ones.