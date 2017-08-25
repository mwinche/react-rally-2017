David Khourshid - Infinitely Better UIs with Finite Automata
============================================================

@davidkpiano

DFAs!
* React is unidirectional and makes us rethink how we do UIs
* Bottom up approach is so hard to maintain and will have bugs
* User interfaces are graphs
* Finite - limited countable number
* Automata - predetermined sequence
* Deterministic - given current state + action = next state every time
* Finite State Machine === DFA
* State machines provide a common language for designers and developers
* Ryan Florence and the state machine!
* Testing State Machines
  * Generating unit tests with Dijkstra's or Breadth First Search
* State explosion (adding one state can add N more edges between other states)
  * Hierarchical states can help here
* Concurrent states (combinatorial explosion)
* History states
* `xstate` library for DFAs
