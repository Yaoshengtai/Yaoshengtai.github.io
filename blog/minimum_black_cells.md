---
author_profile: true
layout: single

---

## Minimum black cells to fill a \\( n \times n \\) grid

### Problem:
We have an \\( n \times n \\) board, each cell either black or white. The update rule is:

* A white cell turns black if at least two of its four neighbors (up, down, left, right) are black.
* Once a cell turns black, it stays black.
* The process repeats until no more changes happen.

What is the minimum number of black cells needed at the beginning, and how should they be placed, so that the whole board eventually turns black?

### Answer:
The solution is unexpectedly short and neat, 
<details markdown="1">
  <summary>[Click to see the solution]()</summary>
   
It’s easy to see that placing \\( n \\) black cells along the diagonal will eventually turn the entire board black. But is  \\( n \\) the minimum?  
 
Note that the update process does not change the perimeter of the black region. The fully black board has perimeter  \\( 4n \\). If we start with fewer than  \\( n \\) cells, the initial perimeter is less than  \\(4n\\). Hence, the minimum number of black cells required is  \\( n \\).  

</details>
