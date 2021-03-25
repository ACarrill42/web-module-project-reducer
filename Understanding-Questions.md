# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* Eventlistener listens for the onClick.
* Then runs the dispatch function within the listener,while also evaluating any arguements
* dispatch calls the reducer, finds the case it is evaulating.
* the case then spreads state dout, makes a copy, and alters state as defined.
* then the reducer uses the action.type to access the payload if needed. 
...

* TotalDisplay shows the total plus 1.
