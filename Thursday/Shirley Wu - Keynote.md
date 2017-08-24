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
* 
