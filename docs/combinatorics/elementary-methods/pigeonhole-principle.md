# 1.1 &nbsp; Pigeonhole Principle

The pigeonhole principle is a simple statement, yet it is essential in proving several advanced results in combinatorics. 

## Statement 
!!! info "Theorem"
    If there are \(n\) holes, and \(n+1\) pigeons, and each pigeon is in some hole, then there exists a hole with at least two pigeons.

??? note "Proof"
    Suppose all holes have at most one pigeon. Then there are at most \(n\) pigeons. This is a contradiction since we have \(n+1\) pigeons.

## Generalized Form
The above statement can be generalized to the following. 

!!! info "Theorem"
    If there are \(n\) holes, and \(rn+1\) pigeons, and each pigeon is in some hole, then there exists a hole with at least \(r+1\) pigeons.

The proof for this goes along similar lines to the special case of \(r = 1\). 

## Exercises


!!! question "Exercise"
    Nine numbers are selected from the set \(\{1, 2, \ldots , 100 \}\). Show that there exist two numbers whose difference is less than 11.

!!! question "Exercise"
    Choose any 5 points inside a square which has sides of length 2. Show that there exist two points such that the distance between them is no more than \(\sqrt{2}\). 
