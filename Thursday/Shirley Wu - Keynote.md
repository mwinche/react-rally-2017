Shirley Wu - Keynote
====================

@sxywu

Github: React-D3

D3 + React
* Who controls the DOM? => Who needs control of the DOM?
* D3 only needs access to the DOM in three places:
  * Transitions (animations)
  * Axes (rendering axes)
  * Brushes
* Layouts,geo and shapes doesn't actually need the DOM
* Essentially what D3 does is transform data to screen coordinates
* Those three cases where the DOM is needed is the only time when D3 isn't just doing calculations
* Why React + D3?
  * For simple interactions (hover, click) D3 is more than sufficient
  * But if we're crafting a whole UI, then React is really helpful
* Use React with D3 to componentize visualizations and manage interaction state
* Never let D3 and React control the same part of the DOM (seems obvious but will cause terrible bugs)

Links:

* [Slides](http://sxywu.com/react-d3)
* [Example 1](https://bl.ocks.org/sxywu/7785064979f1e03865625b083741bf69/4b7e548a5c29c105d3f67e2cb195b9382e284eaa)
* [Example 2](https://bl.ocks.org/sxywu/b27228f6e37b45a648c78bc196b0e448/085355fe64b7f4849e9ade1cbbbb3c6bc0d57924)
