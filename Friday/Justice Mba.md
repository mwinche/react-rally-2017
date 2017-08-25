Justice Mba - Demystifying setState()
=====================================

@daajust

* Largely a review of how state works in react
* React doesn't diff the whole VDOM tree, instead it will just do whatever component just rendered based on the state change
* setState must be asynchronous because of the cascade on composed components
* 
