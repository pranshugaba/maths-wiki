# 1.1 Pigeonhole Principle

The pigeonhole principle is a simple statement, yet it is essential for proving several advanced results in combinatorics. 

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
    You have a drawer full of red socks, blue socks, and yellow socks. You would like a matching pair of socks, but the room is dark so you can't see the colours of the socks. What is the minimum number of socks you need to take out to guarantee you have a matching pair? 


!!! question "Exercise"
    What are the minimum number of rooks you must place on an \(8 \times 8\) chessboard such that there always exist two rooks that attack each other? Try the same problem with bishops instead of rooks. 

!!! question "Exercise"
    Nine numbers are selected from the set \(\{1, 2, \ldots , 100 \}\). Show that there exist two numbers whose difference is less than 11.

!!! question "Exercise"
    There are 142857 people who reside in the beautiful town of Mathville. Show that there is a group of 357 residents who share their birthday with each other.

!!! question "Exercise"
    Choose any 5 points inside a square with sides of length 2. Show that there exist two points such that the distance between them is no more than \(\sqrt{2}\). 
    
