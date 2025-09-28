---
layout: archive
---
<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$','$$'], ['\\[','\\]']]
    }
  };
</script>


## Minimum black cells to fill a \\( n \times n \\) grid

### Problem
We have an \\( n \times n \\) board, each cell either black or white. The update rule is:

* A white cell becomes black if at least two of its four neighbors (up, down, left, right) are black.

* Once a cell turns black, it stays black.

* The process repeats until no more changes happen.

What is the minimum number of black cells needed at the beginning, and how should they be placed, so that the whole board eventually turns black?
