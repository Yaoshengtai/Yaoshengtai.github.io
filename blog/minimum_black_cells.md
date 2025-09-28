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
<details>
  <summary>Click to see the solution</summary>
  It's easy to see if we put n black cells on the diagonal, we will eventually get whole black board. But is n the minimum?
  
  Obvious that the update process do not change the perimeter of the black area. The whole black board is with perimeter 4n, then if we use less than n cells, the initial perimeter is less than 4n. Then, the minimum is n.

</details>
