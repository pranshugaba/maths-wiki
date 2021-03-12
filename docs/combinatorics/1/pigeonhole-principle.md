# Pigeonhole Principle

>Too many pigeons, not enough holes

## Statement
The pigeonhole theorem[^1] is a simple yet powerful tool that is very useful throughout combinatorics.

[^1]: Often abbreviated to PHP.

!!! info "Theorem"
    If there are \(n\) holes, and \(n+1\) pigeons, and each pigeon is in some hole, then there exists a hole with at least two pigeons.

??? note "Proof"
    Suppose all holes have at most one pigeon. Then there are at most \(n\) pigeons. This is a contradiction since we have \(n+1\) pigeons.

## Generalized PHP


!!! info "Theorem"
    If there are \(n\) holes, and \(rn+1\) pigeons, and each pigeon is in some hole, then there exists a hole with at least \(r+1\) pigeons.

The proof is left as an exercise to the reader. 

## Exercises


!!! question
    Nine numbers are selected from the set \(\{1, 2, \ldots , 100 \}\). Prove that there exist two numbers whose difference is less than 11.
