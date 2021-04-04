# Pigeonhole Principle

## Introduction
Suppose you have a drawer full of red socks, blue socks, and yellow socks, and you would like to wear a matching pair of socks. Any colour is fine, as long as you have two socks of the same colour. 

<figure class="fig-center">
<img src="../socks-in-a-drawer.svg" onload="SVGInject(this)"/>
<figcaption>A drawer full of socks</figcaption>
</figure>

Unfortunately, the room is dark so you can't see the colours of the socks. You have no choice but to draw socks blindly. 

!!! question
    What is the minimum number of socks you must draw in order to guarantee a matching pair? 

Observe that when you draw four socks, you are guaranteed to have drawn a matching pair! (Note that this is also the minimum, since drawing three socks is not enough. It is possible that you draw three socks all of different colours.)

The key idea is that you have four socks, but there are only three kinds of socks. Therefore, there must be a colour of which there are at least two socks.
This idea is known as the **pigeonhole principle**. We now state it formally.


## Statement

!!! info "Pigeonhole Principle"
    If there are \(n\) bins, and \(n+1\) items, and each item is in some bin, then there exists a bin that contains at least two items.

    ??? note "Proof"
        Suppose each bin contains at most one item. Then there are at most \(n\) items. This is a contradiction since there are \(n+1\) items.

The pigeonhole principle is essential for proving several advanced results in combinatorics. It is a simple statement, but in many cases it is not immediately obvious what the "items" and "bins" should be. 

!!! example 
    Nine numbers are selected from the set \(\{1, 2, \ldots , 100 \}\). Show that there exist two numbers whose difference is less than 11.

!!! example 
    There are a hundred guest at a dinner party. Each guest shook hands with at least one other guest. Show that there exist two guests who shook the same number of hands. 


## Generalisation

The statement of the pigeonhole principle can be generalised to the following. 

!!! info "Theorem"
    If there are \(n\) bins and \(rn+1\) items, and each item is in some bin, then there exists a bin with at least \(r+1\) item.

The proof for this goes along similar lines to the special case of \(r = 1\). 



!!! example
    There are 142857 people living in the town of Mathville. Show that there is a group of 357 residents who share their birthday with each other.

## Exercises

!!! question "Exercise"
    What are the minimum number of rooks you must place on an \(8 \times 8\) chessboard so that there always exist two rooks that attack each other? How would the answer change if we are placing bishops instead of rooks?

!!! question "Exercise"
    Choose any 5 points inside a square that has sides of length 2. Show that there exist two points such that the distance between them is no more than \(\sqrt{2}\). 
